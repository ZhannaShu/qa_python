# qa_python
test_init_books_rating_empty_dictionary_true   # проверили, что создан словарь books_rating и он пустой

test_init_favorites_empty_list_true            # проверили, что создан список favorites и он пустой

test_add_new_book_add_one_book_true            # проверяем добавление одной книги и она добавлена в словарь

test_add_new_book_check_rating_of_the_add_book_true       # проверили, что рейтинг равен 1 у добавленной новой книги

test_add_new_book_cannot_add_book_twice_true              # проверили, что нельзя добавить книгу дважды

test_set_book_rating_cant_set_rating_less_than_one_error  # проверили, что нельзя установить рейтинг меньше 1

test_get_book_rating_book_rating_by_name                  # проверили получение рейтинга книги по ее имени

test_get_book_rating_no_book_no_rating                    # проверили, что у не добавленной книги нет рейтинга

test_get_books_with_specific_rating_list_books_specified_rating  # проверили получение списка книг с указанным рейтингом

test_get_books_rating_get_current_dict_true                # проверили получение текущего словаря

test_add_book_in_favorites_book_add_to_favorites_true      # проверили добавление книги в избранное

test_add_book_to_favorites_book_add_to_favorites_twice_cannot_be  # проверили, что книгу нельзя добавить в избранное дважды

test_delete_book_from_favorites_book_remove_from_favorites  # проверили, что книга из избранного удаляется, если она там есть

test_get_list_of_favorites_books_list_favorite_books_true   # проверили получение списка избранных книг