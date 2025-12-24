<?xml version="1.0" encoding="UTF-8"?>
<md:node xmlns:md="http://www.stambia.com/md" defType="com.stambia.file.server" id="_zNxJcJiAEfC7MbyhL5_wzQ" md:ref="resource.md#UUID_TECH_FILE_MD?fileId=UUID_TECH_FILE_MD$type=md$name=File?" internalVersion="v2.0.0">
  <node defType="com.stambia.file.directory" id="_zQnCEJiAEfC7MbyhL5_wzQ" name="Reference_Files_Folder">
    <attribute defType="com.stambia.file.directory.path" id="_zRSXgJiAEfC7MbyhL5_wzQ" value="%{env:workspace_loc}%/Training/Files_In/Reference_Files"/>
    <node defType="com.stambia.file.file" id="_zRUMsJiAEfC7MbyhL5_wzQ" name="discount_range">
      <attribute defType="com.stambia.file.file.type" id="_zRt1UJiAEfC7MbyhL5_wzQ" value="DELIMITED"/>
      <attribute defType="com.stambia.file.file.lineSeparator" id="_zRxfsJiAEfC7MbyhL5_wzQ" value="0D0A"/>
      <attribute defType="com.stambia.file.file.fieldSeparator" id="_zRyGwJiAEfC7MbyhL5_wzQ" value="2C"/>
      <attribute defType="com.stambia.file.file.decimalSeparator" id="_zRzU4JiAEfC7MbyhL5_wzQ" value="2E"/>
      <attribute defType="com.stambia.file.file.lineToSkip" id="_zR0jAJiAEfC7MbyhL5_wzQ" value="0"/>
      <attribute defType="com.stambia.file.file.lastLineToSkip" id="_zR1KEJiAEfC7MbyhL5_wzQ" value="0"/>
      <attribute defType="com.stambia.file.file.header" id="_zR1xIJiAEfC7MbyhL5_wzQ" value="1"/>
      <attribute defType="com.stambia.file.file.physicalName" id="_6zAcgJiAEfC7MbyhL5_wzQ" value="DiscountRanges.txt"/>
      <node defType="com.stambia.file.field" id="_PfFC8JiBEfC7MbyhL5_wzQ" name="min" position="1">
        <attribute defType="com.stambia.file.field.size" id="_PfFC8ZiBEfC7MbyhL5_wzQ" value="12"/>
        <attribute defType="com.stambia.file.field.type" id="_PfFC8piBEfC7MbyhL5_wzQ" value="Numeric"/>
        <attribute defType="com.stambia.file.field.physicalName" id="_PfFC85iBEfC7MbyhL5_wzQ" value="MIN"/>
      </node>
      <node defType="com.stambia.file.field" id="_PfFC-JiBEfC7MbyhL5_wzQ" name="range" position="3">
        <attribute defType="com.stambia.file.field.size" id="_PfFC-ZiBEfC7MbyhL5_wzQ" value="62"/>
        <attribute defType="com.stambia.file.field.type" id="_PfFC-piBEfC7MbyhL5_wzQ" value="String"/>
        <attribute defType="com.stambia.file.field.physicalName" id="_PfFC-5iBEfC7MbyhL5_wzQ" value="RANGE"/>
      </node>
      <node defType="com.stambia.file.field" id="_PfFC9JiBEfC7MbyhL5_wzQ" name="max" position="2">
        <attribute defType="com.stambia.file.field.size" id="_PfFC9ZiBEfC7MbyhL5_wzQ" value="12"/>
        <attribute defType="com.stambia.file.field.type" id="_PfFC9piBEfC7MbyhL5_wzQ" value="Numeric"/>
        <attribute defType="com.stambia.file.field.physicalName" id="_PfFC95iBEfC7MbyhL5_wzQ" value="MAX"/>
      </node>
    </node>
  </node>
</md:node>