#### mThorAuto

> <https://git.ringcentral.com/XMNTA/mThorAuto>

Android-local.run.xml
```xml
<component name="ProjectRunConfigurationManager">
  <configuration default="false" name="Android-local" type="TestNG" folderName="local">
    <module name="mThorAuto" />
    <shortenClasspath name="NONE" />
    <useClassPathOnly />
    <option name="ALTERNATIVE_JRE_PATH_ENABLED" value="true" />
    <option name="ALTERNATIVE_JRE_PATH" value="1.8" />
    <option name="SUITE_NAME" value="" />
    <option name="PACKAGE_NAME" value="com.ringcentral.ta.glip.test.testlink.bdd" />
    <option name="MAIN_CLASS_NAME" value="com.ringcentral.ta.glip.test.testlink.bdd.TestRunner" />
    <option name="GROUP_NAME" value="" />
    <option name="TEST_OBJECT" value="CLASS" />
    <option name="VM_PARAMETERS" value="-Dcucumber.features=src/features/ -Dcucumber.filter.tags=&quot;(@XX) and @Android and @RC&quot; -Dtest=TestRunner -DTOD.nodeUrl=127.0.0.1 -DTOD.nodePort=4723 -DTOD.system_port=9001 -DTOD.version=1 -DTOD.deviceName=1 -DTOD.platform=android -DTOD.UDID=emulator-5554 -DTOD.glipEnvName=webaqaxmn-rc -DTOD.appName=$USER_HOME$/Downloads/BrandApp/web-aqa-xmn-ringcentral-inhouse-debug.apk -Ddebug.domain= -DLocalDebug=true" />
    <option name="PARAMETERS" value="" />
    <option name="OUTPUT_DIRECTORY" value="" />
    <option name="TEST_SEARCH_SCOPE">
      <value defaultName="moduleWithDependencies" />
    </option>
    <option name="PROPERTIES_FILE" value="" />
    <properties />
    <listeners />
    <method v="2">
      <option name="Make" enabled="true" />
    </method>
  </configuration>
</component>
```

real-iOS-local.run.xml
```xml
<component name="ProjectRunConfigurationManager">
  <configuration default="false" name="real-iOS-local" type="TestNG" folderName="local">
    <module name="mThorAuto" />
    <shortenClasspath name="NONE" />
    <useClassPathOnly />
    <option name="ALTERNATIVE_JRE_PATH_ENABLED" value="true" />
    <option name="ALTERNATIVE_JRE_PATH" value="1.8" />
    <option name="SUITE_NAME" value="" />
    <option name="PACKAGE_NAME" value="com.ringcentral.ta.glip.test.testlink.bdd" />
    <option name="MAIN_CLASS_NAME" value="com.ringcentral.ta.glip.test.testlink.bdd.TestRunner" />
    <option name="GROUP_NAME" value="" />
    <option name="TEST_OBJECT" value="CLASS" />
    <option name="VM_PARAMETERS" value="-Dcucumber.features=src/features/ -Dcucumber.filter.tags=&quot;(@XX) and (@iOS or @IOS) and @RC&quot; -Dtest=TestRunner -DTOD.nodeUrl=127.0.0.1 -DTOD.nodePort=4723 -DTOD.system_port=9001 -DTOD.version=13 -DTOD.isSimulator=false -DTOD.deviceName=1 -DTOD.platform=ios -DTOD.UDID= -DTOD.glipEnvName=webaqaxmn-rc -DTOD.appName=$USER_HOME$/Downloads/BrandApp/WEB-AQA-XMN-Glip-Adhoc.ipa -Ddebug.domain= -DLocalDebug=true -DFULLRESET=false" />
    <option name="PARAMETERS" value="" />
    <option name="OUTPUT_DIRECTORY" value="" />
    <option name="TEST_SEARCH_SCOPE">
      <value defaultName="moduleWithDependencies" />
    </option>
    <option name="PROPERTIES_FILE" value="" />
    <properties />
    <listeners />
    <method v="2">
      <option name="Make" enabled="true" />
    </method>
  </configuration>
</component>
```

