/*
 *    This reflects commentary at https://wilsonmar.github.io/jenkins2-pipeline/
 *    Still under construction.
 */
import hudson.model.*
import hudson.EnvVars
import groovy.json.JsonSlurperClassic
import groovy.json.JsonBuilder
import groovy.json.JsonOutput
import java.net.URL

node {
    
   stage '1'
   echo 'checkout'

   git url: "https://github.com/hotwilson/jenkins2.git"

   bat'git rev-parse HEAD > GIT_COMMIT'
   def shortCommit = readFile('GIT_COMMIT').take(6)

   stage '2'
   echo 'branch'
}
