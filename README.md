using namespace std;
struct node
{
int data;
node *left,*right;
};
class BST
{
public:
node *nnode,*temp,*temp1,*root;
BST()
{
root=NULL;
}
void create()
{
char ch;
do
{
nnode=new node;
cout<<"\n Enter the data:";
cin>>nnode->data;
nnode->left=NULL;
nnode->right=NULL;
if(root==NULL)
{
root
