# Team.Dealivery

Dealivery는 Django를 활용한 퀵 서비스 매칭 웹 서비스입니다.

# 기능 설명

- Models: Your application should have at least three models in addition to the User model: one for auction listings, one for bids, and one for comments made on auction listings. It’s up to you to decide what fields each model should have, and what the types of those fields should be. You may have additional models if you would like.

- Create Listing: 의뢰자들은 이곳에서 요청 양식을 작성한 후 의뢰를 보낼수 있습니다. 양식에는 요청사항, 픽업지역, 픽업주소, 배송지역, 배송주소, 경매 시작금액이 있으며 요청사항을 제외하곤 모두 필수적으로 작성되어야합니다.

- Active Listings Page: Create Listing 페이지에서 전송된 요청들을 이곳에서 확인할 수 있습니다. 이곳에서 배송지역과 요청사항을 미리보기로 확인할수있습니다. 요청을 클릭하면 상세한 정보를 볼 수 있습니다.
Listing Page: Clicking on a listing should take users to a page specific to that listing. On that page, users should be able to view all details about the listing, including the current price for the listing.
  - If the user is signed in, the user should be able to add the item to their “Watchlist.” If the item is already on the watchlist, the user should be able to         remove it.
  - If the user is signed in, the user should be able to bid on the item. The bid must be at least as large as the starting bid, and must be greater than any other   bids that have been placed (if any). If the bid doesn’t meet those criteria, the user should be presented with an error.
  - If the user is signed in and is the one who created the listing, the user should have the ability to “close” the auction from this page, which makes the highest     bidder the winner of the auction and makes the listing no longer active.
  - If a user is signed in on a closed listing page, and the user has won that auction, the page should say so.
  - Users who are signed in should be able to add comments to the listing page. The listing page should display all comments that have been made on the listing.
- Watchlist: Users who are signed in should be able to visit a Watchlist page, which should display all of the listings that a user has added to their watchlist. Clicking on any of those listings should take the user to that listing’s page.

- Django Admin Interface: Via the Django admin interface, a site administrator should be able to view, add, edit, and delete any listings, comments, and bids made on the site.

:computer: &nbsp; **View Course [here](https://www.edx.org/course/cs50s-web-programming-with-python-and-javascript)**

:arrow_forward: &nbsp; **View Live Demo [here](https://youtu.be/_oQ1NRAiidI)**

&nbsp;

### Contribute

Contributions are always welcome! Please create a PR to contribute.

### :pencil: &nbsp; License

This project is licensed under [MIT](https://opensource.org/licenses/MIT) license.

### :man_astronaut: &nbsp; Show your support

Give a ⭐️ if this project helped you!

