"C:\Program Files\Java\jdk-12.0.1\bin\java.exe" -agentlib:jdwp=transport=dt_socket,address=localhost:58272,suspend=n,server=y -Xdebug -server -Dsbt.supershell=false -Xms512M -Xmx4096M -Xss2M -XX:MaxMetaspaceSize=1024M -Didea.managed=true -Dfile.encoding=UTF-8 -Dsbt.log.noformat=true -jar C:\Users\Rocky\.IdeaIC2019.2\config\plugins\Scala\launcher\sbt-launch.jar --addPluginSbtFile=C:\Users\Rocky\AppData\Local\Temp\idea.sbt "; set ideaPort in Global := 58267 ; idea-shell"
Listening for transport dt_socket at address: 58272
[info] Loading settings for project global-plugins from idea.sbt ...
[info] Loading global plugins from C:\Users\Rocky\.sbt\1.0\plugins
error: error while loading String, class file '/modules/java.base/java/lang/String.class' is broken
(class java.lang.NullPointerException/null)
[info] Loading settings for project picchu-backend-build from license.sbt,plugins.sbt,sbt-native-packager.sbt ...
[info] Loading project definition from D:\scala_workspace\picchu-backend\project
[info] Updating ProjectRef(uri("file:/D:/scala_workspace/picchu-backend/project/"), "picchu-backend-build")...
[info] Done updating.
[warn] There may be incompatibilities among your library dependencies; run 'evicted' to see detailed eviction warnings.
error: error while loading String, class file '/modules/java.base/java/lang/String.class' is broken
(class java.lang.NullPointerException/null)
[info] Loading settings for project rootProject from build.sbt ...
[info] Set current project to picchu-backend (in build file:/D:/scala_workspace/picchu-backend/)
[info] Configured .env environment
WARNING: An illegal reflective access operation has occurred
WARNING: Illegal reflective access by au.com.onegeek.sbtdotenv.DirtyEnvironmentHack$ (file:/C:/Users/Rocky/.ivy2/cache/scala_2.12/sbt_1.0/au.com.onegeek/sbt-dotenv/jars/sbt-dotenv-2.0.117.jar) to field java.lang.ProcessEnvironment.theEnvironment
WARNING: Please consider reporting this to the maintainers of au.com.onegeek.sbtdotenv.DirtyEnvironmentHack$
WARNING: Use --illegal-access=warn to enable warnings of further illegal reflective access operations
WARNING: All illegal access operations will be denied in a future release
error: error while loading String, class file '/modules/java.base/java/lang/String.class' is broken
(class java.lang.NullPointerException/null)


