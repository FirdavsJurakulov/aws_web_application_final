# aws_web_application_final
A final exam assignment for Operating systems Course


## Links to deployed Resources (S3, RDS, EC2):
- S3: https://ap-south-1.console.aws.amazon.com/s3/buckets/2t-firdavs?region=ap-south-1&bucketType=general&tab=objects
- EC2: https://ap-south-1.console.aws.amazon.com/ec2/home?region=ap-south-1#InstanceDetails:instanceId=i-0e7cebac6f378e4d9
- RDS: https://ap-south-1.console.aws.amazon.com/rds/home?region=ap-south-1#database:id=db-firdavs;is-cluster=false

## Script to Import Data to table:
<code>INSERT INTO tbl_firdavs_data (rank, video, video_views, likes, dislikes, category, published) VALUES
(1, '20 Tennis shots if they were not filmed, NOBODY would believe them', 3471237, 19023, 859, NULL, 2017),
(2, 'Lil Nas X - Old Town Road (Official Movie) ft. Billy Ray Cyrus', 54071677, 3497955, 78799, 'Music', 2019),
(3, 'JoJo Siwa - Karma (Official Video)', 34206747, 293563, NULL, 'Music', 2024),
(4, 'Wiz Khalifa - See You Again ft. Charlie Puth [Official Video] Furious 7 Soundtrack', 6643904918, 44861602, NULL, 'Music', 2015),
(5, '伊賀の天然水強炭酸水「家族で、シュワシェア。」篇　15秒', 236085971, 38, NULL, NULL, 2021),
(6, 'JP Saxe - If the World Was Ending (Official Video) ft. Julia Michaels', 76834495, 804353, 21195, 'Music', 2019),
(7, 'David Kushner - Daylight (Official Music Video)', 18558390, 680732, NULL, 'Music', 2023),
(8, 'Power Star Pawan Kalyan Special Surprise To Sensational Singer Baby|Filmy Poster', 96686, 1007, 82, 'Entertainment', 2018),
(9, 'Kulit Kamu Kulit Kering dan Sensitif? Pakai Aveeno Skin Relief Lotion!', 9605969, 6, NULL, NULL, 2023),
(10, 'Totti with a funny penalty', 8353318, 5613, 1082, 'Sports', 2007),
(11, 'Babilala ที่ทั้งแม่และลูกชื่นชอบนั้นคืออะไร?', 8718326, 46, NULL, NULL, 2021),
(12, 'Polo G, Stunna 4 Vegas & NLE Choppa feat. Mike WiLL Made-It - Go Stupid (Official Video)', 7396199, 320910, 6485, 'Music', 2020),
(13, 'Every Moment With You (너와의 모든 지금)', 7958181, 54903, NULL, 'Music', 2024),
(14, 'Not a mechanical baby', 14612153, 3339, 156, 'Entertainment', 2011),
(15, 'Yovie Widianto, Lyodra, Tiara Andini, Ziva Magnolya - Menyesal', 13894905, 452087, NULL, 'Music', 2023);
</code>
