---
layout: page
title: Minesweeper Kata
permalink: /kata/Minesweeper/
---

###Have you ever played Minesweeper? It's a cute little game which comes within a certain Operating System whose name we can't really remember. Well, the goal of the game is to find all the mines within a field.

---
To help you, the game shows a number in a square (hint) which tells you how many mines there are adjacent to that square. For instance, take the following 4x4 field with 2 mines (which are represented by an X character):

<style>
	table.mine-grid {
		border-collapse: collapse;
	}

	table.mine-grid tbody {
    	border-color: black;
	}
	
	table.mine-grid tr {
		height: 15pt;
	}
	table.mine-grid td {
		border-color: black;
		border-style: solid;
		border-width: 1pt;
		padding: 5pt;
		width: 24pt;
		height: 24pt;
	}
</style>

<table class='mine-grid' cellpadding='0' cellspacing='0'>
 	<tbody>
		<tr>
		    <td colspan='1' rowspan='1'><p>X</p></td>
		    <td colspan='1' rowspan='1'><p></p></td>
		    <td colspan='1' rowspan='1'><p></p></td>
		    <td colspan='1' rowspan='1'><p></p></td>
		</tr>
		<tr>
		    <td colspan='1' rowspan='1'><p></p></td>
		    <td colspan='1' rowspan='1'><p></p></td>
		    <td colspan='1' rowspan='1'><p></p></td>
		    <td colspan='1' rowspan='1'><p></p></td>
		</tr>
		<tr>
		    <td colspan='1' rowspan='1'><p></p></td>
		    <td colspan='1' rowspan='1'><p>X</p></td>
		    <td colspan='1' rowspan='1'><p></p></td>
		    <td colspan='1' rowspan='1'><p></p></td>
		</tr>
		<tr>
		    <td colspan='1' rowspan='1'><p></p></td>
		    <td colspan='1' rowspan='1'><p></p></td>
		    <td colspan='1' rowspan='1'><p></p></td>
		    <td colspan='1' rowspan='1'><p></p></td>
		</tr>
	</tbody>
</table>
<br/>
The same minefield including the hint numbers described above would look like this:

<table class='mine-grid' cellpadding='0' cellspacing='0'>
 	<tbody>
		<tr>
		    <td colspan='1' rowspan='1'><p>X</p></td>
		    <td colspan='1' rowspan='1'><p>1</p></td>
		    <td colspan='1' rowspan='1'><p>0</p></td>
		    <td colspan='1' rowspan='1'><p>0</p></td>
		</tr>
		<tr>
		    <td colspan='1' rowspan='1'><p>2</p></td>
		    <td colspan='1' rowspan='1'><p>2</p></td>
		    <td colspan='1' rowspan='1'><p>1</p></td>
		    <td colspan='1' rowspan='1'><p>0</p></td>
		</tr>
		<tr>
		    <td colspan='1' rowspan='1'><p>1</p></td>
		    <td colspan='1' rowspan='1'><p>X</p></td>
		    <td colspan='1' rowspan='1'><p>1</p></td>
		    <td colspan='1' rowspan='1'><p>0</p></td>
		</tr>
		<tr>
		    <td colspan='1' rowspan='1'><p>1</p></td>
		    <td colspan='1' rowspan='1'><p>1</p></td>
		    <td colspan='1' rowspan='1'><p>1</p></td>
		    <td colspan='1' rowspan='1'><p>0</p></td>
		</tr>
	</tbody>
</table>
<br/>

####You should write a program that takes input as follows:
1. The size of the minefield (e.g. 4x4).
2. The mine location(s) within the minefield (e.g. Row 1, Column 2).

####Your program should produce output revealing the full minefield with hint values, for example:
X100<br/>
2210<br/>
1X10<br/>
1110<br/>

---
Provided by: [http://codingdojo.org/cgi-bin/wiki.pl?KataMinesweeper](http://codingdojo.org/cgi-bin/wiki.pl?KataMinesweeper)