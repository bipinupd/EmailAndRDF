EmailAndRDF
===========

Read  email and store as RDF database.

Give the pointer to the input file of your mailbox:
InputFileName="/home/bipin/.mozilla-thunderbird/dqig5cjg.default/Mail/Local Folders/Inbox";

Give the pointer to the location where you want to store email as RDF
OutputFileName="/home/bipin/test.rdf";


##################################################################
Format of Email RDF

<email:Message rdf:about="1111@gmail.com" >
<dc:date>Thu, 25 Mar 2010 10:14:26 -0400</dc:date>
<email-From><rdfs:label>Anuja</rdfs:label><email-address>ahmad.afsahi@queensu.ca</email-address></email-From>
<email-subject> Hi</email-subject>
Message-Content
</email:Message>


