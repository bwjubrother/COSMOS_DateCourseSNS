INSERT INTO feed VALUE (5, 'testTest', 'Its so delicious', 0, 0, "2020-07-26 08:05:24", 'https://d20aeo683mqd6t.cloudfront.net/ko/articles/title_images/000/026/550/medium/IMG_2236s.jpg?2019');



INSERT INTO feed VALUE (6, 'testTest', 'you must come here', 0, 0, "2020-07-28 08:05:56", 'https://dimg.donga.com/a/500/0/90/5/ugc/CDB/29STREET/Article/5e/b2/04/e8/5eb204e81752d2738236.jpg');



INSERT INTO following VALUE('testTest', 'yeonhee', 's@naver.com');

INSERT INTO following VALUE('yeonhee', 'testTest', 'test@naver.com');



UPDATE feed SET thumbnail='https://encrypted-tbn0.gstatic.com/images?q=tbn%3AANd9GcQFagW0xUymk3gAxMStM3JFf8UfHF-CEPeu_w&usqp=CAU' WHERE feed_no=4;



UPDATE countinfo SET follower_count=5 WHERE email="test@naver.com";

