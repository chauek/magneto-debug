# Magento Debug Toolbar 
Based on http://moprea.ro/2011/04/07/magento-debug-toolbar

## INSTALLATION

#### 1) Copy files catalogs to magento project

#### 2) Add debug option to local.xml, ex:

	<default>
        <debug>
            <options>
                <enable>1</enable>
            </options>
        </debug>
    </default>

#### 3) Set profiler parameter to 1 resource connection section in local.xml, ex:

	<default_setup>
		<connection>
			<!-- Please use a local database for HOC -->
			<host><![CDATA[localhost]]></host>
			<username><![CDATA[root]]></username>
			<password><![CDATA[]]></password>
			<dbname><![CDATA[magento]]></dbname>
			<active>1</active>
			<profiler>1</profiler>
		</connection>
	</default_setup>
