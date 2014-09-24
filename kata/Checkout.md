---
layout: kata
title: Checkout Kata
permalink: /kata/Checkout/
---

###Implement the code for a supermarket checkout that calculates the total price of a number of items.

---
The code will be used by an electronic till that can only scan one item at a time.  At the end of scanning the items the till system will request the total.

Goods are priced individually, however there are weekly special offers for when multiple items are bought. For example "A is 50 each or 3 for 130".

Weekly offers change frequently.  The initial prices and offers are as follows:

<style>
	table.checkout-grid {
		border-collapse: collapse;
	}

	table.checkout-grid tbody {
    	border-color: black;
	}
	
	table.checkout-grid tr {
		height: 15pt;
	}
	table.checkout-grid td, table.mine-grid th {
		border-color: black;
		border-style: solid;
		border-width: 1pt;
		padding: 5pt;
		width: 200pt;
		height: 24pt;
	}
</style>

<table class='checkout-grid' cellpadding='0' cellspacing='0'>
	<tr>
	    <th colspan='1' rowspan='1'><p>SKU</p></td>
	    <th colspan='1' rowspan='1'><p>Item Price</p></td>
	    <th colspan='1' rowspan='1'><p>Special Offers</p></td>
	</tr>
	<tr>
	    <td colspan='1' rowspan='1'><p>A</p></td>
	    <td colspan='1' rowspan='1'><p>50</p></td>
	    <td colspan='1' rowspan='1'><p>3 for 120</p></td>
	</tr>
	<tr>
	    <td colspan='1' rowspan='1'><p>B</p></td>
	    <td colspan='1' rowspan='1'><p>30</p></td>
	    <td colspan='1' rowspan='1'><p>2 for 45</p></td>
	</tr>
	<tr>
	    <td colspan='1' rowspan='1'><p>C</p></td>
	    <td colspan='1' rowspan='1'><p>60</p></td>
	    <td colspan='1' rowspan='1'><p></p></td>
	</tr>
	<tr>
	    <td colspan='1' rowspan='1'><p>D</p></td>
	    <td colspan='1' rowspan='1'><p>99</p></td>
	    <td colspan='1' rowspan='1'><p></p></td>
	</tr>
</table>
<br/>

