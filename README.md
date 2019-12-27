<p><strong>CONTRACT_EXTRACTOR</strong><br />================</p>
<p>Contract extractor allows you to extract contracts for a given string/sub-string and check the mapping to the EPG (AP/L3/VzAny).&nbsp;</p>
<blockquote>
<p><strong><em>sudo ansible-playbook contract_epg_parser.yml -i ../inventories/inventory.txt --vault-password-file ../vault.txt --limit "sandboxapicdc.cisco.com,"</em></strong></p>
</blockquote>
<p><br /><strong>ENDPOINT_LOCATOR</strong><br />===============</p>
<p>Endpoint Locator is a poor man version of the GUI APIC option, you can pass either mac or IP address as argument and see how it maps to Tenant/EPG/Port.</p>
<blockquote>
<p><strong><em>sudo ansible-playbook endpoint_locator.yml -i ../inventories/inventory.txt --vault-password-file ../vault.txt --limit "sandboxapicdc.cisco.com,"</em></strong></p>
</blockquote>
