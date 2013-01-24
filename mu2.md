---
layout: default
title: Achieving MU 2 VDT Requirement with Blue Button
---

# V/D/T and Blue Button+

As a dataholder, by implementing Blue Button+, you will be meeting the requirements of View, Download, and Transmit (V/D/T) in Meaningful Use Stage 2.

Blue Button+ gives specific guidance to dataholders in meeting the V/D/T requirements. In doing so, it describes a few minor clarifications and additions to V/D/T that ensures patients can transmit their records to third party applications of their choice.


<table>
	<tr>
		<th class="table-column">Requirements</th>
		<th class="table-column">Specified in MU 2 VDT</th>
		<th class="table-column">Specified for Blue Button+</th>
	</tr>
	<tr>
		<th>Structure</th>
		<td><a href="healthrecords.html">Consolidated CDA</a></td>
		<td><a href="healthrecords.html">Consolidated CDA</a></td>
	</tr>
	<tr class="odd">
		<th>Section &amp; Fields</th>
		<td><a href="healthrecords.html">Sections and fields described in MU 2</a></td>
		<td><a href="healthrecords.html">Sections and fields described in MU 2</a></td>
	</tr>
	<tr>
		<th>Transmit</th>
		<td><a href="transmit-using-direct.html">Direct Protocol (SMIME/SMTP)</a></td>
		<td><a href="transmit-using-direct.html">Direct Protocol (SMIME/SMTP)</a></td>
	</tr>
	<tr class="odd">
		<th>Trust Anchors</th>
		<td>Manual Anchor Exchange</td>
		<td><a href="https://secure.bluebuttontrust.org" target="_blank">Blue Button Trust Bundle</a></td>
	</tr>
	<tr>
		<th>Certificate Discovery</th>
		<td>Via DNS or LDAP</td>
		<td>Via DNS or LDAP</td>
	</tr>
	<tr class="odd">
		<th>Transmit Context</th>
		<td>-</td>
		<td>In message body and optional Request.txt</td>
	</tr>	
	<tr>
		<th>Download</th>
		<td>Yes</td>
		<td>Yes</td>
	</tr>
	<tr class="odd">
		<th>Transmit: Send Once</th>
		<td>Yes</td>
		<td>Yes</td>
	</tr>
	<tr>
		<th>Transmit: Send on Change</th>
		<td>-</td>
		<td>Yes</td>
	</tr>
</table>