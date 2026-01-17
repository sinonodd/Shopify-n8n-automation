# Shopify-n8n-automation

<img width="1230" height="674" alt="image" src="https://github.com/user-attachments/assets/8e4dfb03-8364-4ee2-bbc7-1fda700a9754" />


## Workflow Information 📌

### Purpose 🎯
The intention of this workflow is to integrate New Shopify Orders into MS Dynamics Business Central:

- **Point-of-Sale (POS):** POS orders will be created in Business Central as Sales Invoices given no fulfillment is expected.
- **Web Orders:** This type of orders will be created as Business Central Sales Orders.

### How to use it 🚀
1. Edit the "D365 BC Environment Settings" node with your own account values (Company Id, Tenanant Id, Tax & Discount Items).
2. Go to the "Shopify" node and edit the connection with your environment.
3. Go to the "Lookup Customers" node to edit the Business Central connection details with your environment settings.
4. Set the required filters on the "Shopify Order Filter" node.
5. Edit the "Schedule Trigger" node with the required frequency.





