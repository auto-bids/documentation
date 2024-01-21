GET - /profiles/user/{email} - returns user with particular mail <br />
GET - /profiles/login/me - secured path, login or login and create user. After that you will be redirect to homepage on frontend <br />
EDIT - /profiles/edit/me - secured edit profiles of logged user after passing object like this<br />
    {<br />
	    "ProfileImage": "https://static.wikia.nocookie.net/egzorcysta/images/0/0c/PapaS%C5%82o%C5%84.png/revision/latest?cb=20231119094139&path-prefix=pl",<br />
	    "UserName": "ssa"<br />
    }<br />
DELETE - /profiles/delete/me - delete current user whole profile (without cars yet) <br />
POST - /logout - logout user <br />

