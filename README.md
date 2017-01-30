# Single Linked List
This project covers about 50+ functions developed in "C" for following operations.
Basic operations covered are:
A. Print.
B. Locate.
C. insert.
D. Replace.
E. Delete.

The corresponding functions implemented in "C" language are:
A. Print:
1. void print_sll(Sll_t **head);

2. void print_first_node_sll(Sll_t **head);

3. void print_last_node_sll(Sll_t **head);

4. void print_first_Nth_node_sll(Sll_t **head, int loc_first);

5. void print_last_Nth_node_sll(Sll_t **head, int loc_first);

6. void print_mid_node_sll(Sll_t **head);

7. void print_node_before_mid_sll(Sll_t **head);

8. void print_node_after_mid_sll(Sll_t **head);

9. void print_first_N_nodes_sll(Sll_t **head, int loc_first);

10. void print_last_N_nodes_sll(Sll_t **head, int loc_first);

11. void print_first_to_mid_nodes_sll(Sll_t **head, int loc_first);

12. void print_mid_to_last_nodes_sll(Sll_t **head, int loc_first);

B. Locate:

13. Sll_t *return_first_node_address_sll(Sll_t **head);

14. Sll_t *return_last_node_address_sll(Sll_t **head);

15. Sll_t *return_Nth_node_address_from_first_sll(Sll_t **head, int loc_first);

16. Sll_t *return_Nth_node_address_from_last_sll(Sll_t **head, int loc_last);

17. Sll_t *return_node_address_after_first_Nth_sll(Sll_t **head, int loc_first);

18. Sll_t *return_node_address_before_first_Nth_sll(Sll_t **head, int loc_first);

19. Sll_t *return_node_address_after_last_Nth_sll(Sll_t **head, int loc_last);

20. Sll_t *return_node_address_before_last_Nth_sll(Sll_t **head, int loc_last);

21. Sll_t *return_mid_node_address_sll(Sll_t **head);

22. Sll_t *return_node_address_after_mid_node_sll(Sll_t **head);

23. Sll_t *return_node_address_before_mid_node_sll(Sll_t **head);

24. int return_mid_node_location_sll(Sll_t **head);

25. int return_unique_node_location_sll(Sll_t **head, data_t data);

C. INSERT:

26. int insert_first_sll(Sll_t **head, data_t data);

27. int insert_last_sll(Sll_t **head, data_t data);

28. int insert_after_sll(Sll_t **head, data_t g_data, data_t n_data);

29. int insert_before_sll(Sll_t **head, data_t g_data, data_t n_data);

30. int insert_at_Nth_first_loc(Sll_t **head, int loc, data_t data);

31. int insert_at_Nth_last_loc(Sll_t **head, int loc, data_t data);

32. int insert_after_Nth_first_loc(Sll_t **head, int loc_first, data_t data);

33. int insert_before_Nth_first_loc(Sll_t **head, int loc_first, data_t data);

34. int insert_after_Nth_last_loc(Sll_t **head, int loc_last, data_t data);

35. int insert_before_Nth_last_loc(Sll_t **head, int loc_last, data_t data);

36. int insert_at_mid_loc_sll(Sll_t **head, data_t data);

37. int insert_after_mid_loc_sll(Sll_t **head, data_t data);

38. int insert_before_mid_loc_sll(Sll_t **head, data_t data);

D. UPDATE:

39. int update_data_Nth_node_from_first_sll(Sll_t **address, int loc_first, data_t data);

40. int update_data_Nth_node_from_last_sll(Sll_t **address, int loc_last, data_t data);

41. int update_mid_node_data_sll(Sll_t **address, data_t data);

42. int update_node_data_after_mid_node_sll(Sll_t **address, data_t data);

43. int update_node_data_before_mid_node_sll(Sll_t **address, data_t data);

E. DELETE:

44. int delete_first_sll(Sll_t **head);

45. int delete_last_sll(Sll_t **head);

46. int delete_data_match_node_sll(Sll_t **head, data_t data);

47. int delete_Nth_first_sll(Sll_t **head, int loc_first);

48. int delete_Nth_last_sll(Sll_t **head, int loc_last);

49. int delete_first_N_nodes_sll(Sll_t **head, int loc_first);

50. int delete_last_N_nodes_sll(Sll_t **head, int loc_last);

51. int delete_node_after_Nth_first_sll(Sll_t **head, int loc_first);

52. int delete_node_before_Nth_first_sll(Sll_t **head, int loc_first);

53. int delete_list_sll(Sll_t **head);

Reversing, Searching, Sorting will be added in next update
