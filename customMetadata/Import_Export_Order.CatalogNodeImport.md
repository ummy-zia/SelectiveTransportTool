<?xml version="1.0" encoding="UTF-8"?>
<CustomMetadata xmlns="http://soap.sforce.com/2006/04/metadata" xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance" xmlns:xsd="http://www.w3.org/2001/XMLSchema">
    <label>CatalogNodeImport</label>
    <protected>false</protected>
    <values>
        <field>BatchSize__c</field>
        <value xsi:nil="true"/>
    </values>
    <values>
        <field>Custom_Object_Name__c</field>
        <value xsi:type="xsd:string">REVVY__MnCatalogNode__c</value>
    </values>
    <values>
        <field>External_Id__c</field>
        <value xsi:type="xsd:string">REVVY__Id__c</value>
    </values>
    <values>
        <field>NeedUpsert__c</field>
        <value xsi:type="xsd:boolean">true</value>
    </values>
    <values>
        <field>Product_Where_Clause__c</field>
        <value xsi:type="xsd:string">Where REVVY__Id__c = &apos;@REVVYID&apos;</value>
    </values>
    <values>
        <field>Sequence__c</field>
        <value xsi:type="xsd:double">4.0</value>
    </values>
    <values>
        <field>Upsert_Field__c</field>
        <value xsi:type="xsd:string">REVVY__Id__c</value>
    </values>
    <values>
        <field>Where_Clause__c</field>
        <value xsi:type="xsd:string">Where REVVY__Type__c in (&apos;Category&apos;,&apos;Catalog&apos;) OR REVVY__Id__c in (@REVVYPRODUCTIDS)</value>
    </values>
</CustomMetadata>
