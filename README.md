# ReactiveSystemsTutorial
create new maven project
    # mvn io.fabric8:vertx-maven-plugin:{$version}:setup \
    #    -DprojectGroupId={$projectGroupId} \
    #    -DprojectArtifactId={$artifactName} \
    #    -Dverticle={$package and name of verticle}

# Example 
mvn io.fabric8:vertx-maven-plugin:1.0.9:setup \
 -DprojectGroupId=io.vertx.sample \
 -DprojectArtifactId=my-first-vertx-app \
 -Dverticle=io.vertx.sample.MyFirstVerticle
