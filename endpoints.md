GET - /profiles/user/{email} - returns user with particular mail <br />
GET - /profiles/login/me - secured path, login or login and create user. After that you will be redirect to homepage on frontend <br />
EDIT - /profiles/edit/me - secured edit profiles of logged user after passing object like this<br />
    {<br />
	    "profile_image": "https://static.wikia.nocookie.net/egzorcysta/images/0/0c/PapaS%C5%82o%C5%84.png/revision/latest?cb=20231119094139&path-prefix=pl",<br />
	    "user_name": "ssa"<br />
    }<br />
DELETE - /profiles/delete/me - delete current user whole profile (without cars yet) <br />
POST - /logout - logout user <br />
<br /><br /><br /><br />



GET - /cars/offer/user/{email}/{page}{filters} - returns all cars from user with particular mail and page <br />
GET - /cars/offer/user/me/{page}{filters} - returns all cars from logged user and page ex. /cars/offers/user/me/1?make=Toyota<br />
GET - /cars/offers/{page}{filters} - returns all cars from page ex. /cars/offers/page/1?make=Toyota<br />
GET - /cars/offer/{id} - returns car with particular id <br />
POST - /cars/add/me - add new car <br />
DELETE - /cars/delete/me - delete one of user cars with given id in object<br />
DELETE - /cars/delete/all/me - delete all user cars <br />
PUT - /cars/edit/me - edit one of user cars with given id in object<br />

