# jenkindsldocker
creating hellow world gradle dsl project
job('ShivDslTest') {
  	label('vci-sci-18.manhdev.com')
    description 'Build and test the app.'
    scm {
        github 'policedocker/jenkindsldocker'
    }
    steps {
        gradle 'hello'
    }
}
