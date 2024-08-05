# Changelog for toolkit-test

## Changes to direct dependencies
 - Updated `org.scala-lang:toolkit_3:0.4.0` from `0.4.0` to `0.5.0` under `org.scala-lang:toolkit-test_3:0.5.0`

## Changes to transitive dependencies
 - Updated `com.lihaoyi:os-lib_3:0.10.0` from `0.10.0` to `0.10.2` under `org.scala-lang:toolkit_3:0.5.0`
 - Updated `com.lihaoyi:ujson_3:3.3.0` from `3.3.0` to `3.3.1` under `com.lihaoyi:upickle_3:3.3.1`
 - Updated `com.lihaoyi:upack_3:3.3.0` from `3.3.0` to `3.3.1` under `com.lihaoyi:upickle_3:3.3.1`
 - Updated `com.lihaoyi:upickle-core_3:3.3.0` from `3.3.0` to `3.3.1` under `com.lihaoyi:ujson_3:3.3.1`
 - Updated `com.lihaoyi:upickle-core_3:3.3.0` from `3.3.0` to `3.3.1` under `com.lihaoyi:upack_3:3.3.1`
 - Updated `com.lihaoyi:upickle-core_3:3.3.0` from `3.3.0` to `3.3.1` under `com.lihaoyi:upickle-implicits_3:3.3.1`
 - Updated `com.lihaoyi:upickle-implicits_3:3.3.0` from `3.3.0` to `3.3.1` under `com.lihaoyi:upickle_3:3.3.1`
 - Updated `com.lihaoyi:upickle_3:3.3.0` from `3.3.0` to `3.3.1` under `org.scala-lang:toolkit_3:0.5.0`

## Full dependency tree

 - org.scala-lang:toolkit-test_3:0.5.0
   - org.scala-lang:toolkit_3:0.5.0
     - com.lihaoyi:os-lib_3:0.10.2
       - com.lihaoyi:geny_3:1.1.0
     - com.lihaoyi:upickle_3:3.3.1
       - com.lihaoyi:ujson_3:3.3.1
         - com.lihaoyi:upickle-core_3:3.3.1
           - com.lihaoyi:geny_3:1.1.0 (already listed)
       - com.lihaoyi:upack_3:3.3.1
         - com.lihaoyi:upickle-core_3:3.3.1 (already listed)
       - com.lihaoyi:upickle-implicits_3:3.3.1
         - com.lihaoyi:upickle-core_3:3.3.1 (already listed)
     - com.softwaremill.sttp.client4:core_3:4.0.0-M14
       - com.softwaremill.sttp.model:core_3:1.7.10
       - com.softwaremill.sttp.shared:core_3:1.3.18
       - com.softwaremill.sttp.shared:ws_3:1.3.18
         - com.softwaremill.sttp.model:core_3:1.7.10 (already listed)
         - com.softwaremill.sttp.shared:core_3:1.3.18 (already listed)
     - com.softwaremill.sttp.client4:upickle_3:4.0.0-M14
       - com.lihaoyi:upickle_3:3.3.0
         - com.lihaoyi:ujson_3:3.3.1 (already listed)
         - com.lihaoyi:upack_3:3.3.1 (already listed)
         - com.lihaoyi:upickle-implicits_3:3.3.1 (already listed)
       - com.softwaremill.sttp.client4:core_3:4.0.0-M14 (already listed)
       - com.softwaremill.sttp.client4:json-common_3:4.0.0-M14
         - com.softwaremill.sttp.client4:core_3:4.0.0-M14 (already listed)
   - org.scalameta:munit_3:1.0.0-RC1
     - junit:junit:4.13.2
       - org.hamcrest:hamcrest-core:1.3.0
     - org.scalameta:junit-interface:1.0.0-RC1
       - junit:junit:4.13.2 (already listed)
       - org.scala-sbt:test-interface:1.0.0
     - org.scalameta:munit-diff_3:1.0.0-RC1