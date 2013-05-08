ant-droid.dir:
    "${ant.file.ant-droid.buildtasks}"

ant-droid.properties:
    ${ant.project.name}.properties" 

ant-droid.app.package:
    Default: "com.ant-droid.config" 

ant-droid.config.target-path:
    Default: ${source.dir}/com/ant-droid/config" 

ant-droid.app.target:
    Default: "dev" 

ant-droid.app.target:
    Default: "$(basedir)/$(ant-droid.app.target}.properties"

ant-droid.app.ver.full:
    Default: ${ant-droid.app.name}-${ant-droid.app.ver.major}.${ant-droid.app.ver.minor}.\
		${ant-droid.app.ver.inline}.${ant-droid.app.ver.build}-${ant-droid.app.target}" 

ant-droid.app.package:
    Default: default="${ant-droid.app.package}" 

ant-droid.app.name:
    Default="${ant.project.name}"

ant-droid.app.ver.major:
    Type="int" Default="1"

ant-droid.app.ver.minor:
    type="int" Default="0"

ant-droid.app.ver.inline:
    type="int" Default="0"

ant-droid.app.ver:
     Default: ${ant-droid.app.ver.major}.${ant-droid.app.ver.minor}" 

ant-droid.app.config.debug:
    Default: "false" 

ant-droid.app.config.logging:
    Default: "false" 

ant-droid.app.ver.inline:
    type="int" Default="0"

ant-droid.config.template:
    Default: ${ant-droid.dir}/config/AppConfig.java" 

ant-droid.config.manifest.template:
    Default: ${basedir}/AndroidManifest.xml" 
