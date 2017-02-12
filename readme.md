Models

	Book 
		* Author
		* Title
		* URL
	
	User
		* 

	UserBooks
		* date
		* user_id
		* book_id

	BookTrade
		* date
		* user_1_id
		* user_2_id
		* user_1_book_id
		* user_2_book_id
		* status (requested, rejected, accepted)


	Add books to my collection (authenticated users)
	Browse/Search all Books by author/title (all users, scoped to location (eventually))
	Request a trade 
		* specify book desired
		* specify book to give 
