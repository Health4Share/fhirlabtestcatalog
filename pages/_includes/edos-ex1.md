


**Generated Example**

Click here For [Raw Xml](..\resources\edos-ex1.xml)


	<?xml version="1.0" encoding="UTF-8"?>
	<LabTestCatalog xmlns:xhtml="http://www.w3.org/1999/xhtml" xsi:schemaLocation="http://hl7.org/fhir //ERICS-AIR/ehaas/Documents/FHIR/FHIR%20tools/fhir-all-xsd/labtestcatalog.xsd" xmlns="http://hl7.org/fhir" xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance" id="edos-ex1">
		<publisher value="^2.16.840.1.113883.3.72.5.21^ISO"/>
		<entry>
			<sequence value="1"/>
			<code>
				<coding>
					<system value="99USL"/>
					<code value="10"/>
					<display value="PT + INR"/>
				</coding>
				<text value="10^PT + INR^99USL"/>
			</code>
			<name value="PT + INR"/>
			<orderable value="true"/>
			<longname value="Prothrombin Time and International Normalized Ratio Panel"/>
			<type>
				<text value="P"/>
			</type>
			<component>
				<system value="99USL"/>
				<code value="11"/>
				<display value="Prothrombin Time, PT"/>
			</component>
			<component>
				<system value="99USL"/>
				<code value="12"/>
				<display value="INR"/>
			</component>
			<chargeCharacteristic>
				<shortName value="N/A"/>
				<longName value="longName"/>
				<coding>
					<system value="85610"/>
					<code value="Prothrombin Time"/>
					<display value="C4"/>
				</coding>
			</chargeCharacteristic>
			<payerPolicy>
				<healthPlan>
					<value value="Healthplan1"/>
				</healthPlan>
				<InsCompany>
					<display value="SMCA2^^^&amp;2.16.840.1.113883.3.72.5.22&amp;ISO^XX"/>
				</InsCompany>
				<priceRange/>
				<reason/>
				<approvedProcedures/>
				<dxCode/>
				<pxCode/>
			</payerPolicy>
		</entry>
		<entry>
			<sequence value="2"/>
			<code>
				<coding>
					<system value="99USL"/>
					<code value="11"/>
					<display value="Prothrombin Time, PT"/>
				</coding>
				<text value="11^Prothrombin Time, PT^99USL"/>
			</code>
			<name value="PT"/>
			<orderable value="false"/>
			<longname value="Prothrombin Time"/>
			<type>
				<text value="A"/>
			</type>
		</entry>
		<entry>
			<sequence value="3"/>
			<code>
				<coding>
					<system value="99USL"/>
					<code value="12"/>
					<display value="INR"/>
				</coding>
				<text value="12^INR^99USL"/>
			</code>
			<name value="INR"/>
			<orderable value="false"/>
			<longname value="International Normalized Ratio"/>
			<type>
				<text value="C"/>
			</type>
		</entry>
	</LabTestCatalog>

