# jackson-dataformat-xml-osgi

jackson-dataformat-xml (and its dependencies) repackaged as an OSGI bundle.

For Apache Felix/ Adobe Experience Manager (AEM)

## Building
Run `mvn clean install` to generate the OSGI bundle `target/jackson-dataformat-xml-osgi-2.8.8.jar`.

Deploy the bundle to your OSGI instance.

For Apache Felix/AEM:

1. Go to `http://<host>:<port>/system/console/bundles`
2. Click "install/update..." button (top left corner)
3. Check "Start bundle" and "Refresh Packages"
4. Chose the jar from it's location
5. Click "Install or Update" button
