Based on http://moprea.ro/2011/04/07/magento-debug-toolbar

to local.xml:
<profiler>1</profiler> in:

			<default_setup>
                <connection>
					<!-- Please use a local database for HOC -->
                    <host><![CDATA[localhost]]></host>
                    <username><![CDATA[root]]></username>
                    <password><![CDATA[root]]></password>
                    <dbname><![CDATA[hoc]]></dbname>
                    <active>1</active>
                    <profiler>1</profiler>
                </connection>
            </default_setup>







	<default>
        <debug>
            <options>
                <enable>1</enable>
            </options>
        </debug>
    </default>
