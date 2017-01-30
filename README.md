# Single Linked List
This project covers about 54+ functions developed in "C" from scratch.
Basic operations covered are:
A. Print.
B. Locate.
C. insert.
D. Replace.
E. Delete.

The corresponding functions implemented are:
A. Print:
1. Prints all elements in Single Linked List(SLL).                //  void print_sll(Sll_t **head);
2. Prints element at first node.                                  //  void print_first_node_sll(Sll_t **head);
3. Prints element at last node.                                   //  void print_last_node_sll(Sll_t **head);
4. 
void print_first_Nth_node_sll(Sll_t **head, int loc_first);
void print_last_Nth_node_sll(Sll_t **head, int loc_first);

void print_mid_node_sll(Sll_t **head);
void print_node_before_mid_sll(Sll_t **head);
void print_node_after_mid_sll(Sll_t **head);

void print_first_N_nodes_sll(Sll_t **head, int loc_first);
void print_last_N_nodes_sll(Sll_t **head, int loc_first);

void print_first_to_mid_nodes_sll(Sll_t **head, int loc_first);
void print_mid_to_last_nodes_sll(Sll_t **head, int loc_first);

int insert_first_sll(Sll_t **head, data_t data);
int insert_last_sll(Sll_t **head, data_t data);

int insert_after_sll(Sll_t **head, data_t g_data, data_t n_data);
int insert_before_sll(Sll_t **head, data_t g_data, data_t n_data);

int insert_at_Nth_first_loc(Sll_t **head, int loc, data_t data);
int insert_at_Nth_last_loc(Sll_t **head, int loc, data_t data);

int delete_first_sll(Sll_t **head);
int delete_last_sll(Sll_t **head);

/* TODO (pavan#2#): do All 45 below, once completed move them above*/
int insert_after_Nth_first_loc(Sll_t **head, int loc_first, data_t data);
int insert_before_Nth_first_loc(Sll_t **head, int loc_first, data_t data);

int insert_after_Nth_last_loc(Sll_t **head, int loc_last, data_t data);
int insert_before_Nth_last_loc(Sll_t **head, int loc_last, data_t data);

int insert_at_mid_loc_sll(Sll_t **head, data_t data);
int insert_after_mid_loc_sll(Sll_t **head, data_t data);
int insert_before_mid_loc_sll(Sll_t **head, data_t data);

Sll_t *return_first_node_address_sll(Sll_t **head);
Sll_t *return_last_node_address_sll(Sll_t **head);

Sll_t *return_Nth_node_address_from_first_sll(Sll_t **head, int loc_first);
Sll_t *return_Nth_node_address_from_last_sll(Sll_t **head, int loc_last);

Sll_t *return_node_address_after_first_Nth_sll(Sll_t **head, int loc_first);
Sll_t *return_node_address_before_first_Nth_sll(Sll_t **head, int loc_first);

Sll_t *return_node_address_after_last_Nth_sll(Sll_t **head, int loc_last);
Sll_t *return_node_address_before_last_Nth_sll(Sll_t **head, int loc_last);

Sll_t *return_mid_node_address_sll(Sll_t **head);
Sll_t *return_node_address_after_mid_node_sll(Sll_t **head);
Sll_t *return_node_address_before_mid_node_sll(Sll_t **head);

int return_mid_node_location_sll(Sll_t **head);
int return_unique_node_location_sll(Sll_t **head, data_t data);

int update_data_Nth_node_from_first_sll(Sll_t **address, int loc_first, data_t data);
int update_data_Nth_node_from_last_sll(Sll_t **address, int loc_last, data_t data);

int update_mid_node_data_sll(Sll_t **address, data_t data);
int update_node_data_after_mid_node_sll(Sll_t **address, data_t data);
int update_node_data_before_mid_node_sll(Sll_t **address, data_t data);

int delete_data_match_node_sll(Sll_t **head, data_t data);

int delete_Nth_first_sll(Sll_t **head, int loc_first);
int delete_Nth_last_sll(Sll_t **head, int loc_last);

int delete_first_N_nodes_sll(Sll_t **head, int loc_first);
int delete_last_N_nodes_sll(Sll_t **head, int loc_last);

int delete_node_after_Nth_first_sll(Sll_t **head, int loc_first);
int delete_node_before_Nth_first_sll(Sll_t **head, int loc_first);

int delete_list_sll(Sll_t **head);
