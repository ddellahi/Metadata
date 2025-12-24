<?xml version="1.0" encoding="UTF-8"?>
<md:node xmlns:md="http://www.stambia.com/md" defType="com.stambia.xml.xsd" id="_-OiBsODNEfC7ivsSxMkT5A" name="customerDetails" md:ref="resource.md#UUID_MD_XML_DEFAULT?fileId=UUID_MD_XML_DEFAULT$type=md$name=Xml?" internalVersion="v2.0.0">
  <attribute defType="com.stambia.xml.xsd.xsdReverseVersion" id="_-Oj24ODNEfC7ivsSxMkT5A" value="1"/>
  <attribute defType="com.stambia.xml.xsd.xsdPath" id="_QGJjgODOEfC7ivsSxMkT5A" value="%{env:workspace_loc}%/Training/Files_In/Xml/customerDetails.xsd"/>
  <attribute defType="com.stambia.xml.xsd.targetNamespace" id="_QGJjgeDOEfC7ivsSxMkT5A" value="http://semarchy.com/samples/management"/>
  <attribute defType="com.stambia.xml.xsd.prefixForAttribute" id="_QGKKkODOEfC7ivsSxMkT5A" value="unqualified"/>
  <attribute defType="com.stambia.xml.xsd.xmlPath" id="_QGKKkeDOEfC7ivsSxMkT5A" value="%{env:workspace_loc}%/Training/Files_Out/Xml/customerDetails.xml"/>
  <attribute defType="com.stambia.xml.xsd.prefixForElement" id="_QGKKkuDOEfC7ivsSxMkT5A" value="unqualified"/>
  <node defType="com.stambia.xml.root" id="_QGI8fuDOEfC7ivsSxMkT5A" name="customerDetails" position="0">
    <node defType="com.stambia.xml.sequence" id="_QGI8f-DOEfC7ivsSxMkT5A" position="3">
      <attribute defType="com.stambia.xml.sequence.minOccurs" id="_QGI8gODOEfC7ivsSxMkT5A" value="1"/>
      <attribute defType="com.stambia.xml.sequence.maxOccurs" id="_QGI8geDOEfC7ivsSxMkT5A" value="1"/>
      <node defType="com.stambia.xml.element" id="_QGI8guDOEfC7ivsSxMkT5A" name="customer" position="0">
        <attribute defType="com.stambia.xml.element.minOccurs" id="_QGI8g-DOEfC7ivsSxMkT5A" value="0"/>
        <attribute defType="com.stambia.xml.element.maxOccurs" id="_QGI8hODOEfC7ivsSxMkT5A" value="-1"/>
        <attribute defType="com.stambia.xml.element.originalType" id="_QGI8heDOEfC7ivsSxMkT5A" value="mgt:CustomerDetail"/>
        <node defType="com.stambia.xml.attribute" id="_QGI8huDOEfC7ivsSxMkT5A" name="customerId" position="0">
          <attribute defType="com.stambia.xml.attribute.type" id="_QGI8h-DOEfC7ivsSxMkT5A" value="integer"/>
          <attribute defType="com.stambia.xml.attribute.originalType" id="_QGI8iODOEfC7ivsSxMkT5A" value="xs:integer"/>
          <attribute defType="com.stambia.xml.attribute.use" id="_QGI8ieDOEfC7ivsSxMkT5A" value="optional"/>
        </node>
        <node defType="com.stambia.xml.attribute" id="_QGI8iuDOEfC7ivsSxMkT5A" name="titleCode" position="1">
          <attribute defType="com.stambia.xml.attribute.type" id="_QGI8i-DOEfC7ivsSxMkT5A" value="string"/>
          <attribute defType="com.stambia.xml.attribute.originalType" id="_QGI8jODOEfC7ivsSxMkT5A" value="xs:string"/>
          <attribute defType="com.stambia.xml.attribute.use" id="_QGI8jeDOEfC7ivsSxMkT5A" value="optional"/>
        </node>
        <node defType="com.stambia.xml.attribute" id="_QGI8juDOEfC7ivsSxMkT5A" name="title" position="2">
          <attribute defType="com.stambia.xml.attribute.type" id="_QGI8j-DOEfC7ivsSxMkT5A" value="string"/>
          <attribute defType="com.stambia.xml.attribute.originalType" id="_QGI8kODOEfC7ivsSxMkT5A" value="xs:string"/>
          <attribute defType="com.stambia.xml.attribute.use" id="_QGI8keDOEfC7ivsSxMkT5A" value="optional"/>
        </node>
        <node defType="com.stambia.xml.attribute" id="_QGI8kuDOEfC7ivsSxMkT5A" name="firstName" position="3">
          <attribute defType="com.stambia.xml.attribute.type" id="_QGI8k-DOEfC7ivsSxMkT5A" value="string"/>
          <attribute defType="com.stambia.xml.attribute.originalType" id="_QGI8lODOEfC7ivsSxMkT5A" value="xs:string"/>
          <attribute defType="com.stambia.xml.attribute.use" id="_QGI8leDOEfC7ivsSxMkT5A" value="optional"/>
        </node>
        <node defType="com.stambia.xml.attribute" id="_QGI8luDOEfC7ivsSxMkT5A" name="lastName" position="4">
          <attribute defType="com.stambia.xml.attribute.type" id="_QGI8l-DOEfC7ivsSxMkT5A" value="string"/>
          <attribute defType="com.stambia.xml.attribute.originalType" id="_QGI8mODOEfC7ivsSxMkT5A" value="xs:string"/>
          <attribute defType="com.stambia.xml.attribute.use" id="_QGI8meDOEfC7ivsSxMkT5A" value="optional"/>
        </node>
        <node defType="com.stambia.xml.attribute" id="_QGI8muDOEfC7ivsSxMkT5A" name="company" position="5">
          <attribute defType="com.stambia.xml.attribute.type" id="_QGI8m-DOEfC7ivsSxMkT5A" value="string"/>
          <attribute defType="com.stambia.xml.attribute.originalType" id="_QGI8nODOEfC7ivsSxMkT5A" value="xs:string"/>
          <attribute defType="com.stambia.xml.attribute.use" id="_QGI8neDOEfC7ivsSxMkT5A" value="optional"/>
        </node>
        <node defType="com.stambia.xml.attribute" id="_QGI8nuDOEfC7ivsSxMkT5A" name="birthDate" position="6">
          <attribute defType="com.stambia.xml.attribute.type" id="_QGI8n-DOEfC7ivsSxMkT5A" value="dateTime"/>
          <attribute defType="com.stambia.xml.attribute.originalType" id="_QGI8oODOEfC7ivsSxMkT5A" value="xs:dateTime"/>
          <attribute defType="com.stambia.xml.attribute.use" id="_QGI8oeDOEfC7ivsSxMkT5A" value="optional"/>
        </node>
        <node defType="com.stambia.xml.sequence" id="_QGI8ouDOEfC7ivsSxMkT5A" position="10">
          <attribute defType="com.stambia.xml.sequence.minOccurs" id="_QGI8o-DOEfC7ivsSxMkT5A" value="1"/>
          <attribute defType="com.stambia.xml.sequence.maxOccurs" id="_QGI8pODOEfC7ivsSxMkT5A" value="1"/>
          <node defType="com.stambia.xml.element" id="_QGI8peDOEfC7ivsSxMkT5A" name="address" position="0">
            <attribute defType="com.stambia.xml.element.minOccurs" id="_QGI8puDOEfC7ivsSxMkT5A" value="0"/>
            <attribute defType="com.stambia.xml.element.maxOccurs" id="_QGI8p-DOEfC7ivsSxMkT5A" value="-1"/>
            <attribute defType="com.stambia.xml.element.originalType" id="_QGI8qODOEfC7ivsSxMkT5A" value="com:Address"/>
            <node defType="com.stambia.xml.attribute" id="_QGI8qeDOEfC7ivsSxMkT5A" name="addressId" position="0">
              <attribute defType="com.stambia.xml.attribute.type" id="_QGI8quDOEfC7ivsSxMkT5A" value="integer"/>
              <attribute defType="com.stambia.xml.attribute.originalType" id="_QGI8q-DOEfC7ivsSxMkT5A" value="xs:integer"/>
              <attribute defType="com.stambia.xml.attribute.use" id="_QGI8rODOEfC7ivsSxMkT5A" value="optional"/>
            </node>
            <node defType="com.stambia.xml.attribute" id="_QGI8reDOEfC7ivsSxMkT5A" name="addressDetails" position="1">
              <attribute defType="com.stambia.xml.attribute.type" id="_QGI8ruDOEfC7ivsSxMkT5A" value="string"/>
              <attribute defType="com.stambia.xml.attribute.originalType" id="_QGI8r-DOEfC7ivsSxMkT5A" value="xs:string"/>
              <attribute defType="com.stambia.xml.attribute.use" id="_QGI8sODOEfC7ivsSxMkT5A" value="optional"/>
            </node>
            <node defType="com.stambia.xml.attribute" id="_QGI8seDOEfC7ivsSxMkT5A" name="zipCode" position="2">
              <attribute defType="com.stambia.xml.attribute.type" id="_QGI8suDOEfC7ivsSxMkT5A" value="string"/>
              <attribute defType="com.stambia.xml.attribute.originalType" id="_QGI8s-DOEfC7ivsSxMkT5A" value="xs:string"/>
              <attribute defType="com.stambia.xml.attribute.use" id="_QGI8tODOEfC7ivsSxMkT5A" value="optional"/>
            </node>
            <node defType="com.stambia.xml.attribute" id="_QGI8teDOEfC7ivsSxMkT5A" name="city" position="3">
              <attribute defType="com.stambia.xml.attribute.type" id="_QGI8tuDOEfC7ivsSxMkT5A" value="string"/>
              <attribute defType="com.stambia.xml.attribute.originalType" id="_QGI8t-DOEfC7ivsSxMkT5A" value="xs:string"/>
              <attribute defType="com.stambia.xml.attribute.use" id="_QGI8uODOEfC7ivsSxMkT5A" value="optional"/>
            </node>
            <node defType="com.stambia.xml.attribute" id="_QGI8ueDOEfC7ivsSxMkT5A" name="stateCode" position="4">
              <attribute defType="com.stambia.xml.attribute.type" id="_QGI8uuDOEfC7ivsSxMkT5A" value="string"/>
              <attribute defType="com.stambia.xml.attribute.originalType" id="_QGI8u-DOEfC7ivsSxMkT5A" value="xs:string"/>
              <attribute defType="com.stambia.xml.attribute.use" id="_QGI8vODOEfC7ivsSxMkT5A" value="optional"/>
            </node>
          </node>
          <node defType="com.stambia.xml.element" id="_QGI8veDOEfC7ivsSxMkT5A" name="phone" position="1">
            <attribute defType="com.stambia.xml.element.minOccurs" id="_QGI8vuDOEfC7ivsSxMkT5A" value="0"/>
            <attribute defType="com.stambia.xml.element.maxOccurs" id="_QGI8v-DOEfC7ivsSxMkT5A" value="-1"/>
            <attribute defType="com.stambia.xml.element.originalType" id="_QGI8wODOEfC7ivsSxMkT5A" value="com:Phone"/>
            <node defType="com.stambia.xml.attribute" id="_QGI8weDOEfC7ivsSxMkT5A" name="phoneId" position="0">
              <attribute defType="com.stambia.xml.attribute.type" id="_QGI8wuDOEfC7ivsSxMkT5A" value="integer"/>
              <attribute defType="com.stambia.xml.attribute.originalType" id="_QGI8w-DOEfC7ivsSxMkT5A" value="xs:integer"/>
              <attribute defType="com.stambia.xml.attribute.use" id="_QGI8xODOEfC7ivsSxMkT5A" value="optional"/>
            </node>
            <node defType="com.stambia.xml.attribute" id="_QGI8xeDOEfC7ivsSxMkT5A" name="phoneTypeCode" position="1">
              <attribute defType="com.stambia.xml.attribute.type" id="_QGI8xuDOEfC7ivsSxMkT5A" value="string"/>
              <attribute defType="com.stambia.xml.attribute.originalType" id="_QGI8x-DOEfC7ivsSxMkT5A" value="xs:string"/>
              <attribute defType="com.stambia.xml.attribute.use" id="_QGI8yODOEfC7ivsSxMkT5A" value="optional"/>
            </node>
            <node defType="com.stambia.xml.attribute" id="_QGI8yeDOEfC7ivsSxMkT5A" name="phoneNumber" position="2">
              <attribute defType="com.stambia.xml.attribute.type" id="_QGI8yuDOEfC7ivsSxMkT5A" value="string"/>
              <attribute defType="com.stambia.xml.attribute.originalType" id="_QGI8y-DOEfC7ivsSxMkT5A" value="xs:string"/>
              <attribute defType="com.stambia.xml.attribute.use" id="_QGI8zODOEfC7ivsSxMkT5A" value="optional"/>
            </node>
            <node defType="com.stambia.xml.attribute" id="_QGI8zeDOEfC7ivsSxMkT5A" name="phoneType" position="3">
              <attribute defType="com.stambia.xml.attribute.type" id="_QGI8zuDOEfC7ivsSxMkT5A" value="string"/>
              <attribute defType="com.stambia.xml.attribute.originalType" id="_QGI8z-DOEfC7ivsSxMkT5A" value="xs:string"/>
              <attribute defType="com.stambia.xml.attribute.use" id="_QGI80ODOEfC7ivsSxMkT5A" value="optional"/>
            </node>
            <node defType="com.stambia.xml.attribute" id="_QGI80eDOEfC7ivsSxMkT5A" name="phoningAllowed" position="4">
              <attribute defType="com.stambia.xml.attribute.type" id="_QGI80uDOEfC7ivsSxMkT5A" value="boolean"/>
              <attribute defType="com.stambia.xml.attribute.originalType" id="_QGI80-DOEfC7ivsSxMkT5A" value="xs:boolean"/>
              <attribute defType="com.stambia.xml.attribute.use" id="_QGI81ODOEfC7ivsSxMkT5A" value="optional"/>
            </node>
          </node>
          <node defType="com.stambia.xml.element" id="_QGI81eDOEfC7ivsSxMkT5A" name="email" position="2">
            <attribute defType="com.stambia.xml.element.minOccurs" id="_QGI81uDOEfC7ivsSxMkT5A" value="0"/>
            <attribute defType="com.stambia.xml.element.maxOccurs" id="_QGI81-DOEfC7ivsSxMkT5A" value="-1"/>
            <attribute defType="com.stambia.xml.element.originalType" id="_QGI82ODOEfC7ivsSxMkT5A" value="com:Email"/>
            <node defType="com.stambia.xml.attribute" id="_QGI82eDOEfC7ivsSxMkT5A" name="emailId" position="0">
              <attribute defType="com.stambia.xml.attribute.type" id="_QGI82uDOEfC7ivsSxMkT5A" value="integer"/>
              <attribute defType="com.stambia.xml.attribute.originalType" id="_QGI82-DOEfC7ivsSxMkT5A" value="xs:integer"/>
              <attribute defType="com.stambia.xml.attribute.use" id="_QGI83ODOEfC7ivsSxMkT5A" value="optional"/>
            </node>
            <node defType="com.stambia.xml.attribute" id="_QGI83eDOEfC7ivsSxMkT5A" name="emailAddress" position="1">
              <attribute defType="com.stambia.xml.attribute.type" id="_QGI83uDOEfC7ivsSxMkT5A" value="string"/>
              <attribute defType="com.stambia.xml.attribute.originalType" id="_QGI83-DOEfC7ivsSxMkT5A" value="xs:string"/>
              <attribute defType="com.stambia.xml.attribute.use" id="_QGI84ODOEfC7ivsSxMkT5A" value="optional"/>
            </node>
            <node defType="com.stambia.xml.attribute" id="_QGI84eDOEfC7ivsSxMkT5A" name="emailType" position="2">
              <attribute defType="com.stambia.xml.attribute.type" id="_QGI84uDOEfC7ivsSxMkT5A" value="string"/>
              <attribute defType="com.stambia.xml.attribute.originalType" id="_QGI84-DOEfC7ivsSxMkT5A" value="xs:string"/>
              <attribute defType="com.stambia.xml.attribute.use" id="_QGI85ODOEfC7ivsSxMkT5A" value="optional"/>
            </node>
            <node defType="com.stambia.xml.attribute" id="_QGI85eDOEfC7ivsSxMkT5A" name="mailingAllowed" position="3">
              <attribute defType="com.stambia.xml.attribute.type" id="_QGI85uDOEfC7ivsSxMkT5A" value="boolean"/>
              <attribute defType="com.stambia.xml.attribute.originalType" id="_QGI85-DOEfC7ivsSxMkT5A" value="xs:boolean"/>
              <attribute defType="com.stambia.xml.attribute.use" id="_QGI86ODOEfC7ivsSxMkT5A" value="optional"/>
            </node>
          </node>
        </node>
      </node>
    </node>
  </node>
  <node defType="com.stambia.xml.namespace" id="_QGI8euDOEfC7ivsSxMkT5A" name="http://semarchy.com/samples/management">
    <attribute defType="com.stambia.xml.namespace.prefix" id="_QGI8e-DOEfC7ivsSxMkT5A" value="mgt"/>
  </node>
  <node defType="com.stambia.xml.namespace" id="_QGI8eODOEfC7ivsSxMkT5A" name="http://semarchy.com/samples/common">
    <attribute defType="com.stambia.xml.namespace.prefix" id="_QGI8eeDOEfC7ivsSxMkT5A" value="com"/>
  </node>
  <node defType="com.stambia.xml.namespace" id="_QGI8fODOEfC7ivsSxMkT5A" name="http://www.w3.org/2001/XMLSchema">
    <attribute defType="com.stambia.xml.namespace.prefix" id="_QGI8feDOEfC7ivsSxMkT5A" value="xs"/>
  </node>
</md:node>