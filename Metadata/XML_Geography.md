<?xml version="1.0" encoding="UTF-8"?>
<md:node xmlns:md="http://www.stambia.com/md" defType="com.stambia.xml.xsd" id="_J4oc4ODEEfC7ivsSxMkT5A" name="geography" md:ref="resource.md#UUID_MD_XML_DEFAULT?fileId=UUID_MD_XML_DEFAULT$type=md$name=Xml?" internalVersion="v2.0.0">
  <attribute defType="com.stambia.xml.xsd.xsdReverseVersion" id="_J4q5IODEEfC7ivsSxMkT5A" value="1"/>
  <attribute defType="com.stambia.xml.xsd.xmlPath" id="_PmR8MODEEfC7ivsSxMkT5A" value="%{env:workspace_loc}%/Training/Files_In/xml/geography.xml"/>
  <attribute defType="com.stambia.xml.xsd.xsdPath" id="_PmR8MeDEEfC7ivsSxMkT5A" value=""/>
  <node defType="com.stambia.xml.namespace" id="_PmNDseDEEfC7ivsSxMkT5A" name="http://stambia.org/samples/geography">
    <attribute defType="com.stambia.xml.namespace.prefix" id="_PmNDsuDEEfC7ivsSxMkT5A" value="geo"/>
  </node>
  <node defType="com.stambia.xml.root" id="_PmMcpeDEEfC7ivsSxMkT5A" name="geography">
    <attribute defType="com.stambia.xml.root.originalType" id="_PmMcpuDEEfC7ivsSxMkT5A" value="geo:geography"/>
    <node defType="com.stambia.xml.sequence" id="_PmMcp-DEEfC7ivsSxMkT5A">
      <attribute defType="com.stambia.xml.sequence.position" id="_PmMcqODEEfC7ivsSxMkT5A" value="0"/>
      <node defType="com.stambia.xml.element" id="_PmMcqeDEEfC7ivsSxMkT5A" name="state">
        <attribute defType="com.stambia.xml.element.originalType" id="_PmMcquDEEfC7ivsSxMkT5A" value="state"/>
        <attribute defType="com.stambia.xml.element.minOccurs" id="_PmMcq-DEEfC7ivsSxMkT5A" value="0"/>
        <attribute defType="com.stambia.xml.element.maxOccurs" id="_PmMcrODEEfC7ivsSxMkT5A" value="-1"/>
        <node defType="com.stambia.xml.attribute" id="_PmMcreDEEfC7ivsSxMkT5A" name="stateName">
          <attribute defType="com.stambia.xml.attribute.type" id="_PmMcruDEEfC7ivsSxMkT5A" value="string"/>
          <attribute defType="com.stambia.xml.attribute.position" id="_PmMcr-DEEfC7ivsSxMkT5A" value="0"/>
        </node>
        <node defType="com.stambia.xml.attribute" id="_PmMcsODEEfC7ivsSxMkT5A" name="upperCaseName">
          <attribute defType="com.stambia.xml.attribute.type" id="_PmMcseDEEfC7ivsSxMkT5A" value="string"/>
          <attribute defType="com.stambia.xml.attribute.position" id="_PmMcsuDEEfC7ivsSxMkT5A" value="1"/>
        </node>
        <node defType="com.stambia.xml.attribute" id="_PmMcs-DEEfC7ivsSxMkT5A" name="code">
          <attribute defType="com.stambia.xml.attribute.type" id="_PmMctODEEfC7ivsSxMkT5A" value="string"/>
          <attribute defType="com.stambia.xml.attribute.position" id="_PmMcteDEEfC7ivsSxMkT5A" value="2"/>
        </node>
        <node defType="com.stambia.xml.sequence" id="_PmMctuDEEfC7ivsSxMkT5A">
          <attribute defType="com.stambia.xml.sequence.position" id="_PmMct-DEEfC7ivsSxMkT5A" value="0"/>
          <node defType="com.stambia.xml.element" id="_PmMcuODEEfC7ivsSxMkT5A" name="city">
            <attribute defType="com.stambia.xml.element.originalType" id="_PmMcueDEEfC7ivsSxMkT5A" value="city"/>
            <attribute defType="com.stambia.xml.element.minOccurs" id="_PmMcuuDEEfC7ivsSxMkT5A" value="0"/>
            <attribute defType="com.stambia.xml.element.maxOccurs" id="_PmMcu-DEEfC7ivsSxMkT5A" value="-1"/>
            <node defType="com.stambia.xml.attribute" id="_PmMcvODEEfC7ivsSxMkT5A" name="zipCode">
              <attribute defType="com.stambia.xml.attribute.type" id="_PmMcveDEEfC7ivsSxMkT5A" value="integer"/>
              <attribute defType="com.stambia.xml.attribute.position" id="_PmMcvuDEEfC7ivsSxMkT5A" value="0"/>
            </node>
            <node defType="com.stambia.xml.attribute" id="_PmMcv-DEEfC7ivsSxMkT5A" name="cityName">
              <attribute defType="com.stambia.xml.attribute.type" id="_PmMcwODEEfC7ivsSxMkT5A" value="string"/>
              <attribute defType="com.stambia.xml.attribute.position" id="_PmNDsODEEfC7ivsSxMkT5A" value="1"/>
            </node>
          </node>
        </node>
      </node>
    </node>
  </node>
</md:node>