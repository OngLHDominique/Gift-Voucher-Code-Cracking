===== OVERVIEW =====
An online shopping retailer runs a server to generate gift voucher codes for customers.
More specifically, the server will generate a gift voucher code if it receives a client ID from the customer’s machine and sends the generated gift voucher code to the customer.
The known technical detail about this system is that the server provides this service using UDP on a port between 12345 and 12500 and uses the MD5 hash function (weak one!) to generate the voucher code.
The gift voucher code has monetary value and is sent to the customer for a certain period only. However, as a hacker, you discovered that the server admin forgot to close the port for the service.
You want to generate valid gift voucher codes on your own using many client IDs you collected from information gathering.

===== HOW TO RUN THE PROGRAM =====
*Refer to the PDF file provided for detailed information and explanation.

===== EXPECTED RESULTS =====
The end result should provide you with 2 files, voucher_dict.txt and target_hash.txt.
*Refer to the PDF file provided for detailed information and explanation.
