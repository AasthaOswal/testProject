# pehle uss newproject ko git add . karo, fir commit bhi kardo, aur fr jab git push origin main karenge tab error aayega

# git remote add origin <link>
basically jis repository mein hume testProject ya kisi bhi project ko add karna hain uska link hum yaha pehle specify karte hain, kyuki git push origin main se error aa raha hain

# git remote add origin <link>
matlab abhi jaha project ko add karna hain, usko origin bol rahe hain, aur origin kya hain hum uss link mein pecify kar denge

# get remote -v
yeh batata hai ki jaha push pull ho raha hain woh kya remote hain?

# git branch
basically example se samjo: three frends hain  woh 3 alag branch mein sme project par kaam karte hain and then later they merge it

# Tracking changes
just checking after pushing the project if changes can be seen in the files

# git push -u origin main
matlab origin ko set kar rahe hain
ab iske baad sirf git push likhna hain

# -u in above comand means upstream
upstream matlab upar, matlab cloud, github jaha bhi hume data bhejna hain woh humne set kar diya, ki bass yahi par data bhejo!

# result after using above command:
PS C:\Users\AASTHA OSWAL\ACWebDev\31_Git_and_gitHub\testProject> git push -u origin main
branch 'main' set up to track 'origin/main'.
Everything up-to-date
PS C:\Users\AASTHA OSWAL\ACWebDev\31_Git_and_gitHub\testProject> 

# git commit -am "messgae"
basically combining flags:
-a is for add
-m message

# merging branched waale mein yeh comment hain ki
jab feature branch mein changes kiye
usko add and commit kiya
uske baad push nahinho paya kyuki error aaya i feature branch ke liye no upstream is set
Hence to set upstream we wrote this command:
# git push --set-upstream origin feature