simu-iOS-local.run.xml
```xml
<component name="ProjectRunConfigurationManager">
  <configuration default="false" name="simu-iOS-local" type="TestNG" folderName="local">
    <module name="mThorAuto" />
    <shortenClasspath name="NONE" />
    <useClassPathOnly />
    <option name="ALTERNATIVE_JRE_PATH_ENABLED" value="true" />
    <option name="ALTERNATIVE_JRE_PATH" value="1.8" />
    <option name="SUITE_NAME" value="" />
    <option name="PACKAGE_NAME" value="com.ringcentral.ta.glip.test.testlink.bdd" />
    <option name="MAIN_CLASS_NAME" value="com.ringcentral.ta.glip.test.testlink.bdd.TestRunner" />
    <option name="GROUP_NAME" value="" />
    <option name="TEST_OBJECT" value="CLASS" />
    <option name="VM_PARAMETERS" value="-Dcucumber.features=src/features/ -Dcucumber.filter.tags=&quot;(@XX) and (@iOS or @IOS) and @RC&quot; -Dtest=TestRunner -DTOD.nodeUrl=127.0.0.1 -DTOD.nodePort=4723 -DTOD.system_port=9001 -DTOD.version=13 -DTOD.isSimulator=true -DTOD.deviceName=1 -DTOD.platform=ios -DTOD.UDID=893A0AFC-1BD8-4B84-8EC9-5B95FE7CFFD5 -DTOD.glipEnvName=webaqaxmn-rc -DTOD.appName=$USER_HOME$/Downloads/BrandApp/WEB-AQA-XMN-Glip.zip -Ddebug.domain= -DLocalDebug=true -DFULLRESET=false" />
    <option name="PARAMETERS" value="" />
    <option name="OUTPUT_DIRECTORY" value="" />
    <option name="TEST_SEARCH_SCOPE">
      <value defaultName="moduleWithDependencies" />
    </option>
    <option name="PROPERTIES_FILE" value="" />
    <properties />
    <listeners />
    <method v="2">
      <option name="Make" enabled="true" />
    </method>
  </configuration>
</component>
```

Android-remote.run.xml
```xml
<component name="ProjectRunConfigurationManager">
  <configuration default="false" name="Android-remote" type="TestNG" folderName="remote">
    <module name="mThorAuto" />
    <shortenClasspath name="NONE" />
    <useClassPathOnly />
    <option name="SUITE_NAME" value="" />
    <option name="PACKAGE_NAME" value="com.ringcentral.ta.glip.test.testlink.bdd" />
    <option name="MAIN_CLASS_NAME" value="com.ringcentral.ta.glip.test.testlink.bdd.TestRunner" />
    <option name="GROUP_NAME" value="" />
    <option name="TEST_OBJECT" value="CLASS" />
    <option name="VM_PARAMETERS" value="-Dtest=TestRunner -Dcucumber.features=src/features/ -Dcucumber.filter.tags=&quot;(@XX) and @Android and @RC&quot; -DTOD.platform=android -DTOD.deviceName=1 -DTOD.isAccountPoolEnabled=true -DTOD.glipEnvName=webaqaxmn-rc -DTOD.AUTO_DISPATCH_DEVICE=true -DTOD.PARALLEL_THREAD_COUNT=5 -DstartIWDP=true -Ddebug.domain= -DcustomizedUdid= -DenableDashboard=false -DLocalDebug=true" />
    <option name="PARAMETERS" value="" />
    <option name="OUTPUT_DIRECTORY" value="" />
    <option name="TEST_SEARCH_SCOPE">
      <value defaultName="moduleWithDependencies" />
    </option>
    <option name="PROPERTIES_FILE" value="" />
    <properties />
    <listeners />
    <method v="2">
      <option name="Make" enabled="true" />
    </method>
  </configuration>
</component>
```

iOS-remote.run.xml
```xml
<component name="ProjectRunConfigurationManager">
  <configuration default="false" name="iOS-remote" type="TestNG" folderName="remote">
    <module name="mThorAuto" />
    <shortenClasspath name="NONE" />
    <useClassPathOnly />
    <option name="SUITE_NAME" value="" />
    <option name="PACKAGE_NAME" value="com.ringcentral.ta.glip.test.testlink.bdd" />
    <option name="MAIN_CLASS_NAME" value="com.ringcentral.ta.glip.test.testlink.bdd.TestRunner" />
    <option name="GROUP_NAME" value="" />
    <option name="TEST_OBJECT" value="CLASS" />
    <option name="VM_PARAMETERS" value="-Dtest=TestRunner -Dcucumber.features=src/features/ -Dcucumber.filter.tags=&quot;(@XX) and (@iOS or @IOS) and @RC&quot; -DTOD.platform=ios -DTOD.deviceName=1 -DTOD.isAccountPoolEnabled=true -DTOD.glipEnvName=webaqaxmn-rc -DTOD.AUTO_DISPATCH_DEVICE=true -DTOD.PARALLEL_THREAD_COUNT=5 -DstartIWDP=true -Ddebug.domain= -DcustomizedUdid= -DenableDashboard=false -DLocalDebug=true" />
    <option name="PARAMETERS" value="" />
    <option name="OUTPUT_DIRECTORY" value="" />
    <option name="TEST_SEARCH_SCOPE">
      <value defaultName="moduleWithDependencies" />
    </option>
    <option name="PROPERTIES_FILE" value="" />
    <properties />
    <listeners />
    <method v="2">
      <option name="Make" enabled="true" />
    </method>
  </configuration>
</component>
```

#### LocalDebugTool
```bash
chmod 777 scripts/load-local-debug-tool-customized-TestStep.sh
./scripts/load-local-debug-tool-customized-TestStep.sh
```
