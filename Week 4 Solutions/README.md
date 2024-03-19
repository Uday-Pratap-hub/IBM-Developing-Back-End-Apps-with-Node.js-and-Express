# SOLUTIONS OF WEEK 4 PEER-GRADED ASSIGNMENT. :- 😇✅👇
## Do follow these below mentioned steps for solving this assignment. 👇
## Firstly download these above photos mentioned in this repository in some folder on your PC for future use.   !!! [ If while submitting in end there is ERROR of content issue then just do some slight editing on the images. ]
# TASK 1 :- 👇 [ USE THIS IMAGE ]
## TITLE :- ```BOOK LIST AVAILABLE```
![1-getallbooks](https://github.com/Uday-Pratap-hub/IBM-Developing-Back-End-Apps-with-Node.js-and-Express/assets/67860426/c513eae5-3c5c-407e-b607-d3f39370c5dd)

# TASK 2 :- 👇 [ USE THIS IMAGE ]
## TITLE :- ```IBN BASED BOOK RETRIEVAL```
![2-gedetailsISBN](https://github.com/Uday-Pratap-hub/IBM-Developing-Back-End-Apps-with-Node.js-and-Express/assets/67860426/e1edb608-cb5f-4955-b750-245b9441a8bb)

# TASK 3 :- 👇 [ USE THIS IMAGE ]
## TITLE :- ```BOOKS BY AUTHOR```
![3-getbooksbyauthor](https://github.com/Uday-Pratap-hub/IBM-Developing-Back-End-Apps-with-Node.js-and-Express/assets/67860426/1056f36b-10b4-4a2e-9165-26d65ac5eec6)

# TASK 4 :- 👇 [ USE THIS IMAGE ]
## TITLE :- ```BOOKS BY TITLE```
![4-getbooksbytitle](https://github.com/Uday-Pratap-hub/IBM-Developing-Back-End-Apps-with-Node.js-and-Express/assets/67860426/04bf7aa3-19c0-4ff3-93e9-cdee3caaef6d)

# TASK 5 :- 👇 [ USE THIS IMAGE ]
## TITLE :- ```BOOK REVIEW```
![5-getbookreview](https://github.com/Uday-Pratap-hub/IBM-Developing-Back-End-Apps-with-Node.js-and-Express/assets/67860426/03e38b15-4166-4c0c-9015-eb8289f3d38a)

# TASK 6 :- 👇 [ USE THIS IMAGE ]
## TITLE :- ```NEW USER REGISRATION.```
![6-register](https://github.com/Uday-Pratap-hub/IBM-Developing-Back-End-Apps-with-Node.js-and-Express/assets/67860426/07a8493e-fdf2-49d8-8099-8583550dab0a)

# TASK 7 :- 👇 [ USE THIS IMAGE ]
## TITLE :- ```USER LOGIN PAGE.```
![7-login](https://github.com/Uday-Pratap-hub/IBM-Developing-Back-End-Apps-with-Node.js-and-Express/assets/67860426/78bb01e6-a066-404c-baef-5c5faab74842)

# TASK 8 :- 👇 [ USE THIS IMAGE ]
## TITLE :- ```MODIFYING BOOK REVIEW```
![8-reviewadded](https://github.com/Uday-Pratap-hub/IBM-Developing-Back-End-Apps-with-Node.js-and-Express/assets/67860426/8e0af366-fe68-4ff4-b685-5d659d3202c2)

# TASK 9 :- 👇 [ USE THIS IMAGE ]
## TITLE :- ```DELETING BOOK REVIEW```
![9-deletereview](https://github.com/Uday-Pratap-hub/IBM-Developing-Back-End-Apps-with-Node.js-and-Express/assets/67860426/8fd948b3-2fc6-4e47-a326-056c79fdc026)

# TASK 10 :- 👇 
## DESCRIPTION :- [ USE THE COPY BUTTON BELOW ]
```
public_users.get('/async', async function (req, res) {  try {    const bookList = await getBookListAsync('http://localhost:5000/'); //    res.json(bookList);  } catch (error) {    console.error(error);    res.status(500).json({ message: "Error retrieving book list" });  }}); 
```

# TASK 11 :- 👇 
## DESCRIPTION :- [ USE THE COPY BUTTON BELOW ]
```
public_users.get('/async/isbn/:isbn', async function (req, res) {  try {    const requestedIsbn = req.params.isbn;    const book = await getBookListAsync("http://localhost:5000/isbn/" + requestedIsbn);    res.json(book);  } catch (error) {    console.error(error);    res.status(500).json({ message: "Error retrieving book details" });  }});
```

# TASK 12 :- 👇
## DESCRIPTION :- [ USE THE COPY BUTTON BELOW ]
```
public_users.get('/async/author/:author', async function (req, res) {  try {    const requestedAuthor = req.params.author;    const book = await getBookListAsync("http://localhost:5000/author/" + requestedAuthor);    res.json(book);  } catch (error) {    console.error(error);    res.status(500).json({ message: "Error retrieving book details" });  }});
```

# TASK 13 :- 👇
## DESCRIPTION :- [ USE THE COPY BUTTON BELOW ]
```
public_users.get('/async/title/:title', async function (req, res) {  try {    const requestedTitle = req.params.title;    const book = await getBookListAsync("http://localhost:5000/title/" + requestedTitle);    res.json(book);  } catch (error) {    console.error(error);    res.status(500).json({ message: "Error retrieving book details" });  }});
```

# TASK 14 :- 👇 ✅
## DESCRIPTION :- [ USE THE COPY BUTTON BELOW ]
```
https://github.com/williamg1750/expressBookReviews
```
# So After submitting the Assignment now, you need to do Peer-Reviewing [ Follow the below Video Step by Step for Reference ] :- 👇✅
https://github.com/Uday-Pratap-hub/IBM-Developing-Back-End-Apps-with-Node.js-and-Express/assets/67860426/597efbe5-dad0-4da3-98a2-c4d57fead5ab

# SO now as you have completed this course NOW enjoy your CERTIFICATION ... !! ✅😇😎💯😎
