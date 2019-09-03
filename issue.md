[error] java.lang.NoClassDefFoundError: Ljavax/activation/MimetypesFileTypeMap;
[error]         at java.base/java.lang.Class.getDeclaredFields0(Native Method)
[error]         at java.base/java.lang.Class.privateGetDeclaredFields(Class.java:3067)
[error]         at java.base/java.lang.Class.getDeclaredFields(Class.java:2254)
[error]         at com.google.inject.spi.InjectionPoint.getDeclaredFields(InjectionPoint.java:760)
[error]         at com.google.inject.spi.InjectionPoint.getInjectionPoints(InjectionPoint.java:670)
[error]         at com.google.inject.spi.InjectionPoint.forInstanceMethodsAndFields(InjectionPoint.java:378)
[error]         at com.google.inject.internal.ConstructorBindingImpl.getInternalDependencies(ConstructorBindingImpl.java:182)
[error]         at com.google.inject.internal.InjectorImpl.getInternalDependencies(InjectorImpl.java:661)
[error]         at com.google.inject.internal.InjectorImpl.cleanup(InjectorImpl.java:617)
[error]         at com.google.inject.internal.InjectorImpl.initializeJitBinding(InjectorImpl.java:603)
[error]         at com.google.inject.internal.InjectorImpl.createJustInTimeBinding(InjectorImpl.java:932)
[error]         at com.google.inject.internal.InjectorImpl.createJustInTimeBindingRecursive(InjectorImpl.java:852)
[error]         at com.google.inject.internal.InjectorImpl.getJustInTimeBinding(InjectorImpl.java:291)
[error]         at com.google.inject.internal.InjectorImpl.getBindingOrThrow(InjectorImpl.java:222)
[error]         at com.google.inject.internal.InjectorImpl.createParameterInjector(InjectorImpl.java:991)
[error]         at com.google.inject.internal.InjectorImpl.getParametersInjectors(InjectorImpl.java:978)
[error]         at com.google.inject.internal.ProviderMethod.initialize(ProviderMethod.java:166)
[error]         at com.google.inject.internal.InternalProviderInstanceBindingImpl.initialize(InternalProviderInstanceBindingImpl.java:64)
[error]         at com.google.inject.internal.InjectorImpl.initializeBinding(InjectorImpl.java:581)
[error]         at com.google.inject.internal.AbstractBindingProcessor$Processor$1.run(AbstractBindingProcessor.java:176)
[error]         at com.google.inject.internal.ProcessedBindingData.initializeBindings(ProcessedBindingData.java:49)
[error]         at com.google.inject.internal.InternalInjectorCreator.initializeStatically(InternalInjectorCreator.java:122)
[error]         at com.google.inject.internal.InternalInjectorCreator.build(InternalInjectorCreator.java:106)
[error]         at com.google.inject.Guice.createInjector(Guice.java:87)
[error]         at com.google.inject.Guice.createInjector(Guice.java:78)
[error]         at com.twitter.inject.app.internal.InstalledModules$.create(InstalledModules.scala:37)
[error]         at com.twitter.inject.app.App.loadModules(App.scala:141)
[error]         at com.twitter.inject.app.App.loadModules$(App.scala:136)
[error]         at com.picchu.picchubackend.Server.loadModules(Server.scala:20)
[error]         at com.twitter.inject.app.App.main(App.scala:52)
[error]         at com.twitter.inject.app.App.main$(App.scala:51)
[error]         at com.picchu.picchubackend.Server.com$twitter$inject$server$TwitterServer$$super$main(Server.scala:20)
[error]         at com.twitter.inject.server.TwitterServer.main(TwitterServer.scala:174)
[error]         at com.twitter.inject.server.TwitterServer.main$(TwitterServer.scala:173)
[error]         at com.picchu.picchubackend.Server.main(Server.scala:20)
[error]         at java.base/jdk.internal.reflect.NativeMethodAccessorImpl.invoke0(Native Method)
[error]         at java.base/jdk.internal.reflect.NativeMethodAccessorImpl.invoke(NativeMethodAccessorImpl.java:62)
[error]         at java.base/jdk.internal.reflect.DelegatingMethodAccessorImpl.invoke(DelegatingMethodAccessorImpl.java:43)
[error]         at java.base/java.lang.reflect.Method.invoke(Method.java:567)
[error]         at com.twitter.app.App.$anonfun$nonExitingMain$4(App.scala:364)
[error]         at scala.Option.foreach(Option.scala:257)
[error]         at com.twitter.app.App.nonExitingMain(App.scala:363)
[error]         at com.twitter.app.App.nonExitingMain$(App.scala:344)
[error]         at com.picchu.picchubackend.Server.nonExitingMain(Server.scala:20)
[error]         at com.twitter.app.App.main(App.scala:333)
[error]         at com.twitter.app.App.main$(App.scala:331)
[error]         at com.picchu.picchubackend.Server.main(Server.scala:20)
[error]         at com.picchu.picchubackend.ServerMain.main(Server.scala)
[error] Caused by: java.lang.ClassNotFoundException: javax.activation.MimetypesFileTypeMap
[error]         at java.base/jdk.internal.loader.BuiltinClassLoader.loadClass(BuiltinClassLoader.java:583)
[error]         at java.base/jdk.internal.loader.ClassLoaders$AppClassLoader.loadClass(ClassLoaders.java:178)
[error]         at java.base/java.lang.ClassLoader.loadClass(ClassLoader.java:521)
[error]         ... 48 more
[error] Exception thrown in main on startup
[error] Nonzero exit code returned from runner: 1
[error] (Compile / run) Nonzero exit code returned from runner: 1
[error] Total time: 165 s, completed 2019���?????����?10:00:48
0:48
[IJ]picchu-backend> compile
[success] Total time: 0 s, completed 2019���?????����?10:01:16
1:16
[IJ]picchu-backend> test
[info] Compiling 6 Scala sources to C:\Users\Rocky\Desktop\picchu-backend-master\target\scala-2.12\test-classes ...
[warn]  [E1] src\test\scala\com\picchu\picchubackend\MongoTestKit.scala
[warn]       Java enum V3_0 in Java enum Main is deprecated: see corresponding Javadoc for more information.
[warn]       L26:     val config    = new MongodConfigBuilder().version(Version.Main.V3_0).net(net).build()
[warn]                                                                               ^
[error] [E2] src\test\scala\com\picchu\picchubackend\MongoTestKit.scala
[error]      implicit error;
[error]      !I writer: BSONDocumentWriter[Account]
[error]      L98:       .flatMap(_.insert[Account](account))
[error]                                           ^
[error] [E3] src\test\scala\com\picchu\picchubackend\MongoTestKit.scala
[error]      not enough arguments for method insert: (implicit writer: reactivemongo.bson.BSONDocumentWriter[com.picchu.picchubackend.models.dbo.Account], implicit ec: scala.concurrent.ExecutionContext)scala.concurrent.Future[reactivemongo.api.commands.WriteResult].
[error]      Unspecified value parameters writer, ec.
[error]      L98:       .flatMap(_.insert[Account](account))
[error]                                           ^
[error] [E4] src\test\scala\com\picchu\picchubackend\MongoTestKit.scala
[error]      implicit error;
[error]      !I evidence$1: BSONDocumentWriter[Account]
[error]      L105:       .flatMap(_.insert[Account](true).many(accounts))
[error]                                            ^
[error] [E5] src\test\scala\com\picchu\picchubackend\MongoTestKit.scala
[error]      not enough arguments for method insert: (implicit evidence$1: reactivemongo.bson.BSONDocumentWriter[com.picchu.picchubackend.models.dbo.Account])x$15.InsertBuilder[com.picchu.picchubackend.models.dbo.Account].
[error]      Unspecified value parameter evidence$1.
[error]      L105:       .flatMap(_.insert[Account](true).many(accounts))
[error]                                            ^
[error] [E6] src\test\scala\com\picchu\picchubackend\MongoTestKit.scala
[error]      implicit error;
[error]      !I reader: BSONDocumentReader[Account]
[error]      L113:         _.find(BSONDocument("uid" -> uid)).one[Account]
[error]                                                          ^
[error] [E7] src\test\scala\com\picchu\picchubackend\MongoTestKit.scala
[error]      not enough arguments for method one: (implicit reader: reactivemongo.bson.BSONDocumentReader[com.picchu.picchubackend.models.dbo.Account], implicit ec: scala.concurrent.ExecutionContext)scala.concurrent.Future[Option[com.picchu.picchubackend.models.dbo.Account]].
[error]      Unspecified value parameters reader, ec.
[error]      L113:         _.find(BSONDocument("uid" -> uid)).one[Account]
[error]                                                          ^
[error] [E8] src\test\scala\com\picchu\picchubackend\MongoTestKit.scala
[error]      implicit error;
[error]      !I reader: BSONDocumentReader[Account]
[error]      L123:           .cursor[Account]()
[error]                                      ^
[error] [E9] src\test\scala\com\picchu\picchubackend\MongoTestKit.scala
[error]      not enough arguments for method cursor: (implicit reader: reactivemongo.bson.BSONDocumentReader[com.picchu.picchubackend.models.dbo.Account], implicit cp: reactivemongo.api.CursorProducer[com.picchu.picchubackend.models.dbo.Account])cp.ProducedCursor.
[error]      Unspecified value parameters reader, cp.
[error]      L123:           .cursor[Account]()
[error]                                      ^
[warn]  [E10] src\test\scala\com\picchu\picchubackend\MongoTestKit.scala
[warn]        parameter value account in method insertAccount is never used
[warn]        L95:   def insertAccount(account: Account): Boolean =
[warn]                                 ^
[warn]  [E11] src\test\scala\com\picchu\picchubackend\MongoTestKit.scala
[warn]        parameter value accounts in method bulkInsertAccounts is never used
[warn]        L102:   def bulkInsertAccounts(accounts: List[Account]): Boolean =
[warn]                                       ^
[warn]  [E12] src\test\scala\com\picchu\picchubackend\MongoTestKit.scala
[warn]        parameter value uid in method findAccount is never used
[warn]        L109:   def findAccount(uid: Option[String] = None): Option[Account] =
[warn]                                ^
[warn]  [E13] src\test\scala\com\picchu\picchubackend\MongoTestKit.scala
[warn]        parameter value uids in method queryAccounts is never used
[warn]        L117:   def queryAccounts(uids: Option[List[String]] = None): List[Account] =
[warn]                                  ^
[error] [E14] src\test\scala\com\picchu\picchubackend\controllers\AccountControllerFeatureTest.scala
[error]       not found: type FeatureTestBase
[error]       L9: class AccountControllerFeatureTest extends FeatureTestBase {
[error]                                                      ^
[error] [E15] src\test\scala\com\picchu\picchubackend\controllers\AccountControllerFeatureTest.scala
[error]       not found: type FeatureTestBase
[error]       L9: class AccountControllerFeatureTest extends FeatureTestBase {
[error]                                                      ^
[error] [E16] src\test\scala\com\picchu\picchubackend\controllers\AccountControllerFeatureTest.scala
[error]       not found: value test
[error]       L14:   test("""sign up an account with 200""") {
[error]              ^
[error] [E17] src\test\scala\com\picchu\picchubackend\controllers\AccountControllerFeatureTest.scala
[error]       not found: value server
[error]       L34:     val response = server.httpPostJson[PicchuResponse[AccountSignUpResult]](
[error]                               ^
[error] [E18] src\test\scala\com\picchu\picchubackend\controllers\AccountControllerFeatureTest.scala
[error]       not found: value path
[error]       L35:       path = "/picchu/v1/account/signup",
[error]                  ^
[error] [E19] src\test\scala\com\picchu\picchubackend\controllers\AccountControllerFeatureTest.scala
[error]       not found: value headers
[error]       L36:       headers = Map(
[error]                  ^
[error] [E20] src\test\scala\com\picchu\picchubackend\controllers\AccountControllerFeatureTest.scala
[error]       not found: value postBody
[error]       L40:       postBody  = mapper.writePrettyString(request),
[error]                  ^
[error] [E21] src\test\scala\com\picchu\picchubackend\controllers\AccountControllerFeatureTest.scala
[error]       not found: value andExpect
[error]       L41:       andExpect = Ok
[error]                  ^
[error] [E22] src\test\scala\com\picchu\picchubackend\controllers\AccountControllerFeatureTest.scala
[error]       not found: value findAccount
[error]       L46:     val account = findAccount(result.uid.some).get
[error]                              ^
[warn]  [E23] src\test\scala\com\picchu\picchubackend\controllers\AccountControllerFeatureTest.scala
[warn]        Unused import
[warn]        L5: import com.twitter.finagle.http.Status._
[warn]                                                   ^
[error] src\test\scala\com\picchu\picchubackend\MongoTestKit.scala: L26 [E1], L95 [E10], L98 [E2], L98 [E3], L102 [E11], L105 [E4], L105 [E5], L109 [E12], L113 [E6], L113 [E7], L117 [E13], L123 [E8], L123 [E9]
[error] src\test\scala\com\picchu\picchubackend\controllers\AccountControllerFeatureTest.scala: L5 [E23], L9 [E14], L9 [E15], L14 [E16], L34 [E17], L35 [E18], L36 [E19], L40 [E20], L41 [E21], L46 [E22]
[info] Legend: Ln = line n, Cn = column n, En = error n
[error] ...................../蝜高蝪�/)
[error] ...................,/蝪�.../
[error] .................../..../
[error] .............../蝜高/'..'/蝜高蝪注蝜飽
[error] .........../'/.../..../....../蝛∠高\
[error] ..........('(....蝜�...蝜�... 蝪泠/'..')
[error] ...........\..............'...../
[error] ............\....\.........._.蝜��
[error] .............\..............(
[error] ..............\..............\
[error] +--------------------------------+
[error] |         picchu-backend         |
[error] +--------------------------------+
[error] (Test / compileIncremental) Compilation failed
[error] Total time: 3 s, completed 2019���?????����?10:01:27