[info] Defining Global / ideaPort
[info] The new value will be used by Compile / compile, Test / compile and 1 others.
[info]  Run `last` for details.
[info] Reapplying settings...
[info] Set current project to picchu-backend (in build file:/D:/scala_workspace/picchu-backend/)
[info] Configured .env environment
[IJ]picchu-backend(master)> ;reload; set _root_.org.jetbrains.sbt.StructureKeys.sbtStructureOptions in Global := "download resolveClassifiers resolveSbtClassifiers" ;*/*:dumpStructureTo C:/Users/Rocky/AppData/Local/Temp/sbt-structure.xml; session clear-all ; set ideaPort in Global := 58267
[info] Loading settings for project global-plugins from idea.sbt ...
[info] Loading global plugins from C:\Users\Rocky\.sbt\1.0\plugins
[info] Loading settings for project picchu-backend-build from license.sbt,plugins.sbt,sbt-native-packager.sbt ...
[info] Loading project definition from D:\scala_workspace\picchu-backend\project
[info] Loading settings for project rootProject from build.sbt ...
[warn] Discarding 1 session setting.  Use 'session save' to persist session settings.
[info] Set current project to picchu-backend (in build file:/D:/scala_workspace/picchu-backend/)
[info] Configured .env environment
error: error while loading String, class file '/modules/java.base/java/lang/String.class' is broken
(class java.lang.NullPointerException/null)
[info] Defining Global / sbtStructureOptions
[info] The new value will be used by Global / ssOptions
[info] Reapplying settings...
[info] Set current project to picchu-backend (in build file:/D:/scala_workspace/picchu-backend/)
[info] Configured .env environment
[info] Writing structure to C:\Users\Rocky\AppData\Local\Temp\sbt-structure.xml...
[info] Done.
[success] Total time: 248 s, completed 2019���?????����?12:28:15
8:15
[info] Reapplying settings...
[info] Set current project to picchu-backend (in build file:/D:/scala_workspace/picchu-backend/)
[info] Configured .env environment
[info] Defining Global / ideaPort
[info] The new value will be used by Compile / compile, Test / compile and 1 others.
[info]  Run `last` for details.
[info] Reapplying settings...
[info] Set current project to picchu-backend (in build file:/D:/scala_workspace/picchu-backend/)
[info] Configured .env environment
[IJ]picchu-backend(master)>
[IJ]picchu-backend(master)> compile
[info] Formatting 229 Scala sources...
[info] Reformatted 215 Scala sources
[info] Compiling 215 Scala sources and 14 Java sources to D:\scala_workspace\picchu-backend\target\scala-2.12\classes ...
[warn]  [E1] src\main\scala\com\picchu\picchubackend\services\GetPostDetailService.scala
[warn]       parameter value getPostService in class GetPostDetailService is never used
[warn]       L19:     getPostService: FindPostService,
[warn]                ^
[warn]  [E2] src\main\scala\com\picchu\picchubackend\services\db\countrySetting\MultiUpsertCountrySettingsService.scala
[warn]       pattern var e in method applyOrElse is never used; `e@_' suppresses this warning
[warn]       L51:               case NonFatal(e) =>
[warn]                                        ^




[warn]  [E3] src\main\scala\com\picchu\picchubackend\services\db\errorCode\MultiUpsertErrorCodesService.scala
[warn]       pattern var e in method applyOrElse is never used; `e@_' suppresses this warning
[warn]       L51:               case NonFatal(e) =>
[warn]                                        ^
[warn]  [E4] src\main\scala\com\picchu\picchubackend\services\db\stringMapping\MultiUpsertStringMappingService.scala
[warn]       pattern var e in method applyOrElse is never used; `e@_' suppresses this warning
[warn]       L51:               case NonFatal(e) =>
[warn]                                        ^
[warn] src\main\scala\com\picchu\picchubackend\services\db\stringMapping\MultiUpsertStringMappingService.scala: L51 [E4]
[warn] src\main\scala\com\picchu\picchubackend\services\db\countrySetting\MultiUpsertCountrySettingsService.scala: L51 [E2]
[warn] src\main\scala\com\picchu\picchubackend\services\GetPostDetailService.scala: L19 [E1]
[warn] src\main\scala\com\picchu\picchubackend\services\db\errorCode\MultiUpsertErrorCodesService.scala: L51 [E3]
[info] Legend: Ln = line n, Cn = column n, En = error n
[info] Done compiling.
[success] Total time: 96 s, completed 2019���?????����?12:35:25
5:25
[IJ]picchu-backend(master)> test
[info] Formatting 215 Scala sources...
[info] Formatting 7 Scala sources...
[info] Reformatted 7 Scala sources
[info] Compiling 7 Scala sources to D:\scala_workspace\picchu-backend\target\scala-2.12\test-classes ...
[warn]  [E1] src\test\scala\com\picchu\picchubackend\MongoTestKit.scala
[warn]       Java enum V3_0 in Java enum Main is deprecated: see corresponding Javadoc for more information.
[warn]       L54:     val config    = new MongodConfigBuilder().version(Version.Main.V3_0).net(net).build()
[warn]                                                                               ^
[warn]  [E2] src\test\scala\com\picchu\picchubackend\MongoTestKit.scala
[warn]       Unused import
[warn]       L27: import com.github.mehmetakiftutuncu.errors.{CommonError, Errors, Maybe}
[warn]                                                                     ^
[warn]  [E3] src\test\scala\com\picchu\picchubackend\MongoTestKit.scala
[warn]       Unused import
[warn]       L27: import com.github.mehmetakiftutuncu.errors.{CommonError, Errors, Maybe}
[warn]                                                                             ^
[warn]  [E4] src\test\scala\com\picchu\picchubackend\MongoTestKit.scala
[warn]       Unused import
[warn]       L33: import mouse.boolean._
[warn]                                 ^
[warn]  [E5] src\test\scala\com\picchu\picchubackend\MongoTestKit.scala
[warn]       Unused import
[warn]       L41: import reactivemongo.api.indexes.{Index, IndexType}
[warn]                                              ^
[warn]  [E6] src\test\scala\com\picchu\picchubackend\MongoTestKit.scala
[warn]       Unused import
[warn]       L41: import reactivemongo.api.indexes.{Index, IndexType}
[warn]                                                     ^
[warn]  [E7] src\test\scala\com\picchu\picchubackend\MongoTestKit.scala
[warn]       Unused import
[warn]       L43: import scala.concurrent.Future
[warn]                                    ^
[warn]  [E8] src\test\scala\com\picchu\picchubackend\controllers\FeatureTestBase.scala
[warn]       Unused import
[warn]       L6: import com.picchu.picchubackend.models.http.AccountSignUpResult
[warn]                                                       ^
[warn] src\test\scala\com\picchu\picchubackend\MongoTestKit.scala: L27 [E2], L27 [E3], L33 [E4], L41 [E5], L41 [E6], L43 [E7], L54 [E1]
[warn] src\test\scala\com\picchu\picchubackend\controllers\FeatureTestBase.scala: L6 [E8]
[info] Legend: Ln = line n, Cn = column n, En = error n
[info] Done compiling.
04:36:09.347 [pool-47-thread-7] INFO  c.t.util.logging.Slf4jBridgeUtility$ - org.slf4j.bridge.SLF4JBridgeHandler installed.
04:36:09.987 [pool-47-thread-7] DEBUG i.n.u.i.l.InternalLoggerFactory - Using SLF4J as the default logging framework
04:36:09.999 [pool-47-thread-7] DEBUG io.netty.util.ResourceLeakDetector - -Dio.netty.leakDetection.level: simple
04:36:10.003 [pool-47-thread-7] DEBUG io.netty.util.ResourceLeakDetector - -Dio.netty.leakDetection.targetRecords: 4
04:36:10.051 [pool-47-thread-7] DEBUG i.n.util.internal.PlatformDependent - Platform: Windows
04:36:10.051 [pool-47-thread-7] DEBUG i.n.util.internal.PlatformDependent0 - -Dio.netty.noUnsafe: false
04:36:10.055 [pool-47-thread-7] DEBUG i.n.util.internal.PlatformDependent0 - Java version: 12
04:36:10.055 [pool-47-thread-7] DEBUG i.n.util.internal.PlatformDependent0 - sun.misc.Unsafe.theUnsafe: available
04:36:10.059 [pool-47-thread-7] DEBUG i.n.util.internal.PlatformDependent0 - sun.misc.Unsafe.copyMemory: available
04:36:10.059 [pool-47-thread-7] DEBUG i.n.util.internal.PlatformDependent0 - java.nio.Buffer.address: available
04:36:10.071 [pool-47-thread-7] DEBUG i.n.util.internal.PlatformDependent0 - direct buffer constructor: unavailable
java.lang.UnsupportedOperationException: Reflective setAccessible(true) disabled
        at io.netty.util.internal.ReflectionUtil.trySetAccessible(ReflectionUtil.java:31)
        at io.netty.util.internal.PlatformDependent0$4.run(PlatformDependent0.java:224)
        at java.base/java.security.AccessController.doPrivileged(AccessController.java:310)
        at io.netty.util.internal.PlatformDependent0.<clinit>(PlatformDependent0.java:218)
        at io.netty.util.internal.PlatformDependent.isAndroid(PlatformDependent.java:212)
        at io.netty.util.internal.PlatformDependent.<clinit>(PlatformDependent.java:80)
        at io.netty.util.ResourceLeakDetector.<init>(ResourceLeakDetector.java:162)
        at io.netty.util.ResourceLeakDetector.<init>(ResourceLeakDetector.java:207)
        at io.netty.util.ResourceLeakDetectorFactory$DefaultResourceLeakDetectorFactory.newResourceLeakDetector(ResourceLeakDetectorFactory.java:201)
        at io.netty.util.HashedWheelTimer.<clinit>(HashedWheelTimer.java:88)
        at com.twitter.finagle.netty4.HashedWheelTimer$.<init>(Netty4HashedWheelTimer.scala:79)
        at com.twitter.finagle.netty4.HashedWheelTimer$.<clinit>(Netty4HashedWheelTimer.scala)
        at com.twitter.finagle.netty4.Netty4HashedWheelTimer.<init>(Netty4HashedWheelTimer.scala:108)
        at java.base/jdk.internal.reflect.NativeConstructorAccessorImpl.newInstance0(Native Method)
        at java.base/jdk.internal.reflect.NativeConstructorAccessorImpl.newInstance(NativeConstructorAccessorImpl.java:62)
        at java.base/jdk.internal.reflect.DelegatingConstructorAccessorImpl.newInstance(DelegatingConstructorAccessorImpl.java:45)
        at java.base/java.lang.reflect.Constructor.newInstanceWithCaller(Constructor.java:500)
        at java.base/java.lang.reflect.ReflectAccess.newInstance(ReflectAccess.java:166)
        at java.base/jdk.internal.reflect.ReflectionFactory.newInstance(ReflectionFactory.java:404)
        at java.base/java.lang.Class.newInstance(Class.java:590)
        at com.twitter.app.LoadService$.$anonfun$loadImpls$7(LoadService.scala:192)
        at scala.collection.TraversableLike.$anonfun$flatMap$1(TraversableLike.scala:241)
        at scala.collection.mutable.ResizableArray.foreach(ResizableArray.scala:59)
        at scala.collection.mutable.ResizableArray.foreach$(ResizableArray.scala:52)
        at scala.collection.mutable.ArrayBuffer.foreach(ArrayBuffer.scala:48)
        at scala.collection.TraversableLike.flatMap(TraversableLike.scala:241)
        at scala.collection.TraversableLike.flatMap$(TraversableLike.scala:238)
        at scala.collection.AbstractTraversable.flatMap(Traversable.scala:104)
        at com.twitter.app.LoadService$.loadImpls(LoadService.scala:181)
        at com.twitter.app.LoadService$.apply(LoadService.scala:135)
        at com.twitter.app.LoadService$.apply(LoadService.scala:149)
        at com.twitter.finagle.util.LoadService$.apply(LoadService.scala:14)
        at com.twitter.finagle.util.DefaultTimer$.<init>(DefaultTimer.scala:80)
        at com.twitter.finagle.util.DefaultTimer$.<clinit>(DefaultTimer.scala)
        at com.twitter.finagle.stats.JsonExporter.<init>(JsonExporter.scala:140)
        at com.twitter.finagle.stats.MetricsExporter.<init>(MetricsStatsReceiver.scala:141)
        at com.twitter.finagle.stats.MetricsExporter.<init>(MetricsStatsReceiver.scala:144)
        at java.base/jdk.internal.reflect.NativeConstructorAccessorImpl.newInstance0(Native Method)
        at java.base/jdk.internal.reflect.NativeConstructorAccessorImpl.newInstance(NativeConstructorAccessorImpl.java:62)
        at java.base/jdk.internal.reflect.DelegatingConstructorAccessorImpl.newInstance(DelegatingConstructorAccessorImpl.java:45)
        at java.base/java.lang.reflect.Constructor.newInstanceWithCaller(Constructor.java:500)
        at java.base/java.lang.reflect.ReflectAccess.newInstance(ReflectAccess.java:166)
        at java.base/jdk.internal.reflect.ReflectionFactory.newInstance(ReflectionFactory.java:404)
        at java.base/java.lang.Class.newInstance(Class.java:590)
        at com.twitter.app.LoadService$.$anonfun$loadImpls$7(LoadService.scala:192)
        at scala.collection.TraversableLike.$anonfun$flatMap$1(TraversableLike.scala:241)
        at scala.collection.mutable.ResizableArray.foreach(ResizableArray.scala:59)
        at scala.collection.mutable.ResizableArray.foreach$(ResizableArray.scala:52)
        at scala.collection.mutable.ArrayBuffer.foreach(ArrayBuffer.scala:48)
        at scala.collection.TraversableLike.flatMap(TraversableLike.scala:241)
        at scala.collection.TraversableLike.flatMap$(TraversableLike.scala:238)
        at scala.collection.AbstractTraversable.flatMap(Traversable.scala:104)
        at com.twitter.app.LoadService$.loadImpls(LoadService.scala:181)
        at com.twitter.app.LoadService$.apply(LoadService.scala:135)
        at com.twitter.app.LoadService$.apply(LoadService.scala:149)
        at com.twitter.finagle.util.LoadService$.apply(LoadService.scala:14)
        at com.twitter.finagle.http.HttpMuxer$.<init>(HttpMuxer.scala:120)
        at com.twitter.finagle.http.HttpMuxer$.<clinit>(HttpMuxer.scala)
        at com.twitter.server.Lifecycle.$init$(Lifecycle.scala:14)
        at com.picchu.picchubackend.Server.<init>(Server.scala:20)
        at com.picchu.picchubackend.StartupTest.<init>(StartupTest.scala:9)
        at java.base/jdk.internal.reflect.NativeConstructorAccessorImpl.newInstance0(Native Method)
        at java.base/jdk.internal.reflect.NativeConstructorAccessorImpl.newInstance(NativeConstructorAccessorImpl.java:62)
        at java.base/jdk.internal.reflect.DelegatingConstructorAccessorImpl.newInstance(DelegatingConstructorAccessorImpl.java:45)
        at java.base/java.lang.reflect.Constructor.newInstanceWithCaller(Constructor.java:500)
        at java.base/java.lang.reflect.ReflectAccess.newInstance(ReflectAccess.java:166)
        at java.base/jdk.internal.reflect.ReflectionFactory.newInstance(ReflectionFactory.java:404)
        at java.base/java.lang.Class.newInstance(Class.java:590)
        at org.scalatest.tools.Framework$ScalaTestTask.execute(Framework.scala:435)
        at sbt.TestRunner.runTest$1(TestFramework.scala:113)
        at sbt.TestRunner.run(TestFramework.scala:124)
        at sbt.TestFramework$$anon$2$$anonfun$$lessinit$greater$1.$anonfun$apply$1(TestFramework.scala:282)
        at sbt.TestFramework$.sbt$TestFramework$$withContextLoader(TestFramework.scala:246)
        at sbt.TestFramework$$anon$2$$anonfun$$lessinit$greater$1.apply(TestFramework.scala:282)
        at sbt.TestFramework$$anon$2$$anonfun$$lessinit$greater$1.apply(TestFramework.scala:282)
        at sbt.TestFunction.apply(TestFramework.scala:294)
        at sbt.Tests$.processRunnable$1(Tests.scala:347)
        at sbt.Tests$.$anonfun$makeSerial$1(Tests.scala:353)
        at sbt.std.Transform$$anon$3.$anonfun$apply$2(System.scala:46)
        at sbt.std.Transform$$anon$4.work(System.scala:67)
        at sbt.Execute.$anonfun$submit$2(Execute.scala:269)
        at sbt.internal.util.ErrorHandling$.wideConvert(ErrorHandling.scala:16)
        at sbt.Execute.work(Execute.scala:278)
        at sbt.Execute.$anonfun$submit$1(Execute.scala:269)
        at sbt.ConcurrentRestrictions$$anon$4.$anonfun$submitValid$1(ConcurrentRestrictions.scala:178)
        at sbt.CompletionService$$anon$2.call(CompletionService.scala:37)
        at java.base/java.util.concurrent.FutureTask.run(FutureTask.java:264)
        at java.base/java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:515)
        at java.base/java.util.concurrent.FutureTask.run(FutureTask.java:264)
        at java.base/java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1128)
        at java.base/java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:628)
        at java.base/java.lang.Thread.run(Thread.java:835)
04:36:10.103 [pool-47-thread-7] DEBUG i.n.util.internal.PlatformDependent0 - java.nio.Bits.unaligned: available, true
04:36:10.111 [pool-47-thread-7] DEBUG i.n.util.internal.PlatformDependent0 - jdk.internal.misc.Unsafe.allocateUninitializedArray(int): unavailable
java.lang.IllegalAccessException: class io.netty.util.internal.PlatformDependent0$6 cannot access class jdk.internal.misc.Unsafe (in module java.base) because module java.base does not export jdk.internal.misc to unnamed module @46adaa9e
        at java.base/jdk.internal.reflect.Reflection.newIllegalAccessException(Reflection.java:355)
        at java.base/java.lang.reflect.AccessibleObject.checkAccess(AccessibleObject.java:639)
        at java.base/java.lang.reflect.Method.invoke(Method.java:559)
        at io.netty.util.internal.PlatformDependent0$6.run(PlatformDependent0.java:334)
        at java.base/java.security.AccessController.doPrivileged(AccessController.java:310)
        at io.netty.util.internal.PlatformDependent0.<clinit>(PlatformDependent0.java:325)
        at io.netty.util.internal.PlatformDependent.isAndroid(PlatformDependent.java:212)
        at io.netty.util.internal.PlatformDependent.<clinit>(PlatformDependent.java:80)
        at io.netty.util.ResourceLeakDetector.<init>(ResourceLeakDetector.java:162)
        at io.netty.util.ResourceLeakDetector.<init>(ResourceLeakDetector.java:207)
        at io.netty.util.ResourceLeakDetectorFactory$DefaultResourceLeakDetectorFactory.newResourceLeakDetector(ResourceLeakDetectorFactory.java:201)
        at io.netty.util.HashedWheelTimer.<clinit>(HashedWheelTimer.java:88)
        at com.twitter.finagle.netty4.HashedWheelTimer$.<init>(Netty4HashedWheelTimer.scala:79)
        at com.twitter.finagle.netty4.HashedWheelTimer$.<clinit>(Netty4HashedWheelTimer.scala)
        at com.twitter.finagle.netty4.Netty4HashedWheelTimer.<init>(Netty4HashedWheelTimer.scala:108)
        at java.base/jdk.internal.reflect.NativeConstructorAccessorImpl.newInstance0(Native Method)
        at java.base/jdk.internal.reflect.NativeConstructorAccessorImpl.newInstance(NativeConstructorAccessorImpl.java:62)
        at java.base/jdk.internal.reflect.DelegatingConstructorAccessorImpl.newInstance(DelegatingConstructorAccessorImpl.java:45)
        at java.base/java.lang.reflect.Constructor.newInstanceWithCaller(Constructor.java:500)
        at java.base/java.lang.reflect.ReflectAccess.newInstance(ReflectAccess.java:166)
        at java.base/jdk.internal.reflect.ReflectionFactory.newInstance(ReflectionFactory.java:404)
        at java.base/java.lang.Class.newInstance(Class.java:590)
        at com.twitter.app.LoadService$.$anonfun$loadImpls$7(LoadService.scala:192)
        at scala.collection.TraversableLike.$anonfun$flatMap$1(TraversableLike.scala:241)
        at scala.collection.mutable.ResizableArray.foreach(ResizableArray.scala:59)
        at scala.collection.mutable.ResizableArray.foreach$(ResizableArray.scala:52)
        at scala.collection.mutable.ArrayBuffer.foreach(ArrayBuffer.scala:48)
        at scala.collection.TraversableLike.flatMap(TraversableLike.scala:241)
        at scala.collection.TraversableLike.flatMap$(TraversableLike.scala:238)
        at scala.collection.AbstractTraversable.flatMap(Traversable.scala:104)
        at com.twitter.app.LoadService$.loadImpls(LoadService.scala:181)
        at com.twitter.app.LoadService$.apply(LoadService.scala:135)
        at com.twitter.app.LoadService$.apply(LoadService.scala:149)
        at com.twitter.finagle.util.LoadService$.apply(LoadService.scala:14)
        at com.twitter.finagle.util.DefaultTimer$.<init>(DefaultTimer.scala:80)
        at com.twitter.finagle.util.DefaultTimer$.<clinit>(DefaultTimer.scala)
        at com.twitter.finagle.stats.JsonExporter.<init>(JsonExporter.scala:140)
        at com.twitter.finagle.stats.MetricsExporter.<init>(MetricsStatsReceiver.scala:141)
        at com.twitter.finagle.stats.MetricsExporter.<init>(MetricsStatsReceiver.scala:144)
        at java.base/jdk.internal.reflect.NativeConstructorAccessorImpl.newInstance0(Native Method)
        at java.base/jdk.internal.reflect.NativeConstructorAccessorImpl.newInstance(NativeConstructorAccessorImpl.java:62)
        at java.base/jdk.internal.reflect.DelegatingConstructorAccessorImpl.newInstance(DelegatingConstructorAccessorImpl.java:45)
        at java.base/java.lang.reflect.Constructor.newInstanceWithCaller(Constructor.java:500)
        at java.base/java.lang.reflect.ReflectAccess.newInstance(ReflectAccess.java:166)
        at java.base/jdk.internal.reflect.ReflectionFactory.newInstance(ReflectionFactory.java:404)
        at java.base/java.lang.Class.newInstance(Class.java:590)
        at com.twitter.app.LoadService$.$anonfun$loadImpls$7(LoadService.scala:192)
        at scala.collection.TraversableLike.$anonfun$flatMap$1(TraversableLike.scala:241)
        at scala.collection.mutable.ResizableArray.foreach(ResizableArray.scala:59)
        at scala.collection.mutable.ResizableArray.foreach$(ResizableArray.scala:52)
        at scala.collection.mutable.ArrayBuffer.foreach(ArrayBuffer.scala:48)
        at scala.collection.TraversableLike.flatMap(TraversableLike.scala:241)
        at scala.collection.TraversableLike.flatMap$(TraversableLike.scala:238)
        at scala.collection.AbstractTraversable.flatMap(Traversable.scala:104)
        at com.twitter.app.LoadService$.loadImpls(LoadService.scala:181)
        at com.twitter.app.LoadService$.apply(LoadService.scala:135)
        at com.twitter.app.LoadService$.apply(LoadService.scala:149)
        at com.twitter.finagle.util.LoadService$.apply(LoadService.scala:14)
        at com.twitter.finagle.http.HttpMuxer$.<init>(HttpMuxer.scala:120)
        at com.twitter.finagle.http.HttpMuxer$.<clinit>(HttpMuxer.scala)
        at com.twitter.server.Lifecycle.$init$(Lifecycle.scala:14)
        at com.picchu.picchubackend.Server.<init>(Server.scala:20)
        at com.picchu.picchubackend.StartupTest.<init>(StartupTest.scala:9)
        at java.base/jdk.internal.reflect.NativeConstructorAccessorImpl.newInstance0(Native Method)
        at java.base/jdk.internal.reflect.NativeConstructorAccessorImpl.newInstance(NativeConstructorAccessorImpl.java:62)
        at java.base/jdk.internal.reflect.DelegatingConstructorAccessorImpl.newInstance(DelegatingConstructorAccessorImpl.java:45)
        at java.base/java.lang.reflect.Constructor.newInstanceWithCaller(Constructor.java:500)
        at java.base/java.lang.reflect.ReflectAccess.newInstance(ReflectAccess.java:166)
        at java.base/jdk.internal.reflect.ReflectionFactory.newInstance(ReflectionFactory.java:404)
        at java.base/java.lang.Class.newInstance(Class.java:590)
        at org.scalatest.tools.Framework$ScalaTestTask.execute(Framework.scala:435)
        at sbt.TestRunner.runTest$1(TestFramework.scala:113)
        at sbt.TestRunner.run(TestFramework.scala:124)
        at sbt.TestFramework$$anon$2$$anonfun$$lessinit$greater$1.$anonfun$apply$1(TestFramework.scala:282)
        at sbt.TestFramework$.sbt$TestFramework$$withContextLoader(TestFramework.scala:246)
        at sbt.TestFramework$$anon$2$$anonfun$$lessinit$greater$1.apply(TestFramework.scala:282)
        at sbt.TestFramework$$anon$2$$anonfun$$lessinit$greater$1.apply(TestFramework.scala:282)
        at sbt.TestFunction.apply(TestFramework.scala:294)
        at sbt.Tests$.processRunnable$1(Tests.scala:347)
        at sbt.Tests$.$anonfun$makeSerial$1(Tests.scala:353)
        at sbt.std.Transform$$anon$3.$anonfun$apply$2(System.scala:46)
        at sbt.std.Transform$$anon$4.work(System.scala:67)
        at sbt.Execute.$anonfun$submit$2(Execute.scala:269)
        at sbt.internal.util.ErrorHandling$.wideConvert(ErrorHandling.scala:16)
        at sbt.Execute.work(Execute.scala:278)
        at sbt.Execute.$anonfun$submit$1(Execute.scala:269)
        at sbt.ConcurrentRestrictions$$anon$4.$anonfun$submitValid$1(ConcurrentRestrictions.scala:178)
        at sbt.CompletionService$$anon$2.call(CompletionService.scala:37)
        at java.base/java.util.concurrent.FutureTask.run(FutureTask.java:264)
        at java.base/java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:515)
        at java.base/java.util.concurrent.FutureTask.run(FutureTask.java:264)
        at java.base/java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1128)
        at java.base/java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:628)
        at java.base/java.lang.Thread.run(Thread.java:835)
04:36:10.135 [pool-47-thread-7] DEBUG i.n.util.internal.PlatformDependent0 - java.nio.DirectByteBuffer.<init>(long, int): unavailable
04:36:10.135 [pool-47-thread-7] DEBUG i.n.util.internal.PlatformDependent - sun.misc.Unsafe: available
04:36:10.135 [pool-47-thread-7] DEBUG i.n.util.internal.PlatformDependent - maxDirectMemory: 4294967296 bytes (maybe)
04:36:10.135 [pool-47-thread-7] DEBUG i.n.util.internal.PlatformDependent - -Dio.netty.tmpdir: C:\Users\Rocky\AppData\Local\Temp (java.io.tmpdir)
04:36:10.135 [pool-47-thread-7] DEBUG i.n.util.internal.PlatformDependent - -Dio.netty.bitMode: 64 (sun.arch.data.model)
04:36:10.135 [pool-47-thread-7] DEBUG i.n.util.internal.PlatformDependent - -Dio.netty.maxDirectMemory: -1 bytes
04:36:10.139 [pool-47-thread-7] DEBUG i.n.util.internal.PlatformDependent - -Dio.netty.uninitializedArrayAllocationThreshold: -1
04:36:10.139 [pool-47-thread-7] DEBUG io.netty.util.internal.CleanerJava9 - java.nio.ByteBuffer.cleaner(): available
04:36:10.139 [pool-47-thread-7] DEBUG i.n.util.internal.PlatformDependent - -Dio.netty.noPreferDirect: false
04:36:10.139 [pool-47-thread-7] DEBUG i.n.util.ResourceLeakDetectorFactory - Loaded default ResourceLeakDetector: io.netty.util.ResourceLeakDetector@109465c2
04:36:10.179 [pool-47-thread-7] DEBUG i.n.util.internal.PlatformDependent - org.jctools-core.MpscChunkedArrayQueue: available
04:36:11.036 [pool-47-thread-7] INFO  com.twitter.finagle.http.HttpMuxer$ - HttpMuxer[/admin/metrics.json] = com.twitter.finagle.stats.MetricsExporter(com.twitter.finagle.stats.MetricsExporter)
04:36:11.036 [pool-47-thread-7] INFO  com.twitter.finagle.http.HttpMuxer$ - HttpMuxer[/admin/per_host_metrics.json] = com.twitter.finagle.stats.HostMetricsExporter(com.twitter.finagle.stats.HostMetricsExporter)

Starting com.picchu.picchubackend-Picchubackend with args: -http.port=127.0.0.1:0 -admin.port=127.0.0.1:0
Waiting for warmup phases to complete...
04:36:11.332 [finatra/embedded/picchubackendpicchubackend-1] INFO  com.picchu.picchubackend.Server - Process started
Waiting for warmup phases to complete...
04:36:12.337 [finatra/embedded/picchubackendpicchubackend-1] DEBUG com.picchu.picchubackend.Server - AdminHttpServer Muxer endpoints:
        /admin/logging => com.twitter.server.AdminHttpServer$Route$IsolateFilter.andThen(com.twitter.server.handler.logback.classic.LoggingHandler)
        /admin/ping => com.twitter.server.handler.ReplyHandler
         => com.twitter.server.AdminHttpServer$Route$IsolateFilter.andThen(com.twitter.server.handler.AdminRedirectHandler)
        /admin => com.twitter.server.AdminHttpServer$Route$IsolateFilter.andThen(com.twitter.server.handler.SummaryHandler)
        /admin/ => com.twitter.server.AdminHttpServer$Route$IsolateFilter.andThen(com.twitter.server.view.NotFoundView.andThen(com.twitter.server.handler.AdminRedirectHandler))
        /admin/server_info => com.twitter.server.AdminHttpServer$Route$IsolateFilter.andThen(com.twitter.server.view.TextBlockView.andThen(com.twitter.server.handler.ServerInfoHandler))
        /admin/contention => com.twitter.server.AdminHttpServer$Route$IsolateFilter.andThen(com.twitter.server.view.TextBlockView.andThen(com.twitter.server.handler.ContentionHandler))
        /admin/lint => com.twitter.server.AdminHttpServer$Route$IsolateFilter.andThen(com.twitter.server.handler.LintHandler)
        /admin/lint.json => com.twitter.server.AdminHttpServer$Route$IsolateFilter.andThen(com.twitter.server.handler.LintHandler)
        /admin/failedlint => com.twitter.server.AdminHttpServer$Route$IsolateFilter.andThen(com.twitter.server.handler.FailedLintRuleHandler)
        /admin/threads => com.twitter.server.AdminHttpServer$Route$IsolateFilter.andThen(com.twitter.server.handler.ThreadsHandler)
        /admin/threads.json => com.twitter.server.AdminHttpServer$Route$IsolateFilter.andThen(com.twitter.server.handler.ThreadsHandler)
        /admin/announcer => com.twitter.server.AdminHttpServer$Route$IsolateFilter.andThen(com.twitter.server.view.TextBlockView.andThen(com.twitter.server.handler.AnnouncerHandler))
        /admin/dtab => com.twitter.server.AdminHttpServer$Route$IsolateFilter.andThen(com.twitter.server.view.TextBlockView.andThen(com.twitter.server.handler.DtabHandler))
        /admin/pprof/heap => com.twitter.server.AdminHttpServer$Route$IsolateFilter.andThen(com.twitter.server.handler.HeapResourceHandler)
        /admin/pprof/profile => com.twitter.server.AdminHttpServer$Route$IsolateFilter.andThen(com.twitter.server.handler.ProfileResourceHandler)
        /admin/pprof/contention => com.twitter.server.AdminHttpServer$Route$IsolateFilter.andThen(com.twitter.server.handler.ProfileResourceHandler)
        /admin/shutdown => com.twitter.server.AdminHttpServer$Route$IsolateFilter.andThen(com.twitter.server.handler.ShutdownHandler)
        /admin/tracing => com.twitter.server.AdminHttpServer$Route$IsolateFilter.andThen(com.twitter.server.handler.TracingHandler)
        /admin/metrics => com.twitter.server.AdminHttpServer$Route$IsolateFilter.andThen(com.twitter.server.handler.MetricQueryHandler)
        /admin/clients/ => com.twitter.server.AdminHttpServer$Route$IsolateFilter.andThen(com.twitter.server.handler.ClientRegistryHandler)
        /admin/balancers.json => com.twitter.server.AdminHttpServer$Route$IsolateFilter.andThen(com.twitter.server.handler.LoadBalancersHandler)
        /admin/servers/ => com.twitter.server.AdminHttpServer$Route$IsolateFilter.andThen(com.twitter.server.handler.ServerRegistryHandler)
        /admin/files/ => com.twitter.server.AdminHttpServer$Route$IsolateFilter.andThen(com.twitter.server.handler.ResourceHandler)
        /admin/registry.json => com.twitter.server.AdminHttpServer$Route$IsolateFilter.andThen(com.twitter.server.handler.RegistryHandler)
        /admin/toggles => com.twitter.server.AdminHttpServer$Route$IsolateFilter.andThen(com.twitter.server.handler.ToggleHandler)
        /admin/toggles/ => com.twitter.server.AdminHttpServer$Route$IsolateFilter.andThen(com.twitter.server.handler.ToggleHandler)
        /admin/tunables => com.twitter.server.AdminHttpServer$Route$IsolateFilter.andThen(com.twitter.server.handler.TunableHandler)
        /admin/tunables/ => com.twitter.server.AdminHttpServer$Route$IsolateFilter.andThen(com.twitter.server.handler.TunableHandler)
        /favicon.ico => com.twitter.server.AdminHttpServer$Route$IsolateFilter.andThen(com.twitter.server.handler.ResourceHandler)
        /admin/histograms => com.twitter.server.handler.HistogramQueryHandler
        /admin/histograms.json => com.twitter.server.handler.HistogramQueryHandler
04:36:12.365 [finatra/embedded/picchubackendpicchubackend-1] INFO  com.picchu.picchubackend.Server - Serving admin http on 127.0.0.1/127.0.0.1:0
04:36:13.205 [finatra/embedded/picchubackendpicchubackend-1] DEBUG i.n.buffer.PooledByteBufAllocator - -Dio.netty.allocator.numHeapArenas: 8
04:36:13.205 [finatra/embedded/picchubackendpicchubackend-1] DEBUG i.n.buffer.PooledByteBufAllocator - -Dio.netty.allocator.numDirectArenas: 8
04:36:13.205 [finatra/embedded/picchubackendpicchubackend-1] DEBUG i.n.buffer.PooledByteBufAllocator - -Dio.netty.allocator.pageSize: 8192
04:36:13.209 [finatra/embedded/picchubackendpicchubackend-1] DEBUG i.n.buffer.PooledByteBufAllocator - -Dio.netty.allocator.maxOrder: 7
04:36:13.209 [finatra/embedded/picchubackendpicchubackend-1] DEBUG i.n.buffer.PooledByteBufAllocator - -Dio.netty.allocator.chunkSize: 1048576
04:36:13.209 [finatra/embedded/picchubackendpicchubackend-1] DEBUG i.n.buffer.PooledByteBufAllocator - -Dio.netty.allocator.tinyCacheSize: 512
04:36:13.209 [finatra/embedded/picchubackendpicchubackend-1] DEBUG i.n.buffer.PooledByteBufAllocator - -Dio.netty.allocator.smallCacheSize: 256
04:36:13.209 [finatra/embedded/picchubackendpicchubackend-1] DEBUG i.n.buffer.PooledByteBufAllocator - -Dio.netty.allocator.normalCacheSize: 64
04:36:13.209 [finatra/embedded/picchubackendpicchubackend-1] DEBUG i.n.buffer.PooledByteBufAllocator - -Dio.netty.allocator.maxCachedBufferCapacity: 32768
04:36:13.209 [finatra/embedded/picchubackendpicchubackend-1] DEBUG i.n.buffer.PooledByteBufAllocator - -Dio.netty.allocator.cacheTrimInterval: 8192
04:36:13.209 [finatra/embedded/picchubackendpicchubackend-1] DEBUG i.n.buffer.PooledByteBufAllocator - -Dio.netty.allocator.useCacheForAllThreads: true
04:36:13.213 [finatra/embedded/picchubackendpicchubackend-1] DEBUG i.n.u.i.InternalThreadLocalMap - -Dio.netty.threadLocalMap.stringBuilder.initialSize: 1024
04:36:13.213 [finatra/embedded/picchubackendpicchubackend-1] DEBUG i.n.u.i.InternalThreadLocalMap - -Dio.netty.threadLocalMap.stringBuilder.maxSize: 4096
04:36:13.245 [finatra/embedded/picchubackendpicchubackend-1] INFO  com.twitter.finagle - Finagle version 18.12.0 (rev=8d741a599d0af0975d1a4a94674d989c187f6c79) built at 20181211-102957
04:36:13.325 [finatra/embedded/picchubackendpicchubackend-1] DEBUG i.n.c.MultithreadEventLoopGroup - -Dio.netty.eventLoopThreads: 8
Waiting for warmup phases to complete...
04:36:13.373 [finatra/embedded/picchubackendpicchubackend-1] DEBUG io.netty.channel.nio.NioEventLoop - -Dio.netty.noKeySetOptimization: false
04:36:13.373 [finatra/embedded/picchubackendpicchubackend-1] DEBUG io.netty.channel.nio.NioEventLoop - -Dio.netty.selectorAutoRebuildThreshold: 512
04:36:13.453 [finatra/embedded/picchubackendpicchubackend-1] DEBUG io.netty.channel.DefaultChannelId - -Dio.netty.processId: 12012 (auto-detected)
04:36:13.457 [finatra/embedded/picchubackendpicchubackend-1] DEBUG io.netty.util.NetUtil - -Djava.net.preferIPv4Stack: false
04:36:13.457 [finatra/embedded/picchubackendpicchubackend-1] DEBUG io.netty.util.NetUtil - -Djava.net.preferIPv6Addresses: false
04:36:13.661 [finatra/embedded/picchubackendpicchubackend-1] DEBUG io.netty.util.NetUtil - Loopback interface: lo (Software Loopback Interface 1, 127.0.0.1)
04:36:13.665 [finatra/embedded/picchubackendpicchubackend-1] DEBUG io.netty.util.NetUtil - Failed to get SOMAXCONN from sysctl and file \proc\sys\net\core\somaxconn. Default: 200
04:36:13.995 [finatra/embedded/picchubackendpicchubackend-1] DEBUG io.netty.channel.DefaultChannelId - -Dio.netty.machineId: 00:15:5d:ff:fe:de:e6:84 (auto-detected)
04:36:14.071 [finatra/embedded/picchubackendpicchubackend-1] DEBUG io.netty.buffer.ByteBufUtil - -Dio.netty.allocator.type: pooled
04:36:14.075 [finatra/embedded/picchubackendpicchubackend-1] DEBUG io.netty.buffer.ByteBufUtil - -Dio.netty.threadLocalDirectBufferSize: 0
04:36:14.083 [finatra/embedded/picchubackendpicchubackend-1] DEBUG io.netty.buffer.ByteBufUtil - -Dio.netty.maxThreadLocalCharBufferSize: 16384
Waiting for warmup phases to complete...
04:36:14.887 [finatra/embedded/picchubackendpicchubackend-1] DEBUG c.t.inject.app.internal.FlagsModule - Binding flag: shutdown.time = 1.minutes
04:36:14.891 [finatra/embedded/picchubackendpicchubackend-1] DEBUG c.t.inject.app.internal.FlagsModule - Binding flag: service.version = 1.0.0
04:36:14.891 [finatra/embedded/picchubackendpicchubackend-1] DEBUG c.t.inject.app.internal.FlagsModule - Binding flag: https.announce =
04:36:14.895 [finatra/embedded/picchubackendpicchubackend-1] DEBUG c.t.inject.app.internal.FlagsModule - Binding flag: log.level = INFO
04:36:14.895 [finatra/embedded/picchubackendpicchubackend-1] DEBUG c.t.inject.app.internal.FlagsModule - Binding flag: local.doc.root =
04:36:14.895 [finatra/embedded/picchubackendpicchubackend-1] DEBUG c.t.inject.app.internal.FlagsModule - Binding flag: https.port =
04:36:14.899 [finatra/embedded/picchubackendpicchubackend-1] DEBUG c.t.inject.app.internal.FlagsModule - Binding flag: mustache.templates.dir = templates
04:36:14.899 [finatra/embedded/picchubackendpicchubackend-1] DEBUG c.t.inject.app.internal.FlagsModule - Binding flag: log.async = true
04:36:14.899 [finatra/embedded/picchubackendpicchubackend-1] DEBUG c.t.inject.app.internal.FlagsModule - Binding flag: http.name = http
04:36:14.903 [finatra/embedded/picchubackendpicchubackend-1] DEBUG c.t.inject.app.internal.FlagsModule - Binding flag: maxRequestSize = 5242880.bytes
04:36:14.903 [finatra/embedded/picchubackendpicchubackend-1] DEBUG c.t.inject.app.internal.FlagsModule - Binding flag: log.rollPolicy = Never
04:36:14.907 [finatra/embedded/picchubackendpicchubackend-1] DEBUG c.t.inject.app.internal.FlagsModule - Binding flag: help = false
04:36:14.907 [finatra/embedded/picchubackendpicchubackend-1] DEBUG c.t.inject.app.internal.FlagsModule - Binding flag: log.output = /dev/stderr
04:36:14.907 [finatra/embedded/picchubackendpicchubackend-1] DEBUG c.t.inject.app.internal.FlagsModule - Binding flag: http.port = 127.0.0.1:0
04:36:14.907 [finatra/embedded/picchubackendpicchubackend-1] DEBUG c.t.inject.app.internal.FlagsModule - Binding flag: log.async.maxsize = 4096
04:36:14.911 [finatra/embedded/picchubackendpicchubackend-1] DEBUG c.t.inject.app.internal.FlagsModule - Binding flag: https.name = https
04:36:14.915 [finatra/embedded/picchubackendpicchubackend-1] DEBUG c.t.inject.app.internal.FlagsModule - Binding flag: http.response.charset.enabled = true
04:36:14.927 [finatra/embedded/picchubackendpicchubackend-1] DEBUG c.t.inject.app.internal.FlagsModule - Binding flag: log.rotateCount = -1
04:36:14.927 [finatra/embedded/picchubackendpicchubackend-1] DEBUG c.t.inject.app.internal.FlagsModule - Binding flag: swagger.docs.endpoint = /docs
04:36:14.931 [finatra/embedded/picchubackendpicchubackend-1] DEBUG c.t.inject.app.internal.FlagsModule - Binding flag: doc.root =
04:36:14.931 [finatra/embedded/picchubackendpicchubackend-1] DEBUG c.t.inject.app.internal.FlagsModule - Binding flag: log.async.inferClassNames = false
04:36:14.931 [finatra/embedded/picchubackendpicchubackend-1] DEBUG c.t.inject.app.internal.FlagsModule - Binding flag: http.announce =
04:36:14.935 [finatra/embedded/picchubackendpicchubackend-1] DEBUG c.t.inject.app.internal.FlagsModule - Binding flag: log.append = true
04:36:14.935 [finatra/embedded/picchubackendpicchubackend-1] DEBUG c.t.inject.app.internal.FlagsModule - Binding flag: admin.port = 127.0.0.1/127.0.0.1:0
Fatal exception in server startup.
Waiting for warmup phases to complete...

Embedded server com.picchu.picchubackend-Picchubackend failed to startup: java.lang.NoClassDefFoundError: Ljavax/activation/MimetypesFileTypeMap;


===========================================================================
Closing EmbeddedHttpServer: com.picchu.picchubackend-Picchubackend
===========================================================================
Closing underlying TwitterServer: com.picchu.picchubackend-Picchubackend
Shutting down Future Pool: finatra/embedded/picchubackendpicchubackend
[info] StartupTest:
[info] com.picchu.picchubackend.StartupTest *** ABORTED ***
[info]   java.lang.Exception: java.lang.NoClassDefFoundError: Ljavax/activation/MimetypesFileTypeMap;
[info]   at com.twitter.inject.server.EmbeddedTwitterServer.$anonfun$runNonExitingMain$1(EmbeddedTwitterServer.scala:434)
[info]   at scala.runtime.java8.JFunction0$mcV$sp.apply(JFunction0$mcV$sp.java:12)
[info]   at com.twitter.util.Try$.apply(Try.scala:26)
[info]   at com.twitter.util.ExecutorServiceFuturePool$$anon$4.run(FuturePool.scala:140)
[info]   at java.base/java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:515)
[info]   at java.base/java.util.concurrent.FutureTask.run(FutureTask.java:264)
[info]   at java.base/java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1128)
[info]   at java.base/java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:628)
[info]   at java.base/java.lang.Thread.run(Thread.java:835)
[info]   ...
[info]   Cause: java.lang.NoClassDefFoundError: Ljavax/activation/MimetypesFileTypeMap;
[info]   at java.base/java.lang.Class.getDeclaredFields0(Native Method)
[info]   at java.base/java.lang.Class.privateGetDeclaredFields(Class.java:3067)
[info]   at java.base/java.lang.Class.getDeclaredFields(Class.java:2254)
[info]   at com.google.inject.spi.InjectionPoint.getDeclaredFields(InjectionPoint.java:760)
[info]   at com.google.inject.spi.InjectionPoint.getInjectionPoints(InjectionPoint.java:670)
[info]   at com.google.inject.spi.InjectionPoint.forInstanceMethodsAndFields(InjectionPoint.java:378)
[info]   at com.google.inject.internal.ConstructorBindingImpl.getInternalDependencies(ConstructorBindingImpl.java:182)
[info]   at com.google.inject.internal.InjectorImpl.getInternalDependencies(InjectorImpl.java:661)
[info]   at com.google.inject.internal.InjectorImpl.cleanup(InjectorImpl.java:617)
[info]   at com.google.inject.internal.InjectorImpl.initializeJitBinding(InjectorImpl.java:603)
[info]   ...
[info]   Cause: java.lang.ClassNotFoundException: javax.activation.MimetypesFileTypeMap
[info]   at java.base/java.net.URLClassLoader.findClass(URLClassLoader.java:436)
[info]   at java.base/java.lang.ClassLoader.loadClass(ClassLoader.java:588)
[info]   at java.base/java.lang.ClassLoader.loadClass(ClassLoader.java:521)
[info]   at java.base/java.lang.Class.getDeclaredFields0(Native Method)
[info]   at java.base/java.lang.Class.privateGetDeclaredFields(Class.java:3067)
[info]   at java.base/java.lang.Class.getDeclaredFields(Class.java:2254)
[info]   at com.google.inject.spi.InjectionPoint.getDeclaredFields(InjectionPoint.java:760)
[info]   at com.google.inject.spi.InjectionPoint.getInjectionPoints(InjectionPoint.java:670)
[info]   at com.google.inject.spi.InjectionPoint.forInstanceMethodsAndFields(InjectionPoint.java:378)
[info]   at com.google.inject.internal.ConstructorBindingImpl.getInternalDependencies(ConstructorBindingImpl.java:182)
[info]   ...
04:36:15.959 [pool-47-thread-7] DEBUG c.t.inject.app.internal.FlagsModule - Binding flag: help = false
04:36:16.435 [pool-47-thread-7] DEBUG org.eclipse.jetty.util.log - Logging to Logger[org.eclipse.jetty.util.log] via org.eclipse.jetty.util.log.Slf4jLog
04:36:16.439 [pool-47-thread-7] INFO  org.eclipse.jetty.util.log - Logging initialized @849063ms
04:36:16.459 [pool-47-thread-7] DEBUG o.e.j.u.component.ContainerLifeCycle - org.eclipse.jetty.server.Server@222e6ec3 added {qtp567376113{STOPPED,8<=0<=10,i=0,q=0},AUTO}
04:36:16.483 [pool-47-thread-7] DEBUG o.e.j.u.component.ContainerLifeCycle - HttpConnectionFactory@10c281c0{HTTP/1.1} added {HttpConfiguration@1c27a02e{32768/8192,8192/8192,https://:0,[]},POJO}
04:36:16.491 [pool-47-thread-7] DEBUG o.e.j.u.component.ContainerLifeCycle - NetworkTrafficServerConnector@77318a85{null}{0.0.0.0:0} added {org.eclipse.jetty.server.Server@222e6ec3,UNMANAGED}
04:36:16.491 [pool-47-thread-7] DEBUG o.e.j.u.component.ContainerLifeCycle - NetworkTrafficServerConnector@77318a85{null}{0.0.0.0:0} added {qtp567376113{STOPPED,8<=0<=10,i=0,q=0},AUTO}
04:36:16.491 [pool-47-thread-7] DEBUG o.e.j.u.component.ContainerLifeCycle - NetworkTrafficServerConnector@77318a85{null}{0.0.0.0:0} added {org.eclipse.jetty.util.thread.ScheduledExecutorScheduler@15e0c467,AUTO}
04:36:16.491 [pool-47-thread-7] DEBUG o.e.j.u.component.ContainerLifeCycle - NetworkTrafficServerConnector@77318a85{null}{0.0.0.0:0} added {org.eclipse.jetty.io.ArrayByteBufferPool@6777ad22,POJO}
04:36:16.491 [pool-47-thread-7] DEBUG o.e.j.u.component.ContainerLifeCycle - NetworkTrafficServerConnector@77318a85{null}{0.0.0.0:0} added {HttpConnectionFactory@10c281c0{HTTP/1.1},AUTO}
04:36:16.495 [pool-47-thread-7] DEBUG o.e.j.u.component.ContainerLifeCycle - NetworkTrafficServerConnector@77318a85{HTTP/1.1}{0.0.0.0:0} added {org.eclipse.jetty.server.ServerConnector$ServerConnectorManager@6e98467e,MANAGED}
04:36:16.495 [pool-47-thread-7] DEBUG o.e.j.u.component.ContainerLifeCycle - org.eclipse.jetty.server.Server@222e6ec3 added {NetworkTrafficServerConnector@77318a85{HTTP/1.1}{0.0.0.0:27554},AUTO}
04:36:16.515 [pool-47-thread-7] DEBUG o.e.j.u.component.ContainerLifeCycle - org.eclipse.jetty.server.Server@222e6ec3 added {o.e.j.s.ServletContextHandler@1f3751ed{/__admin,null,null},AUTO}
04:36:16.523 [pool-47-thread-7] DEBUG o.e.j.u.component.ContainerLifeCycle - o.e.j.s.ServletContextHandler@1f3751ed{/__admin,null,null} added {org.eclipse.jetty.servlet.ServletHandler@16cd66af,AUTO}
04:36:16.535 [pool-47-thread-7] DEBUG o.e.j.u.component.ContainerLifeCycle - org.eclipse.jetty.servlet.ServletHandler@16cd66af added {org.eclipse.jetty.servlet.DefaultServlet-768b9dfe@dfbc4232==org.eclipse.jetty.servlet.DefaultServlet,-1,false,AUTO}
04:36:16.535 [pool-47-thread-7] DEBUG o.e.j.u.component.ContainerLifeCycle - org.eclipse.jetty.servlet.ServletHandler@16cd66af added {[/swagger-ui/*]=>org.eclipse.jetty.servlet.DefaultServlet-768b9dfe,POJO}
04:36:16.535 [pool-47-thread-7] DEBUG o.e.j.u.component.ContainerLifeCycle - org.eclipse.jetty.servlet.ServletHandler@16cd66af added {org.eclipse.jetty.servlet.DefaultServlet-2be80be4@3a5eaaa3==org.eclipse.jetty.servlet.DefaultServlet,-1,false,AUTO}
04:36:16.535 [pool-47-thread-7] DEBUG o.e.j.u.component.ContainerLifeCycle - org.eclipse.jetty.servlet.ServletHandler@16cd66af added {[/recorder/*]=>org.eclipse.jetty.servlet.DefaultServlet-2be80be4,POJO}
04:36:16.539 [pool-47-thread-7] DEBUG o.e.j.u.component.ContainerLifeCycle - org.eclipse.jetty.servlet.ServletHandler@16cd66af added {com.github.tomakehurst.wiremock.servlet.WireMockHandlerDispatchingServlet-2b8f6258@4dcd76cb==com.github.tomakehurst.wiremock.servlet.WireMockHandlerDispatchingServlet,-1,false,AUTO}
04:36:16.539 [pool-47-thread-7] DEBUG o.e.j.u.component.ContainerLifeCycle - org.eclipse.jetty.servlet.ServletHandler@16cd66af added {[/]=>com.github.tomakehurst.wiremock.servlet.WireMockHandlerDispatchingServlet-2b8f6258,POJO}
04:36:16.543 [pool-47-thread-7] DEBUG o.e.j.u.component.ContainerLifeCycle - org.eclipse.jetty.servlet.ServletHandler@16cd66af added {org.eclipse.jetty.servlets.CrossOriginFilter-6ed4be3f,AUTO}
04:36:16.543 [pool-47-thread-7] DEBUG o.e.j.u.component.ContainerLifeCycle - org.eclipse.jetty.servlet.ServletHandler@16cd66af added {[/*]/[]==1=>org.eclipse.jetty.servlets.CrossOriginFilter-6ed4be3f,POJO}
04:36:16.547 [pool-47-thread-7] DEBUG o.e.j.u.component.ContainerLifeCycle - org.eclipse.jetty.server.Server@222e6ec3 added {o.e.j.s.ServletContextHandler@77c953ba{/,null,null},AUTO}
04:36:16.547 [pool-47-thread-7] DEBUG o.e.j.u.component.ContainerLifeCycle - o.e.j.s.ServletContextHandler@77c953ba{/,null,null} added {org.eclipse.jetty.servlet.ServletHandler@23304c73,AUTO}
04:36:16.547 [pool-47-thread-7] DEBUG o.e.j.u.component.ContainerLifeCycle - org.eclipse.jetty.servlet.ServletHandler@23304c73 added {org.eclipse.jetty.servlet.DefaultServlet-91f1b04@83b49264==org.eclipse.jetty.servlet.DefaultServlet,-1,false,AUTO}
04:36:16.547 [pool-47-thread-7] DEBUG o.e.j.u.component.ContainerLifeCycle - org.eclipse.jetty.servlet.ServletHandler@23304c73 added {[/__files/*]=>org.eclipse.jetty.servlet.DefaultServlet-91f1b04,POJO}
04:36:16.551 [pool-47-thread-7] DEBUG o.e.j.u.component.ContainerLifeCycle - org.eclipse.jetty.servlet.ServletHandler@23304c73 added {com.github.tomakehurst.wiremock.servlet.WireMockHandlerDispatchingServlet-42f1624b@7df8c341==com.github.tomakehurst.wiremock.servlet.WireMockHandlerDispatchingServlet,-1,false,AUTO}
04:36:16.551 [pool-47-thread-7] DEBUG o.e.j.u.component.ContainerLifeCycle - org.eclipse.jetty.servlet.ServletHandler@23304c73 added {[/]=>com.github.tomakehurst.wiremock.servlet.WireMockHandlerDispatchingServlet-42f1624b,POJO}
04:36:16.571 [pool-47-thread-7] DEBUG o.e.j.u.component.ContainerLifeCycle - o.e.j.s.ServletContextHandler@77c953ba{/,null,null} added {com.github.tomakehurst.wiremock.jetty9.NotFoundHandler@14166718,AUTO}
04:36:16.575 [pool-47-thread-7] DEBUG o.e.j.u.component.ContainerLifeCycle - org.eclipse.jetty.servlet.ServletHandler@23304c73 added {com.github.tomakehurst.wiremock.servlet.ContentTypeSettingFilter-615fe9c5,AUTO}
04:36:16.575 [pool-47-thread-7] DEBUG o.e.j.u.component.ContainerLifeCycle - org.eclipse.jetty.servlet.ServletHandler@23304c73 added {[/__files/*]/[]==2=>com.github.tomakehurst.wiremock.servlet.ContentTypeSettingFilter-615fe9c5,POJO}
04:36:16.575 [pool-47-thread-7] DEBUG o.e.j.u.component.ContainerLifeCycle - org.eclipse.jetty.servlet.ServletHandler@23304c73 added {com.github.tomakehurst.wiremock.servlet.TrailingSlashFilter-3f4ab2cc,AUTO}
04:36:16.575 [pool-47-thread-7] DEBUG o.e.j.u.component.ContainerLifeCycle - org.eclipse.jetty.servlet.ServletHandler@23304c73 added {[/__files/*]/[]==31=>com.github.tomakehurst.wiremock.servlet.TrailingSlashFilter-3f4ab2cc,POJO}
04:36:16.583 [pool-47-thread-7] DEBUG o.e.j.u.component.ContainerLifeCycle - org.eclipse.jetty.server.handler.HandlerCollection@3f7e81f7[o.e.j.s.ServletContextHandler@1f3751ed{/__admin,null,null}] added {o.e.j.s.ServletContextHandler@1f3751ed{/__admin,null,null},AUTO}
04:36:16.603 [pool-47-thread-7] DEBUG o.e.jetty.servlets.gzip.GzipHandler - org.eclipse.jetty.servlets.gzip.GzipHandler@6055ef72 mime types IncludeExclude@f61a4ac{i=[],ip=org.eclipse.jetty.util.IncludeExcludeSet$SetContainsPredicate@4ce883d1,e=[image/ief, image/vnd.wap.wbmp, image/jpeg, application/bzip2, image/x-portable-graymap, image/gif, image/x-icon, audio/midi, video/x-msvideo, image/x-xbitmap, application/x-rar-compressed, image/x-portable-bitmap, image/x-rgb, image/x-cmu-raster, application/gzip, audio/x-wav, audio/basic, audio/x-pn-realaudio, application/compress, audio/x-aiff, video/x.ms.asx, video/x.ms.asf, image/png, video/vnd.rn-realvideo, image/x-xwindowdump, video/x-sgi-movie, audio/mpeg, video/mpeg, image/x-portable-pixmap, image/tiff, image/x-portable-anymap, image/x-xpixmap, application/zip, video/quicktime],ep=org.eclipse.jetty.util.IncludeExcludeSet$SetContainsPredicate@5139f85f}
04:36:16.607 [pool-47-thread-7] DEBUG o.e.j.u.component.ContainerLifeCycle - org.eclipse.jetty.servlets.gzip.GzipHandler@6055ef72 added {o.e.j.s.ServletContextHandler@77c953ba{/,null,null},AUTO}
04:36:16.607 [pool-47-thread-7] DEBUG o.e.j.u.component.ContainerLifeCycle - org.eclipse.jetty.server.handler.HandlerCollection@3f7e81f7[o.e.j.s.ServletContextHandler@1f3751ed{/__admin,null,null}, org.eclipse.jetty.servlets.gzip.GzipHandler@6055ef72] added {org.eclipse.jetty.servlets.gzip.GzipHandler@6055ef72,AUTO}
04:36:16.611 [pool-47-thread-7] DEBUG o.e.j.u.component.ContainerLifeCycle - org.eclipse.jetty.server.Server@222e6ec3 added {org.eclipse.jetty.server.handler.HandlerCollection@3f7e81f7[o.e.j.s.ServletContextHandler@1f3751ed{/__admin,null,null}, org.eclipse.jetty.servlets.gzip.GzipHandler@6055ef72],AUTO}
04:36:18.750 [pool-47-thread-7] DEBUG d.f.e.process.runtime.ProcessControl - Detected pid: 16156
[mongod output]note: noprealloc may hurt performance in many applications
[mongod output] 2019-09-07T12:36:18.313+0800 I CONTROL  [initandlisten] MongoDB starting : pid=16156 port=27020 dbpath=C:\Users\Rocky\AppData\Local\Temp\embedmongo-db-7b5996f2-693e-4294-a81b-06a010aeb3a1 64-bit host=DESKTOP-33SJOUM
[mongod output] 2019-09-07T12:36:18.314+0800 I CONTROL  [initandlisten] targetMinOS: Windows Server 2003 SP2
[mongod output] 2019-09-07T12:36:18.314+0800 I CONTROL  [initandlisten] db version v3.0.8
[mongod output] 2019-09-07T12:36:18.314+0800 I CONTROL  [initandlisten] git version: 83d8cc25e00e42856924d84e220fbe4a839e605d
[mongod output] 2019-09-07T12:36:18.314+0800 I CONTROL  [initandlisten] build info: windows sys.getwindowsversion(major=6, minor=1, build=7601, platform=2, service_pack='Service Pack 1') BOOST_LIB_VERSION=1_49
[mongod output] 2019-09-07T12:36:18.314+0800 I CONTROL  [initandlisten] allocator: tcmalloc
[mongod output] 2019-09-07T12:36:18.314+0800 I CONTROL  [initandlisten] options: { net: { http: { enabled: false }, port: 27020 }, security: { authorization: "disabled" }, storage: { dbPath: "C:\Users\Rocky\AppData\Local\Temp\embedmongo-db-7b5996f2-693e-4294-a81b-06a010aeb3a1", journal: { enabled: false }, mmapv1: { preallocDataFiles: false, smallFiles: true }, syncPeriodSecs: 0.0 } }
[mongod output] 2019-09-07T12:36:18.328+0800 I STORAGE  [DataFileSync] warning: --syncdelay 0 is not recommended and can have strange performance
[mongod output] 2019-09-07T12:36:18.435+0800 I INDEX    [initandlisten] allocating new ns file C:\Users\Rocky\AppData\Local\Temp\embedmongo-db-7b5996f2-693e-4294-a81b-06a010aeb3a1\local.ns, filling with zeroes...
[mongod output] 2019-09-07T12:36:19.071+0800 I STORAGE  [FileAllocator] allocating new datafile C:\Users\Rocky\AppData\Local\Temp\embedmongo-db-7b5996f2-693e-4294-a81b-06a010aeb3a1\local.0, filling with zeroes...
[mongod output] 2019-09-07T12:36:19.071+0800 I STORAGE  [FileAllocator] creating directory C:\Users\Rocky\AppData\Local\Temp\embedmongo-db-7b5996f2-693e-4294-a81b-06a010aeb3a1\_tmp
[mongod output] 2019-09-07T12:36:19.083+0800 I STORAGE  [FileAllocator] done allocating datafile C:\Users\Rocky\AppData\Local\Temp\embedmongo-db-7b5996f2-693e-4294-a81b-06a010aeb3a1\local.0, size: 16MB,  took 0.01 secs
[mongod output] 2019-09-07T12:36:19.094+0800 I NETWORK  [initandlisten] waiting for connections on port 27020
[mongod output] 04:36:19.094 [pool-47-thread-7] INFO  d.f.embed.process.runtime.Executable - start de.flapdoodle.embed.mongo.config.MongodConfigBuilder$ImmutableMongodConfig@68f2f96d
04:36:19.096 [finatra/embedded/picchubackendpicchubackend-1] WARN  com.twitter.app.App$ - Multiple com.twitter.app.App main methods called. com.picchu.picchubackend-Picchubackend, then com.picchu.picchubackend-Picchubackend
04:36:19.096 [finatra/embedded/picchubackendpicchubackend-1] INFO  com.picchu.picchubackend.Server - Process started
04:36:19.109 [finatra/embedded/picchubackendpicchubackend-1] DEBUG com.picchu.picchubackend.Server - AdminHttpServer Muxer endpoints:
        /admin/logging => com.twitter.server.AdminHttpServer$Route$IsolateFilter.andThen(com.twitter.server.handler.logback.classic.LoggingHandler)
        /admin/ping => com.twitter.server.handler.ReplyHandler
         => com.twitter.server.AdminHttpServer$Route$IsolateFilter.andThen(com.twitter.server.handler.AdminRedirectHandler)
        /admin => com.twitter.server.AdminHttpServer$Route$IsolateFilter.andThen(com.twitter.server.handler.SummaryHandler)
        /admin/ => com.twitter.server.AdminHttpServer$Route$IsolateFilter.andThen(com.twitter.server.view.NotFoundView.andThen(com.twitter.server.handler.AdminRedirectHandler))
        /admin/server_info => com.twitter.server.AdminHttpServer$Route$IsolateFilter.andThen(com.twitter.server.view.TextBlockView.andThen(com.twitter.server.handler.ServerInfoHandler))
        /admin/contention => com.twitter.server.AdminHttpServer$Route$IsolateFilter.andThen(com.twitter.server.view.TextBlockView.andThen(com.twitter.server.handler.ContentionHandler))
        /admin/lint => com.twitter.server.AdminHttpServer$Route$IsolateFilter.andThen(com.twitter.server.handler.LintHandler)
        /admin/lint.json => com.twitter.server.AdminHttpServer$Route$IsolateFilter.andThen(com.twitter.server.handler.LintHandler)
        /admin/failedlint => com.twitter.server.AdminHttpServer$Route$IsolateFilter.andThen(com.twitter.server.handler.FailedLintRuleHandler)
        /admin/threads => com.twitter.server.AdminHttpServer$Route$IsolateFilter.andThen(com.twitter.server.handler.ThreadsHandler)
        /admin/threads.json => com.twitter.server.AdminHttpServer$Route$IsolateFilter.andThen(com.twitter.server.handler.ThreadsHandler)
        /admin/announcer => com.twitter.server.AdminHttpServer$Route$IsolateFilter.andThen(com.twitter.server.view.TextBlockView.andThen(com.twitter.server.handler.AnnouncerHandler))
        /admin/dtab => com.twitter.server.AdminHttpServer$Route$IsolateFilter.andThen(com.twitter.server.view.TextBlockView.andThen(com.twitter.server.handler.DtabHandler))
        /admin/pprof/heap => com.twitter.server.AdminHttpServer$Route$IsolateFilter.andThen(com.twitter.server.handler.HeapResourceHandler)
        /admin/pprof/profile => com.twitter.server.AdminHttpServer$Route$IsolateFilter.andThen(com.twitter.server.handler.ProfileResourceHandler)
        /admin/pprof/contention => com.twitter.server.AdminHttpServer$Route$IsolateFilter.andThen(com.twitter.server.handler.ProfileResourceHandler)
        /admin/shutdown => com.twitter.server.AdminHttpServer$Route$IsolateFilter.andThen(com.twitter.server.handler.ShutdownHandler)
        /admin/tracing => com.twitter.server.AdminHttpServer$Route$IsolateFilter.andThen(com.twitter.server.handler.TracingHandler)
        /admin/metrics => com.twitter.server.AdminHttpServer$Route$IsolateFilter.andThen(com.twitter.server.handler.MetricQueryHandler)
        /admin/clients/ => com.twitter.server.AdminHttpServer$Route$IsolateFilter.andThen(com.twitter.server.handler.ClientRegistryHandler)
        /admin/balancers.json => com.twitter.server.AdminHttpServer$Route$IsolateFilter.andThen(com.twitter.server.handler.LoadBalancersHandler)
        /admin/servers/ => com.twitter.server.AdminHttpServer$Route$IsolateFilter.andThen(com.twitter.server.handler.ServerRegistryHandler)
        /admin/files/ => com.twitter.server.AdminHttpServer$Route$IsolateFilter.andThen(com.twitter.server.handler.ResourceHandler)
        /admin/registry.json => com.twitter.server.AdminHttpServer$Route$IsolateFilter.andThen(com.twitter.server.handler.RegistryHandler)
        /admin/toggles => com.twitter.server.AdminHttpServer$Route$IsolateFilter.andThen(com.twitter.server.handler.ToggleHandler)
        /admin/toggles/ => com.twitter.server.AdminHttpServer$Route$IsolateFilter.andThen(com.twitter.server.handler.ToggleHandler)
        /admin/tunables => com.twitter.server.AdminHttpServer$Route$IsolateFilter.andThen(com.twitter.server.handler.TunableHandler)
        /admin/tunables/ => com.twitter.server.AdminHttpServer$Route$IsolateFilter.andThen(com.twitter.server.handler.TunableHandler)
        /favicon.ico => com.twitter.server.AdminHttpServer$Route$IsolateFilter.andThen(com.twitter.server.handler.ResourceHandler)
        /admin/histograms => com.twitter.server.handler.HistogramQueryHandler
        /admin/histograms.json => com.twitter.server.handler.HistogramQueryHandler
04:36:19.118 [finatra/embedded/picchubackendpicchubackend-1] INFO  com.picchu.picchubackend.Server - Serving admin http on 127.0.0.1/127.0.0.1:0
04:36:19.142 [finatra/embedded/picchubackendpicchubackend-1] WARN  com.twitter.util.registry.Library$ - Tried to register a second library named "finatra"
04:36:19.166 [finatra/embedded/picchubackendpicchubackend-1] DEBUG c.t.inject.app.internal.FlagsModule - Binding flag: shutdown.time = 1.minutes
04:36:19.182 [finatra/embedded/picchubackendpicchubackend-1] DEBUG c.t.inject.app.internal.FlagsModule - Binding flag: service.version = 0.7.4
04:36:19.195 [finatra/embedded/picchubackendpicchubackend-1] DEBUG c.t.inject.app.internal.FlagsModule - Binding flag: https.announce =
04:36:19.202 [finatra/embedded/picchubackendpicchubackend-1] DEBUG c.t.inject.app.internal.FlagsModule - Binding flag: log.level = INFO
04:36:19.213 [finatra/embedded/picchubackendpicchubackend-1] DEBUG c.t.inject.app.internal.FlagsModule - Binding flag: local.doc.root =
04:36:19.224 [finatra/embedded/picchubackendpicchubackend-1] DEBUG c.t.inject.app.internal.FlagsModule - Binding flag: https.port =
04:36:19.230 [finatra/embedded/picchubackendpicchubackend-1] DEBUG c.t.inject.app.internal.FlagsModule - Binding flag: mustache.templates.dir = templates
04:36:19.236 [finatra/embedded/picchubackendpicchubackend-1] DEBUG c.t.inject.app.internal.FlagsModule - Binding flag: log.async = true
04:36:19.246 [finatra/embedded/picchubackendpicchubackend-1] DEBUG c.t.inject.app.internal.FlagsModule - Binding flag: http.name = http
04:36:19.247 [finatra/embedded/picchubackendpicchubackend-1] DEBUG c.t.inject.app.internal.FlagsModule - Binding flag: maxRequestSize = 5242880.bytes
04:36:19.248 [finatra/embedded/picchubackendpicchubackend-1] DEBUG c.t.inject.app.internal.FlagsModule - Binding flag: log.rollPolicy = Never
04:36:19.250 [finatra/embedded/picchubackendpicchubackend-1] DEBUG c.t.inject.app.internal.FlagsModule - Binding flag: help = false
04:36:19.250 [finatra/embedded/picchubackendpicchubackend-1] DEBUG c.t.inject.app.internal.FlagsModule - Binding flag: log.output = /dev/stderr
04:36:19.252 [finatra/embedded/picchubackendpicchubackend-1] DEBUG c.t.inject.app.internal.FlagsModule - Binding flag: http.port = 127.0.0.1:0
04:36:19.253 [finatra/embedded/picchubackendpicchubackend-1] DEBUG c.t.inject.app.internal.FlagsModule - Binding flag: log.async.maxsize = 4096
04:36:19.254 [finatra/embedded/picchubackendpicchubackend-1] DEBUG c.t.inject.app.internal.FlagsModule - Binding flag: https.name = https
04:36:19.255 [finatra/embedded/picchubackendpicchubackend-1] DEBUG c.t.inject.app.internal.FlagsModule - Binding flag: http.response.charset.enabled = true
04:36:19.256 [finatra/embedded/picchubackendpicchubackend-1] DEBUG c.t.inject.app.internal.FlagsModule - Binding flag: log.rotateCount = -1
04:36:19.257 [finatra/embedded/picchubackendpicchubackend-1] DEBUG c.t.inject.app.internal.FlagsModule - Binding flag: swagger.docs.endpoint = /docs
04:36:19.258 [finatra/embedded/picchubackendpicchubackend-1] DEBUG c.t.inject.app.internal.FlagsModule - Binding flag: doc.root =
04:36:19.259 [finatra/embedded/picchubackendpicchubackend-1] DEBUG c.t.inject.app.internal.FlagsModule - Binding flag: log.async.inferClassNames = false
04:36:19.260 [finatra/embedded/picchubackendpicchubackend-1] DEBUG c.t.inject.app.internal.FlagsModule - Binding flag: http.announce =
04:36:19.261 [finatra/embedded/picchubackendpicchubackend-1] DEBUG c.t.inject.app.internal.FlagsModule - Binding flag: log.append = true
04:36:19.262 [finatra/embedded/picchubackendpicchubackend-1] DEBUG c.t.inject.app.internal.FlagsModule - Binding flag: admin.port = 127.0.0.1/127.0.0.1:0
Fatal exception in server startup.

Embedded server com.picchu.picchubackend-Picchubackend failed to startup: java.lang.NoClassDefFoundError: Ljavax/activation/MimetypesFileTypeMap;
[info] AccountControllerFeatureTest:
[info] com.picchu.picchubackend.controllers.AccountControllerFeatureTest *** ABORTED ***
[info]   java.lang.Exception: java.lang.NoClassDefFoundError: Ljavax/activation/MimetypesFileTypeMap;
[info]   at com.twitter.inject.server.EmbeddedTwitterServer.$anonfun$runNonExitingMain$1(EmbeddedTwitterServer.scala:434)
[info]   at scala.runtime.java8.JFunction0$mcV$sp.apply(JFunction0$mcV$sp.java:12)
[info]   at com.twitter.util.Try$.apply(Try.scala:26)
[info]   at com.twitter.util.ExecutorServiceFuturePool$$anon$4.run(FuturePool.scala:140)
[info]   at java.base/java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:515)
[info]   at java.base/java.util.concurrent.FutureTask.run(FutureTask.java:264)
[info]   at java.base/java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1128)
[info]   at java.base/java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:628)
[info]   at java.base/java.lang.Thread.run(Thread.java:835)
[info]   ...
[info]   Cause: java.lang.NoClassDefFoundError: Ljavax/activation/MimetypesFileTypeMap;
[info]   at java.base/java.lang.Class.getDeclaredFields0(Native Method)
[info]   at java.base/java.lang.Class.privateGetDeclaredFields(Class.java:3067)
[info]   at java.base/java.lang.Class.getDeclaredFields(Class.java:2254)
[info]   at com.google.inject.spi.InjectionPoint.getDeclaredFields(InjectionPoint.java:760)
[info]   at com.google.inject.spi.InjectionPoint.getInjectionPoints(InjectionPoint.java:670)
[info]   at com.google.inject.spi.InjectionPoint.forInstanceMethodsAndFields(InjectionPoint.java:378)
[info]   at com.google.inject.internal.ConstructorBindingImpl.getInternalDependencies(ConstructorBindingImpl.java:182)
[info]   at com.google.inject.internal.InjectorImpl.getInternalDependencies(InjectorImpl.java:661)
[info]   at com.google.inject.internal.InjectorImpl.cleanup(InjectorImpl.java:617)
[info]   at com.google.inject.internal.InjectorImpl.initializeJitBinding(InjectorImpl.java:603)
[info]   ...
[info]   Cause: java.lang.ClassNotFoundException: javax.activation.MimetypesFileTypeMap
[info]   at java.base/java.net.URLClassLoader.findClass(URLClassLoader.java:436)
[info]   at java.base/java.lang.ClassLoader.loadClass(ClassLoader.java:588)
[info]   at java.base/java.lang.ClassLoader.loadClass(ClassLoader.java:521)
[info]   at java.base/java.lang.Class.getDeclaredFields0(Native Method)
[info]   at java.base/java.lang.Class.privateGetDeclaredFields(Class.java:3067)
[info]   at java.base/java.lang.Class.getDeclaredFields(Class.java:2254)
[info]   at com.google.inject.spi.InjectionPoint.getDeclaredFields(InjectionPoint.java:760)
[info]   at com.google.inject.spi.InjectionPoint.getInjectionPoints(InjectionPoint.java:670)
[info]   at com.google.inject.spi.InjectionPoint.forInstanceMethodsAndFields(InjectionPoint.java:378)
[info]   at com.google.inject.internal.ConstructorBindingImpl.getInternalDependencies(ConstructorBindingImpl.java:182)
[info]   ...

Starting com.picchu.picchubackend-Picchubackend with args: -http.port=127.0.0.1:0 -admin.port=127.0.0.1:0 -service.version=0.9.9
Waiting for warmup phases to complete...
04:36:20.266 [finatra/embedded/picchubackendpicchubackend-1] WARN  com.twitter.app.App$ - Multiple com.twitter.app.App main methods called. com.picchu.picchubackend-Picchubackend, then com.picchu.picchubackend-Picchubackend
04:36:20.266 [finatra/embedded/picchubackendpicchubackend-1] INFO  com.picchu.picchubackend.Server - Process started
04:36:20.274 [finatra/embedded/picchubackendpicchubackend-1] DEBUG com.picchu.picchubackend.Server - AdminHttpServer Muxer endpoints:
        /admin/logging => com.twitter.server.AdminHttpServer$Route$IsolateFilter.andThen(com.twitter.server.handler.logback.classic.LoggingHandler)
        /admin/ping => com.twitter.server.handler.ReplyHandler
         => com.twitter.server.AdminHttpServer$Route$IsolateFilter.andThen(com.twitter.server.handler.AdminRedirectHandler)
        /admin => com.twitter.server.AdminHttpServer$Route$IsolateFilter.andThen(com.twitter.server.handler.SummaryHandler)
        /admin/ => com.twitter.server.AdminHttpServer$Route$IsolateFilter.andThen(com.twitter.server.view.NotFoundView.andThen(com.twitter.server.handler.AdminRedirectHandler))
        /admin/server_info => com.twitter.server.AdminHttpServer$Route$IsolateFilter.andThen(com.twitter.server.view.TextBlockView.andThen(com.twitter.server.handler.ServerInfoHandler))
        /admin/contention => com.twitter.server.AdminHttpServer$Route$IsolateFilter.andThen(com.twitter.server.view.TextBlockView.andThen(com.twitter.server.handler.ContentionHandler))
        /admin/lint => com.twitter.server.AdminHttpServer$Route$IsolateFilter.andThen(com.twitter.server.handler.LintHandler)
        /admin/lint.json => com.twitter.server.AdminHttpServer$Route$IsolateFilter.andThen(com.twitter.server.handler.LintHandler)
        /admin/failedlint => com.twitter.server.AdminHttpServer$Route$IsolateFilter.andThen(com.twitter.server.handler.FailedLintRuleHandler)
        /admin/threads => com.twitter.server.AdminHttpServer$Route$IsolateFilter.andThen(com.twitter.server.handler.ThreadsHandler)
        /admin/threads.json => com.twitter.server.AdminHttpServer$Route$IsolateFilter.andThen(com.twitter.server.handler.ThreadsHandler)
        /admin/announcer => com.twitter.server.AdminHttpServer$Route$IsolateFilter.andThen(com.twitter.server.view.TextBlockView.andThen(com.twitter.server.handler.AnnouncerHandler))
        /admin/dtab => com.twitter.server.AdminHttpServer$Route$IsolateFilter.andThen(com.twitter.server.view.TextBlockView.andThen(com.twitter.server.handler.DtabHandler))
        /admin/pprof/heap => com.twitter.server.AdminHttpServer$Route$IsolateFilter.andThen(com.twitter.server.handler.HeapResourceHandler)
        /admin/pprof/profile => com.twitter.server.AdminHttpServer$Route$IsolateFilter.andThen(com.twitter.server.handler.ProfileResourceHandler)
        /admin/pprof/contention => com.twitter.server.AdminHttpServer$Route$IsolateFilter.andThen(com.twitter.server.handler.ProfileResourceHandler)
        /admin/shutdown => com.twitter.server.AdminHttpServer$Route$IsolateFilter.andThen(com.twitter.server.handler.ShutdownHandler)
        /admin/tracing => com.twitter.server.AdminHttpServer$Route$IsolateFilter.andThen(com.twitter.server.handler.TracingHandler)
        /admin/metrics => com.twitter.server.AdminHttpServer$Route$IsolateFilter.andThen(com.twitter.server.handler.MetricQueryHandler)
        /admin/clients/ => com.twitter.server.AdminHttpServer$Route$IsolateFilter.andThen(com.twitter.server.handler.ClientRegistryHandler)
        /admin/balancers.json => com.twitter.server.AdminHttpServer$Route$IsolateFilter.andThen(com.twitter.server.handler.LoadBalancersHandler)
        /admin/servers/ => com.twitter.server.AdminHttpServer$Route$IsolateFilter.andThen(com.twitter.server.handler.ServerRegistryHandler)
        /admin/files/ => com.twitter.server.AdminHttpServer$Route$IsolateFilter.andThen(com.twitter.server.handler.ResourceHandler)
        /admin/registry.json => com.twitter.server.AdminHttpServer$Route$IsolateFilter.andThen(com.twitter.server.handler.RegistryHandler)
        /admin/toggles => com.twitter.server.AdminHttpServer$Route$IsolateFilter.andThen(com.twitter.server.handler.ToggleHandler)
        /admin/toggles/ => com.twitter.server.AdminHttpServer$Route$IsolateFilter.andThen(com.twitter.server.handler.ToggleHandler)
        /admin/tunables => com.twitter.server.AdminHttpServer$Route$IsolateFilter.andThen(com.twitter.server.handler.TunableHandler)
        /admin/tunables/ => com.twitter.server.AdminHttpServer$Route$IsolateFilter.andThen(com.twitter.server.handler.TunableHandler)
        /favicon.ico => com.twitter.server.AdminHttpServer$Route$IsolateFilter.andThen(com.twitter.server.handler.ResourceHandler)
        /admin/histograms => com.twitter.server.handler.HistogramQueryHandler
        /admin/histograms.json => com.twitter.server.handler.HistogramQueryHandler
04:36:20.282 [finatra/embedded/picchubackendpicchubackend-1] INFO  com.picchu.picchubackend.Server - Serving admin http on 127.0.0.1/127.0.0.1:0
04:36:20.291 [finatra/embedded/picchubackendpicchubackend-1] WARN  com.twitter.util.registry.Library$ - Tried to register a second library named "finatra"
04:36:20.307 [finatra/embedded/picchubackendpicchubackend-1] DEBUG c.t.inject.app.internal.FlagsModule - Binding flag: shutdown.time = 1.minutes
04:36:20.310 [finatra/embedded/picchubackendpicchubackend-1] DEBUG c.t.inject.app.internal.FlagsModule - Binding flag: service.version = 0.9.9
04:36:20.311 [finatra/embedded/picchubackendpicchubackend-1] DEBUG c.t.inject.app.internal.FlagsModule - Binding flag: https.announce =
04:36:20.311 [finatra/embedded/picchubackendpicchubackend-1] DEBUG c.t.inject.app.internal.FlagsModule - Binding flag: log.level = INFO
04:36:20.313 [finatra/embedded/picchubackendpicchubackend-1] DEBUG c.t.inject.app.internal.FlagsModule - Binding flag: local.doc.root =
04:36:20.314 [finatra/embedded/picchubackendpicchubackend-1] DEBUG c.t.inject.app.internal.FlagsModule - Binding flag: https.port =
04:36:20.315 [finatra/embedded/picchubackendpicchubackend-1] DEBUG c.t.inject.app.internal.FlagsModule - Binding flag: mustache.templates.dir = templates
04:36:20.316 [finatra/embedded/picchubackendpicchubackend-1] DEBUG c.t.inject.app.internal.FlagsModule - Binding flag: log.async = true
04:36:20.317 [finatra/embedded/picchubackendpicchubackend-1] DEBUG c.t.inject.app.internal.FlagsModule - Binding flag: http.name = http
04:36:20.317 [finatra/embedded/picchubackendpicchubackend-1] DEBUG c.t.inject.app.internal.FlagsModule - Binding flag: maxRequestSize = 5242880.bytes
04:36:20.318 [finatra/embedded/picchubackendpicchubackend-1] DEBUG c.t.inject.app.internal.FlagsModule - Binding flag: log.rollPolicy = Never
04:36:20.320 [finatra/embedded/picchubackendpicchubackend-1] DEBUG c.t.inject.app.internal.FlagsModule - Binding flag: help = false
04:36:20.321 [finatra/embedded/picchubackendpicchubackend-1] DEBUG c.t.inject.app.internal.FlagsModule - Binding flag: log.output = /dev/stderr
04:36:20.322 [finatra/embedded/picchubackendpicchubackend-1] DEBUG c.t.inject.app.internal.FlagsModule - Binding flag: http.port = 127.0.0.1:0
04:36:20.323 [finatra/embedded/picchubackendpicchubackend-1] DEBUG c.t.inject.app.internal.FlagsModule - Binding flag: log.async.maxsize = 4096
04:36:20.324 [finatra/embedded/picchubackendpicchubackend-1] DEBUG c.t.inject.app.internal.FlagsModule - Binding flag: https.name = https
04:36:20.325 [finatra/embedded/picchubackendpicchubackend-1] DEBUG c.t.inject.app.internal.FlagsModule - Binding flag: http.response.charset.enabled = true
04:36:20.326 [finatra/embedded/picchubackendpicchubackend-1] DEBUG c.t.inject.app.internal.FlagsModule - Binding flag: log.rotateCount = -1
04:36:20.327 [finatra/embedded/picchubackendpicchubackend-1] DEBUG c.t.inject.app.internal.FlagsModule - Binding flag: swagger.docs.endpoint = /docs
04:36:20.328 [finatra/embedded/picchubackendpicchubackend-1] DEBUG c.t.inject.app.internal.FlagsModule - Binding flag: doc.root =
04:36:20.330 [finatra/embedded/picchubackendpicchubackend-1] DEBUG c.t.inject.app.internal.FlagsModule - Binding flag: log.async.inferClassNames = false
04:36:20.331 [finatra/embedded/picchubackendpicchubackend-1] DEBUG c.t.inject.app.internal.FlagsModule - Binding flag: http.announce =
04:36:20.332 [finatra/embedded/picchubackendpicchubackend-1] DEBUG c.t.inject.app.internal.FlagsModule - Binding flag: log.append = true
04:36:20.333 [finatra/embedded/picchubackendpicchubackend-1] DEBUG c.t.inject.app.internal.FlagsModule - Binding flag: admin.port = 127.0.0.1/127.0.0.1:0
Fatal exception in server startup.
Waiting for warmup phases to complete...

Embedded server com.picchu.picchubackend-Picchubackend failed to startup: java.lang.NoClassDefFoundError: Ljavax/activation/MimetypesFileTypeMap;


===========================================================================
Closing EmbeddedHttpServer: com.picchu.picchubackend-Picchubackend
===========================================================================
Closing underlying TwitterServer: com.picchu.picchubackend-Picchubackend
Shutting down Future Pool: finatra/embedded/picchubackendpicchubackend
[info] MainControllerFeatureTest:
[info] com.picchu.picchubackend.controllers.MainControllerFeatureTest *** ABORTED ***
[info]   java.lang.Exception: java.lang.NoClassDefFoundError: Ljavax/activation/MimetypesFileTypeMap;
[info]   at com.twitter.inject.server.EmbeddedTwitterServer.$anonfun$runNonExitingMain$1(EmbeddedTwitterServer.scala:434)
[info]   at scala.runtime.java8.JFunction0$mcV$sp.apply(JFunction0$mcV$sp.java:12)
[info]   at com.twitter.util.Try$.apply(Try.scala:26)
[info]   at com.twitter.util.ExecutorServiceFuturePool$$anon$4.run(FuturePool.scala:140)
[info]   at java.base/java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:515)
[info]   at java.base/java.util.concurrent.FutureTask.run(FutureTask.java:264)
[info]   at java.base/java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1128)
[info]   at java.base/java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:628)
[info]   at java.base/java.lang.Thread.run(Thread.java:835)
[info]   ...
[info]   Cause: java.lang.NoClassDefFoundError: Ljavax/activation/MimetypesFileTypeMap;
[info]   at java.base/java.lang.Class.getDeclaredFields0(Native Method)
[info]   at java.base/java.lang.Class.privateGetDeclaredFields(Class.java:3067)
[info]   at java.base/java.lang.Class.getDeclaredFields(Class.java:2254)
[info]   at com.google.inject.spi.InjectionPoint.getDeclaredFields(InjectionPoint.java:760)
[info]   at com.google.inject.spi.InjectionPoint.getInjectionPoints(InjectionPoint.java:670)
[info]   at com.google.inject.spi.InjectionPoint.forInstanceMethodsAndFields(InjectionPoint.java:378)
[info]   at com.google.inject.internal.ConstructorBindingImpl.getInternalDependencies(ConstructorBindingImpl.java:182)
[info]   at com.google.inject.internal.InjectorImpl.getInternalDependencies(InjectorImpl.java:661)
[info]   at com.google.inject.internal.InjectorImpl.cleanup(InjectorImpl.java:617)
[info]   at com.google.inject.internal.InjectorImpl.initializeJitBinding(InjectorImpl.java:603)
[info]   ...
[info]   Cause: java.lang.ClassNotFoundException: javax.activation.MimetypesFileTypeMap
[info]   at java.base/java.net.URLClassLoader.findClass(URLClassLoader.java:436)
[info]   at java.base/java.lang.ClassLoader.loadClass(ClassLoader.java:588)
[info]   at java.base/java.lang.ClassLoader.loadClass(ClassLoader.java:521)
[info]   at java.base/java.lang.Class.getDeclaredFields0(Native Method)
[info]   at java.base/java.lang.Class.privateGetDeclaredFields(Class.java:3067)
[info]   at java.base/java.lang.Class.getDeclaredFields(Class.java:2254)
[info]   at com.google.inject.spi.InjectionPoint.getDeclaredFields(InjectionPoint.java:760)
[info]   at com.google.inject.spi.InjectionPoint.getInjectionPoints(InjectionPoint.java:670)
[info]   at com.google.inject.spi.InjectionPoint.forInstanceMethodsAndFields(InjectionPoint.java:378)
[info]   at com.google.inject.internal.ConstructorBindingImpl.getInternalDependencies(ConstructorBindingImpl.java:182)
[info]   ...

Starting com.picchu.picchubackend-Picchubackend with args: -http.port=127.0.0.1:0 -admin.port=127.0.0.1:0 -service.version=0.9.9
Waiting for warmup phases to complete...
04:36:21.414 [finatra/embedded/picchubackendpicchubackend-1] WARN  com.twitter.app.App$ - Multiple com.twitter.app.App main methods called. com.picchu.picchubackend-Picchubackend, then com.picchu.picchubackend-Picchubackend
04:36:21.414 [finatra/embedded/picchubackendpicchubackend-1] INFO  com.picchu.picchubackend.Server - Process started
04:36:21.418 [finatra/embedded/picchubackendpicchubackend-1] DEBUG com.picchu.picchubackend.Server - AdminHttpServer Muxer endpoints:
        /admin/logging => com.twitter.server.AdminHttpServer$Route$IsolateFilter.andThen(com.twitter.server.handler.logback.classic.LoggingHandler)
        /admin/ping => com.twitter.server.handler.ReplyHandler
         => com.twitter.server.AdminHttpServer$Route$IsolateFilter.andThen(com.twitter.server.handler.AdminRedirectHandler)
        /admin => com.twitter.server.AdminHttpServer$Route$IsolateFilter.andThen(com.twitter.server.handler.SummaryHandler)
        /admin/ => com.twitter.server.AdminHttpServer$Route$IsolateFilter.andThen(com.twitter.server.view.NotFoundView.andThen(com.twitter.server.handler.AdminRedirectHandler))
        /admin/server_info => com.twitter.server.AdminHttpServer$Route$IsolateFilter.andThen(com.twitter.server.view.TextBlockView.andThen(com.twitter.server.handler.ServerInfoHandler))
        /admin/contention => com.twitter.server.AdminHttpServer$Route$IsolateFilter.andThen(com.twitter.server.view.TextBlockView.andThen(com.twitter.server.handler.ContentionHandler))
        /admin/lint => com.twitter.server.AdminHttpServer$Route$IsolateFilter.andThen(com.twitter.server.handler.LintHandler)
        /admin/lint.json => com.twitter.server.AdminHttpServer$Route$IsolateFilter.andThen(com.twitter.server.handler.LintHandler)
        /admin/failedlint => com.twitter.server.AdminHttpServer$Route$IsolateFilter.andThen(com.twitter.server.handler.FailedLintRuleHandler)
        /admin/threads => com.twitter.server.AdminHttpServer$Route$IsolateFilter.andThen(com.twitter.server.handler.ThreadsHandler)
        /admin/threads.json => com.twitter.server.AdminHttpServer$Route$IsolateFilter.andThen(com.twitter.server.handler.ThreadsHandler)
        /admin/announcer => com.twitter.server.AdminHttpServer$Route$IsolateFilter.andThen(com.twitter.server.view.TextBlockView.andThen(com.twitter.server.handler.AnnouncerHandler))
        /admin/dtab => com.twitter.server.AdminHttpServer$Route$IsolateFilter.andThen(com.twitter.server.view.TextBlockView.andThen(com.twitter.server.handler.DtabHandler))
        /admin/pprof/heap => com.twitter.server.AdminHttpServer$Route$IsolateFilter.andThen(com.twitter.server.handler.HeapResourceHandler)
        /admin/pprof/profile => com.twitter.server.AdminHttpServer$Route$IsolateFilter.andThen(com.twitter.server.handler.ProfileResourceHandler)
        /admin/pprof/contention => com.twitter.server.AdminHttpServer$Route$IsolateFilter.andThen(com.twitter.server.handler.ProfileResourceHandler)
        /admin/shutdown => com.twitter.server.AdminHttpServer$Route$IsolateFilter.andThen(com.twitter.server.handler.ShutdownHandler)
        /admin/tracing => com.twitter.server.AdminHttpServer$Route$IsolateFilter.andThen(com.twitter.server.handler.TracingHandler)
        /admin/metrics => com.twitter.server.AdminHttpServer$Route$IsolateFilter.andThen(com.twitter.server.handler.MetricQueryHandler)
        /admin/clients/ => com.twitter.server.AdminHttpServer$Route$IsolateFilter.andThen(com.twitter.server.handler.ClientRegistryHandler)
        /admin/balancers.json => com.twitter.server.AdminHttpServer$Route$IsolateFilter.andThen(com.twitter.server.handler.LoadBalancersHandler)
        /admin/servers/ => com.twitter.server.AdminHttpServer$Route$IsolateFilter.andThen(com.twitter.server.handler.ServerRegistryHandler)
        /admin/files/ => com.twitter.server.AdminHttpServer$Route$IsolateFilter.andThen(com.twitter.server.handler.ResourceHandler)
        /admin/registry.json => com.twitter.server.AdminHttpServer$Route$IsolateFilter.andThen(com.twitter.server.handler.RegistryHandler)
        /admin/toggles => com.twitter.server.AdminHttpServer$Route$IsolateFilter.andThen(com.twitter.server.handler.ToggleHandler)
        /admin/toggles/ => com.twitter.server.AdminHttpServer$Route$IsolateFilter.andThen(com.twitter.server.handler.ToggleHandler)
        /admin/tunables => com.twitter.server.AdminHttpServer$Route$IsolateFilter.andThen(com.twitter.server.handler.TunableHandler)
        /admin/tunables/ => com.twitter.server.AdminHttpServer$Route$IsolateFilter.andThen(com.twitter.server.handler.TunableHandler)
        /favicon.ico => com.twitter.server.AdminHttpServer$Route$IsolateFilter.andThen(com.twitter.server.handler.ResourceHandler)
        /admin/histograms => com.twitter.server.handler.HistogramQueryHandler
        /admin/histograms.json => com.twitter.server.handler.HistogramQueryHandler
04:36:21.428 [finatra/embedded/picchubackendpicchubackend-1] INFO  com.picchu.picchubackend.Server - Serving admin http on 127.0.0.1/127.0.0.1:0
04:36:21.436 [finatra/embedded/picchubackendpicchubackend-1] WARN  com.twitter.util.registry.Library$ - Tried to register a second library named "finatra"
04:36:21.461 [finatra/embedded/picchubackendpicchubackend-1] DEBUG c.t.inject.app.internal.FlagsModule - Binding flag: shutdown.time = 1.minutes
04:36:21.463 [finatra/embedded/picchubackendpicchubackend-1] DEBUG c.t.inject.app.internal.FlagsModule - Binding flag: service.version = 0.9.9
04:36:21.463 [finatra/embedded/picchubackendpicchubackend-1] DEBUG c.t.inject.app.internal.FlagsModule - Binding flag: https.announce =
04:36:21.465 [finatra/embedded/picchubackendpicchubackend-1] DEBUG c.t.inject.app.internal.FlagsModule - Binding flag: log.level = INFO
04:36:21.466 [finatra/embedded/picchubackendpicchubackend-1] DEBUG c.t.inject.app.internal.FlagsModule - Binding flag: local.doc.root =
04:36:21.467 [finatra/embedded/picchubackendpicchubackend-1] DEBUG c.t.inject.app.internal.FlagsModule - Binding flag: https.port =
04:36:21.468 [finatra/embedded/picchubackendpicchubackend-1] DEBUG c.t.inject.app.internal.FlagsModule - Binding flag: mustache.templates.dir = templates
04:36:21.469 [finatra/embedded/picchubackendpicchubackend-1] DEBUG c.t.inject.app.internal.FlagsModule - Binding flag: log.async = true
04:36:21.469 [finatra/embedded/picchubackendpicchubackend-1] DEBUG c.t.inject.app.internal.FlagsModule - Binding flag: http.name = http
04:36:21.471 [finatra/embedded/picchubackendpicchubackend-1] DEBUG c.t.inject.app.internal.FlagsModule - Binding flag: maxRequestSize = 5242880.bytes
04:36:21.472 [finatra/embedded/picchubackendpicchubackend-1] DEBUG c.t.inject.app.internal.FlagsModule - Binding flag: log.rollPolicy = Never
04:36:21.473 [finatra/embedded/picchubackendpicchubackend-1] DEBUG c.t.inject.app.internal.FlagsModule - Binding flag: help = false
04:36:21.474 [finatra/embedded/picchubackendpicchubackend-1] DEBUG c.t.inject.app.internal.FlagsModule - Binding flag: log.output = /dev/stderr
04:36:21.475 [finatra/embedded/picchubackendpicchubackend-1] DEBUG c.t.inject.app.internal.FlagsModule - Binding flag: http.port = 127.0.0.1:0
04:36:21.476 [finatra/embedded/picchubackendpicchubackend-1] DEBUG c.t.inject.app.internal.FlagsModule - Binding flag: log.async.maxsize = 4096
04:36:21.478 [finatra/embedded/picchubackendpicchubackend-1] DEBUG c.t.inject.app.internal.FlagsModule - Binding flag: https.name = https
04:36:21.480 [finatra/embedded/picchubackendpicchubackend-1] DEBUG c.t.inject.app.internal.FlagsModule - Binding flag: http.response.charset.enabled = true
04:36:21.484 [finatra/embedded/picchubackendpicchubackend-1] DEBUG c.t.inject.app.internal.FlagsModule - Binding flag: log.rotateCount = -1
04:36:21.500 [finatra/embedded/picchubackendpicchubackend-1] DEBUG c.t.inject.app.internal.FlagsModule - Binding flag: swagger.docs.endpoint = /docs
04:36:21.501 [finatra/embedded/picchubackendpicchubackend-1] DEBUG c.t.inject.app.internal.FlagsModule - Binding flag: doc.root =
04:36:21.503 [finatra/embedded/picchubackendpicchubackend-1] DEBUG c.t.inject.app.internal.FlagsModule - Binding flag: log.async.inferClassNames = false
04:36:21.504 [finatra/embedded/picchubackendpicchubackend-1] DEBUG c.t.inject.app.internal.FlagsModule - Binding flag: http.announce =
04:36:21.506 [finatra/embedded/picchubackendpicchubackend-1] DEBUG c.t.inject.app.internal.FlagsModule - Binding flag: log.append = true
04:36:21.507 [finatra/embedded/picchubackendpicchubackend-1] DEBUG c.t.inject.app.internal.FlagsModule - Binding flag: admin.port = 127.0.0.1/127.0.0.1:0
Fatal exception in server startup.
Waiting for warmup phases to complete...

Embedded server com.picchu.picchubackend-Picchubackend failed to startup: java.lang.NoClassDefFoundError: Ljavax/activation/MimetypesFileTypeMap;


===========================================================================
Closing EmbeddedHttpServer: com.picchu.picchubackend-Picchubackend
===========================================================================
Closing underlying TwitterServer: com.picchu.picchubackend-Picchubackend
Shutting down Future Pool: finatra/embedded/picchubackendpicchubackend
[info] AdminControllerFeatureTest:
[info] com.picchu.picchubackend.controllers.AdminControllerFeatureTest *** ABORTED ***
[info]   java.lang.Exception: java.lang.NoClassDefFoundError: Ljavax/activation/MimetypesFileTypeMap;
[info]   at com.twitter.inject.server.EmbeddedTwitterServer.$anonfun$runNonExitingMain$1(EmbeddedTwitterServer.scala:434)
[info]   at scala.runtime.java8.JFunction0$mcV$sp.apply(JFunction0$mcV$sp.java:12)
[info]   at com.twitter.util.Try$.apply(Try.scala:26)
[info]   at com.twitter.util.ExecutorServiceFuturePool$$anon$4.run(FuturePool.scala:140)
[info]   at java.base/java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:515)
[info]   at java.base/java.util.concurrent.FutureTask.run(FutureTask.java:264)
[info]   at java.base/java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1128)
[info]   at java.base/java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:628)
[info]   at java.base/java.lang.Thread.run(Thread.java:835)
[info]   ...
[info]   Cause: java.lang.NoClassDefFoundError: Ljavax/activation/MimetypesFileTypeMap;
[info]   at java.base/java.lang.Class.getDeclaredFields0(Native Method)
[info]   at java.base/java.lang.Class.privateGetDeclaredFields(Class.java:3067)
[info]   at java.base/java.lang.Class.getDeclaredFields(Class.java:2254)
[info]   at com.google.inject.spi.InjectionPoint.getDeclaredFields(InjectionPoint.java:760)
[info]   at com.google.inject.spi.InjectionPoint.getInjectionPoints(InjectionPoint.java:670)
[info]   at com.google.inject.spi.InjectionPoint.forInstanceMethodsAndFields(InjectionPoint.java:378)
[info]   at com.google.inject.internal.ConstructorBindingImpl.getInternalDependencies(ConstructorBindingImpl.java:182)
[info]   at com.google.inject.internal.InjectorImpl.getInternalDependencies(InjectorImpl.java:661)
[info]   at com.google.inject.internal.InjectorImpl.cleanup(InjectorImpl.java:617)
[info]   at com.google.inject.internal.InjectorImpl.initializeJitBinding(InjectorImpl.java:603)
[info]   ...
[info]   Cause: java.lang.ClassNotFoundException: javax.activation.MimetypesFileTypeMap
[info]   at java.base/java.net.URLClassLoader.findClass(URLClassLoader.java:436)
[info]   at java.base/java.lang.ClassLoader.loadClass(ClassLoader.java:588)
[info]   at java.base/java.lang.ClassLoader.loadClass(ClassLoader.java:521)
[info]   at java.base/java.lang.Class.getDeclaredFields0(Native Method)
[info]   at java.base/java.lang.Class.privateGetDeclaredFields(Class.java:3067)
[info]   at java.base/java.lang.Class.getDeclaredFields(Class.java:2254)
[info]   at com.google.inject.spi.InjectionPoint.getDeclaredFields(InjectionPoint.java:760)
[info]   at com.google.inject.spi.InjectionPoint.getInjectionPoints(InjectionPoint.java:670)
[info]   at com.google.inject.spi.InjectionPoint.forInstanceMethodsAndFields(InjectionPoint.java:378)
[info]   at com.google.inject.internal.ConstructorBindingImpl.getInternalDependencies(ConstructorBindingImpl.java:182)
[info]   ...
formats: Set(WhiteSpaceDelimited, Html, Json)
[info] ScalaTest
[info] Run completed in 14 seconds, 408 milliseconds.
[info] Total number of tests run: 0
[info] Suites: completed 0, aborted 4
[info] Tests: succeeded 0, failed 0, canceled 0, ignored 0, pending 0
[info] *** 4 SUITES ABORTED ***
[error] Error: Total 4, Failed 0, Errors 4, Passed 0
[error] Error during tests:
[error]         com.picchu.picchubackend.controllers.AdminControllerFeatureTest
[error]         com.picchu.picchubackend.controllers.MainControllerFeatureTest
[error]         com.picchu.picchubackend.controllers.AccountControllerFeatureTest
[error]         com.picchu.picchubackend.StartupTest
[error] (Test / test) sbt.TestsFailedException: Tests unsuccessful
[error] Total time: 29 s, completed 2019���?????����?12:36:22
6:22
[IJ]picchu-backend(master)> 04:42:43.386 [Finalizer] DEBUG o.a.h.i.c.PoolingHttpClientConnectionManager - Connection manager is shutting down
04:42:43.391 [Finalizer] DEBUG o.a.h.i.c.PoolingHttpClientConnectionManager - Connection manager shut down

[IJ]picchu-backend(master)> clear
[error] Not a valid command: clear (similar: client, last, eval)
[error] Not a valid project ID: clear
[error] Expected ':'
[error] Not a valid key: clear (similar: clean, compilers, deliver)
[error] clear
[error]      ^
[IJ]picchu-backend(master)>
[IJ]picchu-backend(master)> clean
[success] Total time: 3 s, completed 2019���?????����?12:43:32
3:32
[IJ]picchu-backend(master)> compile
[info] Formatting 229 Scala sources...
[info] Compiling 215 Scala sources and 14 Java sources to D:\scala_workspace\picchu-backend\target\scala-2.12\classes ...
[warn]  [E1] src\main\scala\com\picchu\picchubackend\services\GetPostDetailService.scala
[warn]       parameter value getPostService in class GetPostDetailService is never used
[warn]       L19:     getPostService: FindPostService,
[warn]                ^
[warn]  [E2] src\main\scala\com\picchu\picchubackend\services\db\countrySetting\MultiUpsertCountrySettingsService.scala
[warn]       pattern var e in method applyOrElse is never used; `e@_' suppresses this warning
[warn]       L51:               case NonFatal(e) =>
[warn]                                        ^
[warn]  [E3] src\main\scala\com\picchu\picchubackend\services\db\errorCode\MultiUpsertErrorCodesService.scala
[warn]       pattern var e in method applyOrElse is never used; `e@_' suppresses this warning
[warn]       L51:               case NonFatal(e) =>
[warn]                                        ^
[warn]  [E4] src\main\scala\com\picchu\picchubackend\services\db\stringMapping\MultiUpsertStringMappingService.scala
[warn]       pattern var e in method applyOrElse is never used; `e@_' suppresses this warning
[warn]       L51:               case NonFatal(e) =>
[warn]                                        ^
[warn] src\main\scala\com\picchu\picchubackend\services\db\stringMapping\MultiUpsertStringMappingService.scala: L51 [E4]
[warn] src\main\scala\com\picchu\picchubackend\services\db\countrySetting\MultiUpsertCountrySettingsService.scala: L51 [E2]
[warn] src\main\scala\com\picchu\picchubackend\services\GetPostDetailService.scala: L19 [E1]
[warn] src\main\scala\com\picchu\picchubackend\services\db\errorCode\MultiUpsertErrorCodesService.scala: L51 [E3]
[info] Legend: Ln = line n, Cn = column n, En = error n
[info] Done compiling.
[success] Total time: 58 s, completed 2019���?????����?12:44:33
4:33
[IJ]picchu-backend(master)> test
[info] Formatting 7 Scala sources...
[info] Compiling 7 Scala sources to D:\scala_workspace\picchu-backend\target\scala-2.12\test-classes ...
[warn]  [E1] src\test\scala\com\picchu\picchubackend\MongoTestKit.scala
[warn]       Java enum V3_0 in Java enum Main is deprecated: see corresponding Javadoc for more information.
[warn]       L54:     val config    = new MongodConfigBuilder().version(Version.Main.V3_0).net(net).build()
[warn]                                                                               ^
[warn]  [E2] src\test\scala\com\picchu\picchubackend\MongoTestKit.scala
[warn]       Unused import
[warn]       L27: import com.github.mehmetakiftutuncu.errors.{CommonError, Errors, Maybe}
[warn]                                                                     ^
[warn]  [E3] src\test\scala\com\picchu\picchubackend\MongoTestKit.scala
[warn]       Unused import
[warn]       L27: import com.github.mehmetakiftutuncu.errors.{CommonError, Errors, Maybe}
[warn]                                                                             ^
[warn]  [E4] src\test\scala\com\picchu\picchubackend\MongoTestKit.scala
[warn]       Unused import
[warn]       L33: import mouse.boolean._
[warn]                                 ^
[warn]  [E5] src\test\scala\com\picchu\picchubackend\MongoTestKit.scala
[warn]       Unused import
[warn]       L41: import reactivemongo.api.indexes.{Index, IndexType}
[warn]                                              ^
[warn]  [E6] src\test\scala\com\picchu\picchubackend\MongoTestKit.scala
[warn]       Unused import
[warn]       L41: import reactivemongo.api.indexes.{Index, IndexType}
[warn]                                                     ^
[warn]  [E7] src\test\scala\com\picchu\picchubackend\MongoTestKit.scala
[warn]       Unused import
[warn]       L43: import scala.concurrent.Future
[warn]                                    ^
[warn]  [E8] src\test\scala\com\picchu\picchubackend\controllers\FeatureTestBase.scala
[warn]       Unused import
[warn]       L6: import com.picchu.picchubackend.models.http.AccountSignUpResult
[warn]                                                       ^
[warn] src\test\scala\com\picchu\picchubackend\MongoTestKit.scala: L27 [E2], L27 [E3], L33 [E4], L41 [E5], L41 [E6], L43 [E7], L54 [E1]
[warn] src\test\scala\com\picchu\picchubackend\controllers\FeatureTestBase.scala: L6 [E8]
[info] Legend: Ln = line n, Cn = column n, En = error n
[info] Done compiling.
04:44:51.150 [pool-65-thread-6] INFO  c.t.util.logging.Slf4jBridgeUtility$ - org.slf4j.bridge.SLF4JBridgeHandler installed.
04:44:51.550 [pool-65-thread-6] DEBUG i.n.u.i.l.InternalLoggerFactory - Using SLF4J as the default logging framework
04:44:51.558 [pool-65-thread-6] DEBUG io.netty.util.ResourceLeakDetector - -Dio.netty.leakDetection.level: simple
04:44:51.559 [pool-65-thread-6] DEBUG io.netty.util.ResourceLeakDetector - -Dio.netty.leakDetection.targetRecords: 4
04:44:51.587 [pool-65-thread-6] DEBUG i.n.util.internal.PlatformDependent - Platform: Windows
04:44:51.589 [pool-65-thread-6] DEBUG i.n.util.internal.PlatformDependent0 - -Dio.netty.noUnsafe: false
04:44:51.595 [pool-65-thread-6] DEBUG i.n.util.internal.PlatformDependent0 - Java version: 12
04:44:51.597 [pool-65-thread-6] DEBUG i.n.util.internal.PlatformDependent0 - sun.misc.Unsafe.theUnsafe: available
04:44:51.598 [pool-65-thread-6] DEBUG i.n.util.internal.PlatformDependent0 - sun.misc.Unsafe.copyMemory: available
04:44:51.599 [pool-65-thread-6] DEBUG i.n.util.internal.PlatformDependent0 - java.nio.Buffer.address: available
04:44:51.603 [pool-65-thread-6] DEBUG i.n.util.internal.PlatformDependent0 - direct buffer constructor: unavailable
java.lang.UnsupportedOperationException: Reflective setAccessible(true) disabled
        at io.netty.util.internal.ReflectionUtil.trySetAccessible(ReflectionUtil.java:31)
        at io.netty.util.internal.PlatformDependent0$4.run(PlatformDependent0.java:224)
        at java.base/java.security.AccessController.doPrivileged(AccessController.java:310)
        at io.netty.util.internal.PlatformDependent0.<clinit>(PlatformDependent0.java:218)
        at io.netty.util.internal.PlatformDependent.isAndroid(PlatformDependent.java:212)
        at io.netty.util.internal.PlatformDependent.<clinit>(PlatformDependent.java:80)
        at io.netty.util.ResourceLeakDetector.<init>(ResourceLeakDetector.java:162)
        at io.netty.util.ResourceLeakDetector.<init>(ResourceLeakDetector.java:207)
        at io.netty.util.ResourceLeakDetectorFactory$DefaultResourceLeakDetectorFactory.newResourceLeakDetector(ResourceLeakDetectorFactory.java:201)
        at io.netty.util.HashedWheelTimer.<clinit>(HashedWheelTimer.java:88)
        at com.twitter.finagle.netty4.HashedWheelTimer$.<init>(Netty4HashedWheelTimer.scala:79)
        at com.twitter.finagle.netty4.HashedWheelTimer$.<clinit>(Netty4HashedWheelTimer.scala)
        at com.twitter.finagle.netty4.Netty4HashedWheelTimer.<init>(Netty4HashedWheelTimer.scala:108)
        at java.base/jdk.internal.reflect.NativeConstructorAccessorImpl.newInstance0(Native Method)
        at java.base/jdk.internal.reflect.NativeConstructorAccessorImpl.newInstance(NativeConstructorAccessorImpl.java:62)
        at java.base/jdk.internal.reflect.DelegatingConstructorAccessorImpl.newInstance(DelegatingConstructorAccessorImpl.java:45)
        at java.base/java.lang.reflect.Constructor.newInstanceWithCaller(Constructor.java:500)
        at java.base/java.lang.reflect.ReflectAccess.newInstance(ReflectAccess.java:166)
        at java.base/jdk.internal.reflect.ReflectionFactory.newInstance(ReflectionFactory.java:404)
        at java.base/java.lang.Class.newInstance(Class.java:590)
        at com.twitter.app.LoadService$.$anonfun$loadImpls$7(LoadService.scala:192)
        at scala.collection.TraversableLike.$anonfun$flatMap$1(TraversableLike.scala:241)
        at scala.collection.mutable.ResizableArray.foreach(ResizableArray.scala:59)
        at scala.collection.mutable.ResizableArray.foreach$(ResizableArray.scala:52)
        at scala.collection.mutable.ArrayBuffer.foreach(ArrayBuffer.scala:48)
        at scala.collection.TraversableLike.flatMap(TraversableLike.scala:241)
        at scala.collection.TraversableLike.flatMap$(TraversableLike.scala:238)
        at scala.collection.AbstractTraversable.flatMap(Traversable.scala:104)
        at com.twitter.app.LoadService$.loadImpls(LoadService.scala:181)
        at com.twitter.app.LoadService$.apply(LoadService.scala:135)
        at com.twitter.app.LoadService$.apply(LoadService.scala:149)
        at com.twitter.finagle.util.LoadService$.apply(LoadService.scala:14)
        at com.twitter.finagle.util.DefaultTimer$.<init>(DefaultTimer.scala:80)
        at com.twitter.finagle.util.DefaultTimer$.<clinit>(DefaultTimer.scala)
        at com.twitter.finagle.stats.JsonExporter.<init>(JsonExporter.scala:140)
        at com.twitter.finagle.stats.MetricsExporter.<init>(MetricsStatsReceiver.scala:141)
        at com.twitter.finagle.stats.MetricsExporter.<init>(MetricsStatsReceiver.scala:144)
        at java.base/jdk.internal.reflect.NativeConstructorAccessorImpl.newInstance0(Native Method)
        at java.base/jdk.internal.reflect.NativeConstructorAccessorImpl.newInstance(NativeConstructorAccessorImpl.java:62)
        at java.base/jdk.internal.reflect.DelegatingConstructorAccessorImpl.newInstance(DelegatingConstructorAccessorImpl.java:45)
        at java.base/java.lang.reflect.Constructor.newInstanceWithCaller(Constructor.java:500)
        at java.base/java.lang.reflect.ReflectAccess.newInstance(ReflectAccess.java:166)
        at java.base/jdk.internal.reflect.ReflectionFactory.newInstance(ReflectionFactory.java:404)
        at java.base/java.lang.Class.newInstance(Class.java:590)
        at com.twitter.app.LoadService$.$anonfun$loadImpls$7(LoadService.scala:192)
        at scala.collection.TraversableLike.$anonfun$flatMap$1(TraversableLike.scala:241)
        at scala.collection.mutable.ResizableArray.foreach(ResizableArray.scala:59)
        at scala.collection.mutable.ResizableArray.foreach$(ResizableArray.scala:52)
        at scala.collection.mutable.ArrayBuffer.foreach(ArrayBuffer.scala:48)
        at scala.collection.TraversableLike.flatMap(TraversableLike.scala:241)
        at scala.collection.TraversableLike.flatMap$(TraversableLike.scala:238)
        at scala.collection.AbstractTraversable.flatMap(Traversable.scala:104)
        at com.twitter.app.LoadService$.loadImpls(LoadService.scala:181)
        at com.twitter.app.LoadService$.apply(LoadService.scala:135)
        at com.twitter.app.LoadService$.apply(LoadService.scala:149)
        at com.twitter.finagle.util.LoadService$.apply(LoadService.scala:14)
        at com.twitter.finagle.http.HttpMuxer$.<init>(HttpMuxer.scala:120)
        at com.twitter.finagle.http.HttpMuxer$.<clinit>(HttpMuxer.scala)
        at com.twitter.server.Lifecycle.$init$(Lifecycle.scala:14)
        at com.picchu.picchubackend.Server.<init>(Server.scala:20)
        at com.picchu.picchubackend.StartupTest.<init>(StartupTest.scala:9)
        at java.base/jdk.internal.reflect.NativeConstructorAccessorImpl.newInstance0(Native Method)
        at java.base/jdk.internal.reflect.NativeConstructorAccessorImpl.newInstance(NativeConstructorAccessorImpl.java:62)
        at java.base/jdk.internal.reflect.DelegatingConstructorAccessorImpl.newInstance(DelegatingConstructorAccessorImpl.java:45)
        at java.base/java.lang.reflect.Constructor.newInstanceWithCaller(Constructor.java:500)
        at java.base/java.lang.reflect.ReflectAccess.newInstance(ReflectAccess.java:166)
        at java.base/jdk.internal.reflect.ReflectionFactory.newInstance(ReflectionFactory.java:404)
        at java.base/java.lang.Class.newInstance(Class.java:590)
        at org.scalatest.tools.Framework$ScalaTestTask.execute(Framework.scala:435)
        at sbt.TestRunner.runTest$1(TestFramework.scala:113)
        at sbt.TestRunner.run(TestFramework.scala:124)
        at sbt.TestFramework$$anon$2$$anonfun$$lessinit$greater$1.$anonfun$apply$1(TestFramework.scala:282)
        at sbt.TestFramework$.sbt$TestFramework$$withContextLoader(TestFramework.scala:246)
        at sbt.TestFramework$$anon$2$$anonfun$$lessinit$greater$1.apply(TestFramework.scala:282)
        at sbt.TestFramework$$anon$2$$anonfun$$lessinit$greater$1.apply(TestFramework.scala:282)
        at sbt.TestFunction.apply(TestFramework.scala:294)
        at sbt.Tests$.processRunnable$1(Tests.scala:347)
        at sbt.Tests$.$anonfun$makeSerial$1(Tests.scala:353)
        at sbt.std.Transform$$anon$3.$anonfun$apply$2(System.scala:46)
        at sbt.std.Transform$$anon$4.work(System.scala:67)
        at sbt.Execute.$anonfun$submit$2(Execute.scala:269)
        at sbt.internal.util.ErrorHandling$.wideConvert(ErrorHandling.scala:16)
        at sbt.Execute.work(Execute.scala:278)
        at sbt.Execute.$anonfun$submit$1(Execute.scala:269)
        at sbt.ConcurrentRestrictions$$anon$4.$anonfun$submitValid$1(ConcurrentRestrictions.scala:178)
        at sbt.CompletionService$$anon$2.call(CompletionService.scala:37)
        at java.base/java.util.concurrent.FutureTask.run(FutureTask.java:264)
        at java.base/java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:515)
        at java.base/java.util.concurrent.FutureTask.run(FutureTask.java:264)
        at java.base/java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1128)
        at java.base/java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:628)
        at java.base/java.lang.Thread.run(Thread.java:835)
04:44:51.623 [pool-65-thread-6] DEBUG i.n.util.internal.PlatformDependent0 - java.nio.Bits.unaligned: available, true
04:44:51.625 [pool-65-thread-6] DEBUG i.n.util.internal.PlatformDependent0 - jdk.internal.misc.Unsafe.allocateUninitializedArray(int): unavailable
java.lang.IllegalAccessException: class io.netty.util.internal.PlatformDependent0$6 cannot access class jdk.internal.misc.Unsafe (in module java.base) because module java.base does not export jdk.internal.misc to unnamed module @242bb98a
        at java.base/jdk.internal.reflect.Reflection.newIllegalAccessException(Reflection.java:355)
        at java.base/java.lang.reflect.AccessibleObject.checkAccess(AccessibleObject.java:639)
        at java.base/java.lang.reflect.Method.invoke(Method.java:559)
        at io.netty.util.internal.PlatformDependent0$6.run(PlatformDependent0.java:334)
        at java.base/java.security.AccessController.doPrivileged(AccessController.java:310)
        at io.netty.util.internal.PlatformDependent0.<clinit>(PlatformDependent0.java:325)
        at io.netty.util.internal.PlatformDependent.isAndroid(PlatformDependent.java:212)
        at io.netty.util.internal.PlatformDependent.<clinit>(PlatformDependent.java:80)
        at io.netty.util.ResourceLeakDetector.<init>(ResourceLeakDetector.java:162)
        at io.netty.util.ResourceLeakDetector.<init>(ResourceLeakDetector.java:207)
        at io.netty.util.ResourceLeakDetectorFactory$DefaultResourceLeakDetectorFactory.newResourceLeakDetector(ResourceLeakDetectorFactory.java:201)
        at io.netty.util.HashedWheelTimer.<clinit>(HashedWheelTimer.java:88)
        at com.twitter.finagle.netty4.HashedWheelTimer$.<init>(Netty4HashedWheelTimer.scala:79)
        at com.twitter.finagle.netty4.HashedWheelTimer$.<clinit>(Netty4HashedWheelTimer.scala)
        at com.twitter.finagle.netty4.Netty4HashedWheelTimer.<init>(Netty4HashedWheelTimer.scala:108)
        at java.base/jdk.internal.reflect.NativeConstructorAccessorImpl.newInstance0(Native Method)
        at java.base/jdk.internal.reflect.NativeConstructorAccessorImpl.newInstance(NativeConstructorAccessorImpl.java:62)
        at java.base/jdk.internal.reflect.DelegatingConstructorAccessorImpl.newInstance(DelegatingConstructorAccessorImpl.java:45)
        at java.base/java.lang.reflect.Constructor.newInstanceWithCaller(Constructor.java:500)
        at java.base/java.lang.reflect.ReflectAccess.newInstance(ReflectAccess.java:166)
        at java.base/jdk.internal.reflect.ReflectionFactory.newInstance(ReflectionFactory.java:404)
        at java.base/java.lang.Class.newInstance(Class.java:590)
        at com.twitter.app.LoadService$.$anonfun$loadImpls$7(LoadService.scala:192)
        at scala.collection.TraversableLike.$anonfun$flatMap$1(TraversableLike.scala:241)
        at scala.collection.mutable.ResizableArray.foreach(ResizableArray.scala:59)
        at scala.collection.mutable.ResizableArray.foreach$(ResizableArray.scala:52)
        at scala.collection.mutable.ArrayBuffer.foreach(ArrayBuffer.scala:48)
        at scala.collection.TraversableLike.flatMap(TraversableLike.scala:241)
        at scala.collection.TraversableLike.flatMap$(TraversableLike.scala:238)
        at scala.collection.AbstractTraversable.flatMap(Traversable.scala:104)
        at com.twitter.app.LoadService$.loadImpls(LoadService.scala:181)
        at com.twitter.app.LoadService$.apply(LoadService.scala:135)
        at com.twitter.app.LoadService$.apply(LoadService.scala:149)
        at com.twitter.finagle.util.LoadService$.apply(LoadService.scala:14)
        at com.twitter.finagle.util.DefaultTimer$.<init>(DefaultTimer.scala:80)
        at com.twitter.finagle.util.DefaultTimer$.<clinit>(DefaultTimer.scala)
        at com.twitter.finagle.stats.JsonExporter.<init>(JsonExporter.scala:140)
        at com.twitter.finagle.stats.MetricsExporter.<init>(MetricsStatsReceiver.scala:141)
        at com.twitter.finagle.stats.MetricsExporter.<init>(MetricsStatsReceiver.scala:144)
        at java.base/jdk.internal.reflect.NativeConstructorAccessorImpl.newInstance0(Native Method)
        at java.base/jdk.internal.reflect.NativeConstructorAccessorImpl.newInstance(NativeConstructorAccessorImpl.java:62)
        at java.base/jdk.internal.reflect.DelegatingConstructorAccessorImpl.newInstance(DelegatingConstructorAccessorImpl.java:45)
        at java.base/java.lang.reflect.Constructor.newInstanceWithCaller(Constructor.java:500)
        at java.base/java.lang.reflect.ReflectAccess.newInstance(ReflectAccess.java:166)
        at java.base/jdk.internal.reflect.ReflectionFactory.newInstance(ReflectionFactory.java:404)
        at java.base/java.lang.Class.newInstance(Class.java:590)
        at com.twitter.app.LoadService$.$anonfun$loadImpls$7(LoadService.scala:192)
        at scala.collection.TraversableLike.$anonfun$flatMap$1(TraversableLike.scala:241)
        at scala.collection.mutable.ResizableArray.foreach(ResizableArray.scala:59)
        at scala.collection.mutable.ResizableArray.foreach$(ResizableArray.scala:52)
        at scala.collection.mutable.ArrayBuffer.foreach(ArrayBuffer.scala:48)
        at scala.collection.TraversableLike.flatMap(TraversableLike.scala:241)
        at scala.collection.TraversableLike.flatMap$(TraversableLike.scala:238)
        at scala.collection.AbstractTraversable.flatMap(Traversable.scala:104)
        at com.twitter.app.LoadService$.loadImpls(LoadService.scala:181)
        at com.twitter.app.LoadService$.apply(LoadService.scala:135)
        at com.twitter.app.LoadService$.apply(LoadService.scala:149)
        at com.twitter.finagle.util.LoadService$.apply(LoadService.scala:14)
        at com.twitter.finagle.http.HttpMuxer$.<init>(HttpMuxer.scala:120)
        at com.twitter.finagle.http.HttpMuxer$.<clinit>(HttpMuxer.scala)
        at com.twitter.server.Lifecycle.$init$(Lifecycle.scala:14)
        at com.picchu.picchubackend.Server.<init>(Server.scala:20)
        at com.picchu.picchubackend.StartupTest.<init>(StartupTest.scala:9)
        at java.base/jdk.internal.reflect.NativeConstructorAccessorImpl.newInstance0(Native Method)
        at java.base/jdk.internal.reflect.NativeConstructorAccessorImpl.newInstance(NativeConstructorAccessorImpl.java:62)
        at java.base/jdk.internal.reflect.DelegatingConstructorAccessorImpl.newInstance(DelegatingConstructorAccessorImpl.java:45)
        at java.base/java.lang.reflect.Constructor.newInstanceWithCaller(Constructor.java:500)
        at java.base/java.lang.reflect.ReflectAccess.newInstance(ReflectAccess.java:166)
        at java.base/jdk.internal.reflect.ReflectionFactory.newInstance(ReflectionFactory.java:404)
        at java.base/java.lang.Class.newInstance(Class.java:590)
        at org.scalatest.tools.Framework$ScalaTestTask.execute(Framework.scala:435)
        at sbt.TestRunner.runTest$1(TestFramework.scala:113)
        at sbt.TestRunner.run(TestFramework.scala:124)
        at sbt.TestFramework$$anon$2$$anonfun$$lessinit$greater$1.$anonfun$apply$1(TestFramework.scala:282)
        at sbt.TestFramework$.sbt$TestFramework$$withContextLoader(TestFramework.scala:246)
        at sbt.TestFramework$$anon$2$$anonfun$$lessinit$greater$1.apply(TestFramework.scala:282)
        at sbt.TestFramework$$anon$2$$anonfun$$lessinit$greater$1.apply(TestFramework.scala:282)
        at sbt.TestFunction.apply(TestFramework.scala:294)
        at sbt.Tests$.processRunnable$1(Tests.scala:347)
        at sbt.Tests$.$anonfun$makeSerial$1(Tests.scala:353)
        at sbt.std.Transform$$anon$3.$anonfun$apply$2(System.scala:46)
        at sbt.std.Transform$$anon$4.work(System.scala:67)
        at sbt.Execute.$anonfun$submit$2(Execute.scala:269)
        at sbt.internal.util.ErrorHandling$.wideConvert(ErrorHandling.scala:16)
        at sbt.Execute.work(Execute.scala:278)
        at sbt.Execute.$anonfun$submit$1(Execute.scala:269)
        at sbt.ConcurrentRestrictions$$anon$4.$anonfun$submitValid$1(ConcurrentRestrictions.scala:178)
        at sbt.CompletionService$$anon$2.call(CompletionService.scala:37)
        at java.base/java.util.concurrent.FutureTask.run(FutureTask.java:264)
        at java.base/java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:515)
        at java.base/java.util.concurrent.FutureTask.run(FutureTask.java:264)
        at java.base/java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1128)
        at java.base/java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:628)
        at java.base/java.lang.Thread.run(Thread.java:835)
04:44:51.662 [pool-65-thread-6] DEBUG i.n.util.internal.PlatformDependent0 - java.nio.DirectByteBuffer.<init>(long, int): unavailable
04:44:51.662 [pool-65-thread-6] DEBUG i.n.util.internal.PlatformDependent - sun.misc.Unsafe: available
04:44:51.663 [pool-65-thread-6] DEBUG i.n.util.internal.PlatformDependent - maxDirectMemory: 4294967296 bytes (maybe)
04:44:51.663 [pool-65-thread-6] DEBUG i.n.util.internal.PlatformDependent - -Dio.netty.tmpdir: C:\Users\Rocky\AppData\Local\Temp (java.io.tmpdir)
04:44:51.664 [pool-65-thread-6] DEBUG i.n.util.internal.PlatformDependent - -Dio.netty.bitMode: 64 (sun.arch.data.model)
04:44:51.665 [pool-65-thread-6] DEBUG i.n.util.internal.PlatformDependent - -Dio.netty.maxDirectMemory: -1 bytes
04:44:51.665 [pool-65-thread-6] DEBUG i.n.util.internal.PlatformDependent - -Dio.netty.uninitializedArrayAllocationThreshold: -1
04:44:51.667 [pool-65-thread-6] DEBUG io.netty.util.internal.CleanerJava9 - java.nio.ByteBuffer.cleaner(): available
04:44:51.667 [pool-65-thread-6] DEBUG i.n.util.internal.PlatformDependent - -Dio.netty.noPreferDirect: false
04:44:51.667 [pool-65-thread-6] DEBUG i.n.util.ResourceLeakDetectorFactory - Loaded default ResourceLeakDetector: io.netty.util.ResourceLeakDetector@70a38513
04:44:51.702 [pool-65-thread-6] DEBUG i.n.util.internal.PlatformDependent - org.jctools-core.MpscChunkedArrayQueue: available
04:44:52.225 [pool-65-thread-6] INFO  com.twitter.finagle.http.HttpMuxer$ - HttpMuxer[/admin/metrics.json] = com.twitter.finagle.stats.MetricsExporter(com.twitter.finagle.stats.MetricsExporter)
04:44:52.227 [pool-65-thread-6] INFO  com.twitter.finagle.http.HttpMuxer$ - HttpMuxer[/admin/per_host_metrics.json] = com.twitter.finagle.stats.HostMetricsExporter(com.twitter.finagle.stats.HostMetricsExporter)

Starting com.picchu.picchubackend-Picchubackend with args: -http.port=127.0.0.1:0 -admin.port=127.0.0.1:0
04:44:52.396 [finatra/embedded/picchubackendpicchubackend-1] INFO  com.picchu.picchubackend.Server - Process started
Waiting for warmup phases to complete...
04:44:52.991 [finatra/embedded/picchubackendpicchubackend-1] DEBUG com.picchu.picchubackend.Server - AdminHttpServer Muxer endpoints:
        /admin/logging => com.twitter.server.AdminHttpServer$Route$IsolateFilter.andThen(com.twitter.server.handler.logback.classic.LoggingHandler)
        /admin/ping => com.twitter.server.handler.ReplyHandler
         => com.twitter.server.AdminHttpServer$Route$IsolateFilter.andThen(com.twitter.server.handler.AdminRedirectHandler)
        /admin => com.twitter.server.AdminHttpServer$Route$IsolateFilter.andThen(com.twitter.server.handler.SummaryHandler)
        /admin/ => com.twitter.server.AdminHttpServer$Route$IsolateFilter.andThen(com.twitter.server.view.NotFoundView.andThen(com.twitter.server.handler.AdminRedirectHandler))
        /admin/server_info => com.twitter.server.AdminHttpServer$Route$IsolateFilter.andThen(com.twitter.server.view.TextBlockView.andThen(com.twitter.server.handler.ServerInfoHandler))
        /admin/contention => com.twitter.server.AdminHttpServer$Route$IsolateFilter.andThen(com.twitter.server.view.TextBlockView.andThen(com.twitter.server.handler.ContentionHandler))
        /admin/lint => com.twitter.server.AdminHttpServer$Route$IsolateFilter.andThen(com.twitter.server.handler.LintHandler)
        /admin/lint.json => com.twitter.server.AdminHttpServer$Route$IsolateFilter.andThen(com.twitter.server.handler.LintHandler)
        /admin/failedlint => com.twitter.server.AdminHttpServer$Route$IsolateFilter.andThen(com.twitter.server.handler.FailedLintRuleHandler)
        /admin/threads => com.twitter.server.AdminHttpServer$Route$IsolateFilter.andThen(com.twitter.server.handler.ThreadsHandler)
        /admin/threads.json => com.twitter.server.AdminHttpServer$Route$IsolateFilter.andThen(com.twitter.server.handler.ThreadsHandler)
        /admin/announcer => com.twitter.server.AdminHttpServer$Route$IsolateFilter.andThen(com.twitter.server.view.TextBlockView.andThen(com.twitter.server.handler.AnnouncerHandler))
        /admin/dtab => com.twitter.server.AdminHttpServer$Route$IsolateFilter.andThen(com.twitter.server.view.TextBlockView.andThen(com.twitter.server.handler.DtabHandler))
        /admin/pprof/heap => com.twitter.server.AdminHttpServer$Route$IsolateFilter.andThen(com.twitter.server.handler.HeapResourceHandler)
        /admin/pprof/profile => com.twitter.server.AdminHttpServer$Route$IsolateFilter.andThen(com.twitter.server.handler.ProfileResourceHandler)
        /admin/pprof/contention => com.twitter.server.AdminHttpServer$Route$IsolateFilter.andThen(com.twitter.server.handler.ProfileResourceHandler)
        /admin/shutdown => com.twitter.server.AdminHttpServer$Route$IsolateFilter.andThen(com.twitter.server.handler.ShutdownHandler)
        /admin/tracing => com.twitter.server.AdminHttpServer$Route$IsolateFilter.andThen(com.twitter.server.handler.TracingHandler)
        /admin/metrics => com.twitter.server.AdminHttpServer$Route$IsolateFilter.andThen(com.twitter.server.handler.MetricQueryHandler)
        /admin/clients/ => com.twitter.server.AdminHttpServer$Route$IsolateFilter.andThen(com.twitter.server.handler.ClientRegistryHandler)
        /admin/balancers.json => com.twitter.server.AdminHttpServer$Route$IsolateFilter.andThen(com.twitter.server.handler.LoadBalancersHandler)
        /admin/servers/ => com.twitter.server.AdminHttpServer$Route$IsolateFilter.andThen(com.twitter.server.handler.ServerRegistryHandler)
        /admin/files/ => com.twitter.server.AdminHttpServer$Route$IsolateFilter.andThen(com.twitter.server.handler.ResourceHandler)
        /admin/registry.json => com.twitter.server.AdminHttpServer$Route$IsolateFilter.andThen(com.twitter.server.handler.RegistryHandler)
        /admin/toggles => com.twitter.server.AdminHttpServer$Route$IsolateFilter.andThen(com.twitter.server.handler.ToggleHandler)
        /admin/toggles/ => com.twitter.server.AdminHttpServer$Route$IsolateFilter.andThen(com.twitter.server.handler.ToggleHandler)
        /admin/tunables => com.twitter.server.AdminHttpServer$Route$IsolateFilter.andThen(com.twitter.server.handler.TunableHandler)
        /admin/tunables/ => com.twitter.server.AdminHttpServer$Route$IsolateFilter.andThen(com.twitter.server.handler.TunableHandler)
        /favicon.ico => com.twitter.server.AdminHttpServer$Route$IsolateFilter.andThen(com.twitter.server.handler.ResourceHandler)
        /admin/histograms => com.twitter.server.handler.HistogramQueryHandler
        /admin/histograms.json => com.twitter.server.handler.HistogramQueryHandler
04:44:53.008 [finatra/embedded/picchubackendpicchubackend-1] INFO  com.picchu.picchubackend.Server - Serving admin http on 127.0.0.1/127.0.0.1:0
Waiting for warmup phases to complete...
04:44:53.510 [finatra/embedded/picchubackendpicchubackend-1] DEBUG i.n.buffer.PooledByteBufAllocator - -Dio.netty.allocator.numHeapArenas: 8
04:44:53.510 [finatra/embedded/picchubackendpicchubackend-1] DEBUG i.n.buffer.PooledByteBufAllocator - -Dio.netty.allocator.numDirectArenas: 8
04:44:53.510 [finatra/embedded/picchubackendpicchubackend-1] DEBUG i.n.buffer.PooledByteBufAllocator - -Dio.netty.allocator.pageSize: 8192
04:44:53.511 [finatra/embedded/picchubackendpicchubackend-1] DEBUG i.n.buffer.PooledByteBufAllocator - -Dio.netty.allocator.maxOrder: 7
04:44:53.511 [finatra/embedded/picchubackendpicchubackend-1] DEBUG i.n.buffer.PooledByteBufAllocator - -Dio.netty.allocator.chunkSize: 1048576
04:44:53.511 [finatra/embedded/picchubackendpicchubackend-1] DEBUG i.n.buffer.PooledByteBufAllocator - -Dio.netty.allocator.tinyCacheSize: 512
04:44:53.511 [finatra/embedded/picchubackendpicchubackend-1] DEBUG i.n.buffer.PooledByteBufAllocator - -Dio.netty.allocator.smallCacheSize: 256
04:44:53.511 [finatra/embedded/picchubackendpicchubackend-1] DEBUG i.n.buffer.PooledByteBufAllocator - -Dio.netty.allocator.normalCacheSize: 64
04:44:53.512 [finatra/embedded/picchubackendpicchubackend-1] DEBUG i.n.buffer.PooledByteBufAllocator - -Dio.netty.allocator.maxCachedBufferCapacity: 32768
04:44:53.512 [finatra/embedded/picchubackendpicchubackend-1] DEBUG i.n.buffer.PooledByteBufAllocator - -Dio.netty.allocator.cacheTrimInterval: 8192
04:44:53.512 [finatra/embedded/picchubackendpicchubackend-1] DEBUG i.n.buffer.PooledByteBufAllocator - -Dio.netty.allocator.useCacheForAllThreads: true
04:44:53.517 [finatra/embedded/picchubackendpicchubackend-1] DEBUG i.n.u.i.InternalThreadLocalMap - -Dio.netty.threadLocalMap.stringBuilder.initialSize: 1024
04:44:53.517 [finatra/embedded/picchubackendpicchubackend-1] DEBUG i.n.u.i.InternalThreadLocalMap - -Dio.netty.threadLocalMap.stringBuilder.maxSize: 4096
04:44:53.542 [finatra/embedded/picchubackendpicchubackend-1] INFO  com.twitter.finagle - Finagle version 18.12.0 (rev=8d741a599d0af0975d1a4a94674d989c187f6c79) built at 20181211-102957
04:44:53.620 [finatra/embedded/picchubackendpicchubackend-1] DEBUG i.n.c.MultithreadEventLoopGroup - -Dio.netty.eventLoopThreads: 8
04:44:53.651 [finatra/embedded/picchubackendpicchubackend-1] DEBUG io.netty.channel.nio.NioEventLoop - -Dio.netty.noKeySetOptimization: false
04:44:53.653 [finatra/embedded/picchubackendpicchubackend-1] DEBUG io.netty.channel.nio.NioEventLoop - -Dio.netty.selectorAutoRebuildThreshold: 512
04:44:53.721 [finatra/embedded/picchubackendpicchubackend-1] DEBUG io.netty.channel.DefaultChannelId - -Dio.netty.processId: 12012 (auto-detected)
04:44:53.724 [finatra/embedded/picchubackendpicchubackend-1] DEBUG io.netty.util.NetUtil - -Djava.net.preferIPv4Stack: false
04:44:53.724 [finatra/embedded/picchubackendpicchubackend-1] DEBUG io.netty.util.NetUtil - -Djava.net.preferIPv6Addresses: false
04:44:53.989 [finatra/embedded/picchubackendpicchubackend-1] DEBUG io.netty.util.NetUtil - Loopback interface: lo (Software Loopback Interface 1, 127.0.0.1)
04:44:53.992 [finatra/embedded/picchubackendpicchubackend-1] DEBUG io.netty.util.NetUtil - Failed to get SOMAXCONN from sysctl and file \proc\sys\net\core\somaxconn. Default: 200
04:44:54.304 [finatra/embedded/picchubackendpicchubackend-1] DEBUG io.netty.channel.DefaultChannelId - -Dio.netty.machineId: 00:15:5d:ff:fe:de:e6:84 (auto-detected)
04:44:54.363 [finatra/embedded/picchubackendpicchubackend-1] DEBUG io.netty.buffer.ByteBufUtil - -Dio.netty.allocator.type: pooled
04:44:54.363 [finatra/embedded/picchubackendpicchubackend-1] DEBUG io.netty.buffer.ByteBufUtil - -Dio.netty.threadLocalDirectBufferSize: 0
04:44:54.364 [finatra/embedded/picchubackendpicchubackend-1] DEBUG io.netty.buffer.ByteBufUtil - -Dio.netty.maxThreadLocalCharBufferSize: 16384
Waiting for warmup phases to complete...
04:44:55.079 [finatra/embedded/picchubackendpicchubackend-1] DEBUG c.t.inject.app.internal.FlagsModule - Binding flag: shutdown.time = 1.minutes
04:44:55.088 [finatra/embedded/picchubackendpicchubackend-1] DEBUG c.t.inject.app.internal.FlagsModule - Binding flag: service.version = 1.0.0
04:44:55.102 [finatra/embedded/picchubackendpicchubackend-1] DEBUG c.t.inject.app.internal.FlagsModule - Binding flag: https.announce =
04:44:55.104 [finatra/embedded/picchubackendpicchubackend-1] DEBUG c.t.inject.app.internal.FlagsModule - Binding flag: log.level = INFO
04:44:55.106 [finatra/embedded/picchubackendpicchubackend-1] DEBUG c.t.inject.app.internal.FlagsModule - Binding flag: local.doc.root =
04:44:55.107 [finatra/embedded/picchubackendpicchubackend-1] DEBUG c.t.inject.app.internal.FlagsModule - Binding flag: https.port =
04:44:55.110 [finatra/embedded/picchubackendpicchubackend-1] DEBUG c.t.inject.app.internal.FlagsModule - Binding flag: mustache.templates.dir = templates
04:44:55.112 [finatra/embedded/picchubackendpicchubackend-1] DEBUG c.t.inject.app.internal.FlagsModule - Binding flag: log.async = true
04:44:55.114 [finatra/embedded/picchubackendpicchubackend-1] DEBUG c.t.inject.app.internal.FlagsModule - Binding flag: http.name = http
04:44:55.116 [finatra/embedded/picchubackendpicchubackend-1] DEBUG c.t.inject.app.internal.FlagsModule - Binding flag: maxRequestSize = 5242880.bytes
04:44:55.118 [finatra/embedded/picchubackendpicchubackend-1] DEBUG c.t.inject.app.internal.FlagsModule - Binding flag: log.rollPolicy = Never
04:44:55.120 [finatra/embedded/picchubackendpicchubackend-1] DEBUG c.t.inject.app.internal.FlagsModule - Binding flag: help = false
04:44:55.122 [finatra/embedded/picchubackendpicchubackend-1] DEBUG c.t.inject.app.internal.FlagsModule - Binding flag: log.output = /dev/stderr
04:44:55.124 [finatra/embedded/picchubackendpicchubackend-1] DEBUG c.t.inject.app.internal.FlagsModule - Binding flag: http.port = 127.0.0.1:0
04:44:55.126 [finatra/embedded/picchubackendpicchubackend-1] DEBUG c.t.inject.app.internal.FlagsModule - Binding flag: log.async.maxsize = 4096
04:44:55.134 [finatra/embedded/picchubackendpicchubackend-1] DEBUG c.t.inject.app.internal.FlagsModule - Binding flag: https.name = https
04:44:55.137 [finatra/embedded/picchubackendpicchubackend-1] DEBUG c.t.inject.app.internal.FlagsModule - Binding flag: http.response.charset.enabled = true
04:44:55.161 [finatra/embedded/picchubackendpicchubackend-1] DEBUG c.t.inject.app.internal.FlagsModule - Binding flag: log.rotateCount = -1
04:44:55.163 [finatra/embedded/picchubackendpicchubackend-1] DEBUG c.t.inject.app.internal.FlagsModule - Binding flag: swagger.docs.endpoint = /docs
04:44:55.166 [finatra/embedded/picchubackendpicchubackend-1] DEBUG c.t.inject.app.internal.FlagsModule - Binding flag: doc.root =
04:44:55.168 [finatra/embedded/picchubackendpicchubackend-1] DEBUG c.t.inject.app.internal.FlagsModule - Binding flag: log.async.inferClassNames = false
04:44:55.170 [finatra/embedded/picchubackendpicchubackend-1] DEBUG c.t.inject.app.internal.FlagsModule - Binding flag: http.announce =
04:44:55.171 [finatra/embedded/picchubackendpicchubackend-1] DEBUG c.t.inject.app.internal.FlagsModule - Binding flag: log.append = true
04:44:55.174 [finatra/embedded/picchubackendpicchubackend-1] DEBUG c.t.inject.app.internal.FlagsModule - Binding flag: admin.port = 127.0.0.1/127.0.0.1:0
Fatal exception in server startup.
Waiting for warmup phases to complete...

Embedded server com.picchu.picchubackend-Picchubackend failed to startup: java.lang.NoClassDefFoundError: Ljavax/activation/MimetypesFileTypeMap;


===========================================================================
Closing EmbeddedHttpServer: com.picchu.picchubackend-Picchubackend
===========================================================================
Closing underlying TwitterServer: com.picchu.picchubackend-Picchubackend
Shutting down Future Pool: finatra/embedded/picchubackendpicchubackend
[info] StartupTest:
[info] com.picchu.picchubackend.StartupTest *** ABORTED ***
[info]   java.lang.Exception: java.lang.NoClassDefFoundError: Ljavax/activation/MimetypesFileTypeMap;
[info]   at com.twitter.inject.server.EmbeddedTwitterServer.$anonfun$runNonExitingMain$1(EmbeddedTwitterServer.scala:434)
[info]   at scala.runtime.java8.JFunction0$mcV$sp.apply(JFunction0$mcV$sp.java:12)
[info]   at com.twitter.util.Try$.apply(Try.scala:26)
[info]   at com.twitter.util.ExecutorServiceFuturePool$$anon$4.run(FuturePool.scala:140)
[info]   at java.base/java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:515)
[info]   at java.base/java.util.concurrent.FutureTask.run(FutureTask.java:264)
[info]   at java.base/java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1128)
[info]   at java.base/java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:628)
[info]   at java.base/java.lang.Thread.run(Thread.java:835)
[info]   ...
[info]   Cause: java.lang.NoClassDefFoundError: Ljavax/activation/MimetypesFileTypeMap;
[info]   at java.base/java.lang.Class.getDeclaredFields0(Native Method)
[info]   at java.base/java.lang.Class.privateGetDeclaredFields(Class.java:3067)
[info]   at java.base/java.lang.Class.getDeclaredFields(Class.java:2254)
[info]   at com.google.inject.spi.InjectionPoint.getDeclaredFields(InjectionPoint.java:760)
[info]   at com.google.inject.spi.InjectionPoint.getInjectionPoints(InjectionPoint.java:670)
[info]   at com.google.inject.spi.InjectionPoint.forInstanceMethodsAndFields(InjectionPoint.java:378)
[info]   at com.google.inject.internal.ConstructorBindingImpl.getInternalDependencies(ConstructorBindingImpl.java:182)
[info]   at com.google.inject.internal.InjectorImpl.getInternalDependencies(InjectorImpl.java:661)
[info]   at com.google.inject.internal.InjectorImpl.cleanup(InjectorImpl.java:617)
[info]   at com.google.inject.internal.InjectorImpl.initializeJitBinding(InjectorImpl.java:603)
[info]   ...
[info]   Cause: java.lang.ClassNotFoundException: javax.activation.MimetypesFileTypeMap
[info]   at java.base/java.net.URLClassLoader.findClass(URLClassLoader.java:436)
[info]   at java.base/java.lang.ClassLoader.loadClass(ClassLoader.java:588)
[info]   at java.base/java.lang.ClassLoader.loadClass(ClassLoader.java:521)
[info]   at java.base/java.lang.Class.getDeclaredFields0(Native Method)
[info]   at java.base/java.lang.Class.privateGetDeclaredFields(Class.java:3067)
[info]   at java.base/java.lang.Class.getDeclaredFields(Class.java:2254)
[info]   at com.google.inject.spi.InjectionPoint.getDeclaredFields(InjectionPoint.java:760)
[info]   at com.google.inject.spi.InjectionPoint.getInjectionPoints(InjectionPoint.java:670)
[info]   at com.google.inject.spi.InjectionPoint.forInstanceMethodsAndFields(InjectionPoint.java:378)
[info]   at com.google.inject.internal.ConstructorBindingImpl.getInternalDependencies(ConstructorBindingImpl.java:182)
[info]   ...
04:44:55.549 [pool-65-thread-6] DEBUG c.t.inject.app.internal.FlagsModule - Binding flag: help = false
04:44:55.863 [pool-65-thread-6] DEBUG org.eclipse.jetty.util.log - Logging to Logger[org.eclipse.jetty.util.log] via org.eclipse.jetty.util.log.Slf4jLog
04:44:55.866 [pool-65-thread-6] INFO  org.eclipse.jetty.util.log - Logging initialized @1368487ms
04:44:55.878 [pool-65-thread-6] DEBUG o.e.j.u.component.ContainerLifeCycle - org.eclipse.jetty.server.Server@528e7ed added {qtp1786190489{STOPPED,8<=0<=10,i=0,q=0},AUTO}
04:44:55.893 [pool-65-thread-6] DEBUG o.e.j.u.component.ContainerLifeCycle - HttpConnectionFactory@1acac75a{HTTP/1.1} added {HttpConfiguration@27d8d3b7{32768/8192,8192/8192,https://:0,[]},POJO}
04:44:55.906 [pool-65-thread-6] DEBUG o.e.j.u.component.ContainerLifeCycle - NetworkTrafficServerConnector@54e07668{null}{0.0.0.0:0} added {org.eclipse.jetty.server.Server@528e7ed,UNMANAGED}
04:44:55.906 [pool-65-thread-6] DEBUG o.e.j.u.component.ContainerLifeCycle - NetworkTrafficServerConnector@54e07668{null}{0.0.0.0:0} added {qtp1786190489{STOPPED,8<=0<=10,i=0,q=0},AUTO}
04:44:55.906 [pool-65-thread-6] DEBUG o.e.j.u.component.ContainerLifeCycle - NetworkTrafficServerConnector@54e07668{null}{0.0.0.0:0} added {org.eclipse.jetty.util.thread.ScheduledExecutorScheduler@385daf9,AUTO}
04:44:55.907 [pool-65-thread-6] DEBUG o.e.j.u.component.ContainerLifeCycle - NetworkTrafficServerConnector@54e07668{null}{0.0.0.0:0} added {org.eclipse.jetty.io.ArrayByteBufferPool@63b3ab68,POJO}
04:44:55.907 [pool-65-thread-6] DEBUG o.e.j.u.component.ContainerLifeCycle - NetworkTrafficServerConnector@54e07668{null}{0.0.0.0:0} added {HttpConnectionFactory@1acac75a{HTTP/1.1},AUTO}
04:44:55.909 [pool-65-thread-6] DEBUG o.e.j.u.component.ContainerLifeCycle - NetworkTrafficServerConnector@54e07668{HTTP/1.1}{0.0.0.0:0} added {org.eclipse.jetty.server.ServerConnector$ServerConnectorManager@ca533b5,MANAGED}
04:44:55.910 [pool-65-thread-6] DEBUG o.e.j.u.component.ContainerLifeCycle - org.eclipse.jetty.server.Server@528e7ed added {NetworkTrafficServerConnector@54e07668{HTTP/1.1}{0.0.0.0:27554},AUTO}
04:44:55.930 [pool-65-thread-6] DEBUG o.e.j.u.component.ContainerLifeCycle - org.eclipse.jetty.server.Server@528e7ed added {o.e.j.s.ServletContextHandler@145e2e3d{/__admin,null,null},AUTO}
04:44:55.936 [pool-65-thread-6] DEBUG o.e.j.u.component.ContainerLifeCycle - o.e.j.s.ServletContextHandler@145e2e3d{/__admin,null,null} added {org.eclipse.jetty.servlet.ServletHandler@17d73d4a,AUTO}
04:44:55.945 [pool-65-thread-6] DEBUG o.e.j.u.component.ContainerLifeCycle - org.eclipse.jetty.servlet.ServletHandler@17d73d4a added {org.eclipse.jetty.servlet.DefaultServlet-1d17f10d@e397aa57==org.eclipse.jetty.servlet.DefaultServlet,-1,false,AUTO}
04:44:55.947 [pool-65-thread-6] DEBUG o.e.j.u.component.ContainerLifeCycle - org.eclipse.jetty.servlet.ServletHandler@17d73d4a added {[/swagger-ui/*]=>org.eclipse.jetty.servlet.DefaultServlet-1d17f10d,POJO}
04:44:55.947 [pool-65-thread-6] DEBUG o.e.j.u.component.ContainerLifeCycle - org.eclipse.jetty.servlet.ServletHandler@17d73d4a added {org.eclipse.jetty.servlet.DefaultServlet-692bde1f@c643ca8==org.eclipse.jetty.servlet.DefaultServlet,-1,false,AUTO}
04:44:55.948 [pool-65-thread-6] DEBUG o.e.j.u.component.ContainerLifeCycle - org.eclipse.jetty.servlet.ServletHandler@17d73d4a added {[/recorder/*]=>org.eclipse.jetty.servlet.DefaultServlet-692bde1f,POJO}
04:44:55.949 [pool-65-thread-6] DEBUG o.e.j.u.component.ContainerLifeCycle - org.eclipse.jetty.servlet.ServletHandler@17d73d4a added {com.github.tomakehurst.wiremock.servlet.WireMockHandlerDispatchingServlet-6d7b25c7@552fa97e==com.github.tomakehurst.wiremock.servlet.WireMockHandlerDispatchingServlet,-1,false,AUTO}
04:44:55.950 [pool-65-thread-6] DEBUG o.e.j.u.component.ContainerLifeCycle - org.eclipse.jetty.servlet.ServletHandler@17d73d4a added {[/]=>com.github.tomakehurst.wiremock.servlet.WireMockHandlerDispatchingServlet-6d7b25c7,POJO}
04:44:55.955 [pool-65-thread-6] DEBUG o.e.j.u.component.ContainerLifeCycle - org.eclipse.jetty.servlet.ServletHandler@17d73d4a added {org.eclipse.jetty.servlets.CrossOriginFilter-4d4e817b,AUTO}
04:44:55.958 [pool-65-thread-6] DEBUG o.e.j.u.component.ContainerLifeCycle - org.eclipse.jetty.servlet.ServletHandler@17d73d4a added {[/*]/[]==1=>org.eclipse.jetty.servlets.CrossOriginFilter-4d4e817b,POJO}
04:44:55.960 [pool-65-thread-6] DEBUG o.e.j.u.component.ContainerLifeCycle - org.eclipse.jetty.server.Server@528e7ed added {o.e.j.s.ServletContextHandler@5853f787{/,null,null},AUTO}
04:44:55.961 [pool-65-thread-6] DEBUG o.e.j.u.component.ContainerLifeCycle - o.e.j.s.ServletContextHandler@5853f787{/,null,null} added {org.eclipse.jetty.servlet.ServletHandler@5f27e6ac,AUTO}
04:44:55.972 [pool-65-thread-6] DEBUG o.e.j.u.component.ContainerLifeCycle - org.eclipse.jetty.servlet.ServletHandler@5f27e6ac added {org.eclipse.jetty.servlet.DefaultServlet-767e727a@de3005f1==org.eclipse.jetty.servlet.DefaultServlet,-1,false,AUTO}
04:44:55.972 [pool-65-thread-6] DEBUG o.e.j.u.component.ContainerLifeCycle - org.eclipse.jetty.servlet.ServletHandler@5f27e6ac added {[/__files/*]=>org.eclipse.jetty.servlet.DefaultServlet-767e727a,POJO}
04:44:55.975 [pool-65-thread-6] DEBUG o.e.j.u.component.ContainerLifeCycle - org.eclipse.jetty.servlet.ServletHandler@5f27e6ac added {com.github.tomakehurst.wiremock.servlet.WireMockHandlerDispatchingServlet-64cf133c@b551a521==com.github.tomakehurst.wiremock.servlet.WireMockHandlerDispatchingServlet,-1,false,AUTO}
04:44:55.976 [pool-65-thread-6] DEBUG o.e.j.u.component.ContainerLifeCycle - org.eclipse.jetty.servlet.ServletHandler@5f27e6ac added {[/]=>com.github.tomakehurst.wiremock.servlet.WireMockHandlerDispatchingServlet-64cf133c,POJO}
04:44:55.990 [pool-65-thread-6] DEBUG o.e.j.u.component.ContainerLifeCycle - o.e.j.s.ServletContextHandler@5853f787{/,null,null} added {com.github.tomakehurst.wiremock.jetty9.NotFoundHandler@6b773cc1,AUTO}
04:44:55.991 [pool-65-thread-6] DEBUG o.e.j.u.component.ContainerLifeCycle - org.eclipse.jetty.servlet.ServletHandler@5f27e6ac added {com.github.tomakehurst.wiremock.servlet.ContentTypeSettingFilter-2cfa0c0c,AUTO}
04:44:55.992 [pool-65-thread-6] DEBUG o.e.j.u.component.ContainerLifeCycle - org.eclipse.jetty.servlet.ServletHandler@5f27e6ac added {[/__files/*]/[]==2=>com.github.tomakehurst.wiremock.servlet.ContentTypeSettingFilter-2cfa0c0c,POJO}
04:44:55.993 [pool-65-thread-6] DEBUG o.e.j.u.component.ContainerLifeCycle - org.eclipse.jetty.servlet.ServletHandler@5f27e6ac added {com.github.tomakehurst.wiremock.servlet.TrailingSlashFilter-564a2b3f,AUTO}
04:44:55.994 [pool-65-thread-6] DEBUG o.e.j.u.component.ContainerLifeCycle - org.eclipse.jetty.servlet.ServletHandler@5f27e6ac added {[/__files/*]/[]==31=>com.github.tomakehurst.wiremock.servlet.TrailingSlashFilter-564a2b3f,POJO}
04:44:55.999 [pool-65-thread-6] DEBUG o.e.j.u.component.ContainerLifeCycle - org.eclipse.jetty.server.handler.HandlerCollection@46fa67b8[o.e.j.s.ServletContextHandler@145e2e3d{/__admin,null,null}] added {o.e.j.s.ServletContextHandler@145e2e3d{/__admin,null,null},AUTO}
04:44:56.011 [pool-65-thread-6] DEBUG o.e.jetty.servlets.gzip.GzipHandler - org.eclipse.jetty.servlets.gzip.GzipHandler@5fa2e89b mime types IncludeExclude@6c58064f{i=[],ip=org.eclipse.jetty.util.IncludeExcludeSet$SetContainsPredicate@54defdc0,e=[image/ief, image/vnd.wap.wbmp, image/jpeg, application/bzip2, image/x-portable-graymap, image/gif, image/x-icon, audio/midi, video/x-msvideo, image/x-xbitmap, application/x-rar-compressed, image/x-portable-bitmap, image/x-rgb, image/x-cmu-raster, application/gzip, audio/x-wav, audio/basic, audio/x-pn-realaudio, application/compress, audio/x-aiff, video/x.ms.asx, video/x.ms.asf, image/png, video/vnd.rn-realvideo, image/x-xwindowdump, video/x-sgi-movie, audio/mpeg, video/mpeg, image/x-portable-pixmap, image/tiff, image/x-portable-anymap, image/x-xpixmap, application/zip, video/quicktime],ep=org.eclipse.jetty.util.IncludeExcludeSet$SetContainsPredicate@3657526d}
04:44:56.026 [pool-65-thread-6] DEBUG o.e.j.u.component.ContainerLifeCycle - org.eclipse.jetty.servlets.gzip.GzipHandler@5fa2e89b added {o.e.j.s.ServletContextHandler@5853f787{/,null,null},AUTO}
04:44:56.026 [pool-65-thread-6] DEBUG o.e.j.u.component.ContainerLifeCycle - org.eclipse.jetty.server.handler.HandlerCollection@46fa67b8[o.e.j.s.ServletContextHandler@145e2e3d{/__admin,null,null}, org.eclipse.jetty.servlets.gzip.GzipHandler@5fa2e89b] added {org.eclipse.jetty.servlets.gzip.GzipHandler@5fa2e89b,AUTO}
04:44:56.026 [pool-65-thread-6] DEBUG o.e.j.u.component.ContainerLifeCycle - org.eclipse.jetty.server.Server@528e7ed added {org.eclipse.jetty.server.handler.HandlerCollection@46fa67b8[o.e.j.s.ServletContextHandler@145e2e3d{/__admin,null,null}, org.eclipse.jetty.servlets.gzip.GzipHandler@5fa2e89b],AUTO}
04:44:57.697 [pool-65-thread-6] DEBUG d.f.e.process.runtime.ProcessControl - Detected pid: 20092
[mongod output]note: noprealloc may hurt performance in many applications
[mongod output] 2019-09-07T12:44:58.435+0800 I CONTROL  [initandlisten] MongoDB starting : pid=20092 port=27020 dbpath=C:\Users\Rocky\AppData\Local\Temp\embedmongo-db-9a8c8f3c-1b34-4665-ad9c-56e197eb2b27 64-bit host=DESKTOP-33SJOUM
[mongod output] 2019-09-07T12:44:58.437+0800 I CONTROL  [initandlisten] targetMinOS: Windows Server 2003 SP2
[mongod output] 2019-09-07T12:44:58.437+0800 I CONTROL  [initandlisten] db version v3.0.8
[mongod output] 2019-09-07T12:44:58.437+0800 I CONTROL  [initandlisten] git version: 83d8cc25e00e42856924d84e220fbe4a839e605d
[mongod output] 2019-09-07T12:44:58.437+0800 I CONTROL  [initandlisten] build info: windows sys.getwindowsversion(major=6, minor=1, build=7601, platform=2, service_pack='Service Pack 1') BOOST_LIB_VERSION=1_49
[mongod output] 2019-09-07T12:44:58.437+0800 I CONTROL  [initandlisten] allocator: tcmalloc
[mongod output] 2019-09-07T12:44:58.437+0800 I CONTROL  [initandlisten] options: { net: { http: { enabled: false }, port: 27020 }, security: { authorization: "disabled" }, storage: { dbPath: "C:\Users\Rocky\AppData\Local\Temp\embedmongo-db-9a8c8f3c-1b34-4665-ad9c-56e197eb2b27", journal: { enabled: false }, mmapv1: { preallocDataFiles: false, smallFiles: true }, syncPeriodSecs: 0.0 } }
[mongod output] 2019-09-07T12:44:58.438+0800 E NETWORK  [initandlisten] listen(): bind() failed errno:10048 ������?鞈���?��謍�?��??�??�?� (?謍�??���?/��璆���?/??���????for socket: 0.0.0.0:27020
0.0:27020
[mongod output] 2019-09-07T12:44:58.487+0800 I STORAGE  [DataFileSync] warning: --syncdelay 0 is not recommended and can have strange performance
[mongod output] 2019-09-07T12:44:58.717+0800 I INDEX    [initandlisten] allocating new ns file C:\Users\Rocky\AppData\Local\Temp\embedmongo-db-9a8c8f3c-1b34-4665-ad9c-56e197eb2b27\local.ns, filling with zeroes...
[mongod output] 2019-09-07T12:44:59.474+0800 I STORAGE  [FileAllocator] allocating new datafile C:\Users\Rocky\AppData\Local\Temp\embedmongo-db-9a8c8f3c-1b34-4665-ad9c-56e197eb2b27\local.0, filling with zeroes...
[mongod output] 2019-09-07T12:44:59.475+0800 I STORAGE  [FileAllocator] creating directory C:\Users\Rocky\AppData\Local\Temp\embedmongo-db-9a8c8f3c-1b34-4665-ad9c-56e197eb2b27\_tmp
[mongod output] 2019-09-07T12:44:59.524+0800 I STORAGE  [FileAllocator] done allocating datafile C:\Users\Rocky\AppData\Local\Temp\embedmongo-db-9a8c8f3c-1b34-4665-ad9c-56e197eb2b27\local.0, size: 16MB,  took 0.046 secs
[mongod output] 2019-09-07T12:44:59.568+0800 I CONTROL  [initandlisten] now exiting
[mongod output] 2019-09-07T12:44:59.568+0800 I NETWORK  [initandlisten] shutdown: going to close listening sockets...
[mongod output] 2019-09-07T12:44:59.568+0800 I NETWORK  [initandlisten] shutdown: going to flush diaglog...
[mongod output] 2019-09-07T12:44:59.569+0800 I NETWORK  [initandlisten] shutdown: going to close sockets...
[mongod output]
04:44:59.597 [pool-65-thread-6] ERROR d.f.e.p.runtime.AbstractProcess - failed to call onAfterProcessStart()
java.io.IOException: Could not start process: failed errno:10048 ������?鞈���?��謍�?��??� (?謍�??���?/��璆���?�璆���?�/??���????for socket: 0.0.0.0:27020
7020

        at de.flapdoodle.embed.mongo.AbstractMongoProcess.onAfterProcessStart(AbstractMongoProcess.java:79)
        at de.flapdoodle.embed.process.runtime.AbstractProcess.<init>(AbstractProcess.java:114)
        at de.flapdoodle.embed.mongo.AbstractMongoProcess.<init>(AbstractMongoProcess.java:53)
        at de.flapdoodle.embed.mongo.MongodProcess.<init>(MongodProcess.java:50)
        at de.flapdoodle.embed.mongo.MongodExecutable.start(MongodExecutable.java:44)
        at de.flapdoodle.embed.mongo.MongodExecutable.start(MongodExecutable.java:34)
        at de.flapdoodle.embed.process.runtime.Executable.start(Executable.java:101)
        at com.picchu.picchubackend.MongoTestKit.startMongo(MongoTestKit.scala:56)
        at com.picchu.picchubackend.MongoTestKit.startMongo$(MongoTestKit.scala:51)
        at com.picchu.picchubackend.controllers.AccountControllerFeatureTest.startMongo(AccountControllerFeatureTest.scala:13)
        at com.picchu.picchubackend.controllers.FeatureTestBase.$init$(FeatureTestBase.scala:26)
        at com.picchu.picchubackend.controllers.AccountControllerFeatureTest.<init>(AccountControllerFeatureTest.scala:13)
        at java.base/jdk.internal.reflect.NativeConstructorAccessorImpl.newInstance0(Native Method)
        at java.base/jdk.internal.reflect.NativeConstructorAccessorImpl.newInstance(NativeConstructorAccessorImpl.java:62)
        at java.base/jdk.internal.reflect.DelegatingConstructorAccessorImpl.newInstance(DelegatingConstructorAccessorImpl.java:45)
        at java.base/java.lang.reflect.Constructor.newInstanceWithCaller(Constructor.java:500)
        at java.base/java.lang.reflect.ReflectAccess.newInstance(ReflectAccess.java:166)
        at java.base/jdk.internal.reflect.ReflectionFactory.newInstance(ReflectionFactory.java:404)
        at java.base/java.lang.Class.newInstance(Class.java:590)
        at org.scalatest.tools.Framework$ScalaTestTask.execute(Framework.scala:435)
        at sbt.TestRunner.runTest$1(TestFramework.scala:113)
        at sbt.TestRunner.run(TestFramework.scala:124)
        at sbt.TestFramework$$anon$2$$anonfun$$lessinit$greater$1.$anonfun$apply$1(TestFramework.scala:282)
        at sbt.TestFramework$.sbt$TestFramework$$withContextLoader(TestFramework.scala:246)
        at sbt.TestFramework$$anon$2$$anonfun$$lessinit$greater$1.apply(TestFramework.scala:282)
        at sbt.TestFramework$$anon$2$$anonfun$$lessinit$greater$1.apply(TestFramework.scala:282)
        at sbt.TestFunction.apply(TestFramework.scala:294)
        at sbt.Tests$.processRunnable$1(Tests.scala:347)
        at sbt.Tests$.$anonfun$makeSerial$1(Tests.scala:353)
        at sbt.std.Transform$$anon$3.$anonfun$apply$2(System.scala:46)
        at sbt.std.Transform$$anon$4.work(System.scala:67)
        at sbt.Execute.$anonfun$submit$2(Execute.scala:269)
        at sbt.internal.util.ErrorHandling$.wideConvert(ErrorHandling.scala:16)
        at sbt.Execute.work(Execute.scala:278)
        at sbt.Execute.$anonfun$submit$1(Execute.scala:269)
        at sbt.ConcurrentRestrictions$$anon$4.$anonfun$submitValid$1(ConcurrentRestrictions.scala:178)
        at sbt.CompletionService$$anon$2.call(CompletionService.scala:37)
        at java.base/java.util.concurrent.FutureTask.run(FutureTask.java:264)
        at java.base/java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:515)
        at java.base/java.util.concurrent.FutureTask.run(FutureTask.java:264)
        at java.base/java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1128)
        at java.base/java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:628)
        at java.base/java.lang.Thread.run(Thread.java:835)
2019-09-07T12:44:59.569+0800 I STORAGE  [initandlisten] shutdown: waiting for fs preallocator...
[mongod output] 04:44:59.627 [pool-65-thread-6] INFO  d.f.e.p.runtime.AbstractProcess - construct de.flapdoodle.embed.mongo.config.MongodConfigBuilder$ImmutableMongodConfig@691b0d66
2019-09-07T12:44:59.569+0800 I STORAGE  [initandlisten] shutdown: closing all files...
[mongod output] 04:44:59.628 [pool-65-thread-6] DEBUG d.f.embed.mongo.AbstractMongoProcess - try to stop mongod
2019-09-07T12:44:59.573+0800 I STORAGE  [initandlisten] closeAllFiles() finished
[mongod output] 2019-09-07T12:44:59.573+0800 I STORAGE  [initandlisten] shutdown: removing fs lock...
[mongod output] 2019-09-07T12:44:59.574+0800 I CONTROL  [initandlisten] dbexit:  rc: 48
[mongod output] 2019-09-07T12:44:59.643+0800 I NETWORK  [initandlisten] connection accepted from 127.0.0.1:58692 #1 (1 connection now open)
[mongod output] 2019-09-07T12:44:59.690+0800 I COMMAND  [conn1] terminating, shutdown command received
[mongod output] 2019-09-07T12:44:59.706+0800 I CONTROL  [conn1] now exiting
[mongod output] 2019-09-07T12:44:59.706+0800 I NETWORK  [conn1] shutdown: going to close listening sockets...
[mongod output] 2019-09-07T12:44:59.706+0800 I NETWORK  [conn1] closing listening socket: 636
[mongod output] 2019-09-07T12:44:59.707+0800 I NETWORK  [conn1] shutdown: going to flush diaglog...
[mongod output] 2019-09-07T12:44:59.707+0800 I NETWORK  [conn1] shutdown: going to close sockets...
[mongod output] 2019-09-07T12:44:59.707+0800 I STORAGE  [conn1] shutdown: waiting for fs preallocator...
[mongod output] 2019-09-07T12:44:59.707+0800 I STORAGE  [conn1] shutdown: closing all files...
[mongod output] 2019-09-07T12:44:59.710+0800 I STORAGE  [conn1] closeAllFiles() finished
[mongod output] 2019-09-07T12:44:59.710+0800 I STORAGE  [conn1] shutdown: removing fs lock...
[mongod output] 2019-09-07T12:44:59.710+0800 I CONTROL  [conn1] dbexit:  rc: 0
[mongod output]
04:44:59.824 [pool-65-thread-6] DEBUG d.f.embed.process.io.file.Files - could delete C:\Users\Rocky\AppData\Local\Temp\embedmongo-db-9a8c8f3c-1b34-4665-ad9c-56e197eb2b27
04:44:59.824 [pool-65-thread-6] DEBUG d.f.embed.process.io.file.Files - could delete C:\Users\Rocky\AppData\Local\Temp\extract-fa34157a-ba93-47c9-8b0c-0fc9ee77cfbcextractmongod.pid
[info] AccountControllerFeatureTest:
[info] com.picchu.picchubackend.controllers.AccountControllerFeatureTest *** ABORTED ***
[info]   java.io.IOException: Could not start process: failed errno:10048 ������?鞈���?��謍�?��??� (?謍�??���?/�?���?/���璆���?/??���????for socket: 0.0.0.0:27020
27020
[info]   at de.flapdoodle.embed.mongo.AbstractMongoProcess.onAfterProcessStart(AbstractMongoProcess.java:79)
[info]   at de.flapdoodle.embed.process.runtime.AbstractProcess.<init>(AbstractProcess.java:114)
[info]   at de.flapdoodle.embed.mongo.AbstractMongoProcess.<init>(AbstractMongoProcess.java:53)
[info]   at de.flapdoodle.embed.mongo.MongodProcess.<init>(MongodProcess.java:50)
[info]   at de.flapdoodle.embed.mongo.MongodExecutable.start(MongodExecutable.java:44)
[info]   at de.flapdoodle.embed.mongo.MongodExecutable.start(MongodExecutable.java:34)
[info]   at de.flapdoodle.embed.process.runtime.Executable.start(Executable.java:101)
[info]   at com.picchu.picchubackend.MongoTestKit.startMongo(MongoTestKit.scala:56)
[info]   at com.picchu.picchubackend.MongoTestKit.startMongo$(MongoTestKit.scala:51)
[info]   at com.picchu.picchubackend.controllers.AccountControllerFeatureTest.startMongo(AccountControllerFeatureTest.scala:13)
[info]   ...

Starting com.picchu.picchubackend-Picchubackend with args: -http.port=127.0.0.1:0 -admin.port=127.0.0.1:0 -service.version=0.9.9
Waiting for warmup phases to complete...
04:44:59.900 [finatra/embedded/picchubackendpicchubackend-1] WARN  com.twitter.app.App$ - Multiple com.twitter.app.App main methods called. com.picchu.picchubackend-Picchubackend, then com.picchu.picchubackend-Picchubackend
04:44:59.900 [finatra/embedded/picchubackendpicchubackend-1] INFO  com.picchu.picchubackend.Server - Process started
04:44:59.904 [finatra/embedded/picchubackendpicchubackend-1] DEBUG com.picchu.picchubackend.Server - AdminHttpServer Muxer endpoints:
        /admin/logging => com.twitter.server.AdminHttpServer$Route$IsolateFilter.andThen(com.twitter.server.handler.logback.classic.LoggingHandler)
        /admin/ping => com.twitter.server.handler.ReplyHandler
         => com.twitter.server.AdminHttpServer$Route$IsolateFilter.andThen(com.twitter.server.handler.AdminRedirectHandler)
        /admin => com.twitter.server.AdminHttpServer$Route$IsolateFilter.andThen(com.twitter.server.handler.SummaryHandler)
        /admin/ => com.twitter.server.AdminHttpServer$Route$IsolateFilter.andThen(com.twitter.server.view.NotFoundView.andThen(com.twitter.server.handler.AdminRedirectHandler))
        /admin/server_info => com.twitter.server.AdminHttpServer$Route$IsolateFilter.andThen(com.twitter.server.view.TextBlockView.andThen(com.twitter.server.handler.ServerInfoHandler))
        /admin/contention => com.twitter.server.AdminHttpServer$Route$IsolateFilter.andThen(com.twitter.server.view.TextBlockView.andThen(com.twitter.server.handler.ContentionHandler))
        /admin/lint => com.twitter.server.AdminHttpServer$Route$IsolateFilter.andThen(com.twitter.server.handler.LintHandler)
        /admin/lint.json => com.twitter.server.AdminHttpServer$Route$IsolateFilter.andThen(com.twitter.server.handler.LintHandler)
        /admin/failedlint => com.twitter.server.AdminHttpServer$Route$IsolateFilter.andThen(com.twitter.server.handler.FailedLintRuleHandler)
        /admin/threads => com.twitter.server.AdminHttpServer$Route$IsolateFilter.andThen(com.twitter.server.handler.ThreadsHandler)
        /admin/threads.json => com.twitter.server.AdminHttpServer$Route$IsolateFilter.andThen(com.twitter.server.handler.ThreadsHandler)
        /admin/announcer => com.twitter.server.AdminHttpServer$Route$IsolateFilter.andThen(com.twitter.server.view.TextBlockView.andThen(com.twitter.server.handler.AnnouncerHandler))
        /admin/dtab => com.twitter.server.AdminHttpServer$Route$IsolateFilter.andThen(com.twitter.server.view.TextBlockView.andThen(com.twitter.server.handler.DtabHandler))
        /admin/pprof/heap => com.twitter.server.AdminHttpServer$Route$IsolateFilter.andThen(com.twitter.server.handler.HeapResourceHandler)
        /admin/pprof/profile => com.twitter.server.AdminHttpServer$Route$IsolateFilter.andThen(com.twitter.server.handler.ProfileResourceHandler)
        /admin/pprof/contention => com.twitter.server.AdminHttpServer$Route$IsolateFilter.andThen(com.twitter.server.handler.ProfileResourceHandler)
        /admin/shutdown => com.twitter.server.AdminHttpServer$Route$IsolateFilter.andThen(com.twitter.server.handler.ShutdownHandler)
        /admin/tracing => com.twitter.server.AdminHttpServer$Route$IsolateFilter.andThen(com.twitter.server.handler.TracingHandler)
        /admin/metrics => com.twitter.server.AdminHttpServer$Route$IsolateFilter.andThen(com.twitter.server.handler.MetricQueryHandler)
        /admin/clients/ => com.twitter.server.AdminHttpServer$Route$IsolateFilter.andThen(com.twitter.server.handler.ClientRegistryHandler)
        /admin/balancers.json => com.twitter.server.AdminHttpServer$Route$IsolateFilter.andThen(com.twitter.server.handler.LoadBalancersHandler)
        /admin/servers/ => com.twitter.server.AdminHttpServer$Route$IsolateFilter.andThen(com.twitter.server.handler.ServerRegistryHandler)
        /admin/files/ => com.twitter.server.AdminHttpServer$Route$IsolateFilter.andThen(com.twitter.server.handler.ResourceHandler)
        /admin/registry.json => com.twitter.server.AdminHttpServer$Route$IsolateFilter.andThen(com.twitter.server.handler.RegistryHandler)
        /admin/toggles => com.twitter.server.AdminHttpServer$Route$IsolateFilter.andThen(com.twitter.server.handler.ToggleHandler)
        /admin/toggles/ => com.twitter.server.AdminHttpServer$Route$IsolateFilter.andThen(com.twitter.server.handler.ToggleHandler)
        /admin/tunables => com.twitter.server.AdminHttpServer$Route$IsolateFilter.andThen(com.twitter.server.handler.TunableHandler)
        /admin/tunables/ => com.twitter.server.AdminHttpServer$Route$IsolateFilter.andThen(com.twitter.server.handler.TunableHandler)
        /favicon.ico => com.twitter.server.AdminHttpServer$Route$IsolateFilter.andThen(com.twitter.server.handler.ResourceHandler)
        /admin/histograms => com.twitter.server.handler.HistogramQueryHandler
        /admin/histograms.json => com.twitter.server.handler.HistogramQueryHandler
04:44:59.912 [finatra/embedded/picchubackendpicchubackend-1] INFO  com.picchu.picchubackend.Server - Serving admin http on 127.0.0.1/127.0.0.1:0
04:44:59.920 [finatra/embedded/picchubackendpicchubackend-1] WARN  com.twitter.util.registry.Library$ - Tried to register a second library named "finatra"
04:44:59.932 [finatra/embedded/picchubackendpicchubackend-1] DEBUG c.t.inject.app.internal.FlagsModule - Binding flag: shutdown.time = 1.minutes
04:44:59.936 [finatra/embedded/picchubackendpicchubackend-1] DEBUG c.t.inject.app.internal.FlagsModule - Binding flag: service.version = 0.9.9
04:44:59.936 [finatra/embedded/picchubackendpicchubackend-1] DEBUG c.t.inject.app.internal.FlagsModule - Binding flag: https.announce =
04:44:59.948 [Finalizer] DEBUG o.a.h.i.c.PoolingHttpClientConnectionManager - Connection manager is shutting down
04:44:59.948 [Finalizer] DEBUG o.a.h.i.c.PoolingHttpClientConnectionManager - Connection manager shut down
04:44:59.948 [finatra/embedded/picchubackendpicchubackend-1] DEBUG c.t.inject.app.internal.FlagsModule - Binding flag: log.level = INFO
04:44:59.948 [finatra/embedded/picchubackendpicchubackend-1] DEBUG c.t.inject.app.internal.FlagsModule - Binding flag: local.doc.root =
04:44:59.948 [finatra/embedded/picchubackendpicchubackend-1] DEBUG c.t.inject.app.internal.FlagsModule - Binding flag: https.port =
04:44:59.952 [finatra/embedded/picchubackendpicchubackend-1] DEBUG c.t.inject.app.internal.FlagsModule - Binding flag: mustache.templates.dir = templates
04:44:59.952 [finatra/embedded/picchubackendpicchubackend-1] DEBUG c.t.inject.app.internal.FlagsModule - Binding flag: log.async = true
04:44:59.952 [finatra/embedded/picchubackendpicchubackend-1] DEBUG c.t.inject.app.internal.FlagsModule - Binding flag: http.name = http
04:44:59.952 [finatra/embedded/picchubackendpicchubackend-1] DEBUG c.t.inject.app.internal.FlagsModule - Binding flag: maxRequestSize = 5242880.bytes
04:44:59.952 [finatra/embedded/picchubackendpicchubackend-1] DEBUG c.t.inject.app.internal.FlagsModule - Binding flag: log.rollPolicy = Never
04:44:59.956 [finatra/embedded/picchubackendpicchubackend-1] DEBUG c.t.inject.app.internal.FlagsModule - Binding flag: help = false
04:44:59.956 [finatra/embedded/picchubackendpicchubackend-1] DEBUG c.t.inject.app.internal.FlagsModule - Binding flag: log.output = /dev/stderr
04:44:59.956 [finatra/embedded/picchubackendpicchubackend-1] DEBUG c.t.inject.app.internal.FlagsModule - Binding flag: http.port = 127.0.0.1:0
04:44:59.956 [finatra/embedded/picchubackendpicchubackend-1] DEBUG c.t.inject.app.internal.FlagsModule - Binding flag: log.async.maxsize = 4096
04:44:59.956 [finatra/embedded/picchubackendpicchubackend-1] DEBUG c.t.inject.app.internal.FlagsModule - Binding flag: https.name = https
04:44:59.956 [finatra/embedded/picchubackendpicchubackend-1] DEBUG c.t.inject.app.internal.FlagsModule - Binding flag: http.response.charset.enabled = true
04:44:59.960 [finatra/embedded/picchubackendpicchubackend-1] DEBUG c.t.inject.app.internal.FlagsModule - Binding flag: log.rotateCount = -1
04:44:59.960 [finatra/embedded/picchubackendpicchubackend-1] DEBUG c.t.inject.app.internal.FlagsModule - Binding flag: swagger.docs.endpoint = /docs
04:44:59.960 [finatra/embedded/picchubackendpicchubackend-1] DEBUG c.t.inject.app.internal.FlagsModule - Binding flag: doc.root =
04:44:59.960 [finatra/embedded/picchubackendpicchubackend-1] DEBUG c.t.inject.app.internal.FlagsModule - Binding flag: log.async.inferClassNames = false
04:44:59.960 [finatra/embedded/picchubackendpicchubackend-1] DEBUG c.t.inject.app.internal.FlagsModule - Binding flag: http.announce =
04:44:59.964 [finatra/embedded/picchubackendpicchubackend-1] DEBUG c.t.inject.app.internal.FlagsModule - Binding flag: log.append = true
04:44:59.964 [finatra/embedded/picchubackendpicchubackend-1] DEBUG c.t.inject.app.internal.FlagsModule - Binding flag: admin.port = 127.0.0.1/127.0.0.1:0
Fatal exception in server startup.
Waiting for warmup phases to complete...

Embedded server com.picchu.picchubackend-Picchubackend failed to startup: java.lang.NoClassDefFoundError: Ljavax/activation/MimetypesFileTypeMap;


===========================================================================
Closing EmbeddedHttpServer: com.picchu.picchubackend-Picchubackend
===========================================================================
Closing underlying TwitterServer: com.picchu.picchubackend-Picchubackend
Shutting down Future Pool: finatra/embedded/picchubackendpicchubackend
[info] MainControllerFeatureTest:
[info] com.picchu.picchubackend.controllers.MainControllerFeatureTest *** ABORTED ***
[info]   java.lang.Exception: java.lang.NoClassDefFoundError: Ljavax/activation/MimetypesFileTypeMap;
[info]   at com.twitter.inject.server.EmbeddedTwitterServer.$anonfun$runNonExitingMain$1(EmbeddedTwitterServer.scala:434)
[info]   at scala.runtime.java8.JFunction0$mcV$sp.apply(JFunction0$mcV$sp.java:12)
[info]   at com.twitter.util.Try$.apply(Try.scala:26)
[info]   at com.twitter.util.ExecutorServiceFuturePool$$anon$4.run(FuturePool.scala:140)
[info]   at java.base/java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:515)
[info]   at java.base/java.util.concurrent.FutureTask.run(FutureTask.java:264)
[info]   at java.base/java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1128)
[info]   at java.base/java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:628)
[info]   at java.base/java.lang.Thread.run(Thread.java:835)
[info]   ...
[info]   Cause: java.lang.NoClassDefFoundError: Ljavax/activation/MimetypesFileTypeMap;
[info]   at java.base/java.lang.Class.getDeclaredFields0(Native Method)
[info]   at java.base/java.lang.Class.privateGetDeclaredFields(Class.java:3067)
[info]   at java.base/java.lang.Class.getDeclaredFields(Class.java:2254)
[info]   at com.google.inject.spi.InjectionPoint.getDeclaredFields(InjectionPoint.java:760)
[info]   at com.google.inject.spi.InjectionPoint.getInjectionPoints(InjectionPoint.java:670)
[info]   at com.google.inject.spi.InjectionPoint.forInstanceMethodsAndFields(InjectionPoint.java:378)
[info]   at com.google.inject.internal.ConstructorBindingImpl.getInternalDependencies(ConstructorBindingImpl.java:182)
[info]   at com.google.inject.internal.InjectorImpl.getInternalDependencies(InjectorImpl.java:661)
[info]   at com.google.inject.internal.InjectorImpl.cleanup(InjectorImpl.java:617)
[info]   at com.google.inject.internal.InjectorImpl.initializeJitBinding(InjectorImpl.java:603)
[info]   ...
[info]   Cause: java.lang.ClassNotFoundException: javax.activation.MimetypesFileTypeMap
[info]   at java.base/java.net.URLClassLoader.findClass(URLClassLoader.java:436)
[info]   at java.base/java.lang.ClassLoader.loadClass(ClassLoader.java:588)
[info]   at java.base/java.lang.ClassLoader.loadClass(ClassLoader.java:521)
[info]   at java.base/java.lang.Class.getDeclaredFields0(Native Method)
[info]   at java.base/java.lang.Class.privateGetDeclaredFields(Class.java:3067)
[info]   at java.base/java.lang.Class.getDeclaredFields(Class.java:2254)
[info]   at com.google.inject.spi.InjectionPoint.getDeclaredFields(InjectionPoint.java:760)
[info]   at com.google.inject.spi.InjectionPoint.getInjectionPoints(InjectionPoint.java:670)
[info]   at com.google.inject.spi.InjectionPoint.forInstanceMethodsAndFields(InjectionPoint.java:378)
[info]   at com.google.inject.internal.ConstructorBindingImpl.getInternalDependencies(ConstructorBindingImpl.java:182)
[info]   ...

Starting com.picchu.picchubackend-Picchubackend with args: -http.port=127.0.0.1:0 -admin.port=127.0.0.1:0 -service.version=0.9.9
Waiting for warmup phases to complete...
04:45:01.416 [finatra/embedded/picchubackendpicchubackend-1] WARN  com.twitter.app.App$ - Multiple com.twitter.app.App main methods called. com.picchu.picchubackend-Picchubackend, then com.picchu.picchubackend-Picchubackend
04:45:01.416 [finatra/embedded/picchubackendpicchubackend-1] INFO  com.picchu.picchubackend.Server - Process started
04:45:01.420 [finatra/embedded/picchubackendpicchubackend-1] DEBUG com.picchu.picchubackend.Server - AdminHttpServer Muxer endpoints:
        /admin/logging => com.twitter.server.AdminHttpServer$Route$IsolateFilter.andThen(com.twitter.server.handler.logback.classic.LoggingHandler)
        /admin/ping => com.twitter.server.handler.ReplyHandler
         => com.twitter.server.AdminHttpServer$Route$IsolateFilter.andThen(com.twitter.server.handler.AdminRedirectHandler)
        /admin => com.twitter.server.AdminHttpServer$Route$IsolateFilter.andThen(com.twitter.server.handler.SummaryHandler)
        /admin/ => com.twitter.server.AdminHttpServer$Route$IsolateFilter.andThen(com.twitter.server.view.NotFoundView.andThen(com.twitter.server.handler.AdminRedirectHandler))
        /admin/server_info => com.twitter.server.AdminHttpServer$Route$IsolateFilter.andThen(com.twitter.server.view.TextBlockView.andThen(com.twitter.server.handler.ServerInfoHandler))
        /admin/contention => com.twitter.server.AdminHttpServer$Route$IsolateFilter.andThen(com.twitter.server.view.TextBlockView.andThen(com.twitter.server.handler.ContentionHandler))
        /admin/lint => com.twitter.server.AdminHttpServer$Route$IsolateFilter.andThen(com.twitter.server.handler.LintHandler)
        /admin/lint.json => com.twitter.server.AdminHttpServer$Route$IsolateFilter.andThen(com.twitter.server.handler.LintHandler)
        /admin/failedlint => com.twitter.server.AdminHttpServer$Route$IsolateFilter.andThen(com.twitter.server.handler.FailedLintRuleHandler)
        /admin/threads => com.twitter.server.AdminHttpServer$Route$IsolateFilter.andThen(com.twitter.server.handler.ThreadsHandler)
        /admin/threads.json => com.twitter.server.AdminHttpServer$Route$IsolateFilter.andThen(com.twitter.server.handler.ThreadsHandler)
        /admin/announcer => com.twitter.server.AdminHttpServer$Route$IsolateFilter.andThen(com.twitter.server.view.TextBlockView.andThen(com.twitter.server.handler.AnnouncerHandler))
        /admin/dtab => com.twitter.server.AdminHttpServer$Route$IsolateFilter.andThen(com.twitter.server.view.TextBlockView.andThen(com.twitter.server.handler.DtabHandler))
        /admin/pprof/heap => com.twitter.server.AdminHttpServer$Route$IsolateFilter.andThen(com.twitter.server.handler.HeapResourceHandler)
        /admin/pprof/profile => com.twitter.server.AdminHttpServer$Route$IsolateFilter.andThen(com.twitter.server.handler.ProfileResourceHandler)
        /admin/pprof/contention => com.twitter.server.AdminHttpServer$Route$IsolateFilter.andThen(com.twitter.server.handler.ProfileResourceHandler)
        /admin/shutdown => com.twitter.server.AdminHttpServer$Route$IsolateFilter.andThen(com.twitter.server.handler.ShutdownHandler)
        /admin/tracing => com.twitter.server.AdminHttpServer$Route$IsolateFilter.andThen(com.twitter.server.handler.TracingHandler)
        /admin/metrics => com.twitter.server.AdminHttpServer$Route$IsolateFilter.andThen(com.twitter.server.handler.MetricQueryHandler)
        /admin/clients/ => com.twitter.server.AdminHttpServer$Route$IsolateFilter.andThen(com.twitter.server.handler.ClientRegistryHandler)
        /admin/balancers.json => com.twitter.server.AdminHttpServer$Route$IsolateFilter.andThen(com.twitter.server.handler.LoadBalancersHandler)
        /admin/servers/ => com.twitter.server.AdminHttpServer$Route$IsolateFilter.andThen(com.twitter.server.handler.ServerRegistryHandler)
        /admin/files/ => com.twitter.server.AdminHttpServer$Route$IsolateFilter.andThen(com.twitter.server.handler.ResourceHandler)
        /admin/registry.json => com.twitter.server.AdminHttpServer$Route$IsolateFilter.andThen(com.twitter.server.handler.RegistryHandler)
        /admin/toggles => com.twitter.server.AdminHttpServer$Route$IsolateFilter.andThen(com.twitter.server.handler.ToggleHandler)
        /admin/toggles/ => com.twitter.server.AdminHttpServer$Route$IsolateFilter.andThen(com.twitter.server.handler.ToggleHandler)
        /admin/tunables => com.twitter.server.AdminHttpServer$Route$IsolateFilter.andThen(com.twitter.server.handler.TunableHandler)
        /admin/tunables/ => com.twitter.server.AdminHttpServer$Route$IsolateFilter.andThen(com.twitter.server.handler.TunableHandler)
        /favicon.ico => com.twitter.server.AdminHttpServer$Route$IsolateFilter.andThen(com.twitter.server.handler.ResourceHandler)
        /admin/histograms => com.twitter.server.handler.HistogramQueryHandler
        /admin/histograms.json => com.twitter.server.handler.HistogramQueryHandler
04:45:01.428 [finatra/embedded/picchubackendpicchubackend-1] INFO  com.picchu.picchubackend.Server - Serving admin http on 127.0.0.1/127.0.0.1:0
04:45:01.436 [finatra/embedded/picchubackendpicchubackend-1] WARN  com.twitter.util.registry.Library$ - Tried to register a second library named "finatra"
04:45:01.444 [finatra/embedded/picchubackendpicchubackend-1] DEBUG c.t.inject.app.internal.FlagsModule - Binding flag: shutdown.time = 1.minutes
04:45:01.448 [finatra/embedded/picchubackendpicchubackend-1] DEBUG c.t.inject.app.internal.FlagsModule - Binding flag: service.version = 0.9.9
04:45:01.452 [finatra/embedded/picchubackendpicchubackend-1] DEBUG c.t.inject.app.internal.FlagsModule - Binding flag: https.announce =
04:45:01.472 [finatra/embedded/picchubackendpicchubackend-1] DEBUG c.t.inject.app.internal.FlagsModule - Binding flag: log.level = INFO
04:45:01.472 [finatra/embedded/picchubackendpicchubackend-1] DEBUG c.t.inject.app.internal.FlagsModule - Binding flag: local.doc.root =
04:45:01.472 [finatra/embedded/picchubackendpicchubackend-1] DEBUG c.t.inject.app.internal.FlagsModule - Binding flag: https.port =
04:45:01.476 [finatra/embedded/picchubackendpicchubackend-1] DEBUG c.t.inject.app.internal.FlagsModule - Binding flag: mustache.templates.dir = templates
04:45:01.476 [finatra/embedded/picchubackendpicchubackend-1] DEBUG c.t.inject.app.internal.FlagsModule - Binding flag: log.async = true
04:45:01.476 [finatra/embedded/picchubackendpicchubackend-1] DEBUG c.t.inject.app.internal.FlagsModule - Binding flag: http.name = http
04:45:01.476 [finatra/embedded/picchubackendpicchubackend-1] DEBUG c.t.inject.app.internal.FlagsModule - Binding flag: maxRequestSize = 5242880.bytes
04:45:01.476 [finatra/embedded/picchubackendpicchubackend-1] DEBUG c.t.inject.app.internal.FlagsModule - Binding flag: log.rollPolicy = Never
04:45:01.476 [finatra/embedded/picchubackendpicchubackend-1] DEBUG c.t.inject.app.internal.FlagsModule - Binding flag: help = false
04:45:01.480 [finatra/embedded/picchubackendpicchubackend-1] DEBUG c.t.inject.app.internal.FlagsModule - Binding flag: log.output = /dev/stderr
04:45:01.480 [finatra/embedded/picchubackendpicchubackend-1] DEBUG c.t.inject.app.internal.FlagsModule - Binding flag: http.port = 127.0.0.1:0
04:45:01.480 [finatra/embedded/picchubackendpicchubackend-1] DEBUG c.t.inject.app.internal.FlagsModule - Binding flag: log.async.maxsize = 4096
04:45:01.480 [finatra/embedded/picchubackendpicchubackend-1] DEBUG c.t.inject.app.internal.FlagsModule - Binding flag: https.name = https
04:45:01.480 [finatra/embedded/picchubackendpicchubackend-1] DEBUG c.t.inject.app.internal.FlagsModule - Binding flag: http.response.charset.enabled = true
04:45:01.484 [finatra/embedded/picchubackendpicchubackend-1] DEBUG c.t.inject.app.internal.FlagsModule - Binding flag: log.rotateCount = -1
04:45:01.484 [finatra/embedded/picchubackendpicchubackend-1] DEBUG c.t.inject.app.internal.FlagsModule - Binding flag: swagger.docs.endpoint = /docs
04:45:01.484 [finatra/embedded/picchubackendpicchubackend-1] DEBUG c.t.inject.app.internal.FlagsModule - Binding flag: doc.root =
04:45:01.484 [finatra/embedded/picchubackendpicchubackend-1] DEBUG c.t.inject.app.internal.FlagsModule - Binding flag: log.async.inferClassNames = false
04:45:01.484 [finatra/embedded/picchubackendpicchubackend-1] DEBUG c.t.inject.app.internal.FlagsModule - Binding flag: http.announce =
04:45:01.484 [finatra/embedded/picchubackendpicchubackend-1] DEBUG c.t.inject.app.internal.FlagsModule - Binding flag: log.append = true
04:45:01.488 [finatra/embedded/picchubackendpicchubackend-1] DEBUG c.t.inject.app.internal.FlagsModule - Binding flag: admin.port = 127.0.0.1/127.0.0.1:0
Fatal exception in server startup.
Waiting for warmup phases to complete...

Embedded server com.picchu.picchubackend-Picchubackend failed to startup: java.lang.NoClassDefFoundError: Ljavax/activation/MimetypesFileTypeMap;


===========================================================================
Closing EmbeddedHttpServer: com.picchu.picchubackend-Picchubackend
===========================================================================
Closing underlying TwitterServer: com.picchu.picchubackend-Picchubackend
Shutting down Future Pool: finatra/embedded/picchubackendpicchubackend
[info] AdminControllerFeatureTest:
[info] com.picchu.picchubackend.controllers.AdminControllerFeatureTest *** ABORTED ***
[info]   java.lang.Exception: java.lang.NoClassDefFoundError: Ljavax/activation/MimetypesFileTypeMap;
[info]   at com.twitter.inject.server.EmbeddedTwitterServer.$anonfun$runNonExitingMain$1(EmbeddedTwitterServer.scala:434)
[info]   at scala.runtime.java8.JFunction0$mcV$sp.apply(JFunction0$mcV$sp.java:12)
[info]   at com.twitter.util.Try$.apply(Try.scala:26)
[info]   at com.twitter.util.ExecutorServiceFuturePool$$anon$4.run(FuturePool.scala:140)
[info]   at java.base/java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:515)
[info]   at java.base/java.util.concurrent.FutureTask.run(FutureTask.java:264)
[info]   at java.base/java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1128)
[info]   at java.base/java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:628)
[info]   at java.base/java.lang.Thread.run(Thread.java:835)
[info]   ...
[info]   Cause: java.lang.NoClassDefFoundError: Ljavax/activation/MimetypesFileTypeMap;
[info]   at java.base/java.lang.Class.getDeclaredFields0(Native Method)
[info]   at java.base/java.lang.Class.privateGetDeclaredFields(Class.java:3067)
[info]   at java.base/java.lang.Class.getDeclaredFields(Class.java:2254)
[info]   at com.google.inject.spi.InjectionPoint.getDeclaredFields(InjectionPoint.java:760)
[info]   at com.google.inject.spi.InjectionPoint.getInjectionPoints(InjectionPoint.java:670)
[info]   at com.google.inject.spi.InjectionPoint.forInstanceMethodsAndFields(InjectionPoint.java:378)
[info]   at com.google.inject.internal.ConstructorBindingImpl.getInternalDependencies(ConstructorBindingImpl.java:182)
[info]   at com.google.inject.internal.InjectorImpl.getInternalDependencies(InjectorImpl.java:661)
[info]   at com.google.inject.internal.InjectorImpl.cleanup(InjectorImpl.java:617)
[info]   at com.google.inject.internal.InjectorImpl.initializeJitBinding(InjectorImpl.java:603)
[info]   ...
[info]   Cause: java.lang.ClassNotFoundException: javax.activation.MimetypesFileTypeMap
[info]   at java.base/java.net.URLClassLoader.findClass(URLClassLoader.java:436)
[info]   at java.base/java.lang.ClassLoader.loadClass(ClassLoader.java:588)
[info]   at java.base/java.lang.ClassLoader.loadClass(ClassLoader.java:521)
[info]   at java.base/java.lang.Class.getDeclaredFields0(Native Method)
[info]   at java.base/java.lang.Class.privateGetDeclaredFields(Class.java:3067)
[info]   at java.base/java.lang.Class.getDeclaredFields(Class.java:2254)
[info]   at com.google.inject.spi.InjectionPoint.getDeclaredFields(InjectionPoint.java:760)
[info]   at com.google.inject.spi.InjectionPoint.getInjectionPoints(InjectionPoint.java:670)
[info]   at com.google.inject.spi.InjectionPoint.forInstanceMethodsAndFields(InjectionPoint.java:378)
[info]   at com.google.inject.internal.ConstructorBindingImpl.getInternalDependencies(ConstructorBindingImpl.java:182)
[info]   ...
formats: Set(WhiteSpaceDelimited, Html, Json)
[info] ScalaTest
[info] Run completed in 12 seconds, 126 milliseconds.
[info] Total number of tests run: 0
[info] Suites: completed 0, aborted 4
[info] Tests: succeeded 0, failed 0, canceled 0, ignored 0, pending 0
[info] *** 4 SUITES ABORTED ***
[error] Error: Total 4, Failed 0, Errors 4, Passed 0
[error] Error during tests:
[error]         com.picchu.picchubackend.controllers.AdminControllerFeatureTest
[error]         com.picchu.picchubackend.controllers.MainControllerFeatureTest
[error]         com.picchu.picchubackend.controllers.AccountControllerFeatureTest
[error]         com.picchu.picchubackend.StartupTest
[error] (Test / test) sbt.TestsFailedException: Tests unsuccessful
[error] Total time: 26 s, completed 2019���?????����?12:45:02
5:02
