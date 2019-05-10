2019-05-10 17:46:17,585 Thread-0 ERROR Could not register mbeans java.security.AccessControlException: access denied ("javax.management.MBeanTrustPermission" "register") 
at java.security.AccessControlContext.checkPermission(AccessControlContext.java:472) 
at java.lang.SecurityManager.checkPermission(SecurityManager.java:585) 
at com.sun.jmx.interceptor.DefaultMBeanServerInterceptor.checkMBeanTrustPermission(DefaultMBeanServerInterceptor.java:1848)
at com.sun.jmx.interceptor.DefaultMBeanServerInterceptor.registerMBean(DefaultMBeanServerInterceptor.java:322)
at com.sun.jmx.mbeanserver.JmxMBeanServer.registerMBean(JmxMBeanServer.java:522) 
at org.apache.logging.log4j.core.jmx.Server.register(Server.java:389) 
at org.apache.logging.log4j.core.jmx.Server.reregisterMBeansAfterReconfigure(Server.java:167) 
at org.apache.logging.log4j.core.jmx.Server.reregisterMBeansAfterReconfigure(Server.java:140) 
at org.apache.logging.log4j.core.LoggerContext.setConfiguration(LoggerContext.java:556) 
at org.apache.logging.log4j.core.LoggerContext.reconfigure(LoggerContext.java:617) 
at org.apache.logging.log4j.core.LoggerContext.reconfigure(LoggerContext.java:634) 
at org.apache.logging.log4j.core.LoggerContext.start(LoggerContext.java:229) 
at org.apache.logging.log4j.core.impl.Log4jContextFactory.getContext(Log4jContextFactory.java:242) 
at org.apache.logging.log4j.core.impl.Log4jContextFactory.getContext(Log4jContextFactory.java:45) 
at org.apache.logging.log4j.LogManager.getContext(LogManager.java:174) 
at org.apache.logging.log4j.LogManager.getLogger(LogManager.java:618) 
at net.minecraft.launchwrapper.LogWrapper.configureLogging(LogWrapper.java:14) 
at net.minecraft.launchwrapper.LogWrapper.log(LogWrapper.java:28) 
at net.minecraft.launchwrapper.Launch.launch(Launch.java:94) 
at net.minecraft.launchwrapper.Launch.main(Launch.java:28) 
at sun.reflect.NativeMethodAccessorImpl.invoke0(Native Method) 
at sun.reflect.NativeMethodAccessorImpl.invoke(NativeMethodAccessorImpl.java:62) 
at sun.reflect.DelegatingMethodAccessorImpl.invoke(DelegatingMethodAccessorImpl.java:43) 
at java.lang.reflect.Method.invoke(Method.java:498) 
at net.minecraftforge.fml.relauncher.ServerLaunchWrapper.run(ServerLaunchWrapper.java:70) 
at net.minecraftforge.fml.relauncher.ServerLaunchWrapper.main(ServerLaunchWrapper.java:34) 
at sun.reflect.NativeMethodAccessorImpl.invoke0(Native Method) 
at sun.reflect.NativeMethodAccessorImpl.invoke(NativeMethodAccessorImpl.java:62) 
at sun.reflect.DelegatingMethodAccessorImpl.invoke(DelegatingMethodAccessorImpl.java:43) 
at java.lang.reflect.Method.invoke(Method.java:498) 
at com.hicoria.javaSandBox.Main$1.run(Main.java:67) 
at java.lang.Thread.run(Thread.java:748) 

[17:46:17] [Thread-0/INFO] [LaunchWrapper]: Loading tweak class name net.minecraftforge.fml.common.launcher.FMLServerTweaker 
[17:46:17] [Thread-0/INFO] [LaunchWrapper]: Using primary tweak class name net.minecraftforge.fml.common.launcher.FMLServerTweaker 
[17:46:17] [Thread-0/INFO] [LaunchWrapper]: Calling tweak class net.minecraftforge.fml.common.launcher.FMLServerTweaker 
[17:46:17] [Thread-0/INFO] [FML]: Forge Mod Loader version 14.23.5.2836 for Minecraft 1.12.2 loading 
[17:46:17] [Thread-0/INFO] [FML]: Java is Java HotSpot(TM) 64-Bit Server VM, version 1.8.0_201, running on Linux:amd64:4.19.0-0.bpo.1-amd64, installed at /usr/lib/jvm/java-8-oracle/jre 
[17:46:18] [Thread-0/WARN] [FML]: The coremod FMLCorePlugin (net.minecraftforge.fml.relauncher.FMLCorePlugin) is not signed! 
[39;0m[17:46:18] [Thread-0/WARN] [FML]: The coremod FMLForgePlugin (net.minecraftforge.classloading.FMLForgePlugin) is not signed! 
[39;0m[17:46:18] [Thread-0/INFO] [FML]: Searching /home/hosting/servers/211912/./mods for mods 
[17:46:18] [Thread-0/INFO] [FML]: Searching /home/hosting/servers/211912/./mods/1.12.2 for mods 
[17:46:18] [Thread-0/WARN] [FML]: Found FMLCorePluginContainsFMLMod marker in astral-sorcery.jar. This is not recommended, @Mods should be in a separate jar from the coremod. 
[39;0m2019-05-10 17:46:18,437 Thread-0 ERROR Could not register mbeans java.security.AccessControlException: access denied ("javax.management.MBeanTrustPermission" "register") 
at java.security.AccessControlContext.checkPermission(AccessControlContext.java:472) 
at java.lang.SecurityManager.checkPermission(SecurityManager.java:585) 
at com.sun.jmx.interceptor.DefaultMBeanServerInterceptor.checkMBeanTrustPermission(DefaultMBeanServerInterceptor.java:1848)
at com.sun.jmx.interceptor.DefaultMBeanServerInterceptor.registerMBean(DefaultMBeanServerInterceptor.java:322)
at com.sun.jmx.mbeanserver.JmxMBeanServer.registerMBean(JmxMBeanServer.java:522) 
at org.apache.logging.log4j.core.jmx.Server.register(Server.java:389) 
at org.apache.logging.log4j.core.jmx.Server.reregisterMBeansAfterReconfigure(Server.java:167) 
at org.apache.logging.log4j.core.jmx.Server.reregisterMBeansAfterReconfigure(Server.java:140) 
at org.apache.logging.log4j.core.LoggerContext.setConfiguration(LoggerContext.java:556) 
at org.apache.logging.log4j.core.LoggerContext.reconfigure(LoggerContext.java:617) 
at org.apache.logging.log4j.core.LoggerContext.reconfigure(LoggerContext.java:634) 
at org.apache.logging.log4j.core.LoggerContext.start(LoggerContext.java:229) 
at org.apache.logging.log4j.core.impl.Log4jContextFactory.getContext(Log4jContextFactory.java:242) 
at org.apache.logging.log4j.core.impl.Log4jContextFactory.getContext(Log4jContextFactory.java:45) 
at org.apache.logging.log4j.LogManager.getContext(LogManager.java:174) 
at org.apache.logging.log4j.LogManager.getLogger(LogManager.java:618) 
at hellfirepvp.astralsorcery.core.AstralCore.<clinit>(AstralCore.java:32) 
at java.lang.Class.forName0(Native Method) 
at java.lang.Class.forName(Class.java:348) 
at net.minecraftforge.fml.relauncher.CoreModManager.loadCoreMod(CoreModManager.java:527) 
at net.minecraftforge.fml.relauncher.CoreModManager.discoverCoreMods(CoreModManager.java:451) 
at net.minecraftforge.fml.relauncher.CoreModManager.handleLaunch(CoreModManager.java:265) 
at net.minecraftforge.fml.relauncher.FMLLaunchHandler.setupHome(FMLLaunchHandler.java:107) 
at net.minecraftforge.fml.relauncher.FMLLaunchHandler.setupServer(FMLLaunchHandler.java:87) 
at net.minecraftforge.fml.relauncher.FMLLaunchHandler.configureForServerLaunch(FMLLaunchHandler.java:47) 
at net.minecraftforge.fml.common.launcher.FMLServerTweaker.injectIntoClassLoader(FMLServerTweaker.java:62)
at net.minecraft.launchwrapper.Launch.launch(Launch.java:115) 
at net.minecraft.launchwrapper.Launch.main(Launch.java:28) 
at sun.reflect.NativeMethodAccessorImpl.invoke0(Native Method) 
at sun.reflect.NativeMethodAccessorImpl.invoke(NativeMethodAccessorImpl.java:62) 
at sun.reflect.DelegatingMethodAccessorImpl.invoke(DelegatingMethodAccessorImpl.java:43) 
at java.lang.reflect.Method.invoke(Method.java:498) 
at net.minecraftforge.fml.relauncher.ServerLaunchWrapper.run(ServerLaunchWrapper.java:70) 
at net.minecraftforge.fml.relauncher.ServerLaunchWrapper.main(ServerLaunchWrapper.java:34) 
at sun.reflect.NativeMethodAccessorImpl.invoke0(Native Method) 
at sun.reflect.NativeMethodAccessorImpl.invoke(NativeMethodAccessorImpl.java:62) 
at sun.reflect.DelegatingMethodAccessorImpl.invoke(DelegatingMethodAccessorImpl.java:43) 
at java.lang.reflect.Method.invoke(Method.java:498) 
at com.hicoria.javaSandBox.Main$1.run(Main.java:67) 
at java.lang.Thread.run(Thread.java:748) 

[17:46:18] [Thread-0/WARN] [FML]: The coremod hellfirepvp.astralsorcery.core.AstralCore does not have a MCVersion annotation, it may cause issues with this version of Minecraft 
[39;0m[17:46:18] [Thread-0/INFO] [Astral Core]: [AstralCore] Initialized. 
[17:46:18] [Thread-0/WARN] [FML]: Found FMLCorePluginContainsFMLMod marker in backpacks.jar. This is not recommended, @Mods should be in a separate jar from the coremod. 
[39;0m[17:46:18] [Thread-0/WARN] [FML]: The coremod BCModPlugin (brad16840.core.BCModPlugin) is not signed! 
[39;0m[17:46:18] [Thread-0/WARN] [FML]: Found FMLCorePluginContainsFMLMod marker in bed-patch.jar. This is not recommended, @Mods should be in a separate jar from the coremod. 
[39;0m[17:46:18] [Thread-0/WARN] [FML]: Found FMLCorePluginContainsFMLMod marker in ctm.jar. This is not recommended, @Mods should be in a separate jar from the coremod. 
[39;0m[17:46:18] [Thread-0/WARN] [FML]: The coremod team.chisel.ctm.client.asm.CTMCorePlugin does not have a MCVersion annotation, it may cause issues with this version of Minecraft 
[39;0m[17:46:18] [Thread-0/WARN] [FML]: The coremod CTMCorePlugin (team.chisel.ctm.client.asm.CTMCorePlugin) is not signed! 
[39;0m[17:46:18] [Thread-0/WARN] [FML]: Found FMLCorePluginContainsFMLMod marker in dummycore-unofficial.jar. This is not recommended, @Mods should be in a separate jar from the coremod. 
[39;0m[17:46:18] [Thread-0/WARN] [FML]: The coremod DummyCore.ASM.DCLoadingPlugin does not have a MCVersion annotation, it may cause issues with this version of Minecraft 
[39;0m[17:46:18] [Thread-0/WARN] [FML]: Found FMLCorePluginContainsFMLMod marker in farseek.jar. This is not recommended, @Mods should be in a separate jar from the coremod. 
[39;0m[17:46:18] [Thread-0/WARN] [FML]: The coremod farseek.core.FarseekCoreMod does not have a MCVersion annotation, it may cause issues with this version of Minecraft 
[39;0m[17:46:18] [Thread-0/WARN] [FML]: The coremod FarseekCoreMod (farseek.core.FarseekCoreMod) is not signed! 
[39;0m[17:46:18] [Thread-0/WARN] [FML]: Found FMLCorePluginContainsFMLMod marker in foamfix-for-minecraft.jar. This is not recommended, @Mods should be in a separate jar from the coremod. 
[39;0m[17:46:18] [Thread-0/WARN] [FML]: The coremod pl.asie.foamfix.coremod.FoamFixCore does not have a MCVersion annotation, it may cause issues with this version of Minecraft 
[39;0m[17:46:18] [Thread-0/WARN] [FML]: The coremod com.thiakil.gottagofast.coremod.GottaGoFastLoader does not have a MCVersion annotation, it may cause issues with this version of Minecraft 
[39;0m[17:46:18] [Thread-0/WARN] [FML]: Found FMLCorePluginContainsFMLMod marker in inventory-tweaks.jar. This is not recommended, @Mods should be in a separate jar from the coremod. 
[39;0m[17:46:18] [Thread-0/WARN] [FML]: The coremod invtweaks.forge.asm.FMLPlugin does not have a MCVersion annotation, it may cause issues with this version of Minecraft 
[39;0m[17:46:18] [Thread-0/INFO] [FML]: Loading tweaker org.spongepowered.asm.launch.MixinTweaker from jeid.jar 
[17:46:18] [Thread-0/INFO] [FML]: Loading tweaker org.spongepowered.asm.launch.MixinTweaker from laggoggles.jar 
[17:46:18] [Thread-0/WARN] [FML]: Found FMLCorePluginContainsFMLMod marker in librarianlib.jar. This is not recommended, @Mods should be in a separate jar from the coremod. 
[39;0m[17:46:18] [Thread-0/WARN] [FML]: The coremod com.teamwizardry.librarianlib.asm.LibLibCorePlugin does not have a MCVersion annotation, it may cause issues with this version of Minecraft 
[39;0m[17:46:18] [Thread-0/WARN] [FML]: The coremod LibrarianLib Plugin (com.teamwizardry.librarianlib.asm.LibLibCorePlugin) is not signed! 
[39;0m[17:46:18] [Thread-0/WARN] [FML]: The coremod ObfuscatePlugin (com.mrcrayfish.obfuscate.asm.ObfuscatePlugin) is not signed! 
[39;0m[17:46:18] [Thread-0/WARN] [FML]: Found FMLCorePluginContainsFMLMod marker in opencomputers.jar. This is not recommended, @Mods should be in a separate jar from the coremod. 
[39;0m[17:46:18] [Thread-0/WARN] [FML]: The coremod li.cil.oc.common.launch.TransformerLoader does not have a MCVersion annotation, it may cause issues with this version of Minecraft 
[39;0m[17:46:18] [Thread-0/WARN] [FML]: The coremod TransformerLoader (li.cil.oc.common.launch.TransformerLoader) is not signed! 
[39;0m[17:46:18] [Thread-0/WARN] [FML]: Found FMLCorePluginContainsFMLMod marker in opendisks.jar. This is not recommended, @Mods should be in a separate jar from the coremod. 
[39;0m[17:46:18] [Thread-0/WARN] [FML]: The coremod pcl.opendisks.OpenDisksUnpack does not have a MCVersion annotation, it may cause issues with this version of Minecraft 
[39;0m[17:46:18] [Thread-0/WARN] [FML]: The coremod OpenDisksUnpack (pcl.opendisks.OpenDisksUnpack) is not signed! 
[39;0m[17:46:18] [Thread-0/WARN] [FML]: Found FMLCorePluginContainsFMLMod marker in openfm.jar. This is not recommended, @Mods should be in a separate jar from the coremod. 
[39;0m[17:46:18] [Thread-0/WARN] [FML]: The coremod pcl.OpenFM.misc.OFMDepLoader does not have a MCVersion annotation, it may cause issues with this version of Minecraft 
[39;0m[17:46:18] [Thread-0/WARN] [FML]: The coremod OFMDepLoader (pcl.OpenFM.misc.OFMDepLoader) is not signed! 
[39;0m[17:46:18] [Thread-0/WARN] [FML]: Found FMLCorePluginContainsFMLMod marker in opensecurity.jar. This is not recommended, @Mods should be in a separate jar from the coremod. 
[39;0m[17:46:18] [Thread-0/WARN] [FML]: The coremod pcl.opensecurity.util.SoundUnpack does not have a MCVersion annotation, it may cause issues with this version of Minecraft 
[39;0m[17:46:18] [Thread-0/WARN] [FML]: The coremod SoundUnpack (pcl.opensecurity.util.SoundUnpack) is not signed! 
[39;0m[17:46:18] [Thread-0/WARN] [FML]: The coremod com.therandomlabs.randompatches.core.RPCore does not have a MCVersion annotation, it may cause issues with this version of Minecraft 
[39;0m[17:46:18] [Thread-0/WARN] [FML]: Found FMLCorePluginContainsFMLMod marker in redstone-paste.jar. This is not recommended, @Mods should be in a separate jar from the coremod. 
[39;0m[17:46:18] [Thread-0/WARN] [FML]: The coremod net.fybertech.nwr.NWRTweak does not have a MCVersion annotation, it may cause issues with this version of Minecraft 
[39;0m[17:46:18] [Thread-0/WARN] [FML]: The coremod NWRTweak (net.fybertech.nwr.NWRTweak) is not signed! 
[39;0m[17:46:18] [Thread-0/WARN] [FML]: Found FMLCorePluginContainsFMLMod marker in shadowfacts-forgelin.jar. This is not recommended, @Mods should be in a separate jar from the coremod. 
[39;0m[17:46:18] [Thread-0/WARN] [FML]: The coremod net.shadowfacts.forgelin.preloader.ForgelinPlugin does not have a MCVersion annotation, it may cause issues with this version of Minecraft 
[39;0m[17:46:18] [Thread-0/WARN] [FML]: The coremod ForgelinPlugin (net.shadowfacts.forgelin.preloader.ForgelinPlugin) is not signed! 
[39;0m[17:46:18] [Thread-0/WARN] [FML]: Found FMLCorePluginContainsFMLMod marker in techguns.jar. This is not recommended, @Mods should be in a separate jar from the coremod. 
[39;0m[17:46:18] [Thread-0/WARN] [FML]: The coremod Techguns Core (techguns.core.TechgunsFMLPlugin) is not signed! 
[39;0m[17:46:18] [Thread-0/INFO] [FML]: Loading tweaker org.spongepowered.asm.launch.MixinTweaker from vanillafix.jar 
[17:46:18] [Thread-0/WARN] [FML]: The coremod blusunrize.immersiveengineering.common.asm.IELoadingPlugin does not have a MCVersion annotation, it may cause issues with this version of Minecraft 
[39;0m[17:46:18] [Thread-0/WARN] [FML]: The coremod shetiphian.asm.TweakPlugin does not have a MCVersion annotation, it may cause issues with this version of Minecraft 
[39;0m[17:46:18] [Thread-0/WARN] [FML]: The coremod ShetiPhian-ASM (shetiphian.asm.TweakPlugin) is not signed! 
[39;0m[17:46:18] [Thread-0/INFO] [LaunchWrapper]: Loading tweak class name net.minecraftforge.fml.common.launcher.FMLInjectionAndSortingTweaker 
[17:46:18] [Thread-0/INFO] [LaunchWrapper]: Loading tweak class name org.spongepowered.asm.launch.MixinTweaker 
[17:46:18] [Thread-0/INFO] ixin]: SpongePowered MIXIN Subsystem Version=0.7.11 Source=file:/home/hosting/servers/211912/./mods/jeid.jar Service=LaunchWrapper Env=SERVER 
[17:46:19] [Thread-0/WARN] [FML]: The coremod JEIDLoadingPlugin (org.dimdev.jeid.JEIDLoadingPlugin) is not signed! 
[39;0m[17:46:19] [Thread-0/INFO] ixin]: Compatibility level set to JAVA_8 
[17:46:19] [Thread-0/INFO] [VanillaFix]: Initializing VanillaFix 
[17:46:19] [Thread-0/INFO] [VanillaFix]: Initializing StacktraceDeobfuscator 
[17:46:19] [Thread-0/INFO] [VanillaFix]: Found MCP method mappings: methods-stable_39.csv 
[17:46:19] [Thread-0/INFO] [VanillaFix]: Done initializing StacktraceDeobfuscator 
[17:46:19] [Thread-0/INFO] [VanillaFix]: Initializing Bug Fix Mixins 
[17:46:19] [Thread-0/INFO] [VanillaFix]: Initializing Crash Fix Mixins 
[17:46:19] [Thread-0/INFO] [VanillaFix]: Initializing Profiler Improvement Mixins 
[17:46:19] [Thread-0/INFO] [VanillaFix]: Initializing Texture Fix Mixins 
[17:46:19] [Thread-0/INFO] [VanillaFix]: Initializing Mod Support Mixins 
[17:46:19] [Thread-0/WARN] [FML]: The coremod VanillaFixLoadingPlugin (org.dimdev.vanillafix.VanillaFixLoadingPlugin) is not signed! 
[39;0m[17:46:19] [Thread-0/WARN] [LaunchWrapper]: Tweak class name org.spongepowered.asm.launch.MixinTweaker has already been visited -- skipping 
[39;0m[17:46:19] [Thread-0/WARN] [LaunchWrapper]: Tweak class name org.spongepowered.asm.launch.MixinTweaker has already been visited -- skipping 
[39;0m[17:46:19] [Thread-0/INFO] [LaunchWrapper]: Loading tweak class name net.minecraftforge.fml.common.launcher.FMLDeobfTweaker 
[17:46:19] [Thread-0/INFO] [LaunchWrapper]: Calling tweak class net.minecraftforge.fml.common.launcher.FMLInjectionAndSortingTweaker 
[17:46:19] [Thread-0/INFO] [LaunchWrapper]: Calling tweak class net.minecraftforge.fml.common.launcher.FMLInjectionAndSortingTweaker 
[17:46:19] [Thread-0/INFO] [LaunchWrapper]: Calling tweak class net.minecraftforge.fml.relauncher.CoreModManager$FMLPluginWrapper 
[17:46:21] [Thread-0/ERROR] [FML]: FML appears to be missing any signature data. This is not a good thing 
[39;0m[17:46:21] [Thread-0/INFO] [LaunchWrapper]: Calling tweak class net.minecraftforge.fml.relauncher.CoreModManager$FMLPluginWrapper 
[17:46:21] [Thread-0/INFO] [LaunchWrapper]: Calling tweak class net.minecraftforge.fml.relauncher.CoreModManager$FMLPluginWrapper 
[17:46:21] [Thread-0/INFO] [LaunchWrapper]: Calling tweak class net.minecraftforge.fml.relauncher.CoreModManager$FMLPluginWrapper 
[17:46:21] [Thread-0/INFO] [STDOUT]: [pcl.opendisks.OpenDisksUnpack:load:23]: Extracting Example Floppy from: assets/opendisks/lua/od-test/ 
[17:46:21] [Thread-0/INFO] [STDOUT]: [pcl.opendisks.OpenDisksUnpack:load:35]: Extracting file: test.lua
[17:46:21] [Thread-0/INFO] [STDOUT]: [pcl.opendisks.OpenDisksUnpack:load:35]: Extracting file: .disk.cfg 
[17:46:21] [Thread-0/INFO] [LaunchWrapper]: Calling tweak class net.minecraftforge.fml.relauncher.CoreModManager$FMLPluginWrapper 
[17:46:21] [Thread-0/INFO] [STDOUT]: [pcl.OpenFM.misc.OFMDepLoader:load:22]: Starting OpenFM DepLoader!
[17:46:21] [Thread-0/INFO] [STDOUT]: [pcl.OpenFM.misc.OFMDepLoader:load:37]: Extracting file: vorbisspi-1.0.3-1.jar 
[17:46:21] [Thread-0/INFO] [STDOUT]: [pcl.OpenFM.misc.OFMDepLoader:load:37]: Extracting file: mp3spi-1.9.5-1.jar 
[17:46:21] [Thread-0/INFO] [LaunchWrapper]: Calling tweak class net.minecraftforge.fml.relauncher.CoreModManager$FMLPluginWrapper 
[17:46:21] [Thread-0/INFO] [STDOUT]: [pcl.opensecurity.util.SoundUnpack:load:25]: Extracting sounds from: assets/opensecurity/sounds/alarms/ 
[17:46:21] [Thread-0/INFO] [STDOUT]: [pcl.opensecurity.util.SoundUnpack:load:37]: Extracting file: klaxon2.ogg 
[17:46:21] [Thread-0/INFO] [STDOUT]: [pcl.opensecurity.util.SoundUnpack:load:37]: Extracting file: klaxon1.ogg 
[17:46:21] [Thread-0/INFO] [LaunchWrapper]: Calling tweak class net.minecraftforge.fml.relauncher.CoreModManager$FMLPluginWrapper 
[17:46:21] [Thread-0/INFO] [LaunchWrapper]: Calling tweak class org.spongepowered.asm.launch.MixinTweaker 
[17:46:21] [Thread-0/ERROR] ixin]: MixinBootstrap.doInit() called during a tweak constructor! 
[39;0m[17:46:21] [Thread-0/INFO] ixin]: Initialised Mixin FML Remapper Adapter with net.minecraftforge.fml.common.asm.transformers.deobf.FMLDeobfuscatingRemapper@28740a2d 
[17:46:21] [Thread-0/INFO] [LaunchWrapper]: Calling tweak class net.minecraftforge.fml.relauncher.CoreModManager$FMLPluginWrapper 
[17:46:21] [Thread-0/INFO] [LaunchWrapper]: Calling tweak class net.minecraftforge.fml.common.launcher.FMLDeobfTweaker 
[17:46:21] [Thread-0/INFO] [Astral Core]: [AstralTransformer] Loading patches... 
May 10, 2019 5:46:21 PM com.google.common.reflect.ClassPath$Scanner scanFrom 
WARNING: Cannot access /bin: java.lang.SecurityException: read permission error: /bin 
[17:46:22] [Thread-0/INFO] [Astral Core]: [AstralTransformer] Initialized! Loaded 14 class patches! 
[17:46:22] [Thread-0/INFO] [LaunchWrapper]: Calling tweak class net.minecraftforge.fml.relauncher.CoreModManager$FMLPluginWrapper 
[17:46:22] [Thread-0/INFO] [LaunchWrapper]: Calling tweak class net.minecraftforge.fml.relauncher.CoreModManager$FMLPluginWrapper 
[17:46:22] [Thread-0/INFO] [LaunchWrapper]: Calling tweak class net.minecraftforge.fml.relauncher.CoreModManager$FMLPluginWrapper 
[17:46:22] [Thread-0/INFO] [LaunchWrapper]: Calling tweak class net.minecraftforge.fml.relauncher.CoreModManager$FMLPluginWrapper 
[17:46:22] [Thread-0/INFO] [LaunchWrapper]: Calling tweak class net.minecraftforge.fml.relauncher.CoreModManager$FMLPluginWrapper 
[17:46:22] [Thread-0/INFO] [LaunchWrapper]: Calling tweak class net.minecraftforge.fml.relauncher.CoreModManager$FMLPluginWrapper 
[17:46:22] [Thread-0/INFO] [LaunchWrapper]: Calling tweak class net.minecraftforge.fml.relauncher.CoreModManager$FMLPluginWrapper 
[17:46:23] [Thread-0/INFO] [LaunchWrapper]: Calling tweak class net.minecraftforge.fml.relauncher.CoreModManager$FMLPluginWrapper 
[17:46:23] [Thread-0/INFO] [LaunchWrapper]: Calling tweak class net.minecraftforge.fml.relauncher.CoreModManager$FMLPluginWrapper 
[17:46:23] [Thread-0/INFO] [LaunchWrapper]: Calling tweak class net.minecraftforge.fml.relauncher.CoreModManager$FMLPluginWrapper 
[17:46:23] [Thread-0/INFO] [LaunchWrapper]: Calling tweak class net.minecraftforge.fml.relauncher.CoreModManager$FMLPluginWrapper 
[17:46:23] [Thread-0/INFO] [LaunchWrapper]: Calling tweak class net.minecraftforge.fml.relauncher.CoreModManager$FMLPluginWrapper 
[17:46:23] [Thread-0/INFO] [net.minecraft]: [farseek] Moving Farseek transformer after Sponge proxy 
[17:46:23] [Thread-0/INFO] [net.minecraft]: [farseek] Excluding Farseek transformer from Sponge pre-mixin transformations 
[17:46:23] [Thread-0/INFO] [net.minecraft]: [farseek] Re-enabling transformations on Sponge TrackingUtil 
[17:46:23] [Thread-0/INFO] [LaunchWrapper]: Calling tweak class net.minecraftforge.fml.relauncher.CoreModManager$FMLPluginWrapper 
[17:46:23] [Thread-0/INFO] [LaunchWrapper]: Calling tweak class net.minecraftforge.fml.relauncher.CoreModManager$FMLPluginWrapper 
[17:46:23] [Thread-0/INFO] [LaunchWrapper]: Calling tweak class net.minecraftforge.fml.relauncher.CoreModManager$FMLPluginWrapper 
[17:46:23] [Thread-0/INFO] [LaunchWrapper]: Calling tweak class net.minecraftforge.fml.relauncher.CoreModManager$FMLPluginWrapper 
[17:46:23] [Thread-0/INFO] [LaunchWrapper]: Loading tweak class name net.minecraftforge.fml.common.launcher.TerminalTweaker 
[17:46:23] [Thread-0/INFO] [LaunchWrapper]: Loading tweak class name org.spongepowered.asm.mixin.EnvironmentStateTweaker 
[17:46:23] [Thread-0/INFO] [LaunchWrapper]: Calling tweak class net.minecraftforge.fml.common.launcher.TerminalTweaker 
[17:46:23] [Thread-0/INFO] [LaunchWrapper]: Calling tweak class org.spongepowered.asm.mixin.EnvironmentStateTweaker 
[17:46:24] [Thread-0/INFO] [STDOUT]: [pl.asie.foamfix.coremod.FoamFixTransformer:spliceClasses:137]: Spliced in METHOD: net.minecraft.world.chunk.BlockStateContainer.func_186018_a 
[17:46:24] [Thread-0/INFO] [STDOUT]: [team.chisel.ctm.client.asm.CTMTransformer:preTransform:230]: Transforming Class [net.minecraft.block.Block], Method [getExtendedState] 
[17:46:24] [Thread-0/INFO] [STDOUT]: [team.chisel.ctm.client.asm.CTMTransformer:finishTransform:242]: Transforming net.minecraft.block.Block Finished. 
[17:46:24] [Thread-0/INFO] [BedPatch]: Patching Chunk 
[17:46:24] [Thread-0/INFO] [STDOUT]: [pl.asie.patchy.helpers.ConstructorReplacingTransformer$FFMethodVisitor:visitTypeInsn:73]: Replaced NEW for net/minecraft/util/ClassInheritanceMultiMap to pl/asie/foamfix/coremod/common/FoamyClassInheritanceMultiMap 
[17:46:24] [Thread-0/INFO] [STDOUT]: [pl.asie.patchy.helpers.ConstructorReplacingTransformer$FFMethodVisitor:visitMethodInsn:85]: Replaced INVOKESPECIAL for net/minecraft/util/ClassInheritanceMultiMap to pl/asie/foamfix/coremod/common/FoamyClassInheritanceMultiMap 
[17:46:24] [Thread-0/INFO] ixin]: A re-entrant transformer '$wrapper.pl.asie.foamfix.coremod.FoamFixTransformer' was detected and will no longer process meta class data 
[17:46:24] [Thread-0/INFO] [Astral Core]: [AstralTransformer] Transforming alm : net.minecraft.enchantment.EnchantmentHelper with 1 patches! 
[17:46:24] [Thread-0/INFO] [Astral Core]: [AstralTransformer] Applied patch PATCHMODIFYENCHANTMENTLEVELS 
[17:46:24] [Thread-0/INFO] [LibrarianLib ASM]: Transforming Entity 
[17:46:24] [Thread-0/INFO] [LibrarianLib ASM]: Applying Transformation to method (Names [onUpdate, func_70071_h_] Descriptor ()V) 
[17:46:24] [Thread-0/INFO] [LibrarianLib ASM]: Attempting to insert: Update hook 
[17:46:24] [Thread-0/INFO] [LibrarianLib ASM]: Patch result: Success 
[17:46:24] [Thread-0/INFO] [ShetiPhian-ASM]: Attempting: Injection of Run Particle Override into Entity.createRunningParticles 
[17:46:24] [Thread-0/INFO] [ShetiPhian-ASM]: Searching for: Entity.createRunningParticles (func_174808_Z) 
[17:46:24] [Thread-0/INFO] [ShetiPhian-ASM]: Found Method: Entity.createRunningParticles 
[17:46:24] [Thread-0/INFO] [ShetiPhian-ASM]: Injecting: Run Particle Override 
[17:46:24] [Thread-0/WARN] ixin]: Error loading class: net/minecraft/server/integrated/IntegratedServer (net.minecraftforge.fml.common.asm.ASMTransformerWrapper$TransformerException: Exception in class transformer net.minecraftforge.fml.common.asm.transformers.SideTransformer@5ea22c84 from coremod FMLCorePlugin) 
[39;0m[17:46:24] [Thread-0/WARN] ixin]: @Mixin target net.minecraft.server.integrated.IntegratedServer was not found mixins.vanillafix.crashes.json:MixinIntegratedServer 
[39;0m[17:46:25] [Thread-0/INFO] [Astral Core]: [AstralTransformer] Transforming amu : net.minecraft.world.World with 2 patches! 
[17:46:25] [Thread-0/INFO] [Astral Core]: [AstralTransformer] Skipping PATCHSUNBRIGHTNESSWORLDCLIENT as it can't be applied for side SERVER 
[17:46:25] [Thread-0/INFO] [Astral Core]: [AstralTransformer] Applied patch PATCHSUNBRIGHTNESSWORLDCOMMON 
[17:46:25] [Thread-0/WARN] ixin]: Error loading class: net/minecraft/client/renderer/tileentity/TileEntityRendererDispatcher (net.minecraftforge.fml.common.asm.ASMTransformerWrapper$TransformerException: Exception in class transformer net.minecraftforge.fml.common.asm.transformers.SideTransformer@5ea22c84 from coremod FMLCorePlugin) 
[39;0m[17:46:25] [Thread-0/WARN] ixin]: @Mixin target net.minecraft.client.renderer.tileentity.TileEntityRendererDispatcher was not found mixins.laggoggles.json:MixinTileEntityRendererDispatcher 
[39;0m[17:46:25] [Thread-0/WARN] ixin]: Error loading class: net/minecraft/client/renderer/entity/RenderManager (net.minecraftforge.fml.common.asm.ASMTransformerWrapper$TransformerException: Exception in class transformer net.minecraftforge.fml.common.asm.transformers.SideTransformer@5ea22c84 from coremod FMLCorePlugin) 
[39;0m[17:46:25] [Thread-0/WARN] ixin]: @Mixin target net.minecraft.client.renderer.entity.RenderManager was not found mixins.laggoggles.json:MixinRenderManager 
[39;0m[17:46:25] [Thread-0/INFO] [Astral Core]: [AstralTransformer] Transforming amu : net.minecraft.world.World with 2 patches! 
[17:46:25] [Thread-0/INFO] [Astral Core]: [AstralTransformer] Skipping PATCHSUNBRIGHTNESSWORLDCLIENT as it can't be applied for side SERVER 
[17:46:25] [Thread-0/INFO] [Astral Core]: [AstralTransformer] Applied patch PATCHSUNBRIGHTNESSWORLDCOMMON 
[17:46:25] [Thread-0/INFO] [STDOUT]: [pl.asie.foamfix.coremod.FoamFixTransformer:spliceClasses:124]: Added INTERFACE: pl/asie/foamfix/coremod/patches/IFoamFixWorldRemovable 
[17:46:25] [Thread-0/INFO] [STDOUT]: [pl.asie.foamfix.coremod.FoamFixTransformer:spliceClasses:161]: Added METHOD: net.minecraft.world.World.foamfix_removeUnloadedEntities 
[17:46:25] [Thread-0/INFO] [STDOUT]: [pl.asie.foamfix.coremod.patches.WorldServerRemovalPatch:apply:62]: Patched updateEntities in net/minecraft/world/WorldServer func_72939_s 
[17:46:25] [Thread-0/INFO] [OpenComputers]: Successfully patched net/minecraft/entity/EntityLiving.recreateLeash. 
[17:46:25] [Thread-0/INFO] [Astral Core]: [AstralTransformer] Transforming vp : net.minecraft.entity.EntityLivingBase with 4 patches! 
[17:46:25] [Thread-0/INFO] [Astral Core]: [AstralTransformer] Applied patch PATCHAPPLYPOTIONEFFECTEVENT
[17:46:25] [Thread-0/INFO] [Astral Core]: [AstralTransformer] Applied patch PATCHENTITYLIVINGBASEWATERSLOWDOWN 
[17:46:25] [Thread-0/INFO] [Astral Core]: [AstralTransformer] Applied patch PATCHSETPLAYERATTRIBUTE 
[17:46:25] [Thread-0/INFO] [Astral Core]: [AstralTransformer] Applied patch PATCHUPDATEELYTRA 
[17:46:25] [Thread-0/INFO] [Astral Core]: [AstralTransformer] Transforming vp : net.minecraft.entity.EntityLivingBase with 4 patches! 
[17:46:25] [Thread-0/INFO] [Astral Core]: [AstralTransformer] Applied patch PATCHAPPLYPOTIONEFFECTEVENT
[17:46:25] [Thread-0/INFO] [Astral Core]: [AstralTransformer] Applied patch PATCHENTITYLIVINGBASEWATERSLOWDOWN 
[17:46:25] [Thread-0/INFO] [Astral Core]: [AstralTransformer] Applied patch PATCHSETPLAYERATTRIBUTE 
[17:46:25] [Thread-0/INFO] [Astral Core]: [AstralTransformer] Applied patch PATCHUPDATEELYTRA 
[17:46:26] [Thread-0/INFO] [LibrarianLib ASM]: Transforming Entity 
[17:46:26] [Thread-0/INFO] [LibrarianLib ASM]: Applying Transformation to method (Names [onUpdate, func_70071_h_] Descriptor ()V) 
[17:46:26] [Thread-0/INFO] [LibrarianLib ASM]: Attempting to insert: Update hook 
[17:46:26] [Thread-0/INFO] [LibrarianLib ASM]: Patch result: Success 
[17:46:26] [Thread-0/INFO] [ShetiPhian-ASM]: Attempting: Injection of Run Particle Override into Entity.createRunningParticles 
[17:46:26] [Thread-0/INFO] [ShetiPhian-ASM]: Searching for: Entity.createRunningParticles (func_174808_Z) 
[17:46:26] [Thread-0/INFO] [ShetiPhian-ASM]: Found Method: Entity.createRunningParticles 
[17:46:26] [Thread-0/INFO] [ShetiPhian-ASM]: Injecting: Run Particle Override 
[17:46:26] [Thread-0/INFO] [LaunchWrapper]: Launching wrapped minecraft {net.minecraft.server.MinecraftServer} 
[17:46:26] [Thread-0/INFO] [STDOUT]: [team.chisel.ctm.client.asm.CTMTransformer:preTransform:230]: Transforming Class [net.minecraft.block.Block], Method [getExtendedState] 
[17:46:26] [Thread-0/INFO] [STDOUT]: [team.chisel.ctm.client.asm.CTMTransformer:finishTransform:242]: Transforming net.minecraft.block.Block Finished. 
[17:46:26] [Thread-0/INFO] [STDOUT]: [pl.asie.foamfix.coremod.FoamFixTransformer:spliceClasses:137]: Spliced in METHOD: net.minecraft.block.state.BlockStateContainer.createState 
[17:46:26] [Thread-0/INFO] [STDOUT]: [pl.asie.foamfix.coremod.FoamFixTransformer:spliceClasses:137]: Spliced in METHOD: net.minecraft.block.properties.PropertyEnum.equals 
[17:46:26] [Thread-0/INFO] [STDOUT]: [pl.asie.foamfix.coremod.FoamFixTransformer:spliceClasses:137]: Spliced in METHOD: net.minecraft.block.properties.PropertyEnum.hashCode 
[17:46:26] [Thread-0/INFO] [STDOUT]: [pl.asie.foamfix.coremod.FoamFixTransformer:spliceClasses:184]: Added FIELD: net.minecraft.block.properties.PropertyEnum.foamfix_hashCode 
[17:46:26] [Thread-0/INFO] [STDOUT]: [pl.asie.foamfix.coremod.FoamFixTransformer:spliceClasses:184]: Added FIELD: net.minecraft.block.properties.PropertyEnum.foamfix_hashCode_calced 
[17:46:26] [Thread-0/INFO] [STDOUT]: [pl.asie.foamfix.coremod.FoamFixTransformer:spliceClasses:137]: Spliced in METHOD: net.minecraft.block.properties.PropertyInteger.hashCode 
[17:46:26] [Thread-0/INFO] [STDOUT]: [pl.asie.foamfix.coremod.FoamFixTransformer:spliceClasses:184]: Added FIELD: net.minecraft.block.properties.PropertyInteger.foamfix_hashCode 
[17:46:26] [Thread-0/INFO] [STDOUT]: [pl.asie.foamfix.coremod.FoamFixTransformer:spliceClasses:184]: Added FIELD: net.minecraft.block.properties.PropertyInteger.foamfix_hashCode_calced 
[17:46:26] [Thread-0/INFO] [STDOUT]: [pl.asie.foamfix.coremod.FoamFixTransformer:spliceClasses:137]: Spliced in METHOD: net.minecraft.block.properties.PropertyBool.equals 
[17:46:26] [Thread-0/INFO] [STDOUT]: [pl.asie.foamfix.coremod.FoamFixTransformer:spliceClasses:137]: Spliced in METHOD: net.minecraft.block.properties.PropertyBool.hashCode 
[17:46:27] [Thread-0/INFO] [Astral Core]: [AstralTransformer] Transforming aip : net.minecraft.item.ItemStack with 2 patches! 
[17:46:27] [Thread-0/INFO] [Astral Core]: [AstralTransformer] Skipping PATCHMODIFYENCHANTMENTLEVELSTOOLTIP as it can't be applied for side SERVER 
[17:46:27] [Thread-0/INFO] [Astral Core]: [AstralTransformer] Skipping PATCHMODIFYENCHANTMENTLEVELSTOOLTIPEVENT as it can't be applied for side SERVER 
[17:46:27] [Thread-0/INFO] [STDOUT]: [pl.asie.foamfix.coremod.FoamFixTransformer:spliceClasses:137]: Spliced in METHOD: net.minecraft.tileentity.TileEntity.func_190559_a 
[17:46:27] [Thread-0/INFO] [STDOUT]: [pl.asie.foamfix.coremod.FoamFixTransformer:spliceClasses:137]: Spliced in METHOD: net.minecraft.block.BlockBed.func_189540_a 
[17:46:28] [Thread-0/INFO] [OpenComputers]: Successfully patched net/minecraft/entity/EntityLiving.recreateLeash. 
[17:46:28] [Thread-0/INFO] [STDOUT]: [pl.asie.patchy.helpers.ConstructorReplacingTransformer$FFMethodVisitor:visitTypeInsn:73]: Replaced NEW for net/minecraft/tileentity/TileEntityHopper to pl/asie/foamfix/common/TileEntityFasterHopper 
[17:46:28] [Thread-0/INFO] [STDOUT]: [pl.asie.patchy.helpers.ConstructorReplacingTransformer$FFMethodVisitor:visitMethodInsn:85]: Replaced INVOKESPECIAL for net/minecraft/tileentity/TileEntityHopper to pl/asie/foamfix/common/TileEntityFasterHopper 
[17:46:29] [Thread-0/INFO] [Astral Core]: [AstralTransformer] Transforming aip : net.minecraft.item.ItemStack with 2 patches! 
[17:46:29] [Thread-0/INFO] [Astral Core]: [AstralTransformer] Skipping PATCHMODIFYENCHANTMENTLEVELSTOOLTIP as it can't be applied for side SERVER 
[17:46:29] [Thread-0/INFO] [Astral Core]: [AstralTransformer] Skipping PATCHMODIFYENCHANTMENTLEVELSTOOLTIPEVENT as it can't be applied for side SERVER 
[17:46:29] [Thread-0/INFO] [Astral Core]: [AstralTransformer] Transforming wg : net.minecraft.entity.ai.attributes.AbstractAttributeMap with 1 patches! 
[17:46:29] [Thread-0/INFO] [Astral Core]: [AstralTransformer] Applied patch PATCHADDPLAYERATTRIBUTE 
[17:46:30] [Thread-0/INFO] [STDOUT]: [pl.asie.foamfix.coremod.FoamFixTransformer:spliceClasses:124]: Added INTERFACE: pl/asie/foamfix/api/IFoamFixMobSpawnerLogic 
[17:46:30] [Thread-0/INFO] [STDOUT]: [pl.asie.foamfix.coremod.FoamFixTransformer:spliceClasses:137]: Spliced in METHOD: net.minecraft.tileentity.MobSpawnerBaseLogic.func_98279_f 
[17:46:30] [Thread-0/INFO] [STDOUT]: [pl.asie.foamfix.coremod.FoamFixTransformer:spliceClasses:184]: Added FIELD: net.minecraft.tileentity.MobSpawnerBaseLogic.foamfix_activatedCache 
[17:46:30] [Thread-0/INFO] [STDOUT]: [pl.asie.foamfix.coremod.FoamFixTransformer:spliceClasses:184]: Added FIELD: net.minecraft.tileentity.MobSpawnerBaseLogic.foamfix_activatedCachePESize 
[17:46:30] [Thread-0/INFO] [STDOUT]: [pl.asie.foamfix.coremod.FoamFixTransformer:spliceClasses:184]: Added FIELD: net.minecraft.tileentity.MobSpawnerBaseLogic.foamfix_activatedCacheTime 
[17:46:30] [Thread-0/INFO] [STDOUT]: [pl.asie.foamfix.coremod.FoamFixTransformer:spliceClasses:184]: Added FIELD: net.minecraft.tileentity.MobSpawnerBaseLogic.foamfix_forcedCache 
[17:46:30] [Thread-0/INFO] [STDOUT]: [pl.asie.foamfix.coremod.FoamFixTransformer:spliceClasses:184]: Added FIELD: net.minecraft.tileentity.MobSpawnerBaseLogic.foamfix_forcedCacheTime 
[17:46:31] [Server thread/INFO] inecraft/DedicatedServer]: Starting minecraft server version 1.12.2 
[17:46:31] [Server thread/INFO] [FML]: MinecraftForge v14.23.5.2836 Initialized 
[17:46:31] [Server thread/INFO] [FML]: Starts to replace vanilla recipe ingredients with ore ingredients. 
[?1h=[?2004h> [K[17:46:32] [Server thread/INFO] [FML]: Invalid recipe found with multiple oredict ingredients in the same ingredient... 
> [K[17:46:32] [Server thread/INFO] [FML]: Replaced 1227 ore ingredients 
> [K[17:46:32] [Server thread/INFO] [FML]: Searching /home/hosting/servers/211912/./mods for mods 
> [K[17:46:32] [Server thread/INFO] [FML]: Searching /home/hosting/servers/211912/./mods/1.12.2 for mods 
> [K[17:46:33] [Server thread/WARN] [FML]: Mod betterbuilderswands is missing the required element 'version' and a version.properties file could not be found. Falling back to metadata version 0.13.2 
[39;0m> [K[17:46:34] [Server thread/INFO] [FML]: Disabling mod blockdrops it is client side only. 
> [K[17:46:34] [Server thread/WARN] [FML]: Mod codechickenlib is missing the required element 'version' and a version.properties file could not be found. Falling back to metadata version 3.2.2.353 
[39;0m> [K[17:46:34] [Server thread/WARN] [FML]: Mod cosmeticarmorreworked is missing the required element 'version' and a version.properties file could not be found. Falling back to metadata version 1.12.2-v4a 
[39;0m> [K[17:46:35] [Server thread/WARN] [FML]: Mod craftingtweaks is missing the required element 'version' and a version.properties file could not be found. Falling back to metadata version 8.1.9 
[39;0m> [K[17:46:35] [Server thread/INFO] [FML]: Disabling mod ctgui it is client side only. 
> [K[17:46:35] [Server thread/INFO] [FML]: Disabling mod ctm it is client side only. 
> [K[17:46:35] [Server thread/WARN] [FML]: Mod enderstorage is missing the required element 'version' and a version.properties file could not be found. Falling back to metadata version 2.4.5.135 
[39;0m> [K[17:46:35] [Server thread/WARN] [FML]: Mod excompressum is missing the required element 'version' and a version.properties file could not be found. Falling back to metadata version 3.0.27 
[39;0m> [K[17:46:35] [Server thread/WARN] [FML]: Mod farseek is missing the required element 'version' and a version.properties file could not be found. Falling back to metadata version 2.3.2 
[39;0m> [K[17:46:36] [Server thread/WARN] [FML]: Mod helpfixer is missing the required element 'version' and a version.properties file could not be found. Falling back to metadata version 1.12.1-1.5.18 
[39;0m> [K[17:46:37] [Server thread/WARN] [FML]: Mod igwmod is missing the required element 'version' and a version.properties file could not be found. Falling back to metadata version 1.4.4-15 
[39;0m> [K[17:46:37] [Server thread/INFO] [FML]: Disabling mod itemscroller it is client side only. 
> [K[17:46:37] [Server thread/INFO] [FML]: Disabling mod jeivillagers it is client side only. 
> [K[17:46:37] [Server thread/WARN] [FML]: Mod jeid is missing the required element 'version' and a version.properties file could not be found. Falling back to metadata version 1.0.2-26 
[39;0m> [K[17:46:37] [Server thread/INFO] [FML]: Disabling mod jeresources it is client side only. 
> [K[17:46:37] [Server thread/WARN] [FML]: Mod mekanism is missing the required element 'version' and a version.properties file could not be found. Falling back to metadata version 1.12.2-1.2.0 
[39;0m> [K[17:46:37] [Server thread/WARN] [FML]: Mod mtrm is missing the required element 'version' and a version.properties file could not be found. Falling back to metadata version 1.2.2.30 
[39;0m> [K[17:46:37] [Server thread/WARN] [FML]: Mod moartinkers is missing the required element 'version' and a version.properties file could not be found. Falling back to metadata version 0.6.0 
[39;0m> [K[17:46:38] [Server thread/ERROR] [FML]: Unable to parse dependency for mod 'opendisks' with dependency string 'after:OpenComputers'. The modId 'OpenComputers' must be all lowercase. 
[39;0m> [K[17:46:39] [Server thread/WARN] [FML]: Mod streams is missing the required element 'version' and a version.properties file could not be found. Falling back to metadata version 0.4.7 
[39;0m> [K[17:46:39] [Server thread/INFO] [FML]: Disabling mod tc6aspects4jei it is client side only. 
> [K[17:46:40] [Server thread/INFO] [FML]: Disabling mod thaumicjei it is client side only. 
> [K[17:46:40] [Server thread/WARN] [FML]: Mod tramplestopper is missing the required element 'version' and a version.properties file could not be found. Falling back to metadata version 1.2.0.4 
[39;0m> [K[17:46:40] [Server thread/WARN] [FML]: Mod vanillafix is missing the required element 'version' and a version.properties file could not be found. Falling back to metadata version 1.0.10-SNAPSHOT 
[39;0m> [K[17:46:40] [Server thread/WARN] [FML]: Mod waystones is missing the required element 'version' and a version.properties file could not be found. Falling back to metadata version 4.0.67 
[39;0m> [K[17:46:41] [Server thread/INFO] [FML]: Forge Mod Loader has identified 209 mods to load 
> [K[17:46:41] [Server thread/WARN] [FML]: Missing English translation for FML: assets/fml/lang/en_us.lang 
[39;0m> [K[17:46:41] [Server thread/WARN] [FML]: Missing English translation for gottagofast: assets/gottagofast/lang/en_us.lang 
[39;0m> [K[17:46:41] [Server thread/WARN] [FML]: Missing English translation for appleskin: assets/appleskin/lang/en_us.lang 
[39;0m> [K[17:46:41] [Server thread/WARN] [FML]: Missing English translation for armoryexpansion-conarm: assets/armoryexpansion-conarm/lang/en_us.lang 
[39;0m> [K[17:46:41] [Server thread/WARN] [FML]: Missing English translation for armoryexpansion-custommaterials: assets/armoryexpansion-custommaterials/lang/en_us.lang 
[39;0m> [K[17:46:41] [Server thread/WARN] [FML]: Missing English translation for armoryexpansion-iceandfire: assets/armoryexpansion-iceandfire/lang/en_us.lang 
[39;0m> [K[17:46:41] [Server thread/WARN] [FML]: Missing English translation for bedpatch: assets/bedpatch/lang/en_us.lang 
[39;0m> [K[17:46:41] [Server thread/WARN] [FML]: Missing English translation for caliper: assets/caliper/lang/en_us.lang 
[39;0m> [K[17:46:41] [Server thread/WARN] [FML]: Missing English translation for cctweaked: assets/cctweaked/lang/en_us.lang 
[39;0m> [K[17:46:41] [Server thread/WARN] [FML]: Missing English translation for chameleon: assets/chameleon/lang/en_us.lang 
[39;0m> [K[17:46:41] [Server thread/WARN] [FML]: Missing English translation for chunkpregenerator: assets/chunkpregenerator/lang/en_us.lang 
[39;0m> [K[17:46:41] [Server thread/WARN] [FML]: Missing English translation for codechickenlib: assets/codechickenlib/lang/en_us.lang 
[39;0m> [K[17:46:41] [Server thread/WARN] [FML]: Missing English translation for cofhcore: assets/cofhcore/lang/en_us.lang 
[39;0m> [K[17:46:41] [Server thread/WARN] [FML]: Missing English translation for craftstudioapi: assets/craftstudioapi/lang/en_us.lang 
[39;0m> [K[17:46:41] [Server thread/WARN] [FML]: Missing English translation for crafttweaker: assets/crafttweaker/lang/en_us.lang 
[39;0m> [K[17:46:41] [Server thread/WARN] [FML]: Missing English translation for crafttweakerjei: assets/crafttweakerjei/lang/en_us.lang 
[39;0m> [K[17:46:41] [Server thread/WARN] [FML]: Missing English translation for diethopper: assets/diethopper/lang/en_us.lang 
[39;0m> [K[17:46:41] [Server thread/WARN] [FML]: Missing English translation for discordintegration: assets/discordintegration/lang/en_us.lang 
[39;0m> [K[17:46:41] [Server thread/WARN] [FML]: Missing English translation for dummycore: assets/dummycore/lang/en_us.lang 
[39;0m> [K[17:46:41] [Server thread/WARN] [FML]: Missing English translation for equaldragons: assets/equaldragons/lang/en_us.lang 
[39;0m> [K[17:46:41] [Server thread/WARN] [FML]: Missing English translation for farseek: assets/farseek/lang/en_us.lang 
[39;0m> [K[17:46:41] [Server thread/WARN] [FML]: Missing English translation for fastleafdecay: assets/fastleafdecay/lang/en_us.lang 
[39;0m> [K[17:46:41] [Server thread/WARN] [FML]: Missing English translation for fasterladderclimbing: assets/fasterladderclimbing/lang/en_us.lang 
[39;0m> [K[17:46:41] [Server thread/WARN] [FML]: Missing English translation for fastbench: assets/fastbench/lang/en_us.lang 
[39;0m> [K[17:46:41] [Server thread/WARN] [FML]: Missing English translation for fencejumper: assets/fencejumper/lang/en_us.lang 
[39;0m> [K[17:46:41] [Server thread/WARN] [FML]: Missing English translation for foamfix: assets/foamfix/lang/en_us.lang 
[39;0m> [K[17:46:41] [Server thread/WARN] [FML]: Missing English translation for grandeconomy: assets/grandeconomy/lang/en_us.lang 
[39;0m> [K[17:46:41] [Server thread/WARN] [FML]: Missing English translation for grandexchange: assets/grandexchange/lang/en_us.lang 
[39;0m> [K[17:46:41] [Server thread/WARN] [FML]: Missing English translation for harvestables: assets/harvestables/lang/en_us.lang 
[39;0m> [K[17:46:41] [Server thread/WARN] [FML]: Missing English translation for helpfixer: assets/helpfixer/lang/en_us.lang 
[39;0m> [K[17:46:41] [Server thread/WARN] [FML]: Missing English translation for instantunify: assets/instantunify/lang/en_us.lang 
[39;0m> [K[17:46:41] [Server thread/WARN] [FML]: Missing English translation for jeid: assets/jeid/lang/en_us.lang 
[39;0m> [K[17:46:41] [Server thread/WARN] [FML]: Missing English translation for jmh: assets/jmh/lang/en_us.lang 
[39;0m> [K[17:46:41] [Server thread/WARN] [FML]: Missing English translation for laggoggles: assets/laggoggles/lang/en_us.lang 
[39;0m> [K[17:46:41] [Server thread/WARN] [FML]: Missing English translation for librarianliblate: assets/librarianliblate/lang/en_us.lang 
[39;0m> [K[17:46:41] [Server thread/WARN] [FML]: Missing English translation for lunatriuscore: assets/lunatriuscore/lang/en_us.lang 
[39;0m> [K[17:46:41] [Server thread/WARN] [FML]: Missing English translation for mantle: assets/mantle/lang/en_us.lang 
[39;0m> [K[17:46:41] [Server thread/WARN] [FML]: Missing English translation for mtrm: assets/mtrm/lang/en_us.lang 
[39;0m> [K[17:46:41] [Server thread/WARN] [FML]: Missing English translation for morpheus: assets/morpheus/lang/en_us.lang 
[39;0m> [K[17:46:41] [Server thread/WARN] [FML]: Missing English translation for tinkersoc: assets/tinkersoc/lang/en_us.lang 
[39;0m> [K[17:46:41] [Server thread/WARN] [FML]: Missing English translation for opendisks: assets/opendisks/lang/en_us.lang 
[39;0m> [K[17:46:41] [Server thread/WARN] [FML]: Missing English translation for placebo: assets/placebo/lang/en_us.lang 
[39;0m> [K[17:46:41] [Server thread/WARN] [FML]: Missing English translation for redstoneflux: assets/redstoneflux/lang/en_us.lang 
[39;0m> [K[17:46:41] [Server thread/WARN] [FML]: Missing English translation for forgelin: assets/forgelin/lang/en_us.lang 
[39;0m> [K[17:46:41] [Server thread/WARN] [FML]: Missing English translation for streams: assets/streams/lang/en_us.lang 
[39;0m> [K[17:46:41] [Server thread/WARN] [FML]: Missing English translation for terracart: assets/terracart/lang/en_us.lang 
[39;0m> [K[17:46:41] [Server thread/WARN] [FML]: Missing English translation for trackapi: assets/trackapi/lang/en_us.lang 
[39;0m> [K[17:46:41] [Server thread/WARN] [FML]: Missing English translation for tramplestopper: assets/tramplestopper/lang/en_us.lang 
[39;0m> [K[17:46:41] [Server thread/WARN] [FML]: Missing English translation for tweakersconstruct: assets/tweakersconstruct/lang/en_us.lang 
[39;0m> [K[17:46:41] [Server thread/WARN] [FML]: Missing English translation for underphangables: assets/underphangables/lang/en_us.lang 
[39;0m> [K[17:46:41] [Server thread/WARN] [FML]: Missing English translation for unidict: assets/unidict/lang/en_us.lang 
[39;0m> [K[17:46:41] [Server thread/WARN] [FML]: Missing English translation for worldedit: assets/worldedit/lang/en_us.lang 
[39;0m> [K[17:46:41] [Server thread/WARN] [FML]: Missing English translation for blockout: assets/blockout/lang/en_us.lang 
[39;0m> [K[17:46:41] [Server thread/WARN] [FML]: Missing English translation for techreborn_compat: assets/techreborn_compat/lang/en_us.lang 
[39;0m> [K[17:46:41] [Server thread/INFO] [FML]: FML has found a non-mod file aopalliance-1.0.jar in your mods directory. It will now be injected into your classpath. This could severe stability issues, it should be removed if possible. 
> [K[17:46:41] [Server thread/INFO] [FML]: FML has found a non-mod file block-drops-jei-addon.jar in your mods directory. It will now be injected into your classpath. This could severe stability issues, it should be removed if possible. 
> [K[17:46:41] [Server thread/INFO] [FML]: FML has found a non-mod file charset-transport-carts-and-rails.jar in your mods directory. It will now be injected into your classpath. This could severe stability issues, it should be removed if possible. 
> [K[17:46:41] [Server thread/INFO] [FML]: FML has found a non-mod file ctm.jar in your mods directory. It will now be injected into your classpath. This could severe stability issues, it should be removed if possible. 
> [K[17:46:41] [Server thread/INFO] [FML]: FML has found a non-mod file guava-21.0.jar in your mods directory. It will now be injected into your classpath. This could severe stability issues, it should be removed if possible. 
> [K[17:46:41] [Server thread/INFO] [FML]: FML has found a non-mod file guice-4.2.1.jar in your mods directory. It will now be injected into your classpath. This could severe stability issues, it should be removed if possible. 
> [K[17:46:41] [Server thread/INFO] [FML]: FML has found a non-mod file item-scroller.jar in your mods directory. It will now be injected into your classpath. This could severe stability issues, it should be removed if possible. 
> [K[17:46:41] [Server thread/INFO] [FML]: FML has found a non-mod file javax.inject-1.jar in your mods directory. It will now be injected into your classpath. This could severe stability issues, it should be removed if possible. 
> [K[17:46:41] [Server thread/INFO] [FML]: FML has found a non-mod file jei-villagers.jar in your mods directory. It will now be injected into your classpath. This could severe stability issues, it should be removed if possible. 
> [K[17:46:41] [Server thread/INFO] [FML]: FML has found a non-mod file just-enough-resources-jer.jar in your mods directory. It will now be injected into your classpath. This could severe stability issues, it should be removed if possible. 
> [K[17:46:41] [Server thread/INFO] [FML]: FML has found a non-mod file kryo-4.0.2.jar in your mods directory. It will now be injected into your classpath. This could severe stability issues, it should be removed if possible. 
> [K[17:46:41] [Server thread/INFO] [FML]: FML has found a non-mod file MathParser.org-mXparser-4.0.0.jar in your mods directory. It will now be injected into your classpath. This could severe stability issues, it should be removed if possible. 
> [K[17:46:41] [Server thread/INFO] [FML]: FML has found a non-mod file minlog-1.3.0.jar in your mods directory. It will now be injected into your classpath. This could severe stability issues, it should be removed if possible. 
> [K[17:46:41] [Server thread/INFO] [FML]: FML has found a non-mod file mp3spi-1.9.5-1.jar in your mods directory. It will now be injected into your classpath. This could severe stability issues, it should be removed if possible. 
> [K[17:46:41] [Server thread/INFO] [FML]: FML has found a non-mod file objenesis-2.5.1.jar in your mods directory. It will now be injected into your classpath. This could severe stability issues, it should be removed if possible. 
> [K[17:46:41] [Server thread/INFO] [FML]: FML has found a non-mod file reflectasm-1.11.3.jar in your mods directory. It will now be injected into your classpath. This could severe stability issues, it should be removed if possible. 
> [K[17:46:41] [Server thread/INFO] [FML]: FML has found a non-mod file thaumcraft-6-aspects-for-jei.jar in your mods directory. It will now be injected into your classpath. This could severe stability issues, it should be removed if possible. 
> [K[17:46:41] [Server thread/INFO] [FML]: FML has found a non-mod file thaumic-jei.jar in your mods directory. It will now be injected into your classpath. This could severe stability issues, it should be removed if possible. 
> [K[17:46:41] [Server thread/INFO] [FML]: FML has found a non-mod file vorbisspi-1.0.3-1.jar in your mods directory. It will now be injected into your classpath. This could severe stability issues, it should be removed if possible. 
> [K[17:46:41] [Server thread/INFO] [FML]: FML has found a non-mod file blockout-main-1.12.2-2.0.12-ALPHA.jar in your mods directory. It will now be injected into your classpath. This could severe stability issues, it should be removed if possible. 
> [K[17:46:41] [Server thread/INFO] [FML]: FML has found a non-mod file blockout-json-1.12.2-2.0.12-ALPHA.jar in your mods directory. It will now be injected into your classpath. This could severe stability issues, it should be removed if possible. 
> [K[17:46:41] [Server thread/INFO] [FML]: FML has found a non-mod file JVoxelizer-1.0.0-RELEASE-api.jar in your mods directory. It will now be injected into your classpath. This could severe stability issues, it should be removed if possible. 
> [K[17:46:41] [Server thread/INFO] [FML]: FML has found a non-mod file JVoxelizer-1.0.0-RELEASE-forge-1.12.jar in your mods directory. It will now be injected into your classpath. This could severe stability issues, it should be removed if possible. 
> [K[17:46:41] [Server thread/INFO] [FML]: FML has found a non-mod file blockout-api-1.12.2-2.0.12-ALPHA.jar in your mods directory. It will now be injected into your classpath. This could severe stability issues, it should be removed if possible. 
> [K[17:46:41] [Server thread/INFO] [FML]: FML has found a non-mod file gigaherz.commons-1.12.1-0.6.4.jar in your mods directory. It will now be injected into your classpath. This could severe stability issues, it should be removed if possible. 
> [K[17:46:43] [Server thread/INFO] [FML]: Attempting connection with missing mods inecraft, mcp, FML, forge, foamfixcore, obfuscate, opencomputers|core, randompatches, gottagofast, techguns_core, acintegration, abyssalcraft, animania, appleskin, armoryexpansion, armoryexpansion-conarm, armoryexpansion-custommaterials, armoryexpansion-iceandfire, astralsorcery, autoreglib, backpacks16840, badwithernocookiereloaded, baubles, bedpatch, betterbuilderswands, bibliocraft, bigbeautifulbuttons, binniecore, botany, binniedesign, extrabees, extratrees, genetics, bookshelf, bookworm, botania, caliper, cctweaked, computercraft, chameleon, charset, chisel, chiselsandbits, chunkpregenerator, codechickenlib, cofhworld, cofhcore, colossalchests, comforts, compactdrawers, conarm, tombstone, cosmeticarmorreworked, cosmeticbeds, craftingtweaks, craftstudioapi, crafttweaker, crafttweakerjei, cucumber, customnpcs, cyclopscore, diamondglass, diethopper, dimensionalcake, dirtdeco, discordintegration, dynamictreestc, dummycore, dynamictrees, eplus, enderstorage, endertanks, equaldragons, excompressum, exnihilocreatio, exactspawn, extrarails, fairylights, farseek, fastleafdecay, fasterladderclimbing, fastbench, fencejumper, flopper, foamfix, forestry, fossil, ftbquests, ftbutilities, ftblib, furenikusroads, furnaceoverhaul, giacomosfoundry, grandeconomy, grandexchange, growablecells, guideapi, harvestables, helpfixer, hopperducts, iceandfire, immersivecables, immersivepetroleum, immersiverailroading, immersivetech, igwmod, instantunify, inventorytweaks, ironbackpacks, ironjetpacks, itemfilters, jei, jeid, journeymap, jepb, jmh, laggoggles, landlust, levelup2, leverbuttonlights, librarianliblate, librarianlib, lunatriuscore, magipsi, mantle, mekanism, metalchests, mtrm, moartinkers, morebeautifulbuttons, morebeautifulplates, morpheus, cfm, vehicle, multipiston, naturescompass, notenoughscaffold, elevatorid, tinkersoc, opencomputers, opendisks, openfm, openprinter, opensecurity, oreexcavation, placebo, psi, rpsideas, rangedpumps, reborncore, rebornstorage, redstoneflux, redstonepaste, refinedstorageaddons, refinedstorage, roleplaycraft, rusticthaumaturgy, rustic, securitycraft, forgelin, shadowmc, flammpfeil.slashblade, soulbottle, stackie, stevescarts, recipehandler, storagedrawers, storagetech, streams, techguns, techreborn, terracart, thaumcraft, thaumcomp, thaumicgrid, thermalcultivation, thermaldynamics, thermalfoundation, thermalinnovation, thermalsolars, thermalexpansion, tinker_io, tinkersaddons, tinkerscompendium, tcomplement, tconstruct, tinkersjei, tinkertoolleveling, tinymobfarm, toroquest, trackapi, tramplestopper, tweakersconstruct, underphangables, unidict, vanillafix, vanillafoodpantry, wanionlib, waystones, witherskelefix, worldedit, blockout, immersiveengineering, gbook, techreborn_compat, shetiphiancore, structurize, minecolonies, llibrary] at CLIENT 
> [K[17:46:43] [Server thread/INFO] [FML]: Attempting connection with missing mods inecraft, mcp, FML, forge, foamfixcore, obfuscate, opencomputers|core, randompatches, gottagofast, techguns_core, acintegration, abyssalcraft, animania, appleskin, armoryexpansion, armoryexpansion-conarm, armoryexpansion-custommaterials, armoryexpansion-iceandfire, astralsorcery, autoreglib, backpacks16840, badwithernocookiereloaded, baubles, bedpatch, betterbuilderswands, bibliocraft, bigbeautifulbuttons, binniecore, botany, binniedesign, extrabees, extratrees, genetics, bookshelf, bookworm, botania, caliper, cctweaked, computercraft, chameleon, charset, chisel, chiselsandbits, chunkpregenerator, codechickenlib, cofhworld, cofhcore, colossalchests, comforts, compactdrawers, conarm, tombstone, cosmeticarmorreworked, cosmeticbeds, craftingtweaks, craftstudioapi, crafttweaker, crafttweakerjei, cucumber, customnpcs, cyclopscore, diamondglass, diethopper, dimensionalcake, dirtdeco, discordintegration, dynamictreestc, dummycore, dynamictrees, eplus, enderstorage, endertanks, equaldragons, excompressum, exnihilocreatio, exactspawn, extrarails, fairylights, farseek, fastleafdecay, fasterladderclimbing, fastbench, fencejumper, flopper, foamfix, forestry, fossil, ftbquests, ftbutilities, ftblib, furenikusroads, furnaceoverhaul, giacomosfoundry, grandeconomy, grandexchange, growablecells, guideapi, harvestables, helpfixer, hopperducts, iceandfire, immersivecables, immersivepetroleum, immersiverailroading, immersivetech, igwmod, instantunify, inventorytweaks, ironbackpacks, ironjetpacks, itemfilters, jei, jeid, journeymap, jepb, jmh, laggoggles, landlust, levelup2, leverbuttonlights, librarianliblate, librarianlib, lunatriuscore, magipsi, mantle, mekanism, metalchests, mtrm, moartinkers, morebeautifulbuttons, morebeautifulplates, morpheus, cfm, vehicle, multipiston, naturescompass, notenoughscaffold, elevatorid, tinkersoc, opencomputers, opendisks, openfm, openprinter, opensecurity, oreexcavation, placebo, psi, rpsideas, rangedpumps, reborncore, rebornstorage, redstoneflux, redstonepaste, refinedstorageaddons, refinedstorage, roleplaycraft, rusticthaumaturgy, rustic, securitycraft, forgelin, shadowmc, flammpfeil.slashblade, soulbottle, stackie, stevescarts, recipehandler, storagedrawers, storagetech, streams, techguns, techreborn, terracart, thaumcraft, thaumcomp, thaumicgrid, thermalcultivation, thermaldynamics, thermalfoundation, thermalinnovation, thermalsolars, thermalexpansion, tinker_io, tinkersaddons, tinkerscompendium, tcomplement, tconstruct, tinkersjei, tinkertoolleveling, tinymobfarm, toroquest, trackapi, tramplestopper, tweakersconstruct, underphangables, unidict, vanillafix, vanillafoodpantry, wanionlib, waystones, witherskelefix, worldedit, blockout, immersiveengineering, gbook, techreborn_compat, shetiphiancore, structurize, minecolonies, llibrary] at SERVER 
> [K[17:46:45] [Server thread/INFO] [Astral Core]: [AstralTransformer] Transforming pa : net.minecraft.network.NetHandlerPlayServer with 1 patches! 
> [K[17:46:45] [Server thread/INFO] [Astral Core]: [AstralTransformer] Applied patch PATCHSERVEREXTENDENTITYINTERACTREACH 
> [K[17:46:45] [Server thread/INFO] [Gotta Go Fast]: patching net.minecraft.network.NetHandlerPlayServer.processVehicleMove(CPacketVehicleMove) 
> [K[17:46:45] [Server thread/ERROR] [Gotta Go Fast]: Couldn't find the vehicle constant instruction to modify :( 
[39;0m> [K[17:46:45] [Server thread/ERROR] [Gotta Go Fast]: Please report this 
[39;0m> [K[17:46:45] [Server thread/INFO] [Gotta Go Fast]: patching net.minecraft.network.NetHandlerPlayServer.processPlayer(CPacketPlayer) 
> [K[17:46:45] [Server thread/ERROR] [Gotta Go Fast]: Couldn't find the elytra constant instruction to modify :( 
[39;0m> [K[17:46:45] [Server thread/ERROR] [Gotta Go Fast]: Please report this 
[39;0m> [K[17:46:45] [Server thread/ERROR] [Gotta Go Fast]: Couldn't find the player constant instruction to modify :( 
[39;0m> [K[17:46:45] [Server thread/ERROR] [Gotta Go Fast]: Please report this 
[39;0m> [K[17:46:45] [Server thread/ERROR] [Gotta Go Fast]: Couldn't find the processPlayer method (or any of its patch targets) to patch :( 
[39;0m> [K[17:46:45] [Server thread/ERROR] [Gotta Go Fast]: Please report this 
[39;0m> [K[17:46:45] [Server thread/ERROR] [Gotta Go Fast]: Couldn't find the processVehicleMove method (or any of its patch targets) to patch :( 
[39;0m> [K[17:46:45] [Server thread/ERROR] [Gotta Go Fast]: Please report this 
[39;0m> [K[17:46:45] [Server thread/INFO] [Astral Core]: [AstralTransformer] Transforming thaumcraft.common.lib.events.PlayerEvents : thaumcraft.common.lib.events.PlayerEvents with 1 patches! 
> [K[17:46:45] [Server thread/INFO] [Astral Core]: [AstralTransformer] Applied patch PATCHRUNICSHIELDINGHOOK 
> [K[17:46:45] [Server thread/INFO] [BedPatch]: Patching Chunk 
> [K[17:46:45] [Server thread/INFO] [STDOUT]: [pl.asie.patchy.helpers.ConstructorReplacingTransformer$FFMethodVisitor:visitTypeInsn:73]: Replaced NEW for net/minecraft/util/ClassInheritanceMultiMap to pl/asie/foamfix/coremod/common/FoamyClassInheritanceMultiMap 
> [K[17:46:45] [Server thread/INFO] [STDOUT]: [pl.asie.patchy.helpers.ConstructorReplacingTransformer$FFMethodVisitor:visitMethodInsn:85]: Replaced INVOKESPECIAL for net/minecraft/util/ClassInheritanceMultiMap to pl/asie/foamfix/coremod/common/FoamyClassInheritanceMultiMap 
> [K[17:46:52] [Server thread/INFO] [Pulsar-tconstruct]: Skipping Pulse wailaIntegration; missing dependency: waila 
> [K[17:46:52] [Server thread/INFO] [Pulsar-tconstruct]: Skipping Pulse theoneprobeIntegration; missing dependency: theoneprobe 
> [K[17:46:52] [Server thread/INFO] [tconstruct]: Preparing to take over the world 
> [K[17:47:00] [Server thread/INFO] [STDOUT]: [pl.asie.foamfix.coremod.FoamFixTransformer:spliceClasses:137]: Spliced in METHOD: net.minecraftforge.common.property.ExtendedBlockState.createState 
> [K[17:47:05] [Server thread/INFO] [Pulsar-tcomplement]: Skipping Pulse CeramicsPlugin; missing dependency: ceramics 
> [K[17:47:06] [Server thread/INFO] [FML]: Processing ObjectHolder annotations 
> [K[17:47:07] [Server thread/INFO] [FML]: Found 1885 ObjectHolder annotations 
> [K[17:47:07] [Server thread/INFO] [FML]: Identifying ItemStackHolder annotations 
> [K[17:47:07] [Server thread/INFO] [FML]: Found 7 ItemStackHolder annotations 
> [K[17:47:07] [Server thread/INFO] [FML]: Configured a dormant chunk cache size of 0 
> [K[17:47:07] [Forge Version Check/INFO] [forge.VersionCheck]: [vanillafoodpantry] Starting version check at http://jwaresoftware.org/files/mcmods/versions/vanillafoodpantry.json 
> [K[17:47:07] [Server thread/INFO] [pl.asie.charset.ModCharset]: Charset profile is STABLE 
> [K[17:47:07] [Server thread/INFO] [pl.asie.charset.ModCharset]: Module lib.wires requires mod:mcmultipart, but is not force-enabled. You can ignore this - it is not an error, just information. 
> [K[17:47:08] [Server thread/INFO] [pl.asie.charset.ModCharset]: Charset material heuristics time (phase 1): 22ms 
> [K[17:47:08] [Forge Version Check/INFO] [forge.VersionCheck]: [vanillafoodpantry] Found status: AHEAD Target: null 
> [K[17:47:08] [Forge Version Check/INFO] [forge.VersionCheck]: [enderstorage] Starting version check at http://chickenbones.net/Files/notification/version.php?query=forge&version=1.12&file=EnderStorage 
> [K[17:47:08] [Forge Version Check/INFO] [forge.VersionCheck]: [enderstorage] Found status: BETA Target: null 
> [K[17:47:08] [Forge Version Check/INFO] [forge.VersionCheck]: [gbook] Starting version check at https://raw.githubusercontent.com/gigaherz/guidebook/master/update.json 
> [K[17:47:08] [Forge Version Check/INFO] [forge.VersionCheck]: [gbook] Found status: OUTDATED Target: 2.9.1 
> [K[17:47:08] [Forge Version Check/INFO] [forge.VersionCheck]: [thermalinnovation] Starting version check at https://raw.github.com/cofh/version/master/thermalinnovation_update.json 
> [K[17:47:08] [Forge Version Check/INFO] [forge.VersionCheck]: [thermalinnovation] Found status: UP_TO_DATE Target: null 
> [K[17:47:08] [Forge Version Check/INFO] [forge.VersionCheck]: [forge] Starting version check at http://files.minecraftforge.net/maven/net/minecraftforge/forge/promotions_slim.json 
> [K[17:47:09] [Forge Version Check/INFO] [forge.VersionCheck]: [forge] Found status: OUTDATED Target: 14.23.5.2837 
> [K[17:47:09] [Forge Version Check/INFO] [forge.VersionCheck]: [shetiphiancore] Starting version check at https://gist.githubusercontent.com/ShetiPhian/5a4332ca6221ae61ab3c6d531a989f21/raw/ShetiPhianCore 
> [K[17:47:09] [Forge Version Check/INFO] [forge.VersionCheck]: [cofhcore] Starting version check at https://raw.github.com/cofh/version/master/cofhcore_update.json 
> [K[17:47:09] [Forge Version Check/INFO] [forge.VersionCheck]: [cofhcore] Found status: UP_TO_DATE Target: null 
> [K[17:47:09] [Forge Version Check/INFO] [forge.VersionCheck]: [thermalexpansion] Starting version check at https://raw.github.com/cofh/version/master/thermalexpansion_update.json 
> [K[17:47:09] [Forge Version Check/INFO] [forge.VersionCheck]: [thermalexpansion] Found status: UP_TO_DATE Target: null 
> [K[17:47:09] [Forge Version Check/INFO] [forge.VersionCheck]: [abyssalcraft] Starting version check at https://raw.githubusercontent.com/Shinoow/AbyssalCraft/master/version.json 
> [K[17:47:09] [Forge Version Check/INFO] [forge.VersionCheck]: [abyssalcraft] Found status: UP_TO_DATE Target: null 
> [K[17:47:09] [Forge Version Check/INFO] [forge.VersionCheck]: [randompatches] Starting version check at https://raw.githubusercontent.com/TheRandomLabs/RandomPatches/misc/versions.json 
> [K[17:47:09] [Forge Version Check/INFO] [forge.VersionCheck]: [tombstone] Starting version check at https://raw.githubusercontent.com/Corail31/tombstone_lite/master/update.json 
> [K[17:47:09] [Forge Version Check/INFO] [forge.VersionCheck]: [tombstone] Found status: OUTDATED Target: 3.4.0 
> [K[17:47:09] [Forge Version Check/INFO] [forge.VersionCheck]: [jeid] Starting version check at https://gist.githubusercontent.com/Runemoro/67b1d8d31af58e9d35410ef60b2017c3/raw/1fe08a6c45a1f481a8a2a8c71e52d4245dcb7713/jeid_update.json
> [K[17:47:09] [Forge Version Check/INFO] [forge.VersionCheck]: [jeid] Found status: AHEAD Target: null 
> [K[17:47:09] [Forge Version Check/INFO] [forge.VersionCheck]: etalchests] Starting version check at https://raw.githubusercontent.com/T145/metalchests/master/update.json 
> [K[17:47:09] [Forge Version Check/INFO] [forge.VersionCheck]: etalchests] Found status: UP_TO_DATE Target: null 
> [K[17:47:09] [Forge Version Check/INFO] [forge.VersionCheck]: [thermalcultivation] Starting version check at https://raw.github.com/cofh/version/master/thermalcultivation_update.json 
> [K[17:47:09] [Forge Version Check/INFO] [forge.VersionCheck]: [thermalcultivation] Found status: UP_TO_DATE Target: null 
> [K[17:47:09] [Forge Version Check/INFO] [forge.VersionCheck]: [cofhworld] Starting version check at https://raw.github.com/cofh/version/master/cofhworld_update.json 
> [K[17:47:09] [Forge Version Check/INFO] [forge.VersionCheck]: [cofhworld] Found status: AHEAD Target: null 
> [K[17:47:09] [Forge Version Check/INFO] [forge.VersionCheck]: [immersiveengineering] Starting version check at https://raw.githubusercontent.com/BluSunrize/ImmersiveEngineering/master/changelog.json 
> [K[17:47:09] [Forge Version Check/INFO] [forge.VersionCheck]: [immersiveengineering] Found status: UP_TO_DATE Target: null 
> [K[17:47:09] [Forge Version Check/INFO] [forge.VersionCheck]: [thermalfoundation] Starting version check at https://raw.github.com/cofh/version/master/thermalfoundation_update.json 
> [K[17:47:09] [Forge Version Check/INFO] [forge.VersionCheck]: [thermalfoundation] Found status: UP_TO_DATE Target: null 
> [K[17:47:09] [Forge Version Check/INFO] [forge.VersionCheck]: [opensecurity] Starting version check at http://modupdates.pc-logix.com/opensecurity 
> [K[17:47:10] [Forge Version Check/INFO] [forge.VersionCheck]: [opensecurity] Found status: AHEAD Target: null 
> [K[17:47:10] [Forge Version Check/INFO] [forge.VersionCheck]: [securitycraft] Starting version check at https://www.github.com/Geforce132/SecurityCraft/raw/master/Updates/Forge.json 
> [K[17:47:10] [Forge Version Check/INFO] [forge.VersionCheck]: [securitycraft] Found status: UP_TO_DATE Target: null 
> [K[17:47:10] [Forge Version Check/INFO] [forge.VersionCheck]: [thermaldynamics] Starting version check at https://raw.github.com/cofh/version/master/thermaldynamics_update.json 
> [K[17:47:10] [Forge Version Check/INFO] [forge.VersionCheck]: [thermaldynamics] Found status: UP_TO_DATE Target: null 
> [K[17:47:10] [Forge Version Check/INFO] [forge.VersionCheck]: [llibrary] Starting version check at https://gist.githubusercontent.com/gegy1000/a6639456aeb8edd92cbf7cbfcf9d65d9/raw/llibrary_updates.json 
> [K[17:47:10] [Forge Version Check/INFO] [forge.VersionCheck]: [llibrary] Found status: AHEAD Target: null 
> [K[17:47:10] [Forge Version Check/INFO] [forge.VersionCheck]: [fastleafdecay] Starting version check at http://www.olafkeijsers.net/fastleafdecay-update.json 
> [K[17:47:10] [Forge Version Check/INFO] [forge.VersionCheck]: [fastleafdecay] Found status: UP_TO_DATE Target: null 
> [K[17:47:10] [Forge Version Check/INFO] [forge.VersionCheck]: [craftstudioapi] Starting version check at https://leviathan-studio.com/craftstudioapi/update.json 
> [K[17:47:10] [Forge Version Check/INFO] [forge.VersionCheck]: [craftstudioapi] Found status: OUTDATED Target: 1.0.1.95-alpha 
> [K[17:47:10] [Forge Version Check/INFO] [forge.VersionCheck]: [techguns] Starting version check at https://raw.githubusercontent.com/pWn3d1337/Techguns2/master/update.json 
> [K[17:47:10] [Forge Version Check/INFO] [forge.VersionCheck]: [techguns] Found status: UP_TO_DATE Target: null 
> [K[17:47:10] [Forge Version Check/INFO] [forge.VersionCheck]: [shadowmc] Starting version check at https://update.shadowfacts.net/shadowmc 
> [K[17:47:10] [Server thread/INFO] [AbyssalCraft]: Starting the Integration Handler. 
> [K[17:47:10] [Forge Version Check/INFO] [forge.VersionCheck]: [acintegration] Starting version check at https://raw.githubusercontent.com/Shinoow/AbyssalCraft-Integration/master/version.json 
> [K[17:47:10] [Server thread/INFO] [AbyssalCraft]: Preliminary integration search complete: found 6 possible mod integration(s)! 
> [K[17:47:10] [Forge Version Check/INFO] [forge.VersionCheck]: [acintegration] Found status: UP_TO_DATE Target: null 
> [K[17:47:10] [Forge Version Check/INFO] [forge.VersionCheck]: [charset] Starting version check at http://charset.asie.pl/update.json 
> [K[17:47:10] [Server thread/INFO] [FML]: Applying holder lookups 
> [K[17:47:11] [Server thread/INFO] [FML]: Holder lookups applied 
> [K[17:47:11] [Forge Version Check/INFO] [forge.VersionCheck]: [charset] Found status: UP_TO_DATE Target: null 
> [K[17:47:11] [Forge Version Check/INFO] [forge.VersionCheck]: [endertanks] Starting version check at https://gist.githubusercontent.com/ShetiPhian/5a4332ca6221ae61ab3c6d531a989f21/raw/EnderTanks 
> [K[17:47:11] [Forge Version Check/INFO] [forge.VersionCheck]: [refinedstorage] Starting version check at https://refinedstorage.raoulvdberge.com/update 
> [K[17:47:12] [Forge Version Check/INFO] [forge.VersionCheck]: [refinedstorage] Found status: UP_TO_DATE Target: null 
> [K[17:47:12] [Forge Version Check/INFO] [forge.VersionCheck]: [vanillafix] Starting version check at https://gist.githubusercontent.com/Runemoro/28e8cf4c24a5f17f508a5d34f66d229f/raw/vanillafix_update.json
> [K[17:47:12] [Forge Version Check/INFO] [forge.VersionCheck]: [vanillafix] Found status: AHEAD Target: null 
> [K[17:47:12] [Forge Version Check/INFO] [forge.VersionCheck]: [codechickenlib] Starting version check at http://chickenbones.net/Files/notification/version.php?query=forge&version=1.12&file=CodeChickenLib 
> [K[17:47:12] [Forge Version Check/INFO] [forge.VersionCheck]: [codechickenlib] Found status: BETA Target: null 
> [K[17:47:14] [Server thread/INFO] [STDOUT]: [com.animania.common.handler.EntityHandler:getBiomes:701]: LUSH biome type not found. Please review valid Biome Types in BiomeDictionary. 
> [K[17:47:14] [Server thread/INFO] [STDOUT]: [com.animania.common.handler.EntityHandler:getBiomes:701]: LUSH biome type not found. Please review valid Biome Types in BiomeDictionary. 
> [K[17:47:14] [Server thread/INFO] [STDOUT]: [com.animania.common.handler.EntityHandler:getBiomes:701]: MAGICAL biome type not found. Please review valid Biome Types in BiomeDictionary. 
> [K[17:47:15] [Server thread/WARN] [FML]: Potentially Dangerous alternative prefix `minecraft` for name `tileentitytrough`, expected `animania`. This could be a intended override, but in most cases indicates a broken mod. 
[39;0m> [K[17:47:15] [Server thread/WARN] [FML]: Potentially Dangerous alternative prefix `minecraft` for name `tileentitynest`, expected `animania`. This could be a intended override, but in most cases indicates a broken mod. 
[39;0m> [K[17:47:15] [Server thread/WARN] [FML]: Potentially Dangerous alternative prefix `minecraft` for name `tileentityinvisiblock`, expected `animania`. This could be a intended override, but in most cases indicates a broken mod. 
[39;0m> [K[17:47:15] [Server thread/WARN] [FML]: Potentially Dangerous alternative prefix `minecraft` for name `tileentityhamsterwheel`, expected `animania`. This could be a intended override, but in most cases indicates a broken mod. 
[39;0m> [K[17:47:15] [Server thread/WARN] [FML]: Potentially Dangerous alternative prefix `minecraft` for name `tileentitycheesemold`, expected `animania`. This could be a intended override, but in most cases indicates a broken mod. 
[39;0m> [K[17:47:15] [Server thread/WARN] [FML]: Potentially Dangerous alternative prefix `minecraft` for name `tileentitysaltlick`, expected `animania`. This could be a intended override, but in most cases indicates a broken mod. 
[39;0m> [K[17:47:15] [Server thread/WARN] [FML]: Potentially Dangerous alternative prefix `minecraft` for name `tileentityhive`, expected `animania`. This could be a intended override, but in most cases indicates a broken mod. 
[39;0m> [K[17:47:16] [Server thread/INFO] [Ice And Fire]: A raven flies from the north to the sea 
> [K[17:47:16] [Server thread/INFO] [Ice And Fire]: A dragon whispers her name in the east 
> [K[17:47:16] [Server thread/INFO] [armoryexpansion-iceandfire]: Registered tinker's material {leatherfrosttroll}; 
> [K[17:47:16] [Server thread/INFO] [armoryexpansion-iceandfire]: Registered tinker's material {chitindesertmyrmex}; 
> [K[17:47:16] [Server thread/INFO] [armoryexpansion-iceandfire]: Registered tinker's material {chitintandeathworm}; 
> [K[17:47:16] [Server thread/INFO] [armoryexpansion-iceandfire]: Registered tinker's material {chitinjunglemyrmex}; 
> [K[17:47:16] [Server thread/INFO] [armoryexpansion-iceandfire]: Registered tinker's material {scalebronzedragon}; 
> [K[17:47:16] [Server thread/INFO] [armoryexpansion-iceandfire]: Registered tinker's material {scaleblueseaserpent}; 
> [K[17:47:16] [Server thread/INFO] [armoryexpansion-iceandfire]: Registered tinker's material {scalepurpleseaserpent}; 
> [K[17:47:16] [Server thread/INFO] [armoryexpansion-iceandfire]: Registered tinker's material {scalewhitedragon}; 
> [K[17:47:16] [Server thread/INFO] [armoryexpansion-iceandfire]: Registered tinker's material {chitinwhitedeathworm}; 
> [K[17:47:16] [Server thread/INFO] [armoryexpansion-iceandfire]: Registered tinker's material {chitinbrowndeathworm}; 
> [K[17:47:16] [Server thread/INFO] [armoryexpansion-iceandfire]: Registered tinker's material {scalegraydragon}; 
> [K[17:47:16] [Server thread/INFO] [armoryexpansion-iceandfire]: Registered tinker's material {scalesapphiredragon}; 
> [K[17:47:16] [Server thread/INFO] [armoryexpansion-iceandfire]: Registered tinker's material {scaletealseaserpent}; 
> [K[17:47:16] [Server thread/INFO] [armoryexpansion-iceandfire]: Registered tinker's material {scalebluedragon}; 
> [K[17:47:16] [Server thread/INFO] [armoryexpansion-iceandfire]: Registered tinker's material {leatherforesttroll}; 
> [K[17:47:16] [Server thread/INFO] [armoryexpansion-iceandfire]: Registered tinker's material {bonedragon}; 
> [K[17:47:16] [Server thread/INFO] [armoryexpansion-iceandfire]: Registered tinker's material {scalegreendragon}; 
> [K[17:47:16] [Server thread/INFO] [armoryexpansion-iceandfire]: Registered tinker's material {leathermountaintroll}; 
> [K[17:47:16] [Server thread/INFO] [armoryexpansion-iceandfire]: Registered tinker's material {scalebronzeseaserpent}; 
> [K[17:47:16] [Server thread/INFO] [armoryexpansion-iceandfire]: Registered tinker's material {scalereddragon}; 
> [K[17:47:16] [Server thread/INFO] [armoryexpansion-iceandfire]: Registered tinker's material {scaledeepblueseaserpent}; 
> [K[17:47:16] [Server thread/INFO] [armoryexpansion-iceandfire]: Registered tinker's material {scaleredseaserpent}; 
> [K[17:47:16] [Server thread/INFO] [armoryexpansion-iceandfire]: Registered tinker's material {scalegreenseaserpent}; 
> [K[17:47:16] [Server thread/INFO] [armoryexpansion-iceandfire]: Registered tinker's material {scalesilverdragon}; 
> [K[17:47:16] [Server thread/INFO] [armoryexpansion-iceandfire]: Registered stats for tinker's material {leatherfrosttroll}; 
> [K[17:47:16] [Server thread/INFO] [armoryexpansion-iceandfire]: Registered stats for tinker's material {chitindesertmyrmex}; 
> [K[17:47:16] [Server thread/INFO] [armoryexpansion-iceandfire]: Registered stats for tinker's material {chitintandeathworm}; 
> [K[17:47:16] [Server thread/INFO] [armoryexpansion-iceandfire]: Registered stats for tinker's material {chitinjunglemyrmex}; 
> [K[17:47:16] [Server thread/INFO] [armoryexpansion-iceandfire]: Registered stats for tinker's material {scalebronzedragon}; 
> [K[17:47:16] [Server thread/INFO] [armoryexpansion-iceandfire]: Registered stats for tinker's material {scaleblueseaserpent}; 
> [K[17:47:16] [Server thread/INFO] [armoryexpansion-iceandfire]: Registered stats for tinker's material {scalepurpleseaserpent}; 
> [K[17:47:16] [Server thread/INFO] [armoryexpansion-iceandfire]: Registered stats for tinker's material {scalewhitedragon}; 
> [K[17:47:16] [Server thread/INFO] [armoryexpansion-iceandfire]: Registered stats for tinker's material {chitinwhitedeathworm}; 
> [K[17:47:16] [Server thread/INFO] [armoryexpansion-iceandfire]: Registered stats for tinker's material {chitinbrowndeathworm}; 
> [K[17:47:16] [Server thread/INFO] [armoryexpansion-iceandfire]: Registered stats for tinker's material {scalegraydragon}; 
> [K[17:47:16] [Server thread/INFO] [armoryexpansion-iceandfire]: Registered stats for tinker's material {scalesapphiredragon}; 
> [K[17:47:16] [Server thread/INFO] [armoryexpansion-iceandfire]: Registered stats for tinker's material {scaletealseaserpent}; 
> [K[17:47:16] [Server thread/INFO] [armoryexpansion-iceandfire]: Registered stats for tinker's material {scalebluedragon}; 
> [K[17:47:16] [Server thread/INFO] [armoryexpansion-iceandfire]: Registered stats for tinker's material {leatherforesttroll}; 
> [K[17:47:16] [Server thread/INFO] [armoryexpansion-iceandfire]: Registered stats for tinker's material {bonedragon}; 
> [K[17:47:16] [Server thread/INFO] [armoryexpansion-iceandfire]: Registered stats for tinker's material {scalegreendragon}; 
> [K[17:47:16] [Server thread/INFO] [armoryexpansion-iceandfire]: Registered stats for tinker's material {leathermountaintroll}; 
> [K[17:47:16] [Server thread/INFO] [armoryexpansion-iceandfire]: Registered stats for tinker's material {scalebronzeseaserpent}; 
> [K[17:47:16] [Server thread/INFO] [armoryexpansion-iceandfire]: Registered stats for tinker's material {scalereddragon}; 
> [K[17:47:16] [Server thread/INFO] [armoryexpansion-iceandfire]: Registered stats for tinker's material {scaledeepblueseaserpent}; 
> [K[17:47:16] [Server thread/INFO] [armoryexpansion-iceandfire]: Registered stats for tinker's material {scaleredseaserpent}; 
> [K[17:47:16] [Server thread/INFO] [armoryexpansion-iceandfire]: Registered stats for tinker's material {scalegreenseaserpent}; 
> [K[17:47:16] [Server thread/INFO] [armoryexpansion-iceandfire]: Registered stats for tinker's material {scalesilverdragon}; 
> [K[17:47:20] [Server thread/INFO] [Astral Core]: [AstralTransformer] Transforming wh : net.minecraft.entity.ai.attributes.ModifiableAttributeInstance with 1 patches! 
> [K[17:47:20] [Server thread/INFO] [Astral Core]: [AstralTransformer] Applied patch PATCHPOSTPROCESSATTRIBUTES 
> [K[17:47:20] [Server thread/INFO] [Astral Sorcery]: Crafttweaker found! Adding recipe handlers... 
> [K[17:47:20] [Server thread/INFO] [betterbuilderswands]: Access transform success createStackedBlock (func_180643_i). 
> [K[17:47:21] [Server thread/INFO] [reborncore]: Pre loaded registries in 752ms 
> [K[17:47:21] [Server thread/INFO] [reborncore]: Loaded registrys for reborncore.common.registration.RegistryConstructionEvent in 136ms 
> [K[17:47:21] [Server thread/INFO] [reborncore]: Loaded power manager from: ForgePowerManager 
> [K[17:47:21] [Server thread/INFO] [reborncore]: Loaded module: BaublesCompat 
> [K[17:47:21] [Server thread/INFO] [reborncore]: Loaded module: CraftTweakerCompat 
> [K[17:47:21] [Server thread/INFO] [reborncore]: Loaded module: RecipeImmersiveEngineering 
> [K[17:47:21] [Server thread/INFO] [reborncore]: Loaded module: MekanismCompat 
> [K[17:47:21] [Server thread/INFO] [reborncore]: Loaded module: CompatOpenComputers 
> [K[17:47:21] [Server thread/INFO] [reborncore]: Loaded module: RecipeThermalExpansion 
> [K[17:47:21] [Server thread/INFO] [reborncore]: Loaded registrys for net.minecraftforge.fml.common.event.FMLPreInitializationEvent in 31ms 
> [K[17:47:22] [Server thread/INFO] [techreborn]: TechReborns Blocks Loaded 
> [K[17:47:22] [Server thread/INFO] [techreborn]: TechReborns Items Loaded 
> [K[17:47:22] [Server thread/INFO] [techreborn]: PreInitialization Complete 
> [K[17:47:23] [Server thread/INFO] [forestry]: Module BuildCraft 6 Statements Module failed to load: Compatible BuildCraftAPI|statements version not found 
> [K[17:47:23] [Server thread/INFO] [forestry]: Module Extra Utilities Module failed to load: Extra Utilities not found 
> [K[17:47:23] [Server thread/INFO] [forestry]: Module Mystical Agriculture Module failed to load: Mystical Agriculture not found 
> [K[17:47:23] [Server thread/INFO] [forestry]: Module BuildCraft 6 Recipes Module failed to load: Compatible BuildCraftAPI|recipes version not found 
> [K[17:47:23] [Server thread/INFO] [forestry]: Module Actually Additions Module failed to load: Actually Additions not found 
> [K[17:47:23] [Server thread/INFO] [forestry]: Module IndustrialCraft2 Module failed to load: IndustrialCraft2 not found 
> [K[17:47:23] [Server thread/INFO] [forestry]: Module Better With Mods Module failed to load: Better With Mods not found 
> [K[17:47:23] [Server thread/INFO] [forestry]: Module BiomesOPlenty Module failed to load: BiomesOPlenty not found 
> [K[17:47:23] [Server thread/INFO] [forestry]: Module EnderIO Module failed to load: EnderIO not found 
> [K[17:47:23] [Server thread/INFO] [forestry]: Module BuildCraft 6 Transport Module failed to load: buildcrafttransport not found 
> [K[17:47:23] [Server thread/INFO] [forestry]: Module HarvestCraft Module failed to load: HarvestCraft not found 
> [K[17:47:23] [Server thread/INFO] [forestry]: Module Roots Module failed to load: Roots not found 
> [K[17:47:23] [Server thread/INFO] [forestry]: Module Natura Module failed to load: Natura not found 
> [K[17:47:23] [Server thread/INFO] [forestry]: Module BuildCraft 6 Fuels Module failed to load: Compatible BuildCraftAPI|fuels version not found 
> [K[17:47:27] [Server thread/WARN] [FML]: Potentially Dangerous alternative prefix `minecraft` for name `botany.tile.ceramic`, expected `botany`. This could be a intended override, but in most cases indicates a broken mod. 
[39;0m> [K[17:47:27] [Server thread/WARN] [FML]: Potentially Dangerous alternative prefix `minecraft` for name `botany.tile.ceramicbrick`, expected `botany`. This could be a intended override, but in most cases indicates a broken mod. 
[39;0m> [K[17:47:27] [Server thread/WARN] [FML]: Potentially Dangerous alternative prefix `minecraft` for name `botany.tile.flower`, expected `botany`. This could be a intended override, but in most cases indicates a broken mod. 
[39;0m> [K[17:47:28] [Server thread/WARN] [FML]: Potentially Dangerous alternative prefix `minecraft` for name `extrabees.tile.alveary`, expected `extrabees`. This could be a intended override, but in most cases indicates a broken mod. 
[39;0m> [K[17:47:28] [Server thread/WARN] [FML]: Potentially Dangerous alternative prefix `minecraft` for name `binnie.tile.nursery`, expected `extratrees`. This could be a intended override, but in most cases indicates a broken mod. 
[39;0m> [K[17:47:28] [Server thread/WARN] [FML]: Potentially Dangerous alternative prefix `minecraft` for name `mod.chiselsandbits.tileentitychiseled`, expected `chiselsandbits`. This could be a intended override, but in most cases indicates a broken mod. 
[39;0m> [K[17:47:28] [Server thread/WARN] [FML]: Potentially Dangerous alternative prefix `minecraft` for name `mod.chiselsandbits.tileentitychiseled.tesr`, expected `chiselsandbits`. This could be a intended override, but in most cases indicates a broken mod. 
[39;0m> [K[17:47:28] [Server thread/WARN] [FML]: Potentially Dangerous alternative prefix `minecraft` for name `mod.chiselsandbits.tileentitybittank`, expected `chiselsandbits`. This could be a intended override, but in most cases indicates a broken mod. 
[39;0m> [K[17:47:29] [Server thread/INFO] [FML]: Made the Pregenerator ThreadSave 
> [K[17:47:29] [Server thread/INFO] [CoFH World]: Registering default Feature Templates... 
> [K[17:47:29] [Server thread/INFO] [CoFH World]: Registering default World Generators... 
> [K[17:47:29] [Server thread/INFO] [CoFH World]: Verifying or creating base world generation directory... 
> [K[17:47:29] [Server thread/INFO] [CoFH World]: Complete. 
> [K[17:47:29] [Server thread/INFO] orpheus]: Loading configuration 
> [17:47:30][FINE/CustomNPCs][noppes.npcs.LogWriter:71] Fri May 10 17:47:30 CEST 2019 
[17:47:30][FINE/CustomNPCs][noppes.npcs.controllers.ScriptController:66] Script Engines Available: 
[K[17:47:30] [Server thread/WARN] [FML]: Potentially Dangerous alternative prefix `minecraft` for name `hopper`, expected `diethopper`. This could be a intended override, but in most cases indicates a broken mod. 
[39;0m> [K[17:47:30] [Server thread/WARN] [FML]: Potentially Dangerous alternative prefix `minecraft` for name `species_tile_entity`, expected `dynamictrees`. This could be a intended override, but in most cases indicates a broken mod. 
[39;0m> [K[17:47:30] [Server thread/WARN] [FML]: Potentially Dangerous alternative prefix `minecraft` for name `bonsai_tile_entity`, expected `dynamictrees`. This could be a intended override, but in most cases indicates a broken mod. 
[39;0m> [K[17:47:32] [Server thread/WARN] [FML]: Potentially Dangerous alternative prefix `minecraft` for name `ender chest`, expected `enderstorage`. This could be a intended override, but in most cases indicates a broken mod. 
[39;0m> [K[17:47:32] [Server thread/WARN] [FML]: Potentially Dangerous alternative prefix `minecraft` for name `ender tank`, expected `enderstorage`. This could be a intended override, but in most cases indicates a broken mod. 
[39;0m> [K[17:47:32] [Server thread/WARN] [FTB Library]: Replacing com.feed_the_beast.ftblib.lib.config.DefaultRankConfigHandler with com.feed_the_beast.ftbutilities.ranks.FTBUtilitiesPermissionHandler 
[39;0m> [K[17:47:33] [Server thread/INFO] [FML]: [FasterLadderClimbing] Module featureloader is enabled 
> [K[17:47:33] [Server thread/INFO] [STDOUT]: [pl.asie.foamfix.ProxyCommon:preInit:79]: minecraft:hopper 
> [K[17:47:33] [Server thread/INFO] [foamfix]: Removing LaunchWrapper package manifest map... 
> [K[17:47:34] [Server thread/INFO] [fossils]: Started Tinkers integration for FossilsArcheology 
> [K[17:47:34] [Server thread/WARN] [FML]: Potentially Dangerous alternative prefix `tconstruct` for name `enderference`, expected `fossil`. This could be a intended override, but in most cases indicates a broken mod. 
[39;0m> [K[17:47:34] [Server thread/WARN] [FML]: Potentially Dangerous alternative prefix `tconstruct` for name `insatiable`, expected `fossil`. This could be a intended override, but in most cases indicates a broken mod. 
[39;0m> [K[17:47:34] [Server thread/WARN] [FML]: Potentially Dangerous alternative prefix `tconstruct` for name `magnetic`, expected `fossil`. This could be a intended override, but in most cases indicates a broken mod. 
[39;0m> [K[17:47:34] [Server thread/WARN] [FML]: Potentially Dangerous alternative prefix `tconstruct` for name `momentum`, expected `fossil`. This could be a intended override, but in most cases indicates a broken mod. 
[39;0m> [K[17:47:34] [Server thread/WARN] [FML]: Potentially Dangerous alternative prefix `tconstruct` for name `dot`, expected `fossil`. This could be a intended override, but in most cases indicates a broken mod. 
[39;0m> [K[17:47:34] [Server thread/WARN] [FML]: Potentially Dangerous alternative prefix `tconstruct` for name `splinter`, expected `fossil`. This could be a intended override, but in most cases indicates a broken mod. 
[39;0m> [K[17:47:34] [Server thread/INFO] [fossils]: Archaean horizon 
> [K[17:47:34] [Server thread/INFO] [fossils]: The first sunrise 
> [K[17:47:34] [Server thread/INFO] [fossils]: On a pristine Gaea 
> [K[17:47:34] [Server thread/INFO] [fossils]: Opus perfectum 
> [K[17:47:34] [Server thread/INFO] [fossils]: Somewhere there, us sleeping 
> [K[17:47:34] [Server thread/WARN] [FML]: Replacing net.minecraftforge.server.permission.DefaultPermissionHandler with com.feed_the_beast.ftbutilities.ranks.FTBUtilitiesPermissionHandler 
[39;0m> [K[17:47:35] [Server thread/INFO] [furenikusroads]: REGISTRATION COMPLETE! 19 lines, 20 icons, 40 letters, 36 texts, 37 junctions. 
> [K[17:47:36] [Server thread/INFO] [growablecells]: Refined Storage support loaded. 
> [K[17:47:40] [Immersive Engineering Contributors Thread/INFO] [immersiveengineering]: Attempting to download special revolvers from GitHub 
> [K[17:47:40] [Server thread/INFO] [immersiverailroading]: Loading stock rolling_stock/locomotives/a1_peppercorn.json 
> [K[17:47:41] [Server thread/INFO] [immersiverailroading]: Loading stock rolling_stock/locomotives/big_boy.json 
> [K[17:47:43] [Server thread/INFO] [immersiverailroading]: Loading stock rolling_stock/locomotives/k4_pacific.json 
> [K[17:47:45] [Server thread/INFO] [immersiverailroading]: Loading stock rolling_stock/locomotives/e6_atlantic.json 
> [K[17:47:46] [Server thread/INFO] [immersiverailroading]: Loading stock rolling_stock/locomotives/a5_switcher.json 
> [K[17:47:47] [Server thread/INFO] [immersiverailroading]: Loading stock rolling_stock/locomotives/class_38.json 
> [K[17:47:49] [Server thread/INFO] [immersiverailroading]: Loading stock rolling_stock/locomotives/rodgers_460.json 
> [K[17:47:49] [Server thread/INFO] [immersiverailroading]: Loading stock rolling_stock/locomotives/skookum.json 
> [K[17:47:50] [Server thread/INFO] [immersiverailroading]: Loading stock rolling_stock/locomotives/br01.json 
> [K[17:47:51] [Server thread/INFO] [immersiverailroading]: Loading stock rolling_stock/locomotives/cooke_mogul.json 
> [K[17:47:52] [Server thread/INFO] [immersiverailroading]: Loading stock rolling_stock/locomotives/k36.json 
> [K[17:47:53] [Server thread/INFO] [immersiverailroading]: Loading stock rolling_stock/locomotives/firefly.json 
> [K[17:47:53] [Server thread/INFO] [immersiverailroading]: Loading stock rolling_stock/locomotives/iron_duke.json 
> [K[17:47:53] [Server thread/INFO] [immersiverailroading]: Loading stock rolling_stock/locomotives/ge_40_ton_boxcab.json 
> [K[17:47:53] [Server thread/INFO] [immersiverailroading]: Loading stock rolling_stock/locomotives/ge_b40_8.json 
> [K[17:47:54] [Server thread/INFO] [immersiverailroading]: Loading stock rolling_stock/locomotives/ge_b40_8w.json 
> [K[17:47:54] [Server thread/INFO] [immersiverailroading]: Loading stock rolling_stock/locomotives/ge_c44_9cw.json 
> [K[17:47:56] [Server thread/INFO] [immersiverailroading]: Loading stock rolling_stock/locomotives/emd_sd40-2.json 
> [K[17:47:57] [Server thread/INFO] [immersiverailroading]: Loading stock rolling_stock/locomotives/emd_sw1500.json 
> [K[17:47:57] [Server thread/INFO] [immersiverailroading]: Loading stock rolling_stock/locomotives/alco_rs1.json 
> [K[17:47:58] [Server thread/INFO] [immersiverailroading]: Loading stock rolling_stock/tender/a1_peppercorn_tender.json 
> [K[17:47:58] [Server thread/INFO] [immersiverailroading]: Loading stock rolling_stock/tender/big_boy_tender.json 
> [K[17:47:59] [Server thread/INFO] [immersiverailroading]: Loading stock rolling_stock/tender/k4_tender.json 
> [K[17:47:59] [Server thread/INFO] [immersiverailroading]: Loading stock rolling_stock/tender/e6_tender.json 
> [K[17:47:59] [Server thread/INFO] [immersiverailroading]: Loading stock rolling_stock/tender/a5_tender.json 
> [K[17:47:59] [Server thread/INFO] [immersiverailroading]: Loading stock rolling_stock/tender/class_38_tender.json 
> [K[17:48:00] [Server thread/INFO] [immersiverailroading]: Loading stock rolling_stock/tender/rodgers_460_tender.json 
> [K[17:48:00] [Server thread/INFO] [immersiverailroading]: Loading stock rolling_stock/tender/skookum_tender.json 
> [K[17:48:00] [Server thread/INFO] [immersiverailroading]: Loading stock rolling_stock/tender/br01_tender.json 
> [K[17:48:00] [Server thread/INFO] [immersiverailroading]: Loading stock rolling_stock/tender/cooke_tender.json 
> [K[17:48:00] [Server thread/INFO] [immersiverailroading]: Loading stock rolling_stock/tender/k36_tender.json 
> [K[17:48:00] [Server thread/INFO] [immersiverailroading]: Loading stock rolling_stock/passenger/br_coach_mk1.json 
> [K[17:48:01] [Server thread/INFO] [immersiverailroading]: Loading stock rolling_stock/passenger/b70baggage.json 
> [K[17:48:01] [Server thread/INFO] [immersiverailroading]: Loading stock rolling_stock/passenger/p70coach1.json 
> [K[17:48:02] [Server thread/INFO] [immersiverailroading]: Loading stock rolling_stock/freight/boxcar_x26.json 
> [K[17:48:02] [Server thread/INFO] [immersiverailroading]: Loading stock rolling_stock/freight/usra_boxcar_classrr40.json 
> [K[17:48:02] [Server thread/INFO] [immersiverailroading]: Loading stock rolling_stock/freight/70t_hopper_slsf.json 
> [K[17:48:02] [Server thread/INFO] [immersiverailroading]: Loading stock rolling_stock/freight/attx_flatcar_1.json 
> [K[17:48:03] [Server thread/INFO] [immersiverailroading]: Loading stock rolling_stock/freight/dw_gondola.json 
> [K[17:48:03] [Server thread/INFO] [immersiverailroading]: Loading stock rolling_stock/freight/prr_flatcar_1.json 
> [K[17:48:04] [Server thread/INFO] [immersiverailroading]: Loading stock rolling_stock/freight/usra_hopper_55t.json 
> [K[17:48:04] [Server thread/INFO] [immersiverailroading]: Loading stock rolling_stock/freight/n5c_cabin_car.json 
> [K[17:48:04] [Server thread/INFO] [immersiverailroading]: Loading stock rolling_stock/freight/russell_snow_plow.json 
> [K[17:48:04] [Server thread/INFO] [immersiverailroading]: Loading stock rolling_stock/freight/drgw_3000class_boxcar.json 
> [K[17:48:04] [Server thread/INFO] [immersiverailroading]: Loading stock rolling_stock/freight/drgw_1000class_gondola.json 
> [K[17:48:05] [Server thread/INFO] [immersiverailroading]: Loading stock rolling_stock/freight/drgw_5500class_stockcar.json 
> [K[17:48:06] [Server thread/INFO] [immersiverailroading]: Loading stock rolling_stock/freight/drgw_rail_and_tie_outfit.json 
> [K[17:48:06] [Server thread/INFO] [immersiverailroading]: Loading stock rolling_stock/freight/waycar.json 
> [K[17:48:06] [Server thread/INFO] [immersiverailroading]: Loading stock rolling_stock/tank/tank_us2.json 
> [K[17:48:06] [Server thread/INFO] [immersiverailroading]: Loading stock rolling_stock/tank/kamx_t.json 
> [K[17:48:06] [Server thread/INFO] [immersiverailroading]: Loading stock rolling_stock/tank/slag_car_1.json 
> [K[17:48:07] [Server thread/INFO] [immersiverailroading]: Loading stock rolling_stock/hand_car/hand_car_1.json 
> [K[17:48:07] [Server thread/INFO] [immersiverailroading]: Generating heightmap rolling_stock/locomotives/a1_peppercorn.json 
> [K[17:48:07] [Server thread/INFO] [immersiverailroading]: Generating heightmap rolling_stock/locomotives/big_boy.json 
> [K[17:48:08] [Server thread/INFO] [immersiverailroading]: Generating heightmap rolling_stock/locomotives/k4_pacific.json 
> [K[17:48:08] [Server thread/INFO] [immersiverailroading]: Generating heightmap rolling_stock/locomotives/e6_atlantic.json 
> [K[17:48:08] [Server thread/INFO] [immersiverailroading]: Generating heightmap rolling_stock/locomotives/a5_switcher.json 
> [K[17:48:08] [Server thread/INFO] [immersiverailroading]: Generating heightmap rolling_stock/locomotives/class_38.json 
> [K[17:48:08] [Server thread/INFO] [immersiverailroading]: Generating heightmap rolling_stock/locomotives/rodgers_460.json 
> [K[17:48:08] [Server thread/INFO] [immersiverailroading]: Generating heightmap rolling_stock/locomotives/skookum.json 
> [K[17:48:08] [Server thread/INFO] [immersiverailroading]: Generating heightmap rolling_stock/locomotives/br01.json 
> [K[17:48:08] [Server thread/INFO] [immersiverailroading]: Generating heightmap rolling_stock/locomotives/cooke_mogul.json 
> [K[17:48:09] [Server thread/INFO] [immersiverailroading]: Generating heightmap rolling_stock/locomotives/k36.json 
> [K[17:48:09] [Server thread/INFO] [immersiverailroading]: Generating heightmap rolling_stock/locomotives/firefly.json 
> [K[17:48:09] [Server thread/INFO] [immersiverailroading]: Generating heightmap rolling_stock/locomotives/iron_duke.json 
> [K[17:48:09] [Server thread/INFO] [immersiverailroading]: Generating heightmap rolling_stock/locomotives/ge_40_ton_boxcab.json 
> [K[17:48:09] [Server thread/INFO] [immersiverailroading]: Generating heightmap rolling_stock/locomotives/ge_b40_8.json 
> [K[17:48:09] [Server thread/INFO] [immersiverailroading]: Generating heightmap rolling_stock/locomotives/ge_b40_8w.json 
> [K[17:48:09] [Server thread/INFO] [immersiverailroading]: Generating heightmap rolling_stock/locomotives/ge_c44_9cw.json 
> [K[17:48:09] [Server thread/INFO] [immersiverailroading]: Generating heightmap rolling_stock/locomotives/emd_sd40-2.json 
> [K[17:48:09] [Server thread/INFO] [immersiverailroading]: Generating heightmap rolling_stock/locomotives/emd_sw1500.json 
> [K[17:48:09] [Server thread/INFO] [immersiverailroading]: Generating heightmap rolling_stock/locomotives/alco_rs1.json 
> [K[17:48:09] [Server thread/INFO] [immersiverailroading]: Generating heightmap rolling_stock/tender/a1_peppercorn_tender.json 
> [K[17:48:09] [Server thread/INFO] [immersiverailroading]: Generating heightmap rolling_stock/tender/big_boy_tender.json 
> [K[17:48:10] [Server thread/INFO] [immersiverailroading]: Generating heightmap rolling_stock/tender/k4_tender.json 
> [K[17:48:10] [Server thread/INFO] [immersiverailroading]: Generating heightmap rolling_stock/tender/e6_tender.json 
> [K[17:48:10] [Server thread/INFO] [immersiverailroading]: Generating heightmap rolling_stock/tender/a5_tender.json 
> [K[17:48:10] [Server thread/INFO] [immersiverailroading]: Generating heightmap rolling_stock/tender/class_38_tender.json 
> [K[17:48:10] [Server thread/INFO] [immersiverailroading]: Generating heightmap rolling_stock/tender/rodgers_460_tender.json 
> [K[17:48:10] [Server thread/INFO] [immersiverailroading]: Generating heightmap rolling_stock/tender/skookum_tender.json 
> [K[17:48:10] [Server thread/INFO] [immersiverailroading]: Generating heightmap rolling_stock/tender/br01_tender.json 
> [K[17:48:10] [Server thread/INFO] [immersiverailroading]: Generating heightmap rolling_stock/tender/cooke_tender.json 
> [K[17:48:10] [Server thread/INFO] [immersiverailroading]: Generating heightmap rolling_stock/tender/k36_tender.json 
> [K[17:48:10] [Server thread/INFO] [immersiverailroading]: Generating heightmap rolling_stock/passenger/br_coach_mk1.json 
> [K[17:48:10] [Server thread/INFO] [immersiverailroading]: Generating heightmap rolling_stock/passenger/b70baggage.json 
> [K[17:48:10] [Server thread/INFO] [immersiverailroading]: Generating heightmap rolling_stock/passenger/p70coach1.json 
> [K[17:48:10] [Server thread/INFO] [immersiverailroading]: Generating heightmap rolling_stock/freight/boxcar_x26.json 
> [K[17:48:10] [Server thread/INFO] [immersiverailroading]: Generating heightmap rolling_stock/freight/usra_boxcar_classrr40.json 
> [K[17:48:10] [Server thread/INFO] [immersiverailroading]: Generating heightmap rolling_stock/freight/70t_hopper_slsf.json 
> [K[17:48:10] [Server thread/INFO] [immersiverailroading]: Generating heightmap rolling_stock/freight/attx_flatcar_1.json 
> [K[17:48:10] [Server thread/INFO] [immersiverailroading]: Generating heightmap rolling_stock/freight/dw_gondola.json 
> [K[17:48:10] [Server thread/INFO] [immersiverailroading]: Generating heightmap rolling_stock/freight/prr_flatcar_1.json 
> [K[17:48:10] [Server thread/INFO] [immersiverailroading]: Generating heightmap rolling_stock/freight/usra_hopper_55t.json 
> [K[17:48:10] [Server thread/INFO] [immersiverailroading]: Generating heightmap rolling_stock/freight/n5c_cabin_car.json 
> [K[17:48:10] [Server thread/INFO] [immersiverailroading]: Generating heightmap rolling_stock/freight/russell_snow_plow.json 
> [K[17:48:10] [Server thread/INFO] [immersiverailroading]: Generating heightmap rolling_stock/freight/drgw_3000class_boxcar.json 
> [K[17:48:10] [Server thread/INFO] [immersiverailroading]: Generating heightmap rolling_stock/freight/drgw_1000class_gondola.json 
> [K[17:48:10] [Server thread/INFO] [immersiverailroading]: Generating heightmap rolling_stock/freight/drgw_5500class_stockcar.json 
> [K[17:48:10] [Server thread/INFO] [immersiverailroading]: Generating heightmap rolling_stock/freight/drgw_rail_and_tie_outfit.json 
> [K[17:48:10] [Server thread/INFO] [immersiverailroading]: Generating heightmap rolling_stock/freight/waycar.json 
> [K[17:48:10] [Server thread/INFO] [immersiverailroading]: Generating heightmap rolling_stock/tank/tank_us2.json 
> [K[17:48:10] [Server thread/INFO] [immersiverailroading]: Generating heightmap rolling_stock/tank/kamx_t.json 
> [K[17:48:10] [Server thread/INFO] [immersiverailroading]: Generating heightmap rolling_stock/tank/slag_car_1.json 
> [K[17:48:10] [Server thread/INFO] [immersiverailroading]: Generating heightmap rolling_stock/hand_car/hand_car_1.json 
> [K[17:48:10] [Server thread/INFO] [immersiverailroading]: Loading Track immersiverailroading:track/default.json 
> [K[17:48:11] [Server thread/INFO] [immersiverailroading]: Loading Track immersiverailroading:track/concrete.json 
> [K[17:48:11] [Server thread/INFO] [immersiverailroading]: Loading Track immersiverailroading:track/railsonly.json 
> [K[17:48:11] [Server thread/INFO] [laggoggles]: Registered sided proxy for: Dedicated server 
> [K[17:48:12] [Server thread/INFO] [Mekanica]: Didn't detect MCMP, ignoring compatibility package 
> [K[17:48:12] [Server thread/WARN] [FML]: Potentially Dangerous alternative prefix `tconstruct` for name `endermagnetic`, expected `moartinkers`. This could be a intended override, but in most cases indicates a broken mod. 
[39;0m> [K[17:48:13] [Server thread/WARN] inecraft/EntityDataManager]: defineId called for: class net.minecraft.entity.player.EntityPlayer from class com.mrcrayfish.vehicle.common.CommonEvents 
[39;0m> [K[17:48:13] [Server thread/WARN] inecraft/EntityDataManager]: defineId called for: class net.minecraft.entity.player.EntityPlayer from class com.mrcrayfish.vehicle.common.CommonEvents 
[39;0m> [K[17:48:13] [Server thread/WARN] inecraft/EntityDataManager]: defineId called for: class net.minecraft.entity.player.EntityPlayer from class com.mrcrayfish.vehicle.common.CommonEvents 
[39;0m> [K[17:48:14] [Server thread/INFO] [blockout]: Initializing JVoxelizer. 
> [K[17:48:16] [Server thread/WARN] [FML]: Potentially Dangerous alternative prefix `oc` for name `adapter`, expected `opencomputers`. This could be a intended override, but in most cases indicates a broken mod. 
[39;0m> [K[17:48:16] [Server thread/INFO] [OpenComputers]: Skipping interface ic2.api.energy.tile.IEnergySink from missing mod ic2. 
> [K[17:48:16] [Server thread/WARN] [FML]: Potentially Dangerous alternative prefix `oc` for name `assembler`, expected `opencomputers`. This could be a intended override, but in most cases indicates a broken mod. 
[39;0m> [K[17:48:16] [Server thread/WARN] [FML]: Potentially Dangerous alternative prefix `oc` for name `cable`, expected `opencomputers`. This could be a intended override, but in most cases indicates a broken mod. 
[39;0m> [K[17:48:16] [Server thread/WARN] [FML]: Potentially Dangerous alternative prefix `oc` for name `capacitor`, expected `opencomputers`. This could be a intended override, but in most cases indicates a broken mod. 
[39;0m> [K[17:48:16] [Server thread/WARN] [FML]: Potentially Dangerous alternative prefix `oc` for name `carpetedcapacitor`, expected `opencomputers`. This could be a intended override, but in most cases indicates a broken mod. 
[39;0m> [K[17:48:16] [Server thread/WARN] [FML]: Potentially Dangerous alternative prefix `oc` for name `case`, expected `opencomputers`. This could be a intended override, but in most cases indicates a broken mod. 
[39;0m> [K[17:48:16] [Server thread/WARN] [FML]: Potentially Dangerous alternative prefix `oc` for name `charger`, expected `opencomputers`. This could be a intended override, but in most cases indicates a broken mod. 
[39;0m> [K[17:48:16] [Server thread/WARN] [FML]: Potentially Dangerous alternative prefix `oc` for name `diskdrive`, expected `opencomputers`. This could be a intended override, but in most cases indicates a broken mod. 
[39;0m> [K[17:48:16] [Server thread/WARN] [FML]: Potentially Dangerous alternative prefix `oc` for name `disassembler`, expected `opencomputers`. This could be a intended override, but in most cases indicates a broken mod. 
[39;0m> [K[17:48:16] [Server thread/WARN] [FML]: Potentially Dangerous alternative prefix `oc` for name `keyboard`, expected `opencomputers`. This could be a intended override, but in most cases indicates a broken mod. 
[39;0m> [K[17:48:16] [Server thread/WARN] [FML]: Potentially Dangerous alternative prefix `oc` for name `hologram`, expected `opencomputers`. This could be a intended override, but in most cases indicates a broken mod. 
[39;0m> [K[17:48:16] [Server thread/WARN] [FML]: Potentially Dangerous alternative prefix `oc` for name `geolyzer`, expected `opencomputers`. This could be a intended override, but in most cases indicates a broken mod. 
[39;0m> [K[17:48:16] [Server thread/WARN] [FML]: Potentially Dangerous alternative prefix `oc` for name `microcontroller`, expected `opencomputers`. This could be a intended override, but in most cases indicates a broken mod. 
[39;0m> [K[17:48:17] [Server thread/WARN] [FML]: Potentially Dangerous alternative prefix `oc` for name `motionsensor`, expected `opencomputers`. This could be a intended override, but in most cases indicates a broken mod. 
[39;0m> [K[17:48:17] [Server thread/WARN] [FML]: Potentially Dangerous alternative prefix `oc` for name `netsplitter`, expected `opencomputers`. This could be a intended override, but in most cases indicates a broken mod. 
[39;0m> [K[17:48:17] [Server thread/WARN] [FML]: Potentially Dangerous alternative prefix `oc` for name `powerconverter`, expected `opencomputers`. This could be a intended override, but in most cases indicates a broken mod. 
[39;0m> [K[17:48:17] [Server thread/WARN] [FML]: Potentially Dangerous alternative prefix `oc` for name `powerdistributor`, expected `opencomputers`. This could be a intended override, but in most cases indicates a broken mod. 
[39;0m> [K[17:48:17] [Server thread/WARN] [FML]: Potentially Dangerous alternative prefix `oc` for name `print`, expected `opencomputers`. This could be a intended override, but in most cases indicates a broken mod. 
[39;0m> [K[17:48:17] [Server thread/WARN] [FML]: Potentially Dangerous alternative prefix `oc` for name `printer`, expected `opencomputers`. This could be a intended override, but in most cases indicates a broken mod. 
[39;0m> [K[17:48:17] [Server thread/WARN] [FML]: Potentially Dangerous alternative prefix `oc` for name `raid`, expected `opencomputers`. This could be a intended override, but in most cases indicates a broken mod. 
[39;0m> [K[17:48:17] [Server thread/WARN] [FML]: Potentially Dangerous alternative prefix `oc` for name `redstone`, expected `opencomputers`. This could be a intended override, but in most cases indicates a broken mod. 
[39;0m> [K[17:48:17] [Server thread/WARN] [FML]: Potentially Dangerous alternative prefix `oc` for name `relay`, expected `opencomputers`. This could be a intended override, but in most cases indicates a broken mod. 
[39;0m> [K[17:48:17] [Server thread/WARN] [FML]: Potentially Dangerous alternative prefix `oc` for name `robot`, expected `opencomputers`. This could be a intended override, but in most cases indicates a broken mod. 
[39;0m> [K[17:48:17] [Server thread/WARN] [FML]: Potentially Dangerous alternative prefix `oc` for name `screen`, expected `opencomputers`. This could be a intended override, but in most cases indicates a broken mod. 
[39;0m> [K[17:48:17] [Server thread/WARN] [FML]: Potentially Dangerous alternative prefix `oc` for name `rack`, expected `opencomputers`. This could be a intended override, but in most cases indicates a broken mod. 
[39;0m> [K[17:48:17] [Server thread/WARN] [FML]: Potentially Dangerous alternative prefix `oc` for name `transposer`, expected `opencomputers`. This could be a intended override, but in most cases indicates a broken mod. 
[39;0m> [K[17:48:17] [Server thread/WARN] [FML]: Potentially Dangerous alternative prefix `oc` for name `waypoint`, expected `opencomputers`. This could be a intended override, but in most cases indicates a broken mod. 
[39;0m> [K[17:48:17] [Server thread/INFO] [OpenComputers]: Skipping interface ic2.api.item.IBoxable from missing mod ic2. 
> [K[17:48:17] [Server thread/INFO] [OpenComputers]: Skipping interface ic2.api.item.ISpecialElectricItem from missing mod ic2. 
> [K[17:48:18] [Server thread/INFO] [opencomputers]: Initializing OpenComputers API. 
> [K[17:48:18] [Server thread/INFO] [opencomputers]: Found a compatible native library: 'OpenComputersMod-1.7.4.153-lua52-native.64.so'. 
> [K[17:48:18] [Server thread/INFO] [opencomputers]: Found a compatible native library: 'OpenComputersMod-1.7.4.153-lua53-native.64.so'. 
> [K[17:48:18] [Server thread/INFO] [opencomputers]: Done with pre init phase. 
> [K[17:48:18] [Server thread/INFO] [OpenComputers]: Successfully injected component logic into class pcl.OpenFM.TileEntity.TileEntityRadio. 
> [K[17:48:18] [Server thread/WARN] [FML]: Potentially Dangerous alternative prefix `minecraft` for name `openfmradio`, expected `openfm`. This could be a intended override, but in most cases indicates a broken mod. 
[39;0m> [K[17:48:18] [Server thread/WARN] [FML]: Potentially Dangerous alternative prefix `minecraft` for name `openfmspeaker`, expected `openfm`. This could be a intended override, but in most cases indicates a broken mod. 
[39;0m> [K[17:48:18] [Server thread/INFO] [openfm]: Registering BreakEvent 
> [K[17:48:18] [Server thread/WARN] [FML]: Potentially Dangerous alternative prefix `minecraft` for name `printerte`, expected `openprinter`. This could be a intended override, but in most cases indicates a broken mod. 
[39;0m> [K[17:48:18] [Server thread/WARN] [FML]: Potentially Dangerous alternative prefix `minecraft` for name `shredderte`, expected `openprinter`. This could be a intended override, but in most cases indicates a broken mod. 
[39;0m> [K[17:48:18] [Server thread/WARN] [FML]: Potentially Dangerous alternative prefix `minecraft` for name `filecabinette`, expected `openprinter`. This could be a intended override, but in most cases indicates a broken mod. 
[39;0m> [K[17:48:18] [Server thread/WARN] [FML]: Potentially Dangerous alternative prefix `minecraft` for name `reborn storagetilemulticrafter`, expected `rebornstorage`. This could be a intended override, but in most cases indicates a broken mod. 
[39;0m> [K[17:48:18] [Server thread/WARN] [FML]: Potentially Dangerous alternative prefix `minecraft` for name `reborn storagetileioport`, expected `rebornstorage`. This could be a intended override, but in most cases indicates a broken mod. 
[39;0m> [K[17:48:21] [Server thread/WARN] [FML]: Potentially Dangerous alternative prefix `minecraft` for name `assembler`, expected `stevescarts`. This could be a intended override, but in most cases indicates a broken mod. 
[39;0m> [K[17:48:21] [Server thread/WARN] [FML]: Potentially Dangerous alternative prefix `minecraft` for name `cargo`, expected `stevescarts`. This could be a intended override, but in most cases indicates a broken mod. 
[39;0m> [K[17:48:21] [Server thread/WARN] [FML]: Potentially Dangerous alternative prefix `minecraft` for name `liquid`, expected `stevescarts`. This could be a intended override, but in most cases indicates a broken mod. 
[39;0m> [K[17:48:21] [Server thread/WARN] [FML]: Potentially Dangerous alternative prefix `minecraft` for name `distributor`, expected `stevescarts`. This could be a intended override, but in most cases indicates a broken mod. 
[39;0m> [K[17:48:21] [Server thread/WARN] [FML]: Potentially Dangerous alternative prefix `minecraft` for name `activator`, expected `stevescarts`. This could be a intended override, but in most cases indicates a broken mod. 
[39;0m> [K[17:48:21] [Server thread/WARN] [FML]: Potentially Dangerous alternative prefix `minecraft` for name `detector`, expected `stevescarts`. This could be a intended override, but in most cases indicates a broken mod. 
[39;0m> [K[17:48:21] [Server thread/WARN] [FML]: Potentially Dangerous alternative prefix `minecraft` for name `upgrade`, expected `stevescarts`. This could be a intended override, but in most cases indicates a broken mod. 
[39;0m> [K[17:48:21] [Server thread/INFO] [stevescarts]: Loading plugins 
> [K[17:48:21] [Server thread/INFO] [stevescarts]: Found plugin candidate:vswe.stevescarts.compat.ic2.CompatIC2 
> [K[17:48:21] [Server thread/INFO] [stevescarts]: Plugin (vswe.stevescarts.compat.ic2.CompatIC2) was NOT loaded due to mod 'ic2' missing, this isn't an error 
> [K[17:48:21] [Server thread/INFO] [stevescarts]: Found plugin candidate:vswe.stevescarts.compat.techreborn.CompatTR 
> [K[17:48:21] [Server thread/INFO] [stevescarts]: Plugin vswe.stevescarts.compat.techreborn.CompatTR was found and has been initialized successfully! 
> [K[17:48:21] [Server thread/INFO] [stevescarts]: Found plugin candidate:vswe.stevescarts.compat.forestry.CompatForestry 
> [K[17:48:21] [Server thread/INFO] [stevescarts]: Plugin vswe.stevescarts.compat.forestry.CompatForestry was found and has been initialized successfully! 
> [K[17:48:21] [Server thread/INFO] [stevescarts]: Loaded 2 plugins 
> [K[17:48:22] [Server thread/INFO] [thaumcomp]: Done with preInit phase. 
> [K[17:48:24] [Server thread/INFO] [FML]: [ThermalSolars] ThermalSolars -------------- successfully Finished preInit 
> [K[17:48:25] [Server thread/WARN] inecraft/EntityDataManager]: defineId called for: class net.minecraft.entity.monster.EntityEnderman from class net.torocraft.toroquest.entities.EntityToroNpc 
[39;0m> [K[17:48:25] [Server thread/INFO] [VFP]: Starting[B] DS... 
> [K[17:48:28] [Server thread/INFO] [armoryexpansion-conarm]: Registered tinker's material {tanzinite}; 
> [K[17:48:28] [Server thread/INFO] [armoryexpansion-conarm]: Registered tinker's material {lapis}; 
> [K[17:48:28] [Server thread/INFO] [armoryexpansion-conarm]: Registered tinker's material {emerald}; 
> [K[17:48:28] [Server thread/INFO] [armoryexpansion-conarm]: Registered tinker's material {amethyst};
> [K[17:48:28] [Server thread/INFO] [armoryexpansion-conarm]: Registered tinker's material {quartz}; 
> [K[17:48:28] [Server thread/INFO] [armoryexpansion-conarm]: Registered tinker's material {amber}; 
> [K[17:48:28] [Server thread/INFO] [armoryexpansion-conarm]: Registered tinker's material {diamond}; 
> [K[17:48:28] [Server thread/INFO] [armoryexpansion-conarm]: Registered stats for tinker's material {orangecloth}; 
> [K[17:48:28] [Server thread/INFO] [armoryexpansion-conarm]: Registered stats for tinker's material {magentacloth}; 
> [K[17:48:28] [Server thread/INFO] [armoryexpansion-conarm]: Registered stats for tinker's material {whitecloth}; 
> [K[17:48:28] [Server thread/INFO] [armoryexpansion-conarm]: Registered stats for tinker's material {tanzinite}; 
> [K[17:48:28] [Server thread/INFO] [armoryexpansion-conarm]: Registered stats for tinker's material {pinkcloth}; 
> [K[17:48:28] [Server thread/INFO] [armoryexpansion-conarm]: Registered stats for tinker's material {platinum}; 
> [K[17:48:28] [Server thread/INFO] [armoryexpansion-conarm]: Registered stats for tinker's material {tungsten}; 
> [K[17:48:28] [Server thread/INFO] [armoryexpansion-conarm]: Registered stats for tinker's material {manasteel}; 
> [K[17:48:28] [Server thread/INFO] [armoryexpansion-conarm]: Registered stats for tinker's material {rubber}; 
> [K[17:48:28] [Server thread/INFO] [armoryexpansion-conarm]: Registered stats for tinker's material {tin}; 
> [K[17:48:28] [Server thread/INFO] [armoryexpansion-conarm]: Registered stats for tinker's material {redgarnet}; 
> [K[17:48:28] [Server thread/INFO] [armoryexpansion-conarm]: Registered stats for tinker's material {invar}; 
> [K[17:48:28] [Server thread/INFO] [armoryexpansion-conarm]: Registered stats for tinker's material {refinedglowstone}; 
> [K[17:48:28] [Server thread/INFO] [armoryexpansion-conarm]: Registered stats for tinker's material {lapis}; 
> [K[17:48:28] [Server thread/INFO] [armoryexpansion-conarm]: Registered stats for tinker's material {zinc}; 
> [K[17:48:28] [Server thread/INFO] [armoryexpansion-conarm]: Registered stats for tinker's material {ivorypsi}; 
> [K[17:48:28] [Server thread/INFO] [armoryexpansion-conarm]: Registered stats for tinker's material {terrasteel}; 
> [K[17:48:28] [Server thread/INFO] [armoryexpansion-conarm]: Registered stats for tinker's material {sapphire}; 
> [K[17:48:28] [Server thread/INFO] [armoryexpansion-conarm]: Registered stats for tinker's material {advancedalloy}; 
> [K[17:48:28] [Server thread/INFO] [armoryexpansion-conarm]: Registered stats for tinker's material {limecloth}; 
> [K[17:48:28] [Server thread/INFO] [armoryexpansion-conarm]: Registered stats for tinker's material {brass}; 
> [K[17:48:28] [Server thread/INFO] [armoryexpansion-conarm]: Registered stats for tinker's material {cyancloth}; 
> [K[17:48:28] [Server thread/INFO] [armoryexpansion-conarm]: Registered stats for tinker's material {abyssalnite}; 
> [K[17:48:28] [Server thread/INFO] [armoryexpansion-conarm]: Registered stats for tinker's material {refinediron}; 
> [K[17:48:28] [Server thread/INFO] [armoryexpansion-conarm]: Registered stats for tinker's material {yellowgarnet}; 
> [K[17:48:28] [Server thread/INFO] [armoryexpansion-conarm]: Registered stats for tinker's material {graycloth}; 
> [K[17:48:28] [Server thread/INFO] [armoryexpansion-conarm]: Registered stats for tinker's material {browncloth}; 
> [K[17:48:28] [Server thread/INFO] [armoryexpansion-conarm]: Registered stats for tinker's material {emerald}; 
> [K[17:48:28] [Server thread/INFO] [armoryexpansion-conarm]: Registered stats for tinker's material {silky}; 
> [K[17:48:28] [Server thread/INFO] [armoryexpansion-conarm]: Registered stats for tinker's material {gaia}; 
> [K[17:48:28] [Server thread/INFO] [armoryexpansion-conarm]: Registered stats for tinker's material {ebonypsi}; 
> [K[17:48:28] [Server thread/INFO] [armoryexpansion-conarm]: Registered stats for tinker's material {titanium}; 
> [K[17:48:28] [Server thread/INFO] [armoryexpansion-conarm]: Registered stats for tinker's material {psi}; 
> [K[17:48:28] [Server thread/INFO] [armoryexpansion-conarm]: Registered stats for tinker's material {refinedobsidian}; 
> [K[17:48:28] [Server thread/INFO] [armoryexpansion-conarm]: Registered stats for tinker's material {aluminum}; 
> [K[17:48:28] [Server thread/INFO] [armoryexpansion-conarm]: Registered stats for tinker's material {amethyst}; 
> [K[17:48:28] [Server thread/INFO] [armoryexpansion-conarm]: Registered stats for tinker's material {lightbluecloth}; 
> [K[17:48:28] [Server thread/INFO] [armoryexpansion-conarm]: Registered stats for tinker's material {redcloth}; 
> [K[17:48:28] [Server thread/INFO] [armoryexpansion-conarm]: Registered stats for tinker's material {iridium}; 
> [K[17:48:28] [Server thread/INFO] [armoryexpansion-conarm]: Registered stats for tinker's material {gold}; 
> [K[17:48:28] [Server thread/INFO] [armoryexpansion-conarm]: Registered stats for tinker's material {lumium}; 
> [K[17:48:28] [Server thread/INFO] [armoryexpansion-conarm]: Registered stats for tinker's material {enderium}; 
> [K[17:48:28] [Server thread/INFO] [armoryexpansion-conarm]: Registered stats for tinker's material {signalum}; 
> [K[17:48:28] [Server thread/INFO] [armoryexpansion-conarm]: Registered stats for tinker's material {peridot}; 
> [K[17:48:28] [Server thread/INFO] [armoryexpansion-conarm]: Registered stats for tinker's material {refined_coralium}; 
> [K[17:48:28] [Server thread/INFO] [armoryexpansion-conarm]: Registered stats for tinker's material {dreadium}; 
> [K[17:48:28] [Server thread/INFO] [armoryexpansion-conarm]: Registered stats for tinker's material {yellowcloth}; 
> [K[17:48:28] [Server thread/INFO] [armoryexpansion-conarm]: Registered stats for tinker's material {nickel}; 
> [K[17:48:28] [Server thread/INFO] [armoryexpansion-conarm]: Registered stats for tinker's material {purplecloth}; 
> [K[17:48:28] [Server thread/INFO] [armoryexpansion-conarm]: Registered stats for tinker's material {lightgraycloth}; 
> [K[17:48:28] [Server thread/INFO] [armoryexpansion-conarm]: Registered stats for tinker's material {blackcloth}; 
> [K[17:48:28] [Server thread/INFO] [armoryexpansion-conarm]: Registered stats for tinker's material {osmium}; 
> [K[17:48:28] [Server thread/INFO] [armoryexpansion-conarm]: Registered stats for tinker's material {quartz}; 
> [K[17:48:28] [Server thread/INFO] [armoryexpansion-conarm]: Registered stats for tinker's material {bluecloth}; 
> [K[17:48:28] [Server thread/INFO] [armoryexpansion-conarm]: Registered stats for tinker's material {treatedwood}; 
> [K[17:48:28] [Server thread/INFO] [armoryexpansion-conarm]: Registered stats for tinker's material {amber}; 
> [K[17:48:28] [Server thread/INFO] [armoryexpansion-conarm]: Registered stats for tinker's material {elvenelementium}; 
> [K[17:48:28] [Server thread/INFO] [armoryexpansion-conarm]: Registered stats for tinker's material {constantan}; 
> [K[17:48:28] [Server thread/INFO] [armoryexpansion-conarm]: Registered stats for tinker's material {psigem}; 
> [K[17:48:28] [Server thread/INFO] [armoryexpansion-conarm]: Registered stats for tinker's material {ruby}; 
> [K[17:48:28] [Server thread/INFO] [armoryexpansion-conarm]: Registered stats for tinker's material {diamond}; 
> [K[17:48:28] [Server thread/INFO] [armoryexpansion-conarm]: Registered stats for tinker's material {greencloth}; 
> [K[17:48:28] [Server thread/INFO] [armoryexpansion-conarm]: Registered stats for tinker's material {quartzenrichediron}; 
> [K[17:48:31] [Server thread/WARN] [FML]: Potentially Dangerous alternative prefix `rpsideas` for name `case`, expected `librarianliblate`. This could be a intended override, but in most cases indicates a broken mod. 
[39;0m> [K[17:48:31] [Server thread/WARN] [FML]: Potentially Dangerous alternative prefix `rpsideas` for name `conjured_pulsar_block`, expected `librarianliblate`. This could be a intended override, but in most cases indicates a broken mod. 
[39;0m> [K[17:48:31] [Server thread/WARN] [FML]: Potentially Dangerous alternative prefix `rpsideas` for name `conjured_star_block`, expected `librarianliblate`. This could be a intended override, but in most cases indicates a broken mod. 
[39;0m> [K[17:48:31] [Server thread/WARN] [FML]: Potentially Dangerous alternative prefix `rpsideas` for name `conjured_ethereal_block`, expected `librarianliblate`. This could be a intended override, but in most cases indicates a broken mod. 
[39;0m> [K[17:48:31] [Server thread/WARN] [FML]: Potentially Dangerous alternative prefix `rpsideas` for name `psi_dampener`, expected `librarianliblate`. This could be a intended override, but in most cases indicates a broken mod. 
[39;0m> [K[17:48:31] [Server thread/INFO] [Chisel]: Loading blocks... 
> [K[17:48:32] [Server thread/INFO] [Chisel]: Skipping feature bloodMagic as its required mod bloodmagic was missing. 
> [K[17:48:32] [Server thread/INFO] [Chisel]: 71 Feature's blocks loaded. 
> [K[17:48:32] [Server thread/INFO] [Chisel]: Loading Tile Entities... 
> [K[17:48:32] [Server thread/INFO] [Chisel]: Tile Entities loaded. 
> [K[17:48:34] [Server thread/WARN] [FML]: Potentially Dangerous alternative prefix `minecraft` for name `tconstruct.table`, expected `tconstruct`. This could be a intended override, but in most cases indicates a broken mod. 
[39;0m> [K[17:48:34] [Server thread/WARN] [FML]: Potentially Dangerous alternative prefix `minecraft` for name `tconstruct.craftingstation`, expected `tconstruct`. This could be a intended override, but in most cases indicates a broken mod. 
[39;0m> [K[17:48:34] [Server thread/WARN] [FML]: Potentially Dangerous alternative prefix `minecraft` for name `tconstruct.stenciltable`, expected `tconstruct`. This could be a intended override, but in most cases indicates a broken mod. 
[39;0m> [K[17:48:34] [Server thread/WARN] [FML]: Potentially Dangerous alternative prefix `minecraft` for name `tconstruct.partbuilder`, expected `tconstruct`. This could be a intended override, but in most cases indicates a broken mod. 
[39;0m> [K[17:48:34] [Server thread/WARN] [FML]: Potentially Dangerous alternative prefix `minecraft` for name `tconstruct.patternchest`, expected `tconstruct`. This could be a intended override, but in most cases indicates a broken mod. 
[39;0m> [K[17:48:34] [Server thread/WARN] [FML]: Potentially Dangerous alternative prefix `minecraft` for name `tconstruct.partchest`, expected `tconstruct`. This could be a intended override, but in most cases indicates a broken mod. 
[39;0m> [K[17:48:34] [Server thread/WARN] [FML]: Potentially Dangerous alternative prefix `minecraft` for name `tconstruct.toolstation`, expected `tconstruct`. This could be a intended override, but in most cases indicates a broken mod. 
[39;0m> [K[17:48:34] [Server thread/WARN] [FML]: Potentially Dangerous alternative prefix `minecraft` for name `tconstruct.toolforge`, expected `tconstruct`. This could be a intended override, but in most cases indicates a broken mod. 
[39;0m> [K[17:48:34] [Server thread/WARN] [FML]: Potentially Dangerous alternative prefix `minecraft` for name `tconstruct.smeltery_controller`, expected `tconstruct`. This could be a intended override, but in most cases indicates a broken mod. 
[39;0m> [K[17:48:34] [Server thread/WARN] [FML]: Potentially Dangerous alternative prefix `minecraft` for name `tconstruct.smeltery_component`, expected `tconstruct`. This could be a intended override, but in most cases indicates a broken mod. 
[39;0m> [K[17:48:34] [Server thread/WARN] [FML]: Potentially Dangerous alternative prefix `minecraft` for name `tconstruct.tank`, expected `tconstruct`. This could be a intended override, but in most cases indicates a broken mod. 
[39;0m> [K[17:48:34] [Server thread/WARN] [FML]: Potentially Dangerous alternative prefix `minecraft` for name `tconstruct.faucet`, expected `tconstruct`. This could be a intended override, but in most cases indicates a broken mod. 
[39;0m> [K[17:48:34] [Server thread/WARN] [FML]: Potentially Dangerous alternative prefix `minecraft` for name `tconstruct.channel`, expected `tconstruct`. This could be a intended override, but in most cases indicates a broken mod. 
[39;0m> [K[17:48:34] [Server thread/WARN] [FML]: Potentially Dangerous alternative prefix `minecraft` for name `tconstruct.casting_table`, expected `tconstruct`. This could be a intended override, but in most cases indicates a broken mod. 
[39;0m> [K[17:48:34] [Server thread/WARN] [FML]: Potentially Dangerous alternative prefix `minecraft` for name `tconstruct.casting_basin`, expected `tconstruct`. This could be a intended override, but in most cases indicates a broken mod. 
[39;0m> [K[17:48:34] [Server thread/WARN] [FML]: Potentially Dangerous alternative prefix `minecraft` for name `tconstruct.smeltery_drain`, expected `tconstruct`. This could be a intended override, but in most cases indicates a broken mod. 
[39;0m> [K[17:48:34] [Server thread/WARN] [FML]: Potentially Dangerous alternative prefix `minecraft` for name `tconstruct.seared_furnace`, expected `tconstruct`. This could be a intended override, but in most cases indicates a broken mod. 
[39;0m> [K[17:48:34] [Server thread/WARN] [FML]: Potentially Dangerous alternative prefix `minecraft` for name `tconstruct.tinker_tank`, expected `tconstruct`. This could be a intended override, but in most cases indicates a broken mod. 
[39;0m> [K[17:48:34] [Server thread/WARN] [FML]: Potentially Dangerous alternative prefix `minecraft` for name `tconstruct.item_rack`, expected `tconstruct`. This could be a intended override, but in most cases indicates a broken mod. 
[39;0m> [K[17:48:34] [Server thread/WARN] [FML]: Potentially Dangerous alternative prefix `minecraft` for name `tconstruct.drying_rack`, expected `tconstruct`. This could be a intended override, but in most cases indicates a broken mod. 
[39;0m> [K[17:48:34] [Server thread/WARN] [FML]: Potentially Dangerous alternative prefix `minecraft` for name `tconstruct.wooden_hopper`, expected `tconstruct`. This could be a intended override, but in most cases indicates a broken mod. 
[39;0m> [K[17:48:34] [Server thread/WARN] [FML]: Potentially Dangerous alternative prefix `minecraft` for name `tconstruct.slime_channel`, expected `tconstruct`. This could be a intended override, but in most cases indicates a broken mod. 
[39;0m> [K[17:48:34] [Server thread/WARN] [FML]: Potentially Dangerous alternative prefix `minecraft` for name `lectern`, expected `iceandfire`. This could be a intended override, but in most cases indicates a broken mod. 
[39;0m> [K[17:48:34] [Server thread/WARN] [FML]: Potentially Dangerous alternative prefix `minecraft` for name `podium`, expected `iceandfire`. This could be a intended override, but in most cases indicates a broken mod. 
[39;0m> [K[17:48:34] [Server thread/WARN] [FML]: Potentially Dangerous alternative prefix `minecraft` for name `egginice`, expected `iceandfire`. This could be a intended override, but in most cases indicates a broken mod. 
[39;0m> [K[17:48:34] [Server thread/WARN] [FML]: Potentially Dangerous alternative prefix `minecraft` for name `pixie_house`, expected `iceandfire`. This could be a intended override, but in most cases indicates a broken mod. 
[39;0m> [K[17:48:34] [Server thread/WARN] [FML]: Potentially Dangerous alternative prefix `minecraft` for name `jar`, expected `iceandfire`. This could be a intended override, but in most cases indicates a broken mod. 
[39;0m> [K[17:48:34] [Server thread/WARN] [FML]: Potentially Dangerous alternative prefix `minecraft` for name `dummygorgonheadidle`, expected `iceandfire`. This could be a intended override, but in most cases indicates a broken mod. 
[39;0m> [K[17:48:34] [Server thread/WARN] [FML]: Potentially Dangerous alternative prefix `minecraft` for name `dummygorgonheadactive`, expected `iceandfire`. This could be a intended override, but in most cases indicates a broken mod. 
[39;0m> [K[17:48:34] [Server thread/WARN] [FML]: Potentially Dangerous alternative prefix `minecraft` for name `myrmexcocoon`, expected `iceandfire`. This could be a intended override, but in most cases indicates a broken mod. 
[39;0m> [K[17:48:34] [Server thread/WARN] [FML]: Potentially Dangerous alternative prefix `minecraft` for name `bookcase`, expected `bibliocraft`. This could be a intended override, but in most cases indicates a broken mod. 
[39;0m> [K[17:48:34] [Server thread/WARN] [FML]: Potentially Dangerous alternative prefix `minecraft` for name `shelf`, expected `bibliocraft`. This could be a intended override, but in most cases indicates a broken mod. 
[39;0m> [K[17:48:34] [Server thread/WARN] [FML]: Potentially Dangerous alternative prefix `minecraft` for name `markerpole`, expected `bibliocraft`. This could be a intended override, but in most cases indicates a broken mod. 
[39;0m> [K[17:48:34] [Server thread/WARN] [FML]: Potentially Dangerous alternative prefix `minecraft` for name `clipboard`, expected `bibliocraft`. This could be a intended override, but in most cases indicates a broken mod. 
[39;0m> [K[17:48:34] [Server thread/WARN] [FML]: Potentially Dangerous alternative prefix `minecraft` for name `bibliolight`, expected `bibliocraft`. This could be a intended override, but in most cases indicates a broken mod. 
[39;0m> [K[17:48:34] [Server thread/WARN] [FML]: Potentially Dangerous alternative prefix `minecraft` for name `furniturepaneler`, expected `bibliocraft`. This could be a intended override, but in most cases indicates a broken mod. 
[39;0m> [K[17:48:34] [Server thread/WARN] [FML]: Potentially Dangerous alternative prefix `minecraft` for name `potionshelf`, expected `bibliocraft`. This could be a intended override, but in most cases indicates a broken mod. 
[39;0m> [K[17:48:34] [Server thread/WARN] [FML]: Potentially Dangerous alternative prefix `minecraft` for name `toolrack`, expected `bibliocraft`. This could be a intended override, but in most cases indicates a broken mod. 
[39;0m> [K[17:48:34] [Server thread/WARN] [FML]: Potentially Dangerous alternative prefix `minecraft` for name `label`, expected `bibliocraft`. This could be a intended override, but in most cases indicates a broken mod. 
[39;0m> [K[17:48:34] [Server thread/WARN] [FML]: Potentially Dangerous alternative prefix `minecraft` for name `desk`, expected `bibliocraft`. This could be a intended override, but in most cases indicates a broken mod. 
[39;0m> [K[17:48:34] [Server thread/WARN] [FML]: Potentially Dangerous alternative prefix `minecraft` for name `table`, expected `bibliocraft`. This could be a intended override, but in most cases indicates a broken mod. 
[39;0m> [K[17:48:34] [Server thread/WARN] [FML]: Potentially Dangerous alternative prefix `minecraft` for name `seat`, expected `bibliocraft`. This could be a intended override, but in most cases indicates a broken mod. 
[39;0m> [K[17:48:34] [Server thread/WARN] [FML]: Potentially Dangerous alternative prefix `minecraft` for name `fancysign`, expected `bibliocraft`. This could be a intended override, but in most cases indicates a broken mod. 
[39;0m> [K[17:48:34] [Server thread/WARN] [FML]: Potentially Dangerous alternative prefix `minecraft` for name `fancyworkbench`, expected `bibliocraft`. This could be a intended override, but in most cases indicates a broken mod. 
[39;0m> [K[17:48:34] [Server thread/WARN] [FML]: Potentially Dangerous alternative prefix `minecraft` for name `framedchest`, expected `bibliocraft`. This could be a intended override, but in most cases indicates a broken mod. 
[39;0m> [K[17:48:34] [Server thread/WARN] [FML]: Potentially Dangerous alternative prefix `minecraft` for name `mapframe`, expected `bibliocraft`. This could be a intended override, but in most cases indicates a broken mod. 
[39;0m> [K[17:48:34] [Server thread/WARN] [FML]: Potentially Dangerous alternative prefix `minecraft` for name `case`, expected `bibliocraft`. This could be a intended override, but in most cases indicates a broken mod. 
[39;0m> [K[17:48:34] [Server thread/WARN] [FML]: Potentially Dangerous alternative prefix `minecraft` for name `clock`, expected `bibliocraft`. This could be a intended override, but in most cases indicates a broken mod. 
[39;0m> [K[17:48:34] [Server thread/WARN] [FML]: Potentially Dangerous alternative prefix `minecraft` for name `paintingframeborderless`, expected `bibliocraft`. This could be a intended override, but in most cases indicates a broken mod. 
[39;0m> [K[17:48:34] [Server thread/WARN] [FML]: Potentially Dangerous alternative prefix `minecraft` for name `paintingframefancy`, expected `bibliocraft`. This could be a intended override, but in most cases indicates a broken mod. 
[39;0m> [K[17:48:34] [Server thread/WARN] [FML]: Potentially Dangerous alternative prefix `minecraft` for name `paintingframeflat`, expected `bibliocraft`. This could be a intended override, but in most cases indicates a broken mod. 
[39;0m> [K[17:48:34] [Server thread/WARN] [FML]: Potentially Dangerous alternative prefix `minecraft` for name `paintingframemiddle`, expected `bibliocraft`. This could be a intended override, but in most cases indicates a broken mod. 
[39;0m> [K[17:48:34] [Server thread/WARN] [FML]: Potentially Dangerous alternative prefix `minecraft` for name `paintingframesimple`, expected `bibliocraft`. This could be a intended override, but in most cases indicates a broken mod. 
[39;0m> [K[17:48:34] [Server thread/WARN] [FML]: Potentially Dangerous alternative prefix `minecraft` for name `paintingpress`, expected `bibliocraft`. This could be a intended override, but in most cases indicates a broken mod. 
[39;0m> [K[17:48:34] [Server thread/WARN] [FML]: Potentially Dangerous alternative prefix `minecraft` for name `armorstand`, expected `bibliocraft`. This could be a intended override, but in most cases indicates a broken mod. 
[39;0m> [K[17:48:34] [Server thread/WARN] [FML]: Potentially Dangerous alternative prefix `minecraft` for name `typesettingtable`, expected `bibliocraft`. This could be a intended override, but in most cases indicates a broken mod. 
[39;0m> [K[17:48:34] [Server thread/WARN] [FML]: Potentially Dangerous alternative prefix `minecraft` for name `printingpress`, expected `bibliocraft`. This could be a intended override, but in most cases indicates a broken mod. 
[39;0m> [K[17:48:34] [Server thread/WARN] [FML]: Potentially Dangerous alternative prefix `minecraft` for name `cookiejar`, expected `bibliocraft`. This could be a intended override, but in most cases indicates a broken mod. 
[39;0m> [K[17:48:34] [Server thread/WARN] [FML]: Potentially Dangerous alternative prefix `minecraft` for name `dinnerplate`, expected `bibliocraft`. This could be a intended override, but in most cases indicates a broken mod. 
[39;0m> [K[17:48:34] [Server thread/WARN] [FML]: Potentially Dangerous alternative prefix `minecraft` for name `discrack`, expected `bibliocraft`. This could be a intended override, but in most cases indicates a broken mod. 
[39;0m> [K[17:48:34] [Server thread/WARN] [FML]: Potentially Dangerous alternative prefix `minecraft` for name `swordpedestal`, expected `bibliocraft`. This could be a intended override, but in most cases indicates a broken mod. 
[39;0m> [K[17:48:34] [Server thread/WARN] [FML]: Potentially Dangerous alternative prefix `minecraft` for name `bell`, expected `bibliocraft`. This could be a intended override, but in most cases indicates a broken mod. 
[39;0m> [K[17:48:34] [Server thread/WARN] [FML]: Potentially Dangerous alternative prefix `minecraft` for name `typewriter`, expected `bibliocraft`. This could be a intended override, but in most cases indicates a broken mod. 
[39;0m> [K[17:48:35] [Server thread/WARN] [FML]: Potentially Dangerous alternative prefix `minecraft` for name `eplus.advanced.table`, expected `eplus`. This could be a intended override, but in most cases indicates a broken mod. 
[39;0m> [K[17:48:35] [Server thread/WARN] [FML]: Potentially Dangerous alternative prefix `minecraft` for name `eplus.decorative.book`, expected `eplus`. This could be a intended override, but in most cases indicates a broken mod. 
[39;0m> [K[17:48:35] [Server thread/WARN] [FML]: Potentially Dangerous alternative prefix `minecraft` for name `block_barrel`, expected `exnihilocreatio`. This could be a intended override, but in most cases indicates a broken mod. 
[39;0m> [K[17:48:35] [Server thread/WARN] [FML]: Potentially Dangerous alternative prefix `minecraft` for name `block_infesting_leaves`, expected `exnihilocreatio`. This could be a intended override, but in most cases indicates a broken mod. 
[39;0m> [K[17:48:35] [Server thread/WARN] [FML]: Potentially Dangerous alternative prefix `minecraft` for name `block_infested_leaves`, expected `exnihilocreatio`. This could be a intended override, but in most cases indicates a broken mod. 
[39;0m> [K[17:48:35] [Server thread/WARN] [FML]: Potentially Dangerous alternative prefix `minecraft` for name `block_crucible`, expected `exnihilocreatio`. This could be a intended override, but in most cases indicates a broken mod. 
[39;0m> [K[17:48:35] [Server thread/WARN] [FML]: Potentially Dangerous alternative prefix `minecraft` for name `block_crucible_wood`, expected `exnihilocreatio`. This could be a intended override, but in most cases indicates a broken mod. 
[39;0m> [K[17:48:35] [Server thread/WARN] [FML]: Potentially Dangerous alternative prefix `minecraft` for name `block_sieve`, expected `exnihilocreatio`. This could be a intended override, but in most cases indicates a broken mod. 
[39;0m> [K[17:48:35] [Server thread/WARN] [FML]: Potentially Dangerous alternative prefix `minecraft` for name `block_waterwheel`, expected `exnihilocreatio`. This could be a intended override, but in most cases indicates a broken mod. 
[39;0m> [K[17:48:35] [Server thread/WARN] [FML]: Potentially Dangerous alternative prefix `minecraft` for name `block_axle_stone`, expected `exnihilocreatio`. This could be a intended override, but in most cases indicates a broken mod. 
[39;0m> [K[17:48:35] [Server thread/WARN] [FML]: Potentially Dangerous alternative prefix `minecraft` for name `block_grinder`, expected `exnihilocreatio`. This could be a intended override, but in most cases indicates a broken mod. 
[39;0m> [K[17:48:35] [Server thread/WARN] [FML]: Potentially Dangerous alternative prefix `minecraft` for name `block_auto_sifter`, expected `exnihilocreatio`. This could be a intended override, but in most cases indicates a broken mod. 
[39;0m> [K[17:48:35] [Server thread/WARN] [FML]: Potentially Dangerous alternative prefix `minecraft` for name `extrarails.teleportingrail`, expected `extrarails`. This could be a intended override, but in most cases indicates a broken mod. 
[39;0m> [K[17:48:35] [Server thread/WARN] [FML]: Potentially Dangerous alternative prefix `minecraft` for name `extrarails.comparatorrail`, expected `extrarails`. This could be a intended override, but in most cases indicates a broken mod. 
[39;0m> [K[17:48:35] [Server thread/WARN] [FML]: Potentially Dangerous alternative prefix `minecraft` for name `block_rail_gag`, expected `immersiverailroading`. This could be a intended override, but in most cases indicates a broken mod. 
[39;0m> [K[17:48:35] [Server thread/WARN] [FML]: Potentially Dangerous alternative prefix `minecraft` for name `block_rail`, expected `immersiverailroading`. This could be a intended override, but in most cases indicates a broken mod. 
[39;0m> [K[17:48:35] [Server thread/WARN] [FML]: Potentially Dangerous alternative prefix `minecraft` for name `block_rail_preview`, expected `immersiverailroading`. This could be a intended override, but in most cases indicates a broken mod. 
[39;0m> [K[17:48:35] [Server thread/WARN] [FML]: Potentially Dangerous alternative prefix `minecraft` for name `multiblock`, expected `immersiverailroading`. This could be a intended override, but in most cases indicates a broken mod. 
[39;0m> [K[17:48:36] [Server thread/WARN] [FML]: Potentially Dangerous alternative prefix `minecraft` for name `armorstationtile`, expected `tinkerscompendium`. This could be a intended override, but in most cases indicates a broken mod. 
[39;0m> [K[17:48:36] [Server thread/WARN] [FML]: Potentially Dangerous alternative prefix `minecraft` for name `finishinganviltile`, expected `tinkerscompendium`. This could be a intended override, but in most cases indicates a broken mod. 
[39;0m> [K[17:48:36] [Server thread/WARN] [FML]: Potentially Dangerous alternative prefix `minecraft` for name `hammeringtabletile`, expected `tinkerscompendium`. This could be a intended override, but in most cases indicates a broken mod. 
[39;0m> [K[17:48:36] [Server thread/WARN] [FML]: Potentially Dangerous alternative prefix `tconstruct` for name `chorusjuice`, expected `tinkerscompendium`. This could be a intended override, but in most cases indicates a broken mod. 
[39;0m> [K[17:48:36] [Server thread/WARN] [FML]: Potentially Dangerous alternative prefix `tconstruct` for name `vile`, expected `tinkerscompendium`. This could be a intended override, but in most cases indicates a broken mod. 
[39;0m> [K[17:48:36] [Server thread/WARN] [FML]: Potentially Dangerous alternative prefix `tconstruct` for name `vibrant`, expected `tinkerscompendium`. This could be a intended override, but in most cases indicates a broken mod. 
[39;0m> [K[17:48:36] [Server thread/WARN] [FML]: Potentially Dangerous alternative prefix `tconstruct` for name `slush`, expected `tinkerscompendium`. This could be a intended override, but in most cases indicates a broken mod. 
[39;0m> [K[17:48:36] [Server thread/WARN] [FML]: Potentially Dangerous alternative prefix `tconstruct` for name `molten_quartz`, expected `tinkerscompendium`. This could be a intended override, but in most cases indicates a broken mod. 
[39;0m> [K[17:48:36] [Server thread/WARN] [FML]: Potentially Dangerous alternative prefix `tconstruct` for name `molten_dragonsbreath`, expected `tinkerscompendium`. This could be a intended override, but in most cases indicates a broken mod. 
[39;0m> [K[17:48:36] [Server thread/WARN] [FML]: Potentially Dangerous alternative prefix `minecraft` for name `torospawnerblock`, expected `toroquest`. This could be a intended override, but in most cases indicates a broken mod. 
[39;0m> [K[17:48:38] [Server thread/WARN] [FML]: Potentially Dangerous alternative prefix `minecraft` for name `backpack_block`, expected `backpacks16840`. This could be a intended override, but in most cases indicates a broken mod. 
[39;0m> [K[17:48:38] [Server thread/WARN] [FML]: Potentially Dangerous alternative prefix `minecraft` for name `quantumchest`, expected `backpacks16840`. This could be a intended override, but in most cases indicates a broken mod. 
[39;0m> [K[17:48:38] [Server thread/WARN] [FML]: Potentially Dangerous alternative prefix `minecraft` for name `tileredstoneblock`, expected `customnpcs`. This could be a intended override, but in most cases indicates a broken mod. 
[39;0m> [K[17:48:38] [Server thread/WARN] [FML]: Potentially Dangerous alternative prefix `minecraft` for name `tileblockanvil`, expected `customnpcs`. This could be a intended override, but in most cases indicates a broken mod. 
[39;0m> [K[17:48:38] [Server thread/WARN] [FML]: Potentially Dangerous alternative prefix `minecraft` for name `tilemailbox`, expected `customnpcs`. This could be a intended override, but in most cases indicates a broken mod. 
[39;0m> [K[17:48:38] [Server thread/WARN] [FML]: Potentially Dangerous alternative prefix `minecraft` for name `tilewaypoint`, expected `customnpcs`. This could be a intended override, but in most cases indicates a broken mod. 
[39;0m> [K[17:48:38] [Server thread/WARN] [FML]: Potentially Dangerous alternative prefix `minecraft` for name `tilenpcscripted`, expected `customnpcs`. This could be a intended override, but in most cases indicates a broken mod. 
[39;0m> [K[17:48:38] [Server thread/WARN] [FML]: Potentially Dangerous alternative prefix `minecraft` for name `tilenpcscripteddoor`, expected `customnpcs`. This could be a intended override, but in most cases indicates a broken mod. 
[39;0m> [K[17:48:38] [Server thread/WARN] [FML]: Potentially Dangerous alternative prefix `minecraft` for name `tilenpcbuilder`, expected `customnpcs`. This could be a intended override, but in most cases indicates a broken mod. 
[39;0m> [K[17:48:38] [Server thread/WARN] [FML]: Potentially Dangerous alternative prefix `minecraft` for name `tilenpccopy`, expected `customnpcs`. This could be a intended override, but in most cases indicates a broken mod. 
[39;0m> [K[17:48:38] [Server thread/WARN] [FML]: Potentially Dangerous alternative prefix `minecraft` for name `tilenpcborder`, expected `customnpcs`. This could be a intended override, but in most cases indicates a broken mod. 
[39;0m> [K[17:48:38] [Server thread/WARN] [FML]: Potentially Dangerous alternative prefix `minecraft` for name `tileentityfoundry`, expected `giacomosfoundry`. This could be a intended override, but in most cases indicates a broken mod. 
[39;0m> [K[17:48:38] [Server thread/WARN] [FML]: Potentially Dangerous alternative prefix `minecraft` for name `tileentityhopperduct`, expected `hopperducts`. This could be a intended override, but in most cases indicates a broken mod. 
[39;0m> [K[17:48:38] [Server thread/WARN] [FML]: Potentially Dangerous alternative prefix `minecraft` for name `tileentitygratedhopper`, expected `hopperducts`. This could be a intended override, but in most cases indicates a broken mod. 
[39;0m> [K[17:48:38] [Server thread/WARN] [FML]: Potentially Dangerous alternative prefix `minecraft` for name `redstonepastete`, expected `redstonepaste`. This could be a intended override, but in most cases indicates a broken mod. 
[39;0m> [K[17:48:38] [Server thread/WARN] [FML]: Potentially Dangerous alternative prefix `minecraft` for name `crafting_table`, expected `fastbench`. This could be a intended override, but in most cases indicates a broken mod. 
[39;0m> [K[17:48:38] [Server thread/WARN] [FML]: Potentially Dangerous alternative prefix `minecraft` for name `crafting_table`, expected `fastbench`. This could be a intended override, but in most cases indicates a broken mod. 
[39;0m> [K[17:48:38] [Server thread/INFO] [FML]: Applying holder lookups 
> [K[17:48:38] [Server thread/INFO] [FML]: Holder lookups applied 
> [K[17:48:38] [Server thread/INFO] [Chisel]: Loading items... 
> [K[17:48:38] [Server thread/INFO] [Chisel]: Skipping feature bloodMagic as its required mod bloodmagic was missing. 
> [K[17:48:38] [Server thread/INFO] [Chisel]: 71 Feature's items loaded. 
> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * Registry Item: The object net.minecraft.item.Item@512a1b9a has been registered twice for the same name tinkerscompendium:ingot_aeonsteel. 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:300) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:281) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.register(ForgeRegistry.java:113) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.core.materials.CompendiumMaterials.registerItems(CompendiumMaterials.java:1165) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.proxy.CommonProxy.registerItems(CommonProxy.java:99) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.fml.common.eventhandler.ASMEventHandler_582_CommonProxy_registerItems_Register.invoke(.dynamic)...
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * Registry Item: The object net.minecraft.item.Item@3e8e8f85 has been registered twice for the same name tinkerscompendium:nugget_aeonsteel. 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:300) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:281) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.register(ForgeRegistry.java:113) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.core.materials.CompendiumMaterials.registerItems(CompendiumMaterials.java:1165) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.proxy.CommonProxy.registerItems(CommonProxy.java:99) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.fml.common.eventhandler.ASMEventHandler_582_CommonProxy_registerItems_Register.invoke(.dynamic)...
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * Registry Item: The object net.minecraft.item.ItemBlock@179b422 has been registered twice for the same name tinkerscompendium:block_aeonsteel. 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:300) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:281) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.register(ForgeRegistry.java:113) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.core.materials.CompendiumMaterials.registerItems(CompendiumMaterials.java:1165) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.proxy.CommonProxy.registerItems(CommonProxy.java:99) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.fml.common.eventhandler.ASMEventHandler_582_CommonProxy_registerItems_Register.invoke(.dynamic)...
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * Registry Item: The object net.minecraft.item.Item@160a5002 has been registered twice for the same name tinkerscompendium:dust_aeonsteel. 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:300) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:281) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.register(ForgeRegistry.java:113) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.core.materials.CompendiumMaterials.registerItems(CompendiumMaterials.java:1165) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.proxy.CommonProxy.registerItems(CommonProxy.java:99) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.fml.common.eventhandler.ASMEventHandler_582_CommonProxy_registerItems_Register.invoke(.dynamic)...
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * Registry Item: The object net.minecraft.item.Item@177d7f92 has been registered twice for the same name tinkerscompendium:grain_aeonsteel. 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:300) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:281) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.register(ForgeRegistry.java:113) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.core.materials.CompendiumMaterials.registerItems(CompendiumMaterials.java:1165) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.proxy.CommonProxy.registerItems(CommonProxy.java:99) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.fml.common.eventhandler.ASMEventHandler_582_CommonProxy_registerItems_Register.invoke(.dynamic)...
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * Registry Item: The object net.minecraft.item.Item@5d45285f has been registered twice for the same name tinkerscompendium:plate_aeonsteel. 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:300) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:281) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.register(ForgeRegistry.java:113) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.core.materials.CompendiumMaterials.registerItems(CompendiumMaterials.java:1165) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.proxy.CommonProxy.registerItems(CommonProxy.java:99) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.fml.common.eventhandler.ASMEventHandler_582_CommonProxy_registerItems_Register.invoke(.dynamic)...
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * Registry Item: The object net.minecraft.item.Item@11d14f71 has been registered twice for the same name tinkerscompendium:coin_aeonsteel. 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:300) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:281) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.register(ForgeRegistry.java:113) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.core.materials.CompendiumMaterials.registerItems(CompendiumMaterials.java:1165) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.proxy.CommonProxy.registerItems(CommonProxy.java:99) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.fml.common.eventhandler.ASMEventHandler_582_CommonProxy_registerItems_Register.invoke(.dynamic)...
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * Registry Item: The object net.minecraft.item.Item@559f9709 has been registered twice for the same name tinkerscompendium:gear_aeonsteel. 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:300) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:281) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.register(ForgeRegistry.java:113) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.core.materials.CompendiumMaterials.registerItems(CompendiumMaterials.java:1165) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.proxy.CommonProxy.registerItems(CommonProxy.java:99) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.fml.common.eventhandler.ASMEventHandler_582_CommonProxy_registerItems_Register.invoke(.dynamic)...
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * Registry Item: The object net.minecraft.item.Item@29e2f3c7 has been registered twice for the same name tinkerscompendium:rod_aeonsteel. 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:300) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:281) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.register(ForgeRegistry.java:113) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.core.materials.CompendiumMaterials.registerItems(CompendiumMaterials.java:1165) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.proxy.CommonProxy.registerItems(CommonProxy.java:99) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.fml.common.eventhandler.ASMEventHandler_582_CommonProxy_registerItems_Register.invoke(.dynamic)...
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * Registry Item: The object net.minecraft.item.Item@5d113174 has been registered twice for the same name tinkerscompendium:coil_aeonsteel. 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:300) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:281) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.register(ForgeRegistry.java:113) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.core.materials.CompendiumMaterials.registerItems(CompendiumMaterials.java:1165) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.proxy.CommonProxy.registerItems(CommonProxy.java:99) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.fml.common.eventhandler.ASMEventHandler_582_CommonProxy_registerItems_Register.invoke(.dynamic)...
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * Registry Item: The object net.minecraft.item.Item@46a05760 has been registered twice for the same name tinkerscompendium:spring_aeonsteel. 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:300) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:281) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.register(ForgeRegistry.java:113) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.core.materials.CompendiumMaterials.registerItems(CompendiumMaterials.java:1165) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.proxy.CommonProxy.registerItems(CommonProxy.java:99) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.fml.common.eventhandler.ASMEventHandler_582_CommonProxy_registerItems_Register.invoke(.dynamic)...
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * Registry Item: The object net.minecraft.item.Item@6f2ea762 has been registered twice for the same name tinkerscompendium:casing_aeonsteel. 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:300) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:281) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.register(ForgeRegistry.java:113) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.core.materials.CompendiumMaterials.registerItems(CompendiumMaterials.java:1165) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.proxy.CommonProxy.registerItems(CommonProxy.java:99) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.fml.common.eventhandler.ASMEventHandler_582_CommonProxy_registerItems_Register.invoke(.dynamic)...
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * Registry Item: The object net.minecraft.item.Item@51ec0d8b has been registered twice for the same name tinkerscompendium:wire_aeonsteel. 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:300) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:281) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.register(ForgeRegistry.java:113) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.core.materials.CompendiumMaterials.registerItems(CompendiumMaterials.java:1165) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.proxy.CommonProxy.registerItems(CommonProxy.java:99) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.fml.common.eventhandler.ASMEventHandler_582_CommonProxy_registerItems_Register.invoke(.dynamic)...
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * Registry Item: The object net.minecraft.item.ItemBlock@5a20c53 has been registered twice for the same name tinkerscompendium:stake_aeonsteel. 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:300) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:281) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.register(ForgeRegistry.java:113) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.core.materials.CompendiumMaterials.registerItems(CompendiumMaterials.java:1165) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.proxy.CommonProxy.registerItems(CommonProxy.java:99) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.fml.common.eventhandler.ASMEventHandler_582_CommonProxy_registerItems_Register.invoke(.dynamic)...
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * Registry Item: The object net.minecraft.item.ItemBlock@41fd50d0 has been registered twice for the same name tinkerscompendium:bars_aeonsteel. 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:300) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:281) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.register(ForgeRegistry.java:113) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.core.materials.CompendiumMaterials.registerItems(CompendiumMaterials.java:1165) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.proxy.CommonProxy.registerItems(CommonProxy.java:99) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.fml.common.eventhandler.ASMEventHandler_582_CommonProxy_registerItems_Register.invoke(.dynamic)...
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * Registry Item: The object net.minecraft.item.ItemBlock@6ac3348a has been registered twice for the same name tinkerscompendium:trapdoor_aeonsteel. 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:300) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:281) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.register(ForgeRegistry.java:113) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.core.materials.CompendiumMaterials.registerItems(CompendiumMaterials.java:1165) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.proxy.CommonProxy.registerItems(CommonProxy.java:99) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.fml.common.eventhandler.ASMEventHandler_582_CommonProxy_registerItems_Register.invoke(.dynamic)...
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * Registry Item: The object net.minecraft.item.Item@7f966d15 has been registered twice for the same name tinkerscompendium:ingot_queensgold. 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:300) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:281) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.register(ForgeRegistry.java:113) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.core.materials.CompendiumMaterials.registerItems(CompendiumMaterials.java:1165) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.proxy.CommonProxy.registerItems(CommonProxy.java:99) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.fml.common.eventhandler.ASMEventHandler_582_CommonProxy_registerItems_Register.invoke(.dynamic)...
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * Registry Item: The object net.minecraft.item.Item@54c6d9e7 has been registered twice for the same name tinkerscompendium:nugget_queensgold. 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:300) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:281) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.register(ForgeRegistry.java:113) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.core.materials.CompendiumMaterials.registerItems(CompendiumMaterials.java:1165) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.proxy.CommonProxy.registerItems(CommonProxy.java:99) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.fml.common.eventhandler.ASMEventHandler_582_CommonProxy_registerItems_Register.invoke(.dynamic)...
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * Registry Item: The object net.minecraft.item.ItemBlock@1829da7f has been registered twice for the same name tinkerscompendium:block_queensgold. 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:300) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:281) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.register(ForgeRegistry.java:113) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.core.materials.CompendiumMaterials.registerItems(CompendiumMaterials.java:1165) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.proxy.CommonProxy.registerItems(CommonProxy.java:99) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.fml.common.eventhandler.ASMEventHandler_582_CommonProxy_registerItems_Register.invoke(.dynamic)...
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * Registry Item: The object net.minecraft.item.Item@6b3dda94 has been registered twice for the same name tinkerscompendium:dust_queensgold. 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:300) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:281) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.register(ForgeRegistry.java:113) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.core.materials.CompendiumMaterials.registerItems(CompendiumMaterials.java:1165) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.proxy.CommonProxy.registerItems(CommonProxy.java:99) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.fml.common.eventhandler.ASMEventHandler_582_CommonProxy_registerItems_Register.invoke(.dynamic)...
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * Registry Item: The object net.minecraft.item.Item@278fec23 has been registered twice for the same name tinkerscompendium:grain_queensgold. 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:300) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:281) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.register(ForgeRegistry.java:113) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.core.materials.CompendiumMaterials.registerItems(CompendiumMaterials.java:1165) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.proxy.CommonProxy.registerItems(CommonProxy.java:99) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.fml.common.eventhandler.ASMEventHandler_582_CommonProxy_registerItems_Register.invoke(.dynamic)...
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * Registry Item: The object net.minecraft.item.Item@456400d4 has been registered twice for the same name tinkerscompendium:plate_queensgold. 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:300) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:281) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.register(ForgeRegistry.java:113) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.core.materials.CompendiumMaterials.registerItems(CompendiumMaterials.java:1165) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.proxy.CommonProxy.registerItems(CommonProxy.java:99) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.fml.common.eventhandler.ASMEventHandler_582_CommonProxy_registerItems_Register.invoke(.dynamic)...
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * Registry Item: The object net.minecraft.item.Item@13c8c025 has been registered twice for the same name tinkerscompendium:coin_queensgold. 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:300) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:281) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.register(ForgeRegistry.java:113) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.core.materials.CompendiumMaterials.registerItems(CompendiumMaterials.java:1165) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.proxy.CommonProxy.registerItems(CommonProxy.java:99) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.fml.common.eventhandler.ASMEventHandler_582_CommonProxy_registerItems_Register.invoke(.dynamic)...
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * Registry Item: The object net.minecraft.item.Item@16a441b2 has been registered twice for the same name tinkerscompendium:gear_queensgold. 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:300) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:281) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.register(ForgeRegistry.java:113) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.core.materials.CompendiumMaterials.registerItems(CompendiumMaterials.java:1165) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.proxy.CommonProxy.registerItems(CommonProxy.java:99) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.fml.common.eventhandler.ASMEventHandler_582_CommonProxy_registerItems_Register.invoke(.dynamic)...
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * Registry Item: The object net.minecraft.item.Item@4e1259b1 has been registered twice for the same name tinkerscompendium:rod_queensgold. 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:300) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:281) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.register(ForgeRegistry.java:113) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.core.materials.CompendiumMaterials.registerItems(CompendiumMaterials.java:1165) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.proxy.CommonProxy.registerItems(CommonProxy.java:99) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.fml.common.eventhandler.ASMEventHandler_582_CommonProxy_registerItems_Register.invoke(.dynamic)...
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * Registry Item: The object net.minecraft.item.Item@2b959207 has been registered twice for the same name tinkerscompendium:coil_queensgold. 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:300) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:281) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.register(ForgeRegistry.java:113) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.core.materials.CompendiumMaterials.registerItems(CompendiumMaterials.java:1165) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.proxy.CommonProxy.registerItems(CommonProxy.java:99) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.fml.common.eventhandler.ASMEventHandler_582_CommonProxy_registerItems_Register.invoke(.dynamic)...
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * Registry Item: The object net.minecraft.item.Item@7e89a6b8 has been registered twice for the same name tinkerscompendium:spring_queensgold. 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:300) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:281) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.register(ForgeRegistry.java:113) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.core.materials.CompendiumMaterials.registerItems(CompendiumMaterials.java:1165) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.proxy.CommonProxy.registerItems(CommonProxy.java:99) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.fml.common.eventhandler.ASMEventHandler_582_CommonProxy_registerItems_Register.invoke(.dynamic)...
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * Registry Item: The object net.minecraft.item.Item@4a14d10a has been registered twice for the same name tinkerscompendium:casing_queensgold. 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:300) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:281) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.register(ForgeRegistry.java:113) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.core.materials.CompendiumMaterials.registerItems(CompendiumMaterials.java:1165) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.proxy.CommonProxy.registerItems(CommonProxy.java:99) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.fml.common.eventhandler.ASMEventHandler_582_CommonProxy_registerItems_Register.invoke(.dynamic)...
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * Registry Item: The object net.minecraft.item.Item@1617d628 has been registered twice for the same name tinkerscompendium:wire_queensgold. 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:300) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:281) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.register(ForgeRegistry.java:113) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.core.materials.CompendiumMaterials.registerItems(CompendiumMaterials.java:1165) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.proxy.CommonProxy.registerItems(CommonProxy.java:99) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.fml.common.eventhandler.ASMEventHandler_582_CommonProxy_registerItems_Register.invoke(.dynamic)...
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * Registry Item: The object net.minecraft.item.ItemBlock@11156b47 has been registered twice for the same name tinkerscompendium:stake_queensgold. 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:300) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:281) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.register(ForgeRegistry.java:113) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.core.materials.CompendiumMaterials.registerItems(CompendiumMaterials.java:1165) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.proxy.CommonProxy.registerItems(CommonProxy.java:99) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.fml.common.eventhandler.ASMEventHandler_582_CommonProxy_registerItems_Register.invoke(.dynamic)...
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * Registry Item: The object net.minecraft.item.ItemBlock@229aa3bb has been registered twice for the same name tinkerscompendium:bars_queensgold. 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:300) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:281) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.register(ForgeRegistry.java:113) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.core.materials.CompendiumMaterials.registerItems(CompendiumMaterials.java:1165) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.proxy.CommonProxy.registerItems(CommonProxy.java:99) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.fml.common.eventhandler.ASMEventHandler_582_CommonProxy_registerItems_Register.invoke(.dynamic)...
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * Registry Item: The object net.minecraft.item.ItemBlock@66649300 has been registered twice for the same name tinkerscompendium:trapdoor_queensgold. 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:300) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:281) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.register(ForgeRegistry.java:113) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.core.materials.CompendiumMaterials.registerItems(CompendiumMaterials.java:1165) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.proxy.CommonProxy.registerItems(CommonProxy.java:99) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.fml.common.eventhandler.ASMEventHandler_582_CommonProxy_registerItems_Register.invoke(.dynamic)...
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * Registry Item: The object net.minecraft.item.Item@5c1183d8 has been registered twice for the same name tinkerscompendium:ingot_dogbearium. 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:300) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:281) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.register(ForgeRegistry.java:113) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.core.materials.CompendiumMaterials.registerItems(CompendiumMaterials.java:1165) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.proxy.CommonProxy.registerItems(CommonProxy.java:99) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.fml.common.eventhandler.ASMEventHandler_582_CommonProxy_registerItems_Register.invoke(.dynamic)...
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * Registry Item: The object net.minecraft.item.Item@2be1749a has been registered twice for the same name tinkerscompendium:nugget_dogbearium. 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:300) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:281) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.register(ForgeRegistry.java:113) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.core.materials.CompendiumMaterials.registerItems(CompendiumMaterials.java:1165) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.proxy.CommonProxy.registerItems(CommonProxy.java:99) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.fml.common.eventhandler.ASMEventHandler_582_CommonProxy_registerItems_Register.invoke(.dynamic)...
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * Registry Item: The object net.minecraft.item.ItemBlock@30437a37 has been registered twice for the same name tinkerscompendium:block_dogbearium. 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:300) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:281) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.register(ForgeRegistry.java:113) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.core.materials.CompendiumMaterials.registerItems(CompendiumMaterials.java:1165) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.proxy.CommonProxy.registerItems(CommonProxy.java:99) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.fml.common.eventhandler.ASMEventHandler_582_CommonProxy_registerItems_Register.invoke(.dynamic)...
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * Registry Item: The object net.minecraft.item.Item@72fd13ac has been registered twice for the same name tinkerscompendium:dust_dogbearium. 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:300) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:281) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.register(ForgeRegistry.java:113) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.core.materials.CompendiumMaterials.registerItems(CompendiumMaterials.java:1165) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.proxy.CommonProxy.registerItems(CommonProxy.java:99) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.fml.common.eventhandler.ASMEventHandler_582_CommonProxy_registerItems_Register.invoke(.dynamic)...
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * Registry Item: The object net.minecraft.item.Item@22225168 has been registered twice for the same name tinkerscompendium:grain_dogbearium. 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:300) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:281) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.register(ForgeRegistry.java:113) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.core.materials.CompendiumMaterials.registerItems(CompendiumMaterials.java:1165) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.proxy.CommonProxy.registerItems(CommonProxy.java:99) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.fml.common.eventhandler.ASMEventHandler_582_CommonProxy_registerItems_Register.invoke(.dynamic)...
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * Registry Item: The object net.minecraft.item.Item@247a412 has been registered twice for the same name tinkerscompendium:plate_dogbearium. 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:300) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:281) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.register(ForgeRegistry.java:113) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.core.materials.CompendiumMaterials.registerItems(CompendiumMaterials.java:1165) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.proxy.CommonProxy.registerItems(CommonProxy.java:99) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.fml.common.eventhandler.ASMEventHandler_582_CommonProxy_registerItems_Register.invoke(.dynamic)...
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * Registry Item: The object net.minecraft.item.Item@29fee4af has been registered twice for the same name tinkerscompendium:coin_dogbearium. 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:300) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:281) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.register(ForgeRegistry.java:113) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.core.materials.CompendiumMaterials.registerItems(CompendiumMaterials.java:1165) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.proxy.CommonProxy.registerItems(CommonProxy.java:99) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.fml.common.eventhandler.ASMEventHandler_582_CommonProxy_registerItems_Register.invoke(.dynamic)...
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * Registry Item: The object net.minecraft.item.Item@3304e24f has been registered twice for the same name tinkerscompendium:gear_dogbearium. 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:300) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:281) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.register(ForgeRegistry.java:113) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.core.materials.CompendiumMaterials.registerItems(CompendiumMaterials.java:1165) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.proxy.CommonProxy.registerItems(CommonProxy.java:99) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.fml.common.eventhandler.ASMEventHandler_582_CommonProxy_registerItems_Register.invoke(.dynamic)...
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * Registry Item: The object net.minecraft.item.Item@31d5c56 has been registered twice for the same name tinkerscompendium:rod_dogbearium. 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:300) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:281) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.register(ForgeRegistry.java:113) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.core.materials.CompendiumMaterials.registerItems(CompendiumMaterials.java:1165) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.proxy.CommonProxy.registerItems(CommonProxy.java:99) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.fml.common.eventhandler.ASMEventHandler_582_CommonProxy_registerItems_Register.invoke(.dynamic)...
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * Registry Item: The object net.minecraft.item.Item@3cc51f13 has been registered twice for the same name tinkerscompendium:coil_dogbearium. 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:300) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:281) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.register(ForgeRegistry.java:113) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.core.materials.CompendiumMaterials.registerItems(CompendiumMaterials.java:1165) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.proxy.CommonProxy.registerItems(CommonProxy.java:99) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.fml.common.eventhandler.ASMEventHandler_582_CommonProxy_registerItems_Register.invoke(.dynamic)...
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * Registry Item: The object net.minecraft.item.Item@62405fb8 has been registered twice for the same name tinkerscompendium:spring_dogbearium. 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:300) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:281) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.register(ForgeRegistry.java:113) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.core.materials.CompendiumMaterials.registerItems(CompendiumMaterials.java:1165) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.proxy.CommonProxy.registerItems(CommonProxy.java:99) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.fml.common.eventhandler.ASMEventHandler_582_CommonProxy_registerItems_Register.invoke(.dynamic)...
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * Registry Item: The object net.minecraft.item.Item@7642df25 has been registered twice for the same name tinkerscompendium:casing_dogbearium. 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:300) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:281) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.register(ForgeRegistry.java:113) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.core.materials.CompendiumMaterials.registerItems(CompendiumMaterials.java:1165) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.proxy.CommonProxy.registerItems(CommonProxy.java:99) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.fml.common.eventhandler.ASMEventHandler_582_CommonProxy_registerItems_Register.invoke(.dynamic)...
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * Registry Item: The object net.minecraft.item.Item@1fd4c257 has been registered twice for the same name tinkerscompendium:wire_dogbearium. 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:300) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:281) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.register(ForgeRegistry.java:113) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.core.materials.CompendiumMaterials.registerItems(CompendiumMaterials.java:1165) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.proxy.CommonProxy.registerItems(CommonProxy.java:99) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.fml.common.eventhandler.ASMEventHandler_582_CommonProxy_registerItems_Register.invoke(.dynamic)...
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * Registry Item: The object net.minecraft.item.ItemBlock@bfd7b39 has been registered twice for the same name tinkerscompendium:stake_dogbearium. 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:300) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:281) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.register(ForgeRegistry.java:113) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.core.materials.CompendiumMaterials.registerItems(CompendiumMaterials.java:1165) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.proxy.CommonProxy.registerItems(CommonProxy.java:99) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.fml.common.eventhandler.ASMEventHandler_582_CommonProxy_registerItems_Register.invoke(.dynamic)...
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * Registry Item: The object net.minecraft.item.ItemBlock@6b205861 has been registered twice for the same name tinkerscompendium:bars_dogbearium. 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:300) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:281) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.register(ForgeRegistry.java:113) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.core.materials.CompendiumMaterials.registerItems(CompendiumMaterials.java:1165) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.proxy.CommonProxy.registerItems(CommonProxy.java:99) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.fml.common.eventhandler.ASMEventHandler_582_CommonProxy_registerItems_Register.invoke(.dynamic)...
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * Registry Item: The object net.minecraft.item.ItemBlock@3284a485 has been registered twice for the same name tinkerscompendium:trapdoor_dogbearium. 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:300) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:281) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.register(ForgeRegistry.java:113) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.core.materials.CompendiumMaterials.registerItems(CompendiumMaterials.java:1165) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.proxy.CommonProxy.registerItems(CommonProxy.java:99) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.fml.common.eventhandler.ASMEventHandler_582_CommonProxy_registerItems_Register.invoke(.dynamic)...
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * Registry Item: The object net.minecraft.item.Item@5240255f has been registered twice for the same name tinkerscompendium:ingot_sinisterium. 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:300) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:281) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.register(ForgeRegistry.java:113) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.core.materials.CompendiumMaterials.registerItems(CompendiumMaterials.java:1165) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.proxy.CommonProxy.registerItems(CommonProxy.java:99) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.fml.common.eventhandler.ASMEventHandler_582_CommonProxy_registerItems_Register.invoke(.dynamic)...
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * Registry Item: The object net.minecraft.item.Item@3bca9c26 has been registered twice for the same name tinkerscompendium:nugget_sinisterium. 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:300) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:281) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.register(ForgeRegistry.java:113) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.core.materials.CompendiumMaterials.registerItems(CompendiumMaterials.java:1165) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.proxy.CommonProxy.registerItems(CommonProxy.java:99) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.fml.common.eventhandler.ASMEventHandler_582_CommonProxy_registerItems_Register.invoke(.dynamic)...
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * Registry Item: The object net.minecraft.item.ItemBlock@682c0f29 has been registered twice for the same name tinkerscompendium:block_sinisterium. 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:300) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:281) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.register(ForgeRegistry.java:113) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.core.materials.CompendiumMaterials.registerItems(CompendiumMaterials.java:1165) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.proxy.CommonProxy.registerItems(CommonProxy.java:99) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.fml.common.eventhandler.ASMEventHandler_582_CommonProxy_registerItems_Register.invoke(.dynamic)...
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * Registry Item: The object net.minecraft.item.Item@7f1b3e25 has been registered twice for the same name tinkerscompendium:dust_sinisterium. 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:300) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:281) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.register(ForgeRegistry.java:113) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.core.materials.CompendiumMaterials.registerItems(CompendiumMaterials.java:1165) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.proxy.CommonProxy.registerItems(CommonProxy.java:99) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.fml.common.eventhandler.ASMEventHandler_582_CommonProxy_registerItems_Register.invoke(.dynamic)...
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * Registry Item: The object net.minecraft.item.Item@2c228644 has been registered twice for the same name tinkerscompendium:grain_sinisterium. 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:300) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:281) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.register(ForgeRegistry.java:113) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.core.materials.CompendiumMaterials.registerItems(CompendiumMaterials.java:1165) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.proxy.CommonProxy.registerItems(CommonProxy.java:99) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.fml.common.eventhandler.ASMEventHandler_582_CommonProxy_registerItems_Register.invoke(.dynamic)...
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * Registry Item: The object net.minecraft.item.Item@4366044a has been registered twice for the same name tinkerscompendium:plate_sinisterium. 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:300) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:281) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.register(ForgeRegistry.java:113) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.core.materials.CompendiumMaterials.registerItems(CompendiumMaterials.java:1165) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.proxy.CommonProxy.registerItems(CommonProxy.java:99) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.fml.common.eventhandler.ASMEventHandler_582_CommonProxy_registerItems_Register.invoke(.dynamic)...
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * Registry Item: The object net.minecraft.item.Item@4bbb1e48 has been registered twice for the same name tinkerscompendium:coin_sinisterium. 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:300) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:281) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.register(ForgeRegistry.java:113) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.core.materials.CompendiumMaterials.registerItems(CompendiumMaterials.java:1165) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.proxy.CommonProxy.registerItems(CommonProxy.java:99) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.fml.common.eventhandler.ASMEventHandler_582_CommonProxy_registerItems_Register.invoke(.dynamic)...
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * Registry Item: The object net.minecraft.item.Item@6df7fb0c has been registered twice for the same name tinkerscompendium:gear_sinisterium. 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:300) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:281) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.register(ForgeRegistry.java:113) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.core.materials.CompendiumMaterials.registerItems(CompendiumMaterials.java:1165) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.proxy.CommonProxy.registerItems(CommonProxy.java:99) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.fml.common.eventhandler.ASMEventHandler_582_CommonProxy_registerItems_Register.invoke(.dynamic)...
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * Registry Item: The object net.minecraft.item.Item@55df4050 has been registered twice for the same name tinkerscompendium:rod_sinisterium. 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:300) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:281) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.register(ForgeRegistry.java:113) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.core.materials.CompendiumMaterials.registerItems(CompendiumMaterials.java:1165) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.proxy.CommonProxy.registerItems(CommonProxy.java:99) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.fml.common.eventhandler.ASMEventHandler_582_CommonProxy_registerItems_Register.invoke(.dynamic)...
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * Registry Item: The object net.minecraft.item.Item@26e85af5 has been registered twice for the same name tinkerscompendium:coil_sinisterium. 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:300) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:281) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.register(ForgeRegistry.java:113) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.core.materials.CompendiumMaterials.registerItems(CompendiumMaterials.java:1165) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.proxy.CommonProxy.registerItems(CommonProxy.java:99) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.fml.common.eventhandler.ASMEventHandler_582_CommonProxy_registerItems_Register.invoke(.dynamic)...
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * Registry Item: The object net.minecraft.item.Item@35b2493e has been registered twice for the same name tinkerscompendium:spring_sinisterium. 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:300) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:281) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.register(ForgeRegistry.java:113) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.core.materials.CompendiumMaterials.registerItems(CompendiumMaterials.java:1165) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.proxy.CommonProxy.registerItems(CommonProxy.java:99) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.fml.common.eventhandler.ASMEventHandler_582_CommonProxy_registerItems_Register.invoke(.dynamic)...
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * Registry Item: The object net.minecraft.item.Item@674ffb1f has been registered twice for the same name tinkerscompendium:casing_sinisterium. 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:300) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:281) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.register(ForgeRegistry.java:113) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.core.materials.CompendiumMaterials.registerItems(CompendiumMaterials.java:1165) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.proxy.CommonProxy.registerItems(CommonProxy.java:99) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.fml.common.eventhandler.ASMEventHandler_582_CommonProxy_registerItems_Register.invoke(.dynamic)...
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * Registry Item: The object net.minecraft.item.Item@483dfa66 has been registered twice for the same name tinkerscompendium:wire_sinisterium. 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:300) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:281) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.register(ForgeRegistry.java:113) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.core.materials.CompendiumMaterials.registerItems(CompendiumMaterials.java:1165) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.proxy.CommonProxy.registerItems(CommonProxy.java:99) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.fml.common.eventhandler.ASMEventHandler_582_CommonProxy_registerItems_Register.invoke(.dynamic)...
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * Registry Item: The object net.minecraft.item.ItemBlock@2c663e66 has been registered twice for the same name tinkerscompendium:stake_sinisterium. 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:300) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:281) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.register(ForgeRegistry.java:113) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.core.materials.CompendiumMaterials.registerItems(CompendiumMaterials.java:1165) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.proxy.CommonProxy.registerItems(CommonProxy.java:99) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.fml.common.eventhandler.ASMEventHandler_582_CommonProxy_registerItems_Register.invoke(.dynamic)...
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * Registry Item: The object net.minecraft.item.ItemBlock@b3a796d has been registered twice for the same name tinkerscompendium:bars_sinisterium. 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:300) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:281) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.register(ForgeRegistry.java:113) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.core.materials.CompendiumMaterials.registerItems(CompendiumMaterials.java:1165) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.proxy.CommonProxy.registerItems(CommonProxy.java:99) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.fml.common.eventhandler.ASMEventHandler_582_CommonProxy_registerItems_Register.invoke(.dynamic)...
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * Registry Item: The object net.minecraft.item.ItemBlock@347cdadc has been registered twice for the same name tinkerscompendium:trapdoor_sinisterium. 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:300) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:281) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.register(ForgeRegistry.java:113) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.core.materials.CompendiumMaterials.registerItems(CompendiumMaterials.java:1165) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.proxy.CommonProxy.registerItems(CommonProxy.java:99) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.fml.common.eventhandler.ASMEventHandler_582_CommonProxy_registerItems_Register.invoke(.dynamic)...
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * Registry Item: The object net.minecraft.item.Item@29f4573b has been registered twice for the same name tinkerscompendium:ingot_nihilite. 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:300) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:281) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.register(ForgeRegistry.java:113) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.core.materials.CompendiumMaterials.registerItems(CompendiumMaterials.java:1165) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.proxy.CommonProxy.registerItems(CommonProxy.java:99) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.fml.common.eventhandler.ASMEventHandler_582_CommonProxy_registerItems_Register.invoke(.dynamic)...
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * Registry Item: The object net.minecraft.item.Item@715da279 has been registered twice for the same name tinkerscompendium:nugget_nihilite. 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:300) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:281) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.register(ForgeRegistry.java:113) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.core.materials.CompendiumMaterials.registerItems(CompendiumMaterials.java:1165) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.proxy.CommonProxy.registerItems(CommonProxy.java:99) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.fml.common.eventhandler.ASMEventHandler_582_CommonProxy_registerItems_Register.invoke(.dynamic)...
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * Registry Item: The object net.minecraft.item.ItemBlock@4d342508 has been registered twice for the same name tinkerscompendium:block_nihilite. 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:300) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:281) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.register(ForgeRegistry.java:113) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.core.materials.CompendiumMaterials.registerItems(CompendiumMaterials.java:1165) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.proxy.CommonProxy.registerItems(CommonProxy.java:99) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.fml.common.eventhandler.ASMEventHandler_582_CommonProxy_registerItems_Register.invoke(.dynamic)...
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * Registry Item: The object net.minecraft.item.Item@1fccbc48 has been registered twice for the same name tinkerscompendium:dust_nihilite. 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:300) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:281) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.register(ForgeRegistry.java:113) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.core.materials.CompendiumMaterials.registerItems(CompendiumMaterials.java:1165) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.proxy.CommonProxy.registerItems(CommonProxy.java:99) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.fml.common.eventhandler.ASMEventHandler_582_CommonProxy_registerItems_Register.invoke(.dynamic)...
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * Registry Item: The object net.minecraft.item.Item@148a7d05 has been registered twice for the same name tinkerscompendium:grain_nihilite. 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:300) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:281) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.register(ForgeRegistry.java:113) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.core.materials.CompendiumMaterials.registerItems(CompendiumMaterials.java:1165) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.proxy.CommonProxy.registerItems(CommonProxy.java:99) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.fml.common.eventhandler.ASMEventHandler_582_CommonProxy_registerItems_Register.invoke(.dynamic)...
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * Registry Item: The object net.minecraft.item.Item@8d85b87 has been registered twice for the same name tinkerscompendium:plate_nihilite. 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:300) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:281) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.register(ForgeRegistry.java:113) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.core.materials.CompendiumMaterials.registerItems(CompendiumMaterials.java:1165) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.proxy.CommonProxy.registerItems(CommonProxy.java:99) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.fml.common.eventhandler.ASMEventHandler_582_CommonProxy_registerItems_Register.invoke(.dynamic)...
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * Registry Item: The object net.minecraft.item.Item@642823f1 has been registered twice for the same name tinkerscompendium:coin_nihilite. 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:300) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:281) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.register(ForgeRegistry.java:113) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.core.materials.CompendiumMaterials.registerItems(CompendiumMaterials.java:1165) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.proxy.CommonProxy.registerItems(CommonProxy.java:99) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.fml.common.eventhandler.ASMEventHandler_582_CommonProxy_registerItems_Register.invoke(.dynamic)...
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * Registry Item: The object net.minecraft.item.Item@1e7cedc0 has been registered twice for the same name tinkerscompendium:gear_nihilite. 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:300) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:281) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.register(ForgeRegistry.java:113) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.core.materials.CompendiumMaterials.registerItems(CompendiumMaterials.java:1165) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.proxy.CommonProxy.registerItems(CommonProxy.java:99) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.fml.common.eventhandler.ASMEventHandler_582_CommonProxy_registerItems_Register.invoke(.dynamic)...
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * Registry Item: The object net.minecraft.item.Item@5959c95f has been registered twice for the same name tinkerscompendium:rod_nihilite. 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:300) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:281) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.register(ForgeRegistry.java:113) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.core.materials.CompendiumMaterials.registerItems(CompendiumMaterials.java:1165) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.proxy.CommonProxy.registerItems(CommonProxy.java:99) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.fml.common.eventhandler.ASMEventHandler_582_CommonProxy_registerItems_Register.invoke(.dynamic)...
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * Registry Item: The object net.minecraft.item.Item@1397b590 has been registered twice for the same name tinkerscompendium:coil_nihilite. 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:300) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:281) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.register(ForgeRegistry.java:113) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.core.materials.CompendiumMaterials.registerItems(CompendiumMaterials.java:1165) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.proxy.CommonProxy.registerItems(CommonProxy.java:99) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.fml.common.eventhandler.ASMEventHandler_582_CommonProxy_registerItems_Register.invoke(.dynamic)...
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * Registry Item: The object net.minecraft.item.Item@36052bb8 has been registered twice for the same name tinkerscompendium:spring_nihilite. 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:300) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:281) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.register(ForgeRegistry.java:113) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.core.materials.CompendiumMaterials.registerItems(CompendiumMaterials.java:1165) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.proxy.CommonProxy.registerItems(CommonProxy.java:99) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.fml.common.eventhandler.ASMEventHandler_582_CommonProxy_registerItems_Register.invoke(.dynamic)...
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * Registry Item: The object net.minecraft.item.Item@4f6ec255 has been registered twice for the same name tinkerscompendium:casing_nihilite. 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:300) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:281) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.register(ForgeRegistry.java:113) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.core.materials.CompendiumMaterials.registerItems(CompendiumMaterials.java:1165) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.proxy.CommonProxy.registerItems(CommonProxy.java:99) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.fml.common.eventhandler.ASMEventHandler_582_CommonProxy_registerItems_Register.invoke(.dynamic)...
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * Registry Item: The object net.minecraft.item.Item@586af9d6 has been registered twice for the same name tinkerscompendium:wire_nihilite. 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:300) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:281) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.register(ForgeRegistry.java:113) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.core.materials.CompendiumMaterials.registerItems(CompendiumMaterials.java:1165) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.proxy.CommonProxy.registerItems(CommonProxy.java:99) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.fml.common.eventhandler.ASMEventHandler_582_CommonProxy_registerItems_Register.invoke(.dynamic)...
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * Registry Item: The object net.minecraft.item.ItemBlock@76ffec7e has been registered twice for the same name tinkerscompendium:stake_nihilite. 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:300) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:281) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.register(ForgeRegistry.java:113) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.core.materials.CompendiumMaterials.registerItems(CompendiumMaterials.java:1165) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.proxy.CommonProxy.registerItems(CommonProxy.java:99) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.fml.common.eventhandler.ASMEventHandler_582_CommonProxy_registerItems_Register.invoke(.dynamic)...
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * Registry Item: The object net.minecraft.item.ItemBlock@693851f2 has been registered twice for the same name tinkerscompendium:bars_nihilite. 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:300) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:281) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.register(ForgeRegistry.java:113) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.core.materials.CompendiumMaterials.registerItems(CompendiumMaterials.java:1165) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.proxy.CommonProxy.registerItems(CommonProxy.java:99) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.fml.common.eventhandler.ASMEventHandler_582_CommonProxy_registerItems_Register.invoke(.dynamic)...
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * Registry Item: The object net.minecraft.item.ItemBlock@5fd6bd6a has been registered twice for the same name tinkerscompendium:trapdoor_nihilite. 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:300) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:281) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.register(ForgeRegistry.java:113) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.core.materials.CompendiumMaterials.registerItems(CompendiumMaterials.java:1165) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.proxy.CommonProxy.registerItems(CommonProxy.java:99) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.fml.common.eventhandler.ASMEventHandler_582_CommonProxy_registerItems_Register.invoke(.dynamic)...
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * Registry Item: The object net.minecraft.item.Item@56c326f2 has been registered twice for the same name tinkerscompendium:ingot_orichalcum. 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:300) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:281) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.register(ForgeRegistry.java:113) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.core.materials.CompendiumMaterials.registerItems(CompendiumMaterials.java:1165) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.proxy.CommonProxy.registerItems(CommonProxy.java:99) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.fml.common.eventhandler.ASMEventHandler_582_CommonProxy_registerItems_Register.invoke(.dynamic)...
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * Registry Item: The object net.minecraft.item.Item@7d5f5a19 has been registered twice for the same name tinkerscompendium:nugget_orichalcum. 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:300) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:281) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.register(ForgeRegistry.java:113) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.core.materials.CompendiumMaterials.registerItems(CompendiumMaterials.java:1165) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.proxy.CommonProxy.registerItems(CommonProxy.java:99) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.fml.common.eventhandler.ASMEventHandler_582_CommonProxy_registerItems_Register.invoke(.dynamic)...
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * Registry Item: The object net.minecraft.item.ItemBlock@47cf7552 has been registered twice for the same name tinkerscompendium:block_orichalcum. 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:300) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:281) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.register(ForgeRegistry.java:113) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.core.materials.CompendiumMaterials.registerItems(CompendiumMaterials.java:1165) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.proxy.CommonProxy.registerItems(CommonProxy.java:99) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.fml.common.eventhandler.ASMEventHandler_582_CommonProxy_registerItems_Register.invoke(.dynamic)...
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * Registry Item: The object net.minecraft.item.Item@2d98bd2c has been registered twice for the same name tinkerscompendium:dust_orichalcum. 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:300) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:281) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.register(ForgeRegistry.java:113) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.core.materials.CompendiumMaterials.registerItems(CompendiumMaterials.java:1165) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.proxy.CommonProxy.registerItems(CommonProxy.java:99) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.fml.common.eventhandler.ASMEventHandler_582_CommonProxy_registerItems_Register.invoke(.dynamic)...
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * Registry Item: The object net.minecraft.item.Item@6223eadb has been registered twice for the same name tinkerscompendium:grain_orichalcum. 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:300) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:281) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.register(ForgeRegistry.java:113) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.core.materials.CompendiumMaterials.registerItems(CompendiumMaterials.java:1165) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.proxy.CommonProxy.registerItems(CommonProxy.java:99) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.fml.common.eventhandler.ASMEventHandler_582_CommonProxy_registerItems_Register.invoke(.dynamic)...
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * Registry Item: The object net.minecraft.item.Item@652beb14 has been registered twice for the same name tinkerscompendium:plate_orichalcum. 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:300) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:281) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.register(ForgeRegistry.java:113) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.core.materials.CompendiumMaterials.registerItems(CompendiumMaterials.java:1165) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.proxy.CommonProxy.registerItems(CommonProxy.java:99) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.fml.common.eventhandler.ASMEventHandler_582_CommonProxy_registerItems_Register.invoke(.dynamic)...
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * Registry Item: The object net.minecraft.item.Item@59f26706 has been registered twice for the same name tinkerscompendium:coin_orichalcum. 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:300) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:281) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.register(ForgeRegistry.java:113) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.core.materials.CompendiumMaterials.registerItems(CompendiumMaterials.java:1165) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.proxy.CommonProxy.registerItems(CommonProxy.java:99) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.fml.common.eventhandler.ASMEventHandler_582_CommonProxy_registerItems_Register.invoke(.dynamic)...
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * Registry Item: The object net.minecraft.item.Item@31ebd0c9 has been registered twice for the same name tinkerscompendium:gear_orichalcum. 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:300) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:281) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.register(ForgeRegistry.java:113) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.core.materials.CompendiumMaterials.registerItems(CompendiumMaterials.java:1165) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.proxy.CommonProxy.registerItems(CommonProxy.java:99) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.fml.common.eventhandler.ASMEventHandler_582_CommonProxy_registerItems_Register.invoke(.dynamic)...
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * Registry Item: The object net.minecraft.item.Item@4c63811d has been registered twice for the same name tinkerscompendium:rod_orichalcum. 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:300) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:281) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.register(ForgeRegistry.java:113) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.core.materials.CompendiumMaterials.registerItems(CompendiumMaterials.java:1165) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.proxy.CommonProxy.registerItems(CommonProxy.java:99) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.fml.common.eventhandler.ASMEventHandler_582_CommonProxy_registerItems_Register.invoke(.dynamic)...
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * Registry Item: The object net.minecraft.item.Item@762ab0ce has been registered twice for the same name tinkerscompendium:coil_orichalcum. 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:300) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:281) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.register(ForgeRegistry.java:113) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.core.materials.CompendiumMaterials.registerItems(CompendiumMaterials.java:1165) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.proxy.CommonProxy.registerItems(CommonProxy.java:99) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.fml.common.eventhandler.ASMEventHandler_582_CommonProxy_registerItems_Register.invoke(.dynamic)...
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * Registry Item: The object net.minecraft.item.Item@3caa235a has been registered twice for the same name tinkerscompendium:spring_orichalcum. 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:300) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:281) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.register(ForgeRegistry.java:113) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.core.materials.CompendiumMaterials.registerItems(CompendiumMaterials.java:1165) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.proxy.CommonProxy.registerItems(CommonProxy.java:99) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.fml.common.eventhandler.ASMEventHandler_582_CommonProxy_registerItems_Register.invoke(.dynamic)...
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * Registry Item: The object net.minecraft.item.Item@5328d19e has been registered twice for the same name tinkerscompendium:casing_orichalcum. 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:300) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:281) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.register(ForgeRegistry.java:113) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.core.materials.CompendiumMaterials.registerItems(CompendiumMaterials.java:1165) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.proxy.CommonProxy.registerItems(CommonProxy.java:99) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.fml.common.eventhandler.ASMEventHandler_582_CommonProxy_registerItems_Register.invoke(.dynamic)...
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * Registry Item: The object net.minecraft.item.Item@313c98f has been registered twice for the same name tinkerscompendium:wire_orichalcum. 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:300) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:281) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.register(ForgeRegistry.java:113) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.core.materials.CompendiumMaterials.registerItems(CompendiumMaterials.java:1165) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.proxy.CommonProxy.registerItems(CommonProxy.java:99) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.fml.common.eventhandler.ASMEventHandler_582_CommonProxy_registerItems_Register.invoke(.dynamic)...
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * Registry Item: The object net.minecraft.item.ItemBlock@209cb5e3 has been registered twice for the same name tinkerscompendium:stake_orichalcum. 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:300) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:281) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.register(ForgeRegistry.java:113) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.core.materials.CompendiumMaterials.registerItems(CompendiumMaterials.java:1165) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.proxy.CommonProxy.registerItems(CommonProxy.java:99) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.fml.common.eventhandler.ASMEventHandler_582_CommonProxy_registerItems_Register.invoke(.dynamic)...
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * Registry Item: The object net.minecraft.item.ItemBlock@4d41e259 has been registered twice for the same name tinkerscompendium:bars_orichalcum. 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:300) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:281) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.register(ForgeRegistry.java:113) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.core.materials.CompendiumMaterials.registerItems(CompendiumMaterials.java:1165) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.proxy.CommonProxy.registerItems(CommonProxy.java:99) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.fml.common.eventhandler.ASMEventHandler_582_CommonProxy_registerItems_Register.invoke(.dynamic)...
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * Registry Item: The object net.minecraft.item.ItemBlock@45329b7e has been registered twice for the same name tinkerscompendium:trapdoor_orichalcum. 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:300) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:281) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.register(ForgeRegistry.java:113) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.core.materials.CompendiumMaterials.registerItems(CompendiumMaterials.java:1165) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.proxy.CommonProxy.registerItems(CommonProxy.java:99) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.fml.common.eventhandler.ASMEventHandler_582_CommonProxy_registerItems_Register.invoke(.dynamic)...
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * Registry Item: The object net.minecraft.item.Item@440d96 has been registered twice for the same name tinkerscompendium:ingot_pandorium. 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:300) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:281) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.register(ForgeRegistry.java:113) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.core.materials.CompendiumMaterials.registerItems(CompendiumMaterials.java:1165) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.proxy.CommonProxy.registerItems(CommonProxy.java:99) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.fml.common.eventhandler.ASMEventHandler_582_CommonProxy_registerItems_Register.invoke(.dynamic)...
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * Registry Item: The object net.minecraft.item.Item@42d574ed has been registered twice for the same name tinkerscompendium:nugget_pandorium. 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:300) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:281) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.register(ForgeRegistry.java:113) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.core.materials.CompendiumMaterials.registerItems(CompendiumMaterials.java:1165) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.proxy.CommonProxy.registerItems(CommonProxy.java:99) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.fml.common.eventhandler.ASMEventHandler_582_CommonProxy_registerItems_Register.invoke(.dynamic)...
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * Registry Item: The object net.minecraft.item.ItemBlock@198ce0f7 has been registered twice for the same name tinkerscompendium:block_pandorium. 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:300) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:281) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.register(ForgeRegistry.java:113) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.core.materials.CompendiumMaterials.registerItems(CompendiumMaterials.java:1165) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.proxy.CommonProxy.registerItems(CommonProxy.java:99) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.fml.common.eventhandler.ASMEventHandler_582_CommonProxy_registerItems_Register.invoke(.dynamic)...
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * Registry Item: The object net.minecraft.item.Item@48b461d3 has been registered twice for the same name tinkerscompendium:dust_pandorium. 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:300) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:281) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.register(ForgeRegistry.java:113) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.core.materials.CompendiumMaterials.registerItems(CompendiumMaterials.java:1165) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.proxy.CommonProxy.registerItems(CommonProxy.java:99) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.fml.common.eventhandler.ASMEventHandler_582_CommonProxy_registerItems_Register.invoke(.dynamic)...
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * Registry Item: The object net.minecraft.item.Item@68bcedee has been registered twice for the same name tinkerscompendium:grain_pandorium. 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:300) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:281) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.register(ForgeRegistry.java:113) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.core.materials.CompendiumMaterials.registerItems(CompendiumMaterials.java:1165) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.proxy.CommonProxy.registerItems(CommonProxy.java:99) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.fml.common.eventhandler.ASMEventHandler_582_CommonProxy_registerItems_Register.invoke(.dynamic)...
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * Registry Item: The object net.minecraft.item.Item@1a79e08 has been registered twice for the same name tinkerscompendium:plate_pandorium. 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:300) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:281) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.register(ForgeRegistry.java:113) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.core.materials.CompendiumMaterials.registerItems(CompendiumMaterials.java:1165) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.proxy.CommonProxy.registerItems(CommonProxy.java:99) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.fml.common.eventhandler.ASMEventHandler_582_CommonProxy_registerItems_Register.invoke(.dynamic)...
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * Registry Item: The object net.minecraft.item.Item@7f525d93 has been registered twice for the same name tinkerscompendium:coin_pandorium. 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:300) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:281) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.register(ForgeRegistry.java:113) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.core.materials.CompendiumMaterials.registerItems(CompendiumMaterials.java:1165) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.proxy.CommonProxy.registerItems(CommonProxy.java:99) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.fml.common.eventhandler.ASMEventHandler_582_CommonProxy_registerItems_Register.invoke(.dynamic)...
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * Registry Item: The object net.minecraft.item.Item@14830153 has been registered twice for the same name tinkerscompendium:gear_pandorium. 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:300) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:281) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.register(ForgeRegistry.java:113) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.core.materials.CompendiumMaterials.registerItems(CompendiumMaterials.java:1165) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.proxy.CommonProxy.registerItems(CommonProxy.java:99) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.fml.common.eventhandler.ASMEventHandler_582_CommonProxy_registerItems_Register.invoke(.dynamic)...
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * Registry Item: The object net.minecraft.item.Item@1b5f5db0 has been registered twice for the same name tinkerscompendium:rod_pandorium. 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:300) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:281) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.register(ForgeRegistry.java:113) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.core.materials.CompendiumMaterials.registerItems(CompendiumMaterials.java:1165) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.proxy.CommonProxy.registerItems(CommonProxy.java:99) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.fml.common.eventhandler.ASMEventHandler_582_CommonProxy_registerItems_Register.invoke(.dynamic)...
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * Registry Item: The object net.minecraft.item.Item@26b5c70d has been registered twice for the same name tinkerscompendium:coil_pandorium. 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:300) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:281) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.register(ForgeRegistry.java:113) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.core.materials.CompendiumMaterials.registerItems(CompendiumMaterials.java:1165) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.proxy.CommonProxy.registerItems(CommonProxy.java:99) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.fml.common.eventhandler.ASMEventHandler_582_CommonProxy_registerItems_Register.invoke(.dynamic)...
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * Registry Item: The object net.minecraft.item.Item@4b66b88d has been registered twice for the same name tinkerscompendium:spring_pandorium. 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:300) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:281) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.register(ForgeRegistry.java:113) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.core.materials.CompendiumMaterials.registerItems(CompendiumMaterials.java:1165) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.proxy.CommonProxy.registerItems(CommonProxy.java:99) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.fml.common.eventhandler.ASMEventHandler_582_CommonProxy_registerItems_Register.invoke(.dynamic)...
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * Registry Item: The object net.minecraft.item.Item@4763a12b has been registered twice for the same name tinkerscompendium:casing_pandorium. 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:300) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:281) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.register(ForgeRegistry.java:113) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.core.materials.CompendiumMaterials.registerItems(CompendiumMaterials.java:1165) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.proxy.CommonProxy.registerItems(CommonProxy.java:99) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.fml.common.eventhandler.ASMEventHandler_582_CommonProxy_registerItems_Register.invoke(.dynamic)...
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * Registry Item: The object net.minecraft.item.Item@26b0d6aa has been registered twice for the same name tinkerscompendium:wire_pandorium. 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:300) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:281) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.register(ForgeRegistry.java:113) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.core.materials.CompendiumMaterials.registerItems(CompendiumMaterials.java:1165) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.proxy.CommonProxy.registerItems(CommonProxy.java:99) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.fml.common.eventhandler.ASMEventHandler_582_CommonProxy_registerItems_Register.invoke(.dynamic)...
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * Registry Item: The object net.minecraft.item.ItemBlock@2eb5e0de has been registered twice for the same name tinkerscompendium:stake_pandorium. 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:300) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:281) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.register(ForgeRegistry.java:113) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.core.materials.CompendiumMaterials.registerItems(CompendiumMaterials.java:1165) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.proxy.CommonProxy.registerItems(CommonProxy.java:99) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.fml.common.eventhandler.ASMEventHandler_582_CommonProxy_registerItems_Register.invoke(.dynamic)...
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * Registry Item: The object net.minecraft.item.ItemBlock@50699755 has been registered twice for the same name tinkerscompendium:bars_pandorium. 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:300) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:281) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.register(ForgeRegistry.java:113) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.core.materials.CompendiumMaterials.registerItems(CompendiumMaterials.java:1165) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.proxy.CommonProxy.registerItems(CommonProxy.java:99) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.fml.common.eventhandler.ASMEventHandler_582_CommonProxy_registerItems_Register.invoke(.dynamic)...
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * Registry Item: The object net.minecraft.item.ItemBlock@2afc9cfd has been registered twice for the same name tinkerscompendium:trapdoor_pandorium. 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:300) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:281) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.register(ForgeRegistry.java:113) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.core.materials.CompendiumMaterials.registerItems(CompendiumMaterials.java:1165) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.proxy.CommonProxy.registerItems(CommonProxy.java:99) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.fml.common.eventhandler.ASMEventHandler_582_CommonProxy_registerItems_Register.invoke(.dynamic)...
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * Registry Item: The object net.minecraft.item.Item@2bce2a6c has been registered twice for the same name tinkerscompendium:dust_gold. 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:300) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:281) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.register(ForgeRegistry.java:113) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.core.materials.CompendiumMaterials.registerItems(CompendiumMaterials.java:1165) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.proxy.CommonProxy.registerItems(CommonProxy.java:99) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.fml.common.eventhandler.ASMEventHandler_582_CommonProxy_registerItems_Register.invoke(.dynamic)...
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * Registry Item: The object net.minecraft.item.Item@3701c37f has been registered twice for the same name tinkerscompendium:grain_gold. 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:300) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:281) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.register(ForgeRegistry.java:113) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.core.materials.CompendiumMaterials.registerItems(CompendiumMaterials.java:1165) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.proxy.CommonProxy.registerItems(CommonProxy.java:99) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.fml.common.eventhandler.ASMEventHandler_582_CommonProxy_registerItems_Register.invoke(.dynamic)...
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * Registry Item: The object net.minecraft.item.Item@75ee364b has been registered twice for the same name tinkerscompendium:plate_gold. 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:300) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:281) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.register(ForgeRegistry.java:113) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.core.materials.CompendiumMaterials.registerItems(CompendiumMaterials.java:1165) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.proxy.CommonProxy.registerItems(CommonProxy.java:99) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.fml.common.eventhandler.ASMEventHandler_582_CommonProxy_registerItems_Register.invoke(.dynamic)...
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * Registry Item: The object net.minecraft.item.Item@3bbb577f has been registered twice for the same name tinkerscompendium:coin_gold. 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:300) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:281) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.register(ForgeRegistry.java:113) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.core.materials.CompendiumMaterials.registerItems(CompendiumMaterials.java:1165) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.proxy.CommonProxy.registerItems(CommonProxy.java:99) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.fml.common.eventhandler.ASMEventHandler_582_CommonProxy_registerItems_Register.invoke(.dynamic)...
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * Registry Item: The object net.minecraft.item.Item@617c872e has been registered twice for the same name tinkerscompendium:gear_gold. 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:300) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:281) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.register(ForgeRegistry.java:113) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.core.materials.CompendiumMaterials.registerItems(CompendiumMaterials.java:1165) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.proxy.CommonProxy.registerItems(CommonProxy.java:99) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.fml.common.eventhandler.ASMEventHandler_582_CommonProxy_registerItems_Register.invoke(.dynamic)...
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * Registry Item: The object net.minecraft.item.Item@585faa45 has been registered twice for the same name tinkerscompendium:rod_gold. 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:300) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:281) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.register(ForgeRegistry.java:113) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.core.materials.CompendiumMaterials.registerItems(CompendiumMaterials.java:1165) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.proxy.CommonProxy.registerItems(CommonProxy.java:99) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.fml.common.eventhandler.ASMEventHandler_582_CommonProxy_registerItems_Register.invoke(.dynamic)...
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * Registry Item: The object net.minecraft.item.Item@5c07936b has been registered twice for the same name tinkerscompendium:coil_gold. 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:300) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:281) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.register(ForgeRegistry.java:113) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.core.materials.CompendiumMaterials.registerItems(CompendiumMaterials.java:1165) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.proxy.CommonProxy.registerItems(CommonProxy.java:99) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.fml.common.eventhandler.ASMEventHandler_582_CommonProxy_registerItems_Register.invoke(.dynamic)...
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * Registry Item: The object net.minecraft.item.Item@3de6373b has been registered twice for the same name tinkerscompendium:spring_gold. 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:300) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:281) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.register(ForgeRegistry.java:113) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.core.materials.CompendiumMaterials.registerItems(CompendiumMaterials.java:1165) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.proxy.CommonProxy.registerItems(CommonProxy.java:99) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.fml.common.eventhandler.ASMEventHandler_582_CommonProxy_registerItems_Register.invoke(.dynamic)...
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * Registry Item: The object net.minecraft.item.Item@3826925e has been registered twice for the same name tinkerscompendium:casing_gold. 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:300) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:281) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.register(ForgeRegistry.java:113) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.core.materials.CompendiumMaterials.registerItems(CompendiumMaterials.java:1165) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.proxy.CommonProxy.registerItems(CommonProxy.java:99) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.fml.common.eventhandler.ASMEventHandler_582_CommonProxy_registerItems_Register.invoke(.dynamic)...
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * Registry Item: The object net.minecraft.item.Item@1d8e1a9d has been registered twice for the same name tinkerscompendium:wire_gold. 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:300) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:281) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.register(ForgeRegistry.java:113) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.core.materials.CompendiumMaterials.registerItems(CompendiumMaterials.java:1165) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.proxy.CommonProxy.registerItems(CommonProxy.java:99) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.fml.common.eventhandler.ASMEventHandler_582_CommonProxy_registerItems_Register.invoke(.dynamic)...
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * Registry Item: The object net.minecraft.item.ItemBlock@7d725e8c has been registered twice for the same name tinkerscompendium:stake_gold. 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:300) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:281) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.register(ForgeRegistry.java:113) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.core.materials.CompendiumMaterials.registerItems(CompendiumMaterials.java:1165) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.proxy.CommonProxy.registerItems(CommonProxy.java:99) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.fml.common.eventhandler.ASMEventHandler_582_CommonProxy_registerItems_Register.invoke(.dynamic)...
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * Registry Item: The object net.minecraft.item.ItemBlock@71a1f1f6 has been registered twice for the same name tinkerscompendium:bars_gold. 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:300) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:281) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.register(ForgeRegistry.java:113) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.core.materials.CompendiumMaterials.registerItems(CompendiumMaterials.java:1165) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.proxy.CommonProxy.registerItems(CommonProxy.java:99) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.fml.common.eventhandler.ASMEventHandler_582_CommonProxy_registerItems_Register.invoke(.dynamic)...
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * Registry Item: The object net.minecraft.item.ItemBlock@10ae8e32 has been registered twice for the same name tinkerscompendium:trapdoor_gold. 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:300) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:281) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.register(ForgeRegistry.java:113) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.core.materials.CompendiumMaterials.registerItems(CompendiumMaterials.java:1165) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.proxy.CommonProxy.registerItems(CommonProxy.java:99) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.fml.common.eventhandler.ASMEventHandler_582_CommonProxy_registerItems_Register.invoke(.dynamic)...
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * Registry Item: The object net.minecraft.item.Item@7f472495 has been registered twice for the same name tinkerscompendium:dust_silver. 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:300) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:281) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.register(ForgeRegistry.java:113) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.core.materials.CompendiumMaterials.registerItems(CompendiumMaterials.java:1165) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.proxy.CommonProxy.registerItems(CommonProxy.java:99) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.fml.common.eventhandler.ASMEventHandler_582_CommonProxy_registerItems_Register.invoke(.dynamic)...
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * Registry Item: The object net.minecraft.item.Item@11754ca has been registered twice for the same name tinkerscompendium:grain_silver. 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:300) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:281) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.register(ForgeRegistry.java:113) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.core.materials.CompendiumMaterials.registerItems(CompendiumMaterials.java:1165) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.proxy.CommonProxy.registerItems(CommonProxy.java:99) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.fml.common.eventhandler.ASMEventHandler_582_CommonProxy_registerItems_Register.invoke(.dynamic)...
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * Registry Item: The object net.minecraft.item.Item@35f5cbcf has been registered twice for the same name tinkerscompendium:plate_silver. 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:300) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:281) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.register(ForgeRegistry.java:113) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.core.materials.CompendiumMaterials.registerItems(CompendiumMaterials.java:1165) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.proxy.CommonProxy.registerItems(CommonProxy.java:99) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.fml.common.eventhandler.ASMEventHandler_582_CommonProxy_registerItems_Register.invoke(.dynamic)...
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * Registry Item: The object net.minecraft.item.Item@51ce0c5d has been registered twice for the same name tinkerscompendium:coin_silver. 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:300) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:281) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.register(ForgeRegistry.java:113) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.core.materials.CompendiumMaterials.registerItems(CompendiumMaterials.java:1165) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.proxy.CommonProxy.registerItems(CommonProxy.java:99) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.fml.common.eventhandler.ASMEventHandler_582_CommonProxy_registerItems_Register.invoke(.dynamic)...
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * Registry Item: The object net.minecraft.item.Item@176bf97d has been registered twice for the same name tinkerscompendium:gear_silver. 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:300) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:281) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.register(ForgeRegistry.java:113) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.core.materials.CompendiumMaterials.registerItems(CompendiumMaterials.java:1165) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.proxy.CommonProxy.registerItems(CommonProxy.java:99) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.fml.common.eventhandler.ASMEventHandler_582_CommonProxy_registerItems_Register.invoke(.dynamic)...
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * Registry Item: The object net.minecraft.item.Item@2ce14e5e has been registered twice for the same name tinkerscompendium:rod_silver. 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:300) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:281) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.register(ForgeRegistry.java:113) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.core.materials.CompendiumMaterials.registerItems(CompendiumMaterials.java:1165) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.proxy.CommonProxy.registerItems(CommonProxy.java:99) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.fml.common.eventhandler.ASMEventHandler_582_CommonProxy_registerItems_Register.invoke(.dynamic)...
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * Registry Item: The object net.minecraft.item.Item@37d153be has been registered twice for the same name tinkerscompendium:coil_silver. 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:300) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:281) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.register(ForgeRegistry.java:113) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.core.materials.CompendiumMaterials.registerItems(CompendiumMaterials.java:1165) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.proxy.CommonProxy.registerItems(CommonProxy.java:99) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.fml.common.eventhandler.ASMEventHandler_582_CommonProxy_registerItems_Register.invoke(.dynamic)...
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * Registry Item: The object net.minecraft.item.Item@16dc0dfd has been registered twice for the same name tinkerscompendium:spring_silver. 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:300) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:281) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.register(ForgeRegistry.java:113) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.core.materials.CompendiumMaterials.registerItems(CompendiumMaterials.java:1165) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.proxy.CommonProxy.registerItems(CommonProxy.java:99) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.fml.common.eventhandler.ASMEventHandler_582_CommonProxy_registerItems_Register.invoke(.dynamic)...
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * Registry Item: The object net.minecraft.item.Item@5e34be4a has been registered twice for the same name tinkerscompendium:casing_silver. 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:300) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:281) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.register(ForgeRegistry.java:113) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.core.materials.CompendiumMaterials.registerItems(CompendiumMaterials.java:1165) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.proxy.CommonProxy.registerItems(CommonProxy.java:99) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.fml.common.eventhandler.ASMEventHandler_582_CommonProxy_registerItems_Register.invoke(.dynamic)...
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * Registry Item: The object net.minecraft.item.Item@7881986c has been registered twice for the same name tinkerscompendium:wire_silver. 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:300) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:281) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.register(ForgeRegistry.java:113) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.core.materials.CompendiumMaterials.registerItems(CompendiumMaterials.java:1165) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.proxy.CommonProxy.registerItems(CommonProxy.java:99) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.fml.common.eventhandler.ASMEventHandler_582_CommonProxy_registerItems_Register.invoke(.dynamic)...
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * Registry Item: The object net.minecraft.item.ItemBlock@45f07861 has been registered twice for the same name tinkerscompendium:stake_silver. 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:300) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:281) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.register(ForgeRegistry.java:113) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.core.materials.CompendiumMaterials.registerItems(CompendiumMaterials.java:1165) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.proxy.CommonProxy.registerItems(CommonProxy.java:99) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.fml.common.eventhandler.ASMEventHandler_582_CommonProxy_registerItems_Register.invoke(.dynamic)...
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * Registry Item: The object net.minecraft.item.ItemBlock@33b526c7 has been registered twice for the same name tinkerscompendium:bars_silver. 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:300) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:281) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.register(ForgeRegistry.java:113) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.core.materials.CompendiumMaterials.registerItems(CompendiumMaterials.java:1165) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.proxy.CommonProxy.registerItems(CommonProxy.java:99) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.fml.common.eventhandler.ASMEventHandler_582_CommonProxy_registerItems_Register.invoke(.dynamic)...
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * Registry Item: The object net.minecraft.item.ItemBlock@3cbeab90 has been registered twice for the same name tinkerscompendium:trapdoor_silver. 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:300) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:281) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.register(ForgeRegistry.java:113) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.core.materials.CompendiumMaterials.registerItems(CompendiumMaterials.java:1165) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.proxy.CommonProxy.registerItems(CommonProxy.java:99) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.fml.common.eventhandler.ASMEventHandler_582_CommonProxy_registerItems_Register.invoke(.dynamic)...
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * Registry Item: The object net.minecraft.item.ItemBlock@7a4bef16 has been registered twice for the same name tinkerscompendium:item_node_ore_silver. 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:300) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:281) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.register(ForgeRegistry.java:113) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.core.materials.CompendiumMaterials.registerItems(CompendiumMaterials.java:1165) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.proxy.CommonProxy.registerItems(CommonProxy.java:99) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.fml.common.eventhandler.ASMEventHandler_582_CommonProxy_registerItems_Register.invoke(.dynamic)...
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * Registry Item: The object net.minecraft.item.Item@60d26d86 has been registered twice for the same name tinkerscompendium:ingot_valyriansteel. 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:300) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:281) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.register(ForgeRegistry.java:113) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.core.materials.CompendiumMaterials.registerItems(CompendiumMaterials.java:1165) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.proxy.CommonProxy.registerItems(CommonProxy.java:99) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.fml.common.eventhandler.ASMEventHandler_582_CommonProxy_registerItems_Register.invoke(.dynamic)...
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * Registry Item: The object net.minecraft.item.Item@68928939 has been registered twice for the same name tinkerscompendium:nugget_valyriansteel. 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:300) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:281) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.register(ForgeRegistry.java:113) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.core.materials.CompendiumMaterials.registerItems(CompendiumMaterials.java:1165) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.proxy.CommonProxy.registerItems(CommonProxy.java:99) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.fml.common.eventhandler.ASMEventHandler_582_CommonProxy_registerItems_Register.invoke(.dynamic)...
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * Registry Item: The object net.minecraft.item.ItemBlock@21b95d90 has been registered twice for the same name tinkerscompendium:block_valyriansteel. 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:300) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:281) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.register(ForgeRegistry.java:113) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.core.materials.CompendiumMaterials.registerItems(CompendiumMaterials.java:1165) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.proxy.CommonProxy.registerItems(CommonProxy.java:99) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.fml.common.eventhandler.ASMEventHandler_582_CommonProxy_registerItems_Register.invoke(.dynamic)...
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * Registry Item: The object net.minecraft.item.Item@42f35ee has been registered twice for the same name tinkerscompendium:dust_valyriansteel. 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:300) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:281) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.register(ForgeRegistry.java:113) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.core.materials.CompendiumMaterials.registerItems(CompendiumMaterials.java:1165) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.proxy.CommonProxy.registerItems(CommonProxy.java:99) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.fml.common.eventhandler.ASMEventHandler_582_CommonProxy_registerItems_Register.invoke(.dynamic)...
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * Registry Item: The object net.minecraft.item.Item@77e2c6b0 has been registered twice for the same name tinkerscompendium:grain_valyriansteel. 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:300) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:281) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.register(ForgeRegistry.java:113) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.core.materials.CompendiumMaterials.registerItems(CompendiumMaterials.java:1165) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.proxy.CommonProxy.registerItems(CommonProxy.java:99) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.fml.common.eventhandler.ASMEventHandler_582_CommonProxy_registerItems_Register.invoke(.dynamic)...
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * Registry Item: The object net.minecraft.item.Item@b454234 has been registered twice for the same name tinkerscompendium:plate_valyriansteel. 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:300) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:281) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.register(ForgeRegistry.java:113) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.core.materials.CompendiumMaterials.registerItems(CompendiumMaterials.java:1165) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.proxy.CommonProxy.registerItems(CommonProxy.java:99) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.fml.common.eventhandler.ASMEventHandler_582_CommonProxy_registerItems_Register.invoke(.dynamic)...
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * Registry Item: The object net.minecraft.item.Item@60fbdb11 has been registered twice for the same name tinkerscompendium:coin_valyriansteel. 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:300) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:281) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.register(ForgeRegistry.java:113) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.core.materials.CompendiumMaterials.registerItems(CompendiumMaterials.java:1165) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.proxy.CommonProxy.registerItems(CommonProxy.java:99) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.fml.common.eventhandler.ASMEventHandler_582_CommonProxy_registerItems_Register.invoke(.dynamic)...
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * Registry Item: The object net.minecraft.item.Item@1d8612a5 has been registered twice for the same name tinkerscompendium:gear_valyriansteel. 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:300) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:281) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.register(ForgeRegistry.java:113) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.core.materials.CompendiumMaterials.registerItems(CompendiumMaterials.java:1165) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.proxy.CommonProxy.registerItems(CommonProxy.java:99) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.fml.common.eventhandler.ASMEventHandler_582_CommonProxy_registerItems_Register.invoke(.dynamic)...
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * Registry Item: The object net.minecraft.item.Item@7cb090e3 has been registered twice for the same name tinkerscompendium:rod_valyriansteel. 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:300) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:281) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.register(ForgeRegistry.java:113) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.core.materials.CompendiumMaterials.registerItems(CompendiumMaterials.java:1165) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.proxy.CommonProxy.registerItems(CommonProxy.java:99) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.fml.common.eventhandler.ASMEventHandler_582_CommonProxy_registerItems_Register.invoke(.dynamic)...
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * Registry Item: The object net.minecraft.item.Item@5d4529a3 has been registered twice for the same name tinkerscompendium:coil_valyriansteel. 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:300) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:281) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.register(ForgeRegistry.java:113) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.core.materials.CompendiumMaterials.registerItems(CompendiumMaterials.java:1165) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.proxy.CommonProxy.registerItems(CommonProxy.java:99) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.fml.common.eventhandler.ASMEventHandler_582_CommonProxy_registerItems_Register.invoke(.dynamic)...
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * Registry Item: The object net.minecraft.item.Item@63d84249 has been registered twice for the same name tinkerscompendium:spring_valyriansteel. 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:300) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:281) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.register(ForgeRegistry.java:113) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.core.materials.CompendiumMaterials.registerItems(CompendiumMaterials.java:1165) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.proxy.CommonProxy.registerItems(CommonProxy.java:99) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.fml.common.eventhandler.ASMEventHandler_582_CommonProxy_registerItems_Register.invoke(.dynamic)...
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * Registry Item: The object net.minecraft.item.Item@4e6667ad has been registered twice for the same name tinkerscompendium:casing_valyriansteel. 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:300) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:281) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.register(ForgeRegistry.java:113) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.core.materials.CompendiumMaterials.registerItems(CompendiumMaterials.java:1165) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.proxy.CommonProxy.registerItems(CommonProxy.java:99) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.fml.common.eventhandler.ASMEventHandler_582_CommonProxy_registerItems_Register.invoke(.dynamic)...
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * Registry Item: The object net.minecraft.item.Item@36a9c10a has been registered twice for the same name tinkerscompendium:wire_valyriansteel. 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:300) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:281) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.register(ForgeRegistry.java:113) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.core.materials.CompendiumMaterials.registerItems(CompendiumMaterials.java:1165) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.proxy.CommonProxy.registerItems(CommonProxy.java:99) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.fml.common.eventhandler.ASMEventHandler_582_CommonProxy_registerItems_Register.invoke(.dynamic)...
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * Registry Item: The object net.minecraft.item.ItemBlock@4255fe4d has been registered twice for the same name tinkerscompendium:stake_valyriansteel. 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:300) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:281) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.register(ForgeRegistry.java:113) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.core.materials.CompendiumMaterials.registerItems(CompendiumMaterials.java:1165) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.proxy.CommonProxy.registerItems(CommonProxy.java:99) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.fml.common.eventhandler.ASMEventHandler_582_CommonProxy_registerItems_Register.invoke(.dynamic)...
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * Registry Item: The object net.minecraft.item.ItemBlock@633e2644 has been registered twice for the same name tinkerscompendium:bars_valyriansteel. 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:300) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:281) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.register(ForgeRegistry.java:113) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.core.materials.CompendiumMaterials.registerItems(CompendiumMaterials.java:1165) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.proxy.CommonProxy.registerItems(CommonProxy.java:99) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.fml.common.eventhandler.ASMEventHandler_582_CommonProxy_registerItems_Register.invoke(.dynamic)...
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * Registry Item: The object net.minecraft.item.ItemBlock@66415dc9 has been registered twice for the same name tinkerscompendium:trapdoor_valyriansteel. 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:300) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:281) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.register(ForgeRegistry.java:113) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.core.materials.CompendiumMaterials.registerItems(CompendiumMaterials.java:1165) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.proxy.CommonProxy.registerItems(CommonProxy.java:99) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.fml.common.eventhandler.ASMEventHandler_582_CommonProxy_registerItems_Register.invoke(.dynamic)...
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * Registry Item: The object net.minecraft.item.Item@b8b70da has been registered twice for the same name tinkerscompendium:ingot_froststeel. 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:300) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:281) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.register(ForgeRegistry.java:113) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.core.materials.CompendiumMaterials.registerItems(CompendiumMaterials.java:1165) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.proxy.CommonProxy.registerItems(CommonProxy.java:99) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.fml.common.eventhandler.ASMEventHandler_582_CommonProxy_registerItems_Register.invoke(.dynamic)...
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * Registry Item: The object net.minecraft.item.Item@19156be9 has been registered twice for the same name tinkerscompendium:nugget_froststeel. 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:300) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:281) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.register(ForgeRegistry.java:113) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.core.materials.CompendiumMaterials.registerItems(CompendiumMaterials.java:1165) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.proxy.CommonProxy.registerItems(CommonProxy.java:99) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.fml.common.eventhandler.ASMEventHandler_582_CommonProxy_registerItems_Register.invoke(.dynamic)...
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * Registry Item: The object net.minecraft.item.ItemBlock@4424723c has been registered twice for the same name tinkerscompendium:block_froststeel. 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:300) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:281) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.register(ForgeRegistry.java:113) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.core.materials.CompendiumMaterials.registerItems(CompendiumMaterials.java:1165) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.proxy.CommonProxy.registerItems(CommonProxy.java:99) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.fml.common.eventhandler.ASMEventHandler_582_CommonProxy_registerItems_Register.invoke(.dynamic)...
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * Registry Item: The object net.minecraft.item.Item@2867c064 has been registered twice for the same name tinkerscompendium:dust_froststeel. 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:300) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:281) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.register(ForgeRegistry.java:113) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.core.materials.CompendiumMaterials.registerItems(CompendiumMaterials.java:1165) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.proxy.CommonProxy.registerItems(CommonProxy.java:99) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.fml.common.eventhandler.ASMEventHandler_582_CommonProxy_registerItems_Register.invoke(.dynamic)...
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * Registry Item: The object net.minecraft.item.Item@78ba7812 has been registered twice for the same name tinkerscompendium:grain_froststeel. 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:300) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:281) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.register(ForgeRegistry.java:113) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.core.materials.CompendiumMaterials.registerItems(CompendiumMaterials.java:1165) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.proxy.CommonProxy.registerItems(CommonProxy.java:99) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.fml.common.eventhandler.ASMEventHandler_582_CommonProxy_registerItems_Register.invoke(.dynamic)...
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * Registry Item: The object net.minecraft.item.Item@4a421ecf has been registered twice for the same name tinkerscompendium:plate_froststeel. 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:300) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:281) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.register(ForgeRegistry.java:113) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.core.materials.CompendiumMaterials.registerItems(CompendiumMaterials.java:1165) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.proxy.CommonProxy.registerItems(CommonProxy.java:99) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.fml.common.eventhandler.ASMEventHandler_582_CommonProxy_registerItems_Register.invoke(.dynamic)...
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * Registry Item: The object net.minecraft.item.Item@2d902029 has been registered twice for the same name tinkerscompendium:coin_froststeel. 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:300) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:281) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.register(ForgeRegistry.java:113) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.core.materials.CompendiumMaterials.registerItems(CompendiumMaterials.java:1165) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.proxy.CommonProxy.registerItems(CommonProxy.java:99) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.fml.common.eventhandler.ASMEventHandler_582_CommonProxy_registerItems_Register.invoke(.dynamic)...
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * Registry Item: The object net.minecraft.item.Item@3b62b11f has been registered twice for the same name tinkerscompendium:gear_froststeel. 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:300) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:281) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.register(ForgeRegistry.java:113) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.core.materials.CompendiumMaterials.registerItems(CompendiumMaterials.java:1165) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.proxy.CommonProxy.registerItems(CommonProxy.java:99) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.fml.common.eventhandler.ASMEventHandler_582_CommonProxy_registerItems_Register.invoke(.dynamic)...
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * Registry Item: The object net.minecraft.item.Item@10b32489 has been registered twice for the same name tinkerscompendium:rod_froststeel. 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:300) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:281) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.register(ForgeRegistry.java:113) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.core.materials.CompendiumMaterials.registerItems(CompendiumMaterials.java:1165) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.proxy.CommonProxy.registerItems(CommonProxy.java:99) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.fml.common.eventhandler.ASMEventHandler_582_CommonProxy_registerItems_Register.invoke(.dynamic)...
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * Registry Item: The object net.minecraft.item.Item@4adde436 has been registered twice for the same name tinkerscompendium:coil_froststeel. 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:300) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:281) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.register(ForgeRegistry.java:113) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.core.materials.CompendiumMaterials.registerItems(CompendiumMaterials.java:1165) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.proxy.CommonProxy.registerItems(CommonProxy.java:99) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.fml.common.eventhandler.ASMEventHandler_582_CommonProxy_registerItems_Register.invoke(.dynamic)...
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * Registry Item: The object net.minecraft.item.Item@6660142c has been registered twice for the same name tinkerscompendium:spring_froststeel. 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:300) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:281) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.register(ForgeRegistry.java:113) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.core.materials.CompendiumMaterials.registerItems(CompendiumMaterials.java:1165) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.proxy.CommonProxy.registerItems(CommonProxy.java:99) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.fml.common.eventhandler.ASMEventHandler_582_CommonProxy_registerItems_Register.invoke(.dynamic)...
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * Registry Item: The object net.minecraft.item.Item@48a4bbb6 has been registered twice for the same name tinkerscompendium:casing_froststeel. 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:300) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:281) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.register(ForgeRegistry.java:113) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.core.materials.CompendiumMaterials.registerItems(CompendiumMaterials.java:1165) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.proxy.CommonProxy.registerItems(CommonProxy.java:99) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.fml.common.eventhandler.ASMEventHandler_582_CommonProxy_registerItems_Register.invoke(.dynamic)...
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * Registry Item: The object net.minecraft.item.Item@413a4947 has been registered twice for the same name tinkerscompendium:wire_froststeel. 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:300) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:281) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.register(ForgeRegistry.java:113) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.core.materials.CompendiumMaterials.registerItems(CompendiumMaterials.java:1165) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.proxy.CommonProxy.registerItems(CommonProxy.java:99) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.fml.common.eventhandler.ASMEventHandler_582_CommonProxy_registerItems_Register.invoke(.dynamic)...
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * Registry Item: The object net.minecraft.item.ItemBlock@6463e902 has been registered twice for the same name tinkerscompendium:stake_froststeel. 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:300) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:281) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.register(ForgeRegistry.java:113) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.core.materials.CompendiumMaterials.registerItems(CompendiumMaterials.java:1165) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.proxy.CommonProxy.registerItems(CommonProxy.java:99) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.fml.common.eventhandler.ASMEventHandler_582_CommonProxy_registerItems_Register.invoke(.dynamic)...
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * Registry Item: The object net.minecraft.item.ItemBlock@2c440d6 has been registered twice for the same name tinkerscompendium:bars_froststeel. 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:300) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:281) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.register(ForgeRegistry.java:113) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.core.materials.CompendiumMaterials.registerItems(CompendiumMaterials.java:1165) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.proxy.CommonProxy.registerItems(CommonProxy.java:99) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.fml.common.eventhandler.ASMEventHandler_582_CommonProxy_registerItems_Register.invoke(.dynamic)...
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * Registry Item: The object net.minecraft.item.ItemBlock@7c333eff has been registered twice for the same name tinkerscompendium:trapdoor_froststeel. 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:300) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.add(ForgeRegistry.java:281) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.registries.ForgeRegistry.register(ForgeRegistry.java:113) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.core.materials.CompendiumMaterials.registerItems(CompendiumMaterials.java:1165) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at lance5057.tDefense.proxy.CommonProxy.registerItems(CommonProxy.java:99) 
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: * at net.minecraftforge.fml.common.eventhandler.ASMEventHandler_582_CommonProxy_registerItems_Register.invoke(.dynamic)...
[39;0m> [K[17:48:40] [Server thread/WARN] [FML]: **************************************** 
[39;0m> [K[17:48:41] [Server thread/INFO] [FML]: Applying holder lookups 
> [K[17:48:41] [Server thread/INFO] [FML]: Holder lookups applied 
> [K[17:48:42] [Server thread/INFO] [FML]: Applying holder lookups 
> [K[17:48:42] [Server thread/INFO] [FML]: Holder lookups applied 
> [K[17:48:42] [Server thread/INFO] [FML]: Applying holder lookups 
> [K[17:48:42] [Server thread/INFO] [FML]: Holder lookups applied 
> [K[17:48:42] [Server thread/INFO] [FML]: Injecting itemstacks 
> [K[17:48:42] [Server thread/INFO] [FML]: Itemstack injection complete 
> [K[17:48:42] [Server thread/INFO] inecraft/DedicatedServer]: Loading properties 
> [K[17:48:42] [Server thread/INFO] inecraft/DedicatedServer]: Default game type: SURVIVAL 
> [K[17:48:42] [Server thread/INFO] inecraft/DedicatedServer]: Generating keypair 
> [K[17:48:43] [Server thread/INFO] inecraft/DedicatedServer]: Starting Minecraft server on 89.203.248.17:27895 
> [K[17:48:43] [Server thread/INFO] inecraft/NetworkSystem]: Using epoll channel type 
> [K[17:48:44] [Server thread/WARN] [pl.asie.charset.ModCharset]: Could not create IOutputSupplierFactory pl.asie.charset.module.storage.barrels.BarrelCartOutputSupplier: pl.asie.charset.module.storage.barrels.BarrelCartOutputSupplier 
[39;0m> [K[17:48:44] [Server thread/WARN] [pl.asie.charset.ModCharset]: Could not create IOutputSupplierFactory pl.asie.charset.module.storage.barrels.BarrelUpgradeOutputSupplier$Factory: pl.asie.charset.module.storage.barrels.BarrelUpgradeOutputSupplier$Factory 
[39;0m> [K[17:48:44] [Server thread/WARN] [pl.asie.charset.ModCharset]: Could not create IOutputSupplierFactory pl.asie.charset.module.storage.locks.KeyOutputSupplier$Factory: pl.asie.charset.module.storage.locks.KeyOutputSupplier$Factory 
[39;0m> [K[17:48:44] [Server thread/WARN] [pl.asie.charset.ModCharset]: Could not create IOutputSupplierFactory pl.asie.charset.module.storage.locks.LockOutputSupplier$Factory: pl.asie.charset.module.storage.locks.LockOutputSupplier$Factory 
[39;0m> [K[17:48:45] [Server thread/ERROR] [FML]: Parsing error loading recipe bibliocraft:markerpole 
com.google.gson.JsonSyntaxException: Invalid pattern: empty pattern not allowed 
at net.minecraftforge.common.crafting.CraftingHelper.lambda$init$14(CraftingHelper.java:487) ~[CraftingHelper.class:?] 
at net.minecraftforge.common.crafting.CraftingHelper.getRecipe(CraftingHelper.java:415) ~[CraftingHelper.class:?] 
at net.minecraftforge.common.crafting.CraftingHelper.lambda$loadRecipes$22(CraftingHelper.java:711) ~[CraftingHelper.class:?] 
at net.minecraftforge.common.crafting.CraftingHelper.findFiles(CraftingHelper.java:821) ~[CraftingHelper.class:?] 
at net.minecraftforge.common.crafting.CraftingHelper.loadRecipes(CraftingHelper.java:676) ~[CraftingHelper.class:?] 
at java.util.ArrayList.forEach(ArrayList.java:1257) [?:1.8.0_201] 
at net.minecraftforge.common.crafting.CraftingHelper.loadRecipes(CraftingHelper.java:626) [CraftingHelper.class:?] 
at net.minecraftforge.fml.common.Loader.initializeMods(Loader.java:742) [Loader.class:?] 
at net.minecraftforge.fml.server.FMLServerHandler.finishServerLoading(FMLServerHandler.java:108) [FMLServerHandler.class:?] 
at net.minecraftforge.fml.common.FMLCommonHandler.onServerStarted(FMLCommonHandler.java:338) [FMLCommonHandler.class:?] 
at net.minecraft.server.dedicated.DedicatedServer.init(DedicatedServer.java:219) [nz.class:?] 
at net.minecraft.server.MinecraftServer.run(MinecraftServer.java:486) [MinecraftServer.class:?] 
at java.lang.Thread.run(Thread.java:748) [?:1.8.0_201] 
[39;0m> [K[17:48:45] [Server thread/ERROR] [FML]: Parsing error loading recipe bibliocraft:clipboard 
com.google.gson.JsonSyntaxException: Invalid pattern: empty pattern not allowed 
at net.minecraftforge.common.crafting.CraftingHelper.lambda$init$14(CraftingHelper.java:487) ~[CraftingHelper.class:?] 
at net.minecraftforge.common.crafting.CraftingHelper.getRecipe(CraftingHelper.java:415) ~[CraftingHelper.class:?] 
at net.minecraftforge.common.crafting.CraftingHelper.lambda$loadRecipes$22(CraftingHelper.java:711) ~[CraftingHelper.class:?] 
at net.minecraftforge.common.crafting.CraftingHelper.findFiles(CraftingHelper.java:821) ~[CraftingHelper.class:?] 
at net.minecraftforge.common.crafting.CraftingHelper.loadRecipes(CraftingHelper.java:676) ~[CraftingHelper.class:?] 
at java.util.ArrayList.forEach(ArrayList.java:1257) [?:1.8.0_201] 
at net.minecraftforge.common.crafting.CraftingHelper.loadRecipes(CraftingHelper.java:626) [CraftingHelper.class:?] 
at net.minecraftforge.fml.common.Loader.initializeMods(Loader.java:742) [Loader.class:?] 
at net.minecraftforge.fml.server.FMLServerHandler.finishServerLoading(FMLServerHandler.java:108) [FMLServerHandler.class:?] 
at net.minecraftforge.fml.common.FMLCommonHandler.onServerStarted(FMLCommonHandler.java:338) [FMLCommonHandler.class:?] 
at net.minecraft.server.dedicated.DedicatedServer.init(DedicatedServer.java:219) [nz.class:?] 
at net.minecraft.server.MinecraftServer.run(MinecraftServer.java:486) [MinecraftServer.class:?] 
at java.lang.Thread.run(Thread.java:748) [?:1.8.0_201] 
[39;0m> [K[17:48:51] [Server thread/ERROR] [FML]: Parsing error loading recipe techguns:techguns_manual_alt 
com.google.gson.JsonSyntaxException: Unknown item 'patchouli:guide_book' 
at net.minecraftforge.common.crafting.CraftingHelper.getItemStack(CraftingHelper.java:213) ~[CraftingHelper.class:?] 
at net.minecraftforge.common.crafting.CraftingHelper.lambda$init$15(CraftingHelper.java:537) ~[CraftingHelper.class:?] 
at net.minecraftforge.common.crafting.CraftingHelper.getRecipe(CraftingHelper.java:415) ~[CraftingHelper.class:?] 
at net.minecraftforge.common.crafting.CraftingHelper.lambda$loadRecipes$22(CraftingHelper.java:711) ~[CraftingHelper.class:?] 
at net.minecraftforge.common.crafting.CraftingHelper.findFiles(CraftingHelper.java:821) ~[CraftingHelper.class:?] 
at net.minecraftforge.common.crafting.CraftingHelper.loadRecipes(CraftingHelper.java:676) ~[CraftingHelper.class:?] 
at java.util.ArrayList.forEach(ArrayList.java:1257) [?:1.8.0_201] 
at net.minecraftforge.common.crafting.CraftingHelper.loadRecipes(CraftingHelper.java:626) [CraftingHelper.class:?] 
at net.minecraftforge.fml.common.Loader.initializeMods(Loader.java:742) [Loader.class:?] 
at net.minecraftforge.fml.server.FMLServerHandler.finishServerLoading(FMLServerHandler.java:108) [FMLServerHandler.class:?] 
at net.minecraftforge.fml.common.FMLCommonHandler.onServerStarted(FMLCommonHandler.java:338) [FMLCommonHandler.class:?] 
at net.minecraft.server.dedicated.DedicatedServer.init(DedicatedServer.java:219) [nz.class:?] 
at net.minecraft.server.MinecraftServer.run(MinecraftServer.java:486) [MinecraftServer.class:?] 
at java.lang.Thread.run(Thread.java:748) [?:1.8.0_201] 
[39;0m> [K[17:48:51] [Server thread/ERROR] [FML]: Parsing error loading recipe techguns:techguns_manual 
com.google.gson.JsonSyntaxException: Unknown item 'patchouli:guide_book' 
at net.minecraftforge.common.crafting.CraftingHelper.getItemStack(CraftingHelper.java:213) ~[CraftingHelper.class:?] 
at net.minecraftforge.common.crafting.CraftingHelper.lambda$init$15(CraftingHelper.java:537) ~[CraftingHelper.class:?] 
at net.minecraftforge.common.crafting.CraftingHelper.getRecipe(CraftingHelper.java:415) ~[CraftingHelper.class:?] 
at net.minecraftforge.common.crafting.CraftingHelper.lambda$loadRecipes$22(CraftingHelper.java:711) ~[CraftingHelper.class:?] 
at net.minecraftforge.common.crafting.CraftingHelper.findFiles(CraftingHelper.java:821) ~[CraftingHelper.class:?] 
at net.minecraftforge.common.crafting.CraftingHelper.loadRecipes(CraftingHelper.java:676) ~[CraftingHelper.class:?] 
at java.util.ArrayList.forEach(ArrayList.java:1257) [?:1.8.0_201] 
at net.minecraftforge.common.crafting.CraftingHelper.loadRecipes(CraftingHelper.java:626) [CraftingHelper.class:?] 
at net.minecraftforge.fml.common.Loader.initializeMods(Loader.java:742) [Loader.class:?] 
at net.minecraftforge.fml.server.FMLServerHandler.finishServerLoading(FMLServerHandler.java:108) [FMLServerHandler.class:?] 
at net.minecraftforge.fml.common.FMLCommonHandler.onServerStarted(FMLCommonHandler.java:338) [FMLCommonHandler.class:?] 
at net.minecraft.server.dedicated.DedicatedServer.init(DedicatedServer.java:219) [nz.class:?] 
at net.minecraft.server.MinecraftServer.run(MinecraftServer.java:486) [MinecraftServer.class:?] 
at java.lang.Thread.run(Thread.java:748) [?:1.8.0_201] 
[39;0m> [K[17:48:51] [Server thread/INFO] [Chisel]: Loading recipes... 
> [K[17:48:51] [Server thread/INFO] [Chisel]: Skipping feature bloodMagic as its required mod bloodmagic was missing. 
> [K[17:48:51] [Server thread/INFO] [Chisel]: 71 Feature's recipes loaded. 
> [K[17:48:51] [Server thread/INFO] [THAUMCRAFT]: Checking for mod & oredict compatibilities 
> [K[17:48:51] [Server thread/INFO] [THAUMCRAFT]: Adding entities to MFR safari net blacklist. 
> [K[17:48:59] [Server thread/INFO] [reborncore]: Found 339 ores 
> [K[17:48:59] [Server thread/INFO] [techreborn]: Crafting Table Recipes Added 
> [K[17:49:02] [Server thread/INFO] [FML]: Applying holder lookups 
> [K[17:49:02] [Server thread/INFO] [FML]: Holder lookups applied 
> [K[17:49:03] [Server thread/INFO] [AbyssalCraft]: Inventory Tweaks is present, initializing sorting stuff. 
> [K[17:49:03] [Server thread/INFO] [AbyssalCraft]: Just Enough Items is present, initializing informative stuff. 
> [K[17:49:03] [Server thread/INFO] [AbyssalCraft]: Found a integration for mod Thaumcraft 
> [K[17:49:03] [Server thread/INFO] [AbyssalCraft]: Found a integration for mod CraftTweaker 
> [K[17:49:03] [Server thread/INFO] [AbyssalCraft]: Found a integration for mod Tinkers' Construct 
> [K[17:49:03] [Server thread/INFO] [AbyssalCraft]: Mod integrations found: [Inventory Tweaks, Just Enough Items, Thaumcraft, CraftTweaker, Tinkers' Construct] 
> [K[17:49:03] [Server thread/INFO] [AbyssalCraft]: Initializing integrations! 
> [K[17:49:04] [Server thread/INFO] [FML]: Ignored smelting recipe with conflicting input: 1xitem.egg@32767 = 1xitem.animania_plain_omelette@0 
> [K[17:49:04] [Server thread/WARN] inecraft/EntityVillager]: PriceRange(2, 1) invalid, 1 smaller than 2 
[39;0m> [K[17:49:04] [Server thread/WARN] inecraft/EntityVillager]: PriceRange(4, 1) invalid, 1 smaller than 4 
[39;0m> [K[17:49:04] [Server thread/WARN] inecraft/EntityVillager]: PriceRange(10, 1) invalid, 1 smaller than 10 
[39;0m> [K[17:49:04] [Server thread/WARN] inecraft/EntityVillager]: PriceRange(9, 1) invalid, 1 smaller than 9 
[39;0m> [K[17:49:04] [Server thread/WARN] inecraft/EntityVillager]: PriceRange(3, 2) invalid, 2 smaller than 3 
[39;0m> [K[17:49:04] [Server thread/INFO] [Ice And Fire]: The watcher waits on the northern wall 
> [K[17:49:04] [Server thread/INFO] [Ice And Fire]: A daughter picks up a warrior's sword 
> [K[17:49:04] [Server thread/INFO] [armoryexpansion-iceandfire]: Updated tinker's material {leatherfrosttroll}; 
> [K[17:49:04] [Server thread/INFO] [armoryexpansion-iceandfire]: Updated tinker's material {chitindesertmyrmex}; 
> [K[17:49:04] [Server thread/INFO] [armoryexpansion-iceandfire]: Updated tinker's material {chitintandeathworm}; 
> [K[17:49:04] [Server thread/INFO] [armoryexpansion-iceandfire]: Updated tinker's material {chitinjunglemyrmex}; 
> [K[17:49:04] [Server thread/INFO] [armoryexpansion-iceandfire]: Updated tinker's material {scalebronzedragon}; 
> [K[17:49:04] [Server thread/INFO] [armoryexpansion-iceandfire]: Updated tinker's material {scaleblueseaserpent}; 
> [K[17:49:04] [Server thread/INFO] [armoryexpansion-iceandfire]: Updated tinker's material {scalepurpleseaserpent}; 
> [K[17:49:04] [Server thread/INFO] [armoryexpansion-iceandfire]: Updated tinker's material {scalewhitedragon}; 
> [K[17:49:04] [Server thread/INFO] [armoryexpansion-iceandfire]: Updated tinker's material {chitinwhitedeathworm}; 
> [K[17:49:04] [Server thread/INFO] [armoryexpansion-iceandfire]: Updated tinker's material {chitinbrowndeathworm}; 
> [K[17:49:04] [Server thread/INFO] [armoryexpansion-iceandfire]: Updated tinker's material {scalegraydragon}; 
> [K[17:49:04] [Server thread/INFO] [armoryexpansion-iceandfire]: Updated tinker's material {scalesapphiredragon}; 
> [K[17:49:04] [Server thread/INFO] [armoryexpansion-iceandfire]: Updated tinker's material {scaletealseaserpent}; 
> [K[17:49:04] [Server thread/INFO] [armoryexpansion-iceandfire]: Updated tinker's material {scalebluedragon}; 
> [K[17:49:04] [Server thread/INFO] [armoryexpansion-iceandfire]: Updated tinker's material {leatherforesttroll}; 
> [K[17:49:04] [Server thread/INFO] [armoryexpansion-iceandfire]: Updated tinker's material {bonedragon}; 
> [K[17:49:04] [Server thread/INFO] [armoryexpansion-iceandfire]: Updated tinker's material {scalegreendragon}; 
> [K[17:49:04] [Server thread/INFO] [armoryexpansion-iceandfire]: Updated tinker's material {leathermountaintroll}; 
> [K[17:49:04] [Server thread/INFO] [armoryexpansion-iceandfire]: Updated tinker's material {scalebronzeseaserpent}; 
> [K[17:49:04] [Server thread/INFO] [armoryexpansion-iceandfire]: Updated tinker's material {scalereddragon}; 
> [K[17:49:04] [Server thread/INFO] [armoryexpansion-iceandfire]: Updated tinker's material {scaledeepblueseaserpent}; 
> [K[17:49:04] [Server thread/INFO] [armoryexpansion-iceandfire]: Updated tinker's material {scaleredseaserpent}; 
> [K[17:49:04] [Server thread/INFO] [armoryexpansion-iceandfire]: Updated tinker's material {scalegreenseaserpent}; 
> [K[17:49:04] [Server thread/INFO] [armoryexpansion-iceandfire]: Updated tinker's material {scalesilverdragon}; 
> [K[17:49:04] [Server thread/INFO] [armoryexpansion-iceandfire]: Registered traits for tinker's material {scalebronzedragon}; 
> [K[17:49:04] [Server thread/INFO] [armoryexpansion-iceandfire]: Registered traits for tinker's material {scaleblueseaserpent}; 
> [K[17:49:04] [Server thread/INFO] [armoryexpansion-iceandfire]: Registered traits for tinker's material {scalepurpleseaserpent}; 
> [K[17:49:04] [Server thread/INFO] [armoryexpansion-iceandfire]: Registered traits for tinker's material {scalewhitedragon}; 
> [K[17:49:04] [Server thread/INFO] [armoryexpansion-iceandfire]: Registered traits for tinker's material {scalegraydragon}; 
> [K[17:49:04] [Server thread/INFO] [armoryexpansion-iceandfire]: Registered traits for tinker's material {scalesapphiredragon}; 
> [K[17:49:04] [Server thread/INFO] [armoryexpansion-iceandfire]: Registered traits for tinker's material {scaletealseaserpent}; 
> [K[17:49:04] [Server thread/INFO] [armoryexpansion-iceandfire]: Registered traits for tinker's material {scalebluedragon}; 
> [K[17:49:04] [Server thread/INFO] [armoryexpansion-iceandfire]: Registered traits for tinker's material {scalegreendragon}; 
> [K[17:49:04] [Server thread/INFO] [armoryexpansion-iceandfire]: Registered traits for tinker's material {scalebronzeseaserpent}; 
> [K[17:49:04] [Server thread/INFO] [armoryexpansion-iceandfire]: Registered traits for tinker's material {scalereddragon}; 
> [K[17:49:04] [Server thread/INFO] [armoryexpansion-iceandfire]: Registered traits for tinker's material {scaledeepblueseaserpent}; 
> [K[17:49:04] [Server thread/INFO] [armoryexpansion-iceandfire]: Registered traits for tinker's material {scaleredseaserpent}; 
> [K[17:49:04] [Server thread/INFO] [armoryexpansion-iceandfire]: Registered traits for tinker's material {scalegreenseaserpent}; 
> [K[17:49:04] [Server thread/INFO] [armoryexpansion-iceandfire]: Registered traits for tinker's material {scalesilverdragon}; 
> [K[17:49:04] [Server thread/INFO] [Astral Sorcery]: Ignoring fluid crystaloil for rarity registry - it doesn't exist in the current environment 
> [K[17:49:04] [Server thread/INFO] [Astral Sorcery]: Ignoring fluid empoweredoil for rarity registry - it doesn't exist in the current environment 
> [K[17:49:04] [Server thread/INFO] [Astral Sorcery]: Ignoring fluid ic2uu_matter for rarity registry - it doesn't exist in the current environment 
> [K[17:49:04] [Server thread/INFO] [Astral Sorcery]: Ignoring fluid ic2biomass for rarity registry - it doesn't exist in the current environment 
> [K[17:49:04] [Server thread/INFO] [Astral Sorcery]: Ignoring fluid ic2biogas for rarity registry - it doesn't exist in the current environment 
> [K[17:49:04] [Server thread/INFO] [Astral Sorcery]: Ignoring fluid nacre for rarity registry - it doesn't exist in the current environment 
> [K[17:49:04] [Server thread/INFO] [Astral Sorcery]: Ignoring whitelist entry minecraft:tb.eldritchbane:2 for amulet enchantments - Enchantment does not exist! 
> [K[17:49:04] [Server thread/INFO] [Astral Sorcery]: Ignoring whitelist entry minecraft:tb.elderknowledge:2 for amulet enchantments - Enchantment does not exist! 
> [K[17:49:04] [Server thread/INFO] [Astral Sorcery]: Ignoring whitelist entry minecraft:tb.tainted:2 for amulet enchantments - Enchantment does not exist! 
> [K[17:49:04] [Server thread/INFO] [Astral Sorcery]: Ignoring whitelist entry gravestone-extended:gs_vampiric_touch:1 for amulet enchantments - Enchantment does not exist! 
> [K[17:49:04] [Server thread/INFO] [Astral Sorcery]: Ignoring whitelist entry gravestone-extended:gs_poisoned_blade:2 for amulet enchantments - Enchantment does not exist! 
> [K[17:49:04] [Server thread/INFO] [Astral Sorcery]: Ignoring whitelist entry gravestone-extended:gs_withered_blade:2 for amulet enchantments - Enchantment does not exist! 
> [K[17:49:04] [Server thread/INFO] [Astral Sorcery]: Ignoring whitelist entry gravestone-extended:gs_shadow_of_death:5 for amulet enchantments - Enchantment does not exist! 
> [K[17:49:04] [Server thread/INFO] [Astral Sorcery]: Ignoring whitelist entry gravestone-extended:gs_necrotic_corrosion:1 for amulet enchantments - Enchantment does not exist! 
> [K[17:49:04] [Server thread/INFO] [Astral Sorcery]: Ignoring whitelist entry gravestone-extended:gs_pain_mirror:1 for amulet enchantments - Enchantment does not exist! 
> [K[17:49:04] [Server thread/INFO] [Astral Sorcery]: Ignoring whitelist entry gravestone-extended:web_crawler:1 for amulet enchantments - Enchantment does not exist! 
> [K[17:49:04] [Server thread/INFO] [Astral Sorcery]: Ignoring whitelist entry gravestone-extended:frozen_nether:1 for amulet enchantments - Enchantment does not exist! 
> [K[17:49:04] [Server thread/INFO] [Astral Sorcery]: Ignoring whitelist entry gravestone-extended:gs_bone_rain:1 for amulet enchantments - Enchantment does not exist! 
> [K[17:49:04] [Server thread/INFO] [Astral Sorcery]: Ignoring whitelist entry gravestone-extended:gs_hellish_angling:1 for amulet enchantments - Enchantment does not exist! 
> [K[17:49:04] [Server thread/INFO] [Astral Sorcery]: Ignoring whitelist entry gravestone-extended:gs_bloody_replication:1 for amulet enchantments - Enchantment does not exist! 
> [K[17:49:04] [Server thread/INFO] [Astral Sorcery]: Ignoring whitelist entry gravestone-extended:soul_bound:1 for amulet enchantments - Enchantment does not exist! 
> [K[17:49:05] [Server thread/INFO] [Astral Sorcery]: Got 0 recipe modifications from CraftTweaker. - Applying... 
> [K[17:49:05] [Server thread/INFO] [Astral Sorcery]: Recipe changes applied. 
> [K[17:49:05] [AstralSorcery Patreon Effect Loader/INFO] [Astral Sorcery]: Patreon effect loading finished. 
> [K[17:49:05] [Server thread/INFO] [Astral Sorcery]: Loaded OAK of minecraft into tree registry. 
> [K[17:49:05] [Server thread/INFO] [Astral Sorcery]: Loaded SPRUCE of minecraft into tree registry. 
> [K[17:49:05] [Server thread/INFO] [Astral Sorcery]: Loaded BIRCH of minecraft into tree registry. 
> [K[17:49:05] [Server thread/INFO] [Astral Sorcery]: Loaded JUNGLE of minecraft into tree registry. 
> [K[17:49:05] [Server thread/INFO] [Astral Sorcery]: Loaded ACACIA of minecraft into tree registry. 
> [K[17:49:05] [Server thread/INFO] [Astral Sorcery]: Loaded DARK_OAK of minecraft into tree registry.
> [K[17:49:05] [Server thread/INFO] [Astral Sorcery]: Loaded SLIME of tconstruct into tree registry. 
> [K[17:49:05] [Server thread/INFO] [reborncore]: Found 343 ores 
> [K[17:49:06] [Server thread/INFO] [reborncore]: Created new network wrapper rc&reborncore.&64769 
> [K[17:49:06] [Server thread/INFO] [reborncore]: Registed packet to rc&reborncore.&64769 side: SERVER id:0 
> [K[17:49:06] [Server thread/INFO] [reborncore]: Created new network wrapper rc&reborncore.&39932 
> [K[17:49:06] [Server thread/INFO] [reborncore]: Registed packet to rc&reborncore.&39932 side: CLIENT id:0 
> [K[17:49:06] [Server thread/INFO] [reborncore]: Registed packet to rc&reborncore.&39932 side: SERVER id:1 
> [K[17:49:06] [Server thread/INFO] [reborncore]: Registed packet to rc&reborncore.&39932 side: SERVER id:2 
> [K[17:49:06] [Server thread/INFO] [reborncore]: Registed packet to rc&reborncore.&39932 side: SERVER id:3 
> [K[17:49:06] [Server thread/INFO] [reborncore]: Registed packet to rc&reborncore.&39932 side: CLIENT id:4 
> [K[17:49:06] [Server thread/INFO] [reborncore]: Registed packet to rc&reborncore.&39932 side: CLIENT id:5 
> [K[17:49:06] [Server thread/INFO] [reborncore]: Registed packet to rc&reborncore.&39932 side: SERVER id:6 
> [K[17:49:06] [Server thread/INFO] [reborncore]: Registed packet to rc&reborncore.&39932 side: SERVER id:7 
> [K[17:49:06] [Server thread/INFO] [reborncore]: Registed packet to rc&reborncore.&39932 side: CLIENT id:8 
> [K[17:49:06] [Server thread/INFO] [reborncore]: Registed packet to rc&reborncore.&39932 side: CLIENT id:9 
> [K[17:49:06] [Server thread/INFO] [reborncore]: Created new network wrapper rc&techreborn.&42258 
> [K[17:49:06] [Server thread/INFO] [reborncore]: Registed packet to rc&techreborn.&42258 side: SERVER id:0 
> [K[17:49:06] [Server thread/INFO] [reborncore]: Registed packet to rc&techreborn.&42258 side: SERVER id:1 
> [K[17:49:06] [Server thread/INFO] [reborncore]: Registed packet to rc&techreborn.&42258 side: SERVER id:2 
> [K[17:49:06] [Server thread/INFO] [reborncore]: Registed packet to rc&techreborn.&42258 side: SERVER id:3 
> [K[17:49:06] [Server thread/INFO] [reborncore]: Registed packet to rc&techreborn.&42258 side: SERVER id:4 
> [K[17:49:06] [Server thread/INFO] [reborncore]: Registed packet to rc&techreborn.&42258 side: SERVER id:5 
> [K[17:49:06] [Server thread/INFO] [reborncore]: Created new network wrapper rc&me.modmuss5&21645 
> [K[17:49:06] [Server thread/INFO] [reborncore]: Registed packet to rc&me.modmuss5&21645 side: SERVER id:0 
> [K[17:49:06] [Server thread/INFO] [reborncore]: Created new network wrapper rc&vswe.steves&10928 
> [K[17:49:06] [Server thread/INFO] [reborncore]: Registed packet to rc&vswe.steves&10928 side: CLIENT id:0 
> [K[17:49:06] [Server thread/INFO] [reborncore]: Registed packet to rc&vswe.steves&10928 side: SERVER id:2 
> [K[17:49:06] [Server thread/INFO] [reborncore]: Registed packet to rc&vswe.steves&10928 side: CLIENT id:3 
> [K[17:49:06] [Server thread/INFO] [reborncore]: Registed packet to rc&vswe.steves&10928 side: SERVER id:4 
> [K[17:49:06] [Server thread/INFO] [reborncore]: Loaded registrys for net.minecraftforge.fml.common.event.FMLInitializationEvent in 0ms 
> [K[17:49:06] [Server thread/INFO] [reborncore]: Loaded torus size map in 426ms 
> [K[17:49:06] [Server thread/INFO] [techreborn]: Initialization Complete 
> [K[17:49:07] [Server thread/WARN] [FML]: Potentially Dangerous alternative prefix `minecraft` for name `binnie.tile.metadata`, expected `binniecore`. This could be a intended override, but in most cases indicates a broken mod. 
[39;0m> [K[17:49:08] [Server thread/WARN] [FML]: Potentially Dangerous alternative prefix `extratrees` for name `alveary_mutator`, expected `extrabees`. This could be a intended override, but in most cases indicates a broken mod. 
[39;0m> [K[17:49:08] [Server thread/WARN] [FML]: Potentially Dangerous alternative prefix `extratrees` for name `alveary_frame`, expected `extrabees`. This could be a intended override, but in most cases indicates a broken mod. 
[39;0m> [K[17:49:08] [Server thread/WARN] [FML]: Potentially Dangerous alternative prefix `extratrees` for name `alveary_rain_shield`, expected `extrabees`. This could be a intended override, but in most cases indicates a broken mod. 
[39;0m> [K[17:49:08] [Server thread/WARN] [FML]: Potentially Dangerous alternative prefix `extratrees` for name `alveary_lighting`, expected `extrabees`. This could be a intended override, but in most cases indicates a broken mod. 
[39;0m> [K[17:49:08] [Server thread/WARN] [FML]: Potentially Dangerous alternative prefix `extratrees` for name `alveary_stimulator`, expected `extrabees`. This could be a intended override, but in most cases indicates a broken mod. 
[39;0m> [K[17:49:08] [Server thread/WARN] [FML]: Potentially Dangerous alternative prefix `extratrees` for name `alveary_hatchery`, expected `extrabees`. This could be a intended override, but in most cases indicates a broken mod. 
[39;0m> [K[17:49:08] [Server thread/WARN] [FML]: Potentially Dangerous alternative prefix `extratrees` for name `alveary_transmission`, expected `extrabees`. This could be a intended override, but in most cases indicates a broken mod. 
[39;0m> [K[17:49:08] [Server thread/INFO] [Cyclops Core]: Cyclops Core is up-to-date! 
> [K[17:49:08] [Server thread/INFO] [ColossalChests]: ColossalChests is up-to-date! 
> [K[17:49:08] [Server thread/INFO] [Flopper]: Flopper is up-to-date! 
> [K[17:49:08] [Server thread/WARN] orpheus]: New day handler for dimension 0 has been replaced 
[39;0m> [K[17:49:08] [Server thread/INFO] [noppes.npcs.CustomNpcs]: CustomNPC Permissions available:
> [K[17:49:08] [Server thread/INFO] [noppes.npcs.CustomNpcs]: customnpcs.edit.blocks 
> [K[17:49:08] [Server thread/INFO] [noppes.npcs.CustomNpcs]: customnpcs.edit.villager 
> [K[17:49:08] [Server thread/INFO] [noppes.npcs.CustomNpcs]: customnpcs.global.bank 
> [K[17:49:08] [Server thread/INFO] [noppes.npcs.CustomNpcs]: customnpcs.global.dialog 
> [K[17:49:08] [Server thread/INFO] [noppes.npcs.CustomNpcs]: customnpcs.global.faction 
> [K[17:49:08] [Server thread/INFO] [noppes.npcs.CustomNpcs]: customnpcs.global.linked 
> [K[17:49:08] [Server thread/INFO] [noppes.npcs.CustomNpcs]: customnpcs.global.naturalspawn 
> [K[17:49:08] [Server thread/INFO] [noppes.npcs.CustomNpcs]: customnpcs.global.playerdata 
> [K[17:49:08] [Server thread/INFO] [noppes.npcs.CustomNpcs]: customnpcs.global.quest 
> [K[17:49:08] [Server thread/INFO] [noppes.npcs.CustomNpcs]: customnpcs.global.recipe 
> [K[17:49:08] [Server thread/INFO] [noppes.npcs.CustomNpcs]: customnpcs.global.transport 
> [K[17:49:08] [Server thread/INFO] [noppes.npcs.CustomNpcs]: customnpcs.npc.advanced 
> [K[17:49:08] [Server thread/INFO] [noppes.npcs.CustomNpcs]: customnpcs.npc.ai 
> [K[17:49:08] [Server thread/INFO] [noppes.npcs.CustomNpcs]: customnpcs.npc.clone 
> [K[17:49:08] [Server thread/INFO] [noppes.npcs.CustomNpcs]: customnpcs.npc.create 
> [K[17:49:08] [Server thread/INFO] [noppes.npcs.CustomNpcs]: customnpcs.npc.delete 
> [K[17:49:08] [Server thread/INFO] [noppes.npcs.CustomNpcs]: customnpcs.npc.display 
> [K[17:49:08] [Server thread/INFO] [noppes.npcs.CustomNpcs]: customnpcs.npc.freeze 
> [K[17:49:08] [Server thread/INFO] [noppes.npcs.CustomNpcs]: customnpcs.npc.gui 
> [K[17:49:08] [Server thread/INFO] [noppes.npcs.CustomNpcs]: customnpcs.npc.inventory 
> [K[17:49:08] [Server thread/INFO] [noppes.npcs.CustomNpcs]: customnpcs.npc.reset 
> [K[17:49:08] [Server thread/INFO] [noppes.npcs.CustomNpcs]: customnpcs.npc.stats 
> [K[17:49:08] [Server thread/INFO] [noppes.npcs.CustomNpcs]: customnpcs.scenes 
> [K[17:49:08] [Server thread/INFO] [noppes.npcs.CustomNpcs]: customnpcs.soulstone.all 
> [K[17:49:08] [Server thread/INFO] [noppes.npcs.CustomNpcs]: customnpcs.spawner.create 
> [K[17:49:08] [Server thread/INFO] [noppes.npcs.CustomNpcs]: customnpcs.spawner.mob 
> [K[17:49:08] [Server thread/INFO] [noppes.npcs.CustomNpcs]: customnpcs.tool.mounter 
> [K[17:49:08] [Server thread/INFO] [noppes.npcs.CustomNpcs]: customnpcs.tool.nbtbook 
> [K[17:49:08] [Server thread/INFO] [noppes.npcs.CustomNpcs]: customnpcs.tool.pather 
> [K[17:49:08] [Server thread/INFO] [noppes.npcs.CustomNpcs]: customnpcs.tool.scripter 
> [K[17:49:09] [Server thread/WARN] [Ex Nihilo Creatio]: Crucible entry for Oak Sapling with meta 0 already exists, skipping. 
[39;0m> [K[17:49:09] [Server thread/WARN] [Ex Nihilo Creatio]: Crucible entry for Spruce Sapling with meta 1 already exists, skipping. 
[39;0m> [K[17:49:09] [Server thread/WARN] [Ex Nihilo Creatio]: Crucible entry for Birch Sapling with meta 2 already exists, skipping. 
[39;0m> [K[17:49:09] [Server thread/WARN] [Ex Nihilo Creatio]: Crucible entry for Jungle Sapling with meta 3 already exists, skipping. 
[39;0m> [K[17:49:09] [Server thread/WARN] [Ex Nihilo Creatio]: Crucible entry for Acacia Sapling with meta 4 already exists, skipping. 
[39;0m> [K[17:49:09] [Server thread/WARN] [Ex Nihilo Creatio]: Crucible entry for Dark Oak Sapling with meta 5 already exists, skipping. 
[39;0m> [K[17:49:09] [Server thread/INFO] [foamfix]: Deduplicated 860 property sets. 
> [K[17:49:09] [Server thread/INFO] [foamfix]: Weakening LaunchWrapper resource cache... 
> [K[17:49:09] [Server thread/INFO] [FML]: Ignored smelting recipe with conflicting input: 1xitem.egg@32767 = 1xitem.cooked_egg@0 
> [K[17:49:09] [Server thread/INFO] [fossils]: After a billion years 
> [K[17:49:09] [Server thread/INFO] [fossils]: The show is still here 
> [K[17:49:09] [Server thread/INFO] [fossils]: Not a single one of your fathers died young 
> [K[17:49:09] [Server thread/INFO] [fossils]: The handy travelers out of Africa 
> [K[17:49:09] [Server thread/INFO] [fossils]: Little Lucy of the Afar 
> [K[17:49:09] [Server thread/INFO] [fossils]: Cheese Touch 
> [K[17:49:10] [Thread-10/INFO] [immersiveengineering]: Arc Recycling: Removed 0 old recipes 
> [K[17:49:10] [Immersive Engineering Registry Iteration Thread/WARN] [immersiveengineering]: Recipe has invalid inputs and will be ignored: net.minecraftforge.oredict.ShapedOreRecipe@58461b34 (excompressum:mana_hammer) 
[39;0m> [K[17:49:10] [Thread-10/INFO] [immersiveengineering]: Finished recipe profiler for Arc Recycling, took 113 milliseconds 
> [K[17:49:11] [Server thread/INFO] [STDOUT]: [flaxbeard.immersivepetroleum.common.Config:addConfigReservoirs:689]: aquifer, water, 5000000, 10000000, 6, 30, [], [0], [], [] 
> [K[17:49:11] [Server thread/INFO] [STDOUT]: [flaxbeard.immersivepetroleum.common.Config:addConfigReservoirs:720]: Added resevoir type aquifer 
> [K[17:49:11] [Server thread/INFO] [STDOUT]: [flaxbeard.immersivepetroleum.common.Config:addConfigReservoirs:689]: oil, oil, 2500000, 15000000, 6, 40, [1], [], [], [] 
> [K[17:49:11] [Server thread/INFO] [STDOUT]: [flaxbeard.immersivepetroleum.common.Config:addConfigReservoirs:720]: Added resevoir type oil 
> [K[17:49:11] [Server thread/INFO] [STDOUT]: [flaxbeard.immersivepetroleum.common.Config:addConfigReservoirs:689]: lava, lava, 250000, 1000000, 0, 30, [1], [], [], [] 
> [K[17:49:11] [Server thread/INFO] [STDOUT]: [flaxbeard.immersivepetroleum.common.Config:addConfigReservoirs:720]: Added resevoir type lava 
> [K[17:49:11] [Server thread/INFO] [STDOUT]: [flaxbeard.immersivepetroleum.common.Config:addDistillationRecipe:376]: Added distillation recipe using oil 
> [K[17:49:11] [Server thread/INFO] [STDOUT]: [flaxbeard.immersivepetroleum.common.Config:addDistillationRecipe:378]: Bitumen 
> [K[17:49:11] [Server thread/WARN] [FML]: Potentially Dangerous alternative prefix `minecraft` for name `landlustcabinet`, expected `landlust`. This could be a intended override, but in most cases indicates a broken mod. 
[39;0m> [K[17:49:11] [Server thread/WARN] [FML]: Potentially Dangerous alternative prefix `minecraft` for name `landlustcommode`, expected `landlust`. This could be a intended override, but in most cases indicates a broken mod. 
[39;0m> [K[17:49:11] [Server thread/WARN] [FML]: Potentially Dangerous alternative prefix `minecraft` for name `landlustcounter`, expected `landlust`. This could be a intended override, but in most cases indicates a broken mod. 
[39;0m> [K[17:49:11] [Server thread/WARN] [FML]: Potentially Dangerous alternative prefix `minecraft` for name `landluststove`, expected `landlust`. This could be a intended override, but in most cases indicates a broken mod. 
[39;0m> [K[17:49:11] [Server thread/INFO] [Mekanica]: Version 9.4.13 initializing... 
> [K[17:49:12] [Server thread/INFO] [Mekanica]: Loading complete. 
> [K[17:49:12] [Server thread/INFO] [Mekanica]: Mod loaded. 
> [K[17:49:12] [Server thread/WARN] [FML]: Potentially Dangerous alternative prefix `minecraft` for name `cfmoven`, expected `cfm`. This could be a intended override, but in most cases indicates a broken mod. 
[39;0m> [K[17:49:12] [Server thread/WARN] [FML]: Potentially Dangerous alternative prefix `minecraft` for name `cfmfridge`, expected `cfm`. This could be a intended override, but in most cases indicates a broken mod. 
[39;0m> [K[17:49:12] [Server thread/WARN] [FML]: Potentially Dangerous alternative prefix `minecraft` for name `cfmcabinet`, expected `cfm`. This could be a intended override, but in most cases indicates a broken mod. 
[39;0m> [K[17:49:12] [Server thread/WARN] [FML]: Potentially Dangerous alternative prefix `minecraft` for name `cfmfreezer`, expected `cfm`. This could be a intended override, but in most cases indicates a broken mod. 
[39;0m> [K[17:49:12] [Server thread/WARN] [FML]: Potentially Dangerous alternative prefix `minecraft` for name `cfmbedsidecabinet`, expected `cfm`. This could be a intended override, but in most cases indicates a broken mod. 
[39;0m> [K[17:49:12] [Server thread/WARN] [FML]: Potentially Dangerous alternative prefix `minecraft` for name `cfmmailbox`, expected `cfm`. This could be a intended override, but in most cases indicates a broken mod. 
[39;0m> [K[17:49:12] [Server thread/WARN] [FML]: Potentially Dangerous alternative prefix `minecraft` for name `cfmcomputer`, expected `cfm`. This could be a intended override, but in most cases indicates a broken mod. 
[39;0m> [K[17:49:12] [Server thread/WARN] [FML]: Potentially Dangerous alternative prefix `minecraft` for name `cfmprinter`, expected `cfm`. This could be a intended override, but in most cases indicates a broken mod. 
[39;0m> [K[17:49:12] [Server thread/WARN] [FML]: Potentially Dangerous alternative prefix `minecraft` for name `cfmstereo`, expected `cfm`. This could be a intended override, but in most cases indicates a broken mod. 
[39;0m> [K[17:49:12] [Server thread/WARN] [FML]: Potentially Dangerous alternative prefix `minecraft` for name `cfmpresent`, expected `cfm`. This could be a intended override, but in most cases indicates a broken mod. 
[39;0m> [K[17:49:12] [Server thread/WARN] [FML]: Potentially Dangerous alternative prefix `minecraft` for name `cfmbin`, expected `cfm`. This could be a intended override, but in most cases indicates a broken mod. 
[39;0m> [K[17:49:12] [Server thread/WARN] [FML]: Potentially Dangerous alternative prefix `minecraft` for name `cfmwallcabinet`, expected `cfm`. This could be a intended override, but in most cases indicates a broken mod. 
[39;0m> [K[17:49:12] [Server thread/WARN] [FML]: Potentially Dangerous alternative prefix `minecraft` for name `cfmbath`, expected `cfm`. This could be a intended override, but in most cases indicates a broken mod. 
[39;0m> [K[17:49:12] [Server thread/WARN] [FML]: Potentially Dangerous alternative prefix `minecraft` for name `cfmshowerhead`, expected `cfm`. This could be a intended override, but in most cases indicates a broken mod. 
[39;0m> [K[17:49:12] [Server thread/WARN] [FML]: Potentially Dangerous alternative prefix `minecraft` for name `cfmplate`, expected `cfm`. This could be a intended override, but in most cases indicates a broken mod. 
[39;0m> [K[17:49:12] [Server thread/WARN] [FML]: Potentially Dangerous alternative prefix `minecraft` for name `cfmcouch`, expected `cfm`. This could be a intended override, but in most cases indicates a broken mod. 
[39;0m> [K[17:49:12] [Server thread/WARN] [FML]: Potentially Dangerous alternative prefix `minecraft` for name `cfmtoaster`, expected `cfm`. This could be a intended override, but in most cases indicates a broken mod. 
[39;0m> [K[17:49:12] [Server thread/WARN] [FML]: Potentially Dangerous alternative prefix `minecraft` for name `cfmchoppingboard`, expected `cfm`. This could be a intended override, but in most cases indicates a broken mod. 
[39;0m> [K[17:49:12] [Server thread/WARN] [FML]: Potentially Dangerous alternative prefix `minecraft` for name `cfmblender`, expected `cfm`. This could be a intended override, but in most cases indicates a broken mod. 
[39;0m> [K[17:49:12] [Server thread/WARN] [FML]: Potentially Dangerous alternative prefix `minecraft` for name `cfmmicrowave`, expected `cfm`. This could be a intended override, but in most cases indicates a broken mod. 
[39;0m> [K[17:49:12] [Server thread/WARN] [FML]: Potentially Dangerous alternative prefix `minecraft` for name `cfmwashingmachine`, expected `cfm`. This could be a intended override, but in most cases indicates a broken mod. 
[39;0m> [K[17:49:12] [Server thread/WARN] [FML]: Potentially Dangerous alternative prefix `minecraft` for name `cfmdishwasher`, expected `cfm`. This could be a intended override, but in most cases indicates a broken mod. 
[39;0m> [K[17:49:12] [Server thread/WARN] [FML]: Potentially Dangerous alternative prefix `minecraft` for name `cfmcabinetkitchen`, expected `cfm`. This could be a intended override, but in most cases indicates a broken mod. 
[39;0m> [K[17:49:12] [Server thread/WARN] [FML]: Potentially Dangerous alternative prefix `minecraft` for name `cfmcup`, expected `cfm`. This could be a intended override, but in most cases indicates a broken mod. 
[39;0m> [K[17:49:12] [Server thread/WARN] [FML]: Potentially Dangerous alternative prefix `minecraft` for name `cfmcookiejar`, expected `cfm`. This could be a intended override, but in most cases indicates a broken mod. 
[39;0m> [K[17:49:12] [Server thread/WARN] [FML]: Potentially Dangerous alternative prefix `minecraft` for name `cfmtree`, expected `cfm`. This could be a intended override, but in most cases indicates a broken mod. 
[39;0m> [K[17:49:12] [Server thread/WARN] [FML]: Potentially Dangerous alternative prefix `minecraft` for name `cfmmirror`, expected `cfm`. This could be a intended override, but in most cases indicates a broken mod. 
[39;0m> [K[17:49:12] [Server thread/WARN] [FML]: Potentially Dangerous alternative prefix `minecraft` for name `cfmgrill`, expected `cfm`. This could be a intended override, but in most cases indicates a broken mod. 
[39;0m> [K[17:49:12] [Server thread/WARN] [FML]: Potentially Dangerous alternative prefix `minecraft` for name `cfmeski`, expected `cfm`. This could be a intended override, but in most cases indicates a broken mod. 
[39;0m> [K[17:49:12] [Server thread/WARN] [FML]: Potentially Dangerous alternative prefix `minecraft` for name `cfmdoormat`, expected `cfm`. This could be a intended override, but in most cases indicates a broken mod. 
[39;0m> [K[17:49:12] [Server thread/WARN] [FML]: Potentially Dangerous alternative prefix `minecraft` for name `cfmcrate`, expected `cfm`. This could be a intended override, but in most cases indicates a broken mod. 
[39;0m> [K[17:49:12] [Server thread/WARN] [FML]: Potentially Dangerous alternative prefix `minecraft` for name `cfmlightswitch`, expected `cfm`. This could be a intended override, but in most cases indicates a broken mod. 
[39;0m> [K[17:49:12] [Server thread/WARN] [FML]: Potentially Dangerous alternative prefix `minecraft` for name `cfmceilingfan`, expected `cfm`. This could be a intended override, but in most cases indicates a broken mod. 
[39;0m> [K[17:49:12] [Server thread/WARN] [FML]: Potentially Dangerous alternative prefix `minecraft` for name `cfmdeskcabinet`, expected `cfm`. This could be a intended override, but in most cases indicates a broken mod. 
[39;0m> [K[17:49:12] [Server thread/WARN] [FML]: Potentially Dangerous alternative prefix `minecraft` for name `cfmmodernslidingdoor`, expected `cfm`. This could be a intended override, but in most cases indicates a broken mod. 
[39;0m> [K[17:49:12] [Server thread/WARN] [FML]: Potentially Dangerous alternative prefix `minecraft` for name `cfmdigitalclock`, expected `cfm`. This could be a intended override, but in most cases indicates a broken mod. 
[39;0m> [K[17:49:12] [Server thread/WARN] [FML]: Potentially Dangerous alternative prefix `minecraft` for name `cfmtv`, expected `cfm`. This could be a intended override, but in most cases indicates a broken mod. 
[39;0m> [K[17:49:12] [Server thread/WARN] [FML]: Potentially Dangerous alternative prefix `minecraft` for name `cfmkitchencounter`, expected `cfm`. This could be a intended override, but in most cases indicates a broken mod. 
[39;0m> [K[17:49:12] [Server thread/WARN] [FML]: Potentially Dangerous alternative prefix `minecraft` for name `cfmkitchencounterdrawer`, expected `cfm`. This could be a intended override, but in most cases indicates a broken mod. 
[39;0m> [K[17:49:12] [Server thread/WARN] [FML]: Potentially Dangerous alternative prefix `minecraft` for name `multipiston.multipiston`, expected `multipiston`. This could be a intended override, but in most cases indicates a broken mod. 
[39;0m> [K[17:49:13] [Server thread/INFO] [opencomputers]: Found extended redstone mods, enabling tier two redstone card. 
> [K[17:49:14] [Server thread/INFO] [opencomputers]: Initializing capabilities. 
> [K[17:49:14] [Server thread/INFO] [opencomputers]: Done with init phase. 
> [K[17:49:15] [Server thread/INFO] [thaumcomp]: Done with init phase. 
> [K[17:49:15] [Server thread/INFO] [FML]: [ThermalSolars] ThermalSolars -------------- successfully Finished init 
> [K[17:49:15] [Server thread/WARN] inecraft/EntityDataManager]: defineId called for: class net.minecraft.entity.monster.EntityWitch from class net.torocraft.toroquest.entities.EntityMage 
[39;0m> [K[17:49:16] [Server thread/INFO] [structurize]: Optifine not found. Disabling compat. 
> [K[17:49:16] [Server thread/INFO] [armoryexpansion-conarm]: Updated tinker's material {orangecloth};
> [K[17:49:16] [Server thread/INFO] [armoryexpansion-conarm]: Updated tinker's material {magentacloth}; 
> [K[17:49:16] [Server thread/INFO] [armoryexpansion-conarm]: Updated tinker's material {whitecloth}; 
> [K[17:49:16] [Server thread/INFO] [armoryexpansion-conarm]: Updated tinker's material {pinkcloth}; 
> [K[17:49:16] [Server thread/INFO] [armoryexpansion-conarm]: Updated tinker's material {platinum}; 
> [K[17:49:16] [Server thread/INFO] [armoryexpansion-conarm]: Updated tinker's material {tungsten}; 
> [K[17:49:16] [Server thread/INFO] [armoryexpansion-conarm]: Updated tinker's material {manasteel}; 
> [K[17:49:16] [Server thread/INFO] [armoryexpansion-conarm]: Updated tinker's material {rubber}; 
> [K[17:49:16] [Server thread/INFO] [armoryexpansion-conarm]: Updated tinker's material {tin}; 
> [K[17:49:16] [Server thread/INFO] [armoryexpansion-conarm]: Updated tinker's material {redgarnet}; 
> [K[17:49:16] [Server thread/INFO] [armoryexpansion-conarm]: Updated tinker's material {invar}; 
> [K[17:49:16] [Server thread/INFO] [armoryexpansion-conarm]: Updated tinker's material {refinedglowstone}; 
> [K[17:49:16] [Server thread/INFO] [armoryexpansion-conarm]: Updated tinker's material {lapis}; 
> [K[17:49:16] [Server thread/INFO] [armoryexpansion-conarm]: Updated tinker's material {zinc}; 
> [K[17:49:16] [Server thread/INFO] [armoryexpansion-conarm]: Updated tinker's material {ivorypsi}; 
> [K[17:49:16] [Server thread/INFO] [armoryexpansion-conarm]: Updated tinker's material {terrasteel}; 
> [K[17:49:16] [Server thread/INFO] [armoryexpansion-conarm]: Updated tinker's material {sapphire}; 
> [K[17:49:16] [Server thread/INFO] [armoryexpansion-conarm]: Updated tinker's material {advancedalloy}; 
> [K[17:49:16] [Server thread/INFO] [armoryexpansion-conarm]: Updated tinker's material {limecloth}; 
> [K[17:49:16] [Server thread/INFO] [armoryexpansion-conarm]: Updated tinker's material {brass}; 
> [K[17:49:16] [Server thread/INFO] [armoryexpansion-conarm]: Updated tinker's material {cyancloth}; 
> [K[17:49:16] [Server thread/INFO] [armoryexpansion-conarm]: Updated tinker's material {abyssalnite};
> [K[17:49:16] [Server thread/INFO] [armoryexpansion-conarm]: Updated tinker's material {refinediron};
> [K[17:49:16] [Server thread/INFO] [armoryexpansion-conarm]: Updated tinker's material {yellowgarnet}; 
> [K[17:49:16] [Server thread/INFO] [armoryexpansion-conarm]: Updated tinker's material {graycloth}; 
> [K[17:49:16] [Server thread/INFO] [armoryexpansion-conarm]: Updated tinker's material {browncloth}; 
> [K[17:49:16] [Server thread/INFO] [armoryexpansion-conarm]: Updated tinker's material {emerald}; 
> [K[17:49:16] [Server thread/INFO] [armoryexpansion-conarm]: Updated tinker's material {silky}; 
> [K[17:49:16] [Server thread/INFO] [armoryexpansion-conarm]: Updated tinker's material {gaia}; 
> [K[17:49:16] [Server thread/INFO] [armoryexpansion-conarm]: Updated tinker's material {ebonypsi}; 
> [K[17:49:16] [Server thread/INFO] [armoryexpansion-conarm]: Updated tinker's material {titanium}; 
> [K[17:49:16] [Server thread/INFO] [armoryexpansion-conarm]: Updated tinker's material {psi}; 
> [K[17:49:16] [Server thread/INFO] [armoryexpansion-conarm]: Updated tinker's material {refinedobsidian}; 
> [K[17:49:16] [Server thread/INFO] [armoryexpansion-conarm]: Updated tinker's material {aluminum}; 
> [K[17:49:16] [Server thread/INFO] [armoryexpansion-conarm]: Updated tinker's material {amethyst}; 
> [K[17:49:16] [Server thread/INFO] [armoryexpansion-conarm]: Updated tinker's material {lightbluecloth}; 
> [K[17:49:16] [Server thread/INFO] [armoryexpansion-conarm]: Updated tinker's material {redcloth}; 
> [K[17:49:16] [Server thread/INFO] [armoryexpansion-conarm]: Updated tinker's material {iridium}; 
> [K[17:49:16] [Server thread/INFO] [armoryexpansion-conarm]: Updated tinker's material {gold}; 
> [K[17:49:16] [Server thread/INFO] [armoryexpansion-conarm]: Updated tinker's material {lumium}; 
> [K[17:49:16] [Server thread/INFO] [armoryexpansion-conarm]: Updated tinker's material {enderium}; 
> [K[17:49:16] [Server thread/INFO] [armoryexpansion-conarm]: Updated tinker's material {signalum}; 
> [K[17:49:16] [Server thread/INFO] [armoryexpansion-conarm]: Updated tinker's material {peridot}; 
> [K[17:49:16] [Server thread/INFO] [armoryexpansion-conarm]: Updated tinker's material {refined_coralium}; 
> [K[17:49:16] [Server thread/INFO] [armoryexpansion-conarm]: Updated tinker's material {dreadium}; 
> [K[17:49:16] [Server thread/INFO] [armoryexpansion-conarm]: Updated tinker's material {yellowcloth};
> [K[17:49:16] [Server thread/INFO] [armoryexpansion-conarm]: Updated tinker's material {nickel}; 
> [K[17:49:16] [Server thread/INFO] [armoryexpansion-conarm]: Updated tinker's material {purplecloth};
> [K[17:49:16] [Server thread/INFO] [armoryexpansion-conarm]: Updated tinker's material {lightgraycloth}; 
> [K[17:49:16] [Server thread/INFO] [armoryexpansion-conarm]: Updated tinker's material {blackcloth}; 
> [K[17:49:16] [Server thread/INFO] [armoryexpansion-conarm]: Updated tinker's material {osmium}; 
> [K[17:49:16] [Server thread/INFO] [armoryexpansion-conarm]: Updated tinker's material {quartz}; 
> [K[17:49:16] [Server thread/INFO] [armoryexpansion-conarm]: Updated tinker's material {bluecloth}; 
> [K[17:49:16] [Server thread/INFO] [armoryexpansion-conarm]: Updated tinker's material {treatedwood};
> [K[17:49:16] [Server thread/INFO] [armoryexpansion-conarm]: Updated tinker's material {amber}; 
> [K[17:49:16] [Server thread/INFO] [armoryexpansion-conarm]: Updated tinker's material {elvenelementium}; 
> [K[17:49:16] [Server thread/INFO] [armoryexpansion-conarm]: Updated tinker's material {constantan}; 
> [K[17:49:16] [Server thread/INFO] [armoryexpansion-conarm]: Updated tinker's material {psigem}; 
> [K[17:49:16] [Server thread/INFO] [armoryexpansion-conarm]: Updated tinker's material {ruby}; 
> [K[17:49:16] [Server thread/INFO] [armoryexpansion-conarm]: Updated tinker's material {diamond}; 
> [K[17:49:16] [Server thread/INFO] [armoryexpansion-conarm]: Updated tinker's material {greencloth}; 
> [K[17:49:16] [Server thread/INFO] [armoryexpansion-conarm]: Updated tinker's material {quartzenrichediron}; 
> [K[17:49:16] [Server thread/INFO] [Chisel]: Received 9 IMC messages from mod immersiveengineering. 
> [K[17:49:16] [Server thread/INFO] [Chisel]: Received 7 IMC messages from mod astralsorcery. 
> [K[17:49:16] [Server thread/INFO] [Chisel]: Received 29 IMC messages from mod techguns. 
> [K[17:49:16] [Server thread/INFO] [Chisel]: Received 22 IMC messages from mod tconstruct. 
> [K[17:49:17] [Server thread/INFO] [net.blay09.mods.craftingtweaks.CraftingTweaks]: fastbench has registered shadows.fastbench.gui.ContainerFastBench for CraftingTweaks 
> [K[17:49:17] [Server thread/INFO] [net.blay09.mods.craftingtweaks.CraftingTweaks]: tconstruct has registered slimeknights.tconstruct.tools.common.inventory.ContainerCraftingStation for CraftingTweaks 
> [K[17:49:17] [Server thread/INFO] [net.blay09.mods.craftingtweaks.CraftingTweaks]: refinedstorage has registered com.raoulvdberge.refinedstorage.container.ContainerGrid for CraftingTweaks 
> [K[17:49:17] [Server thread/INFO] [thermalfoundation]: Thermal Foundation: Tinkers' Construct Plugin Enabled. 
> [K[17:49:17] [Server thread/WARN] [thermalexpansion]: Thermal Expansion received an invalid IMC from chisel! Key was addcompactorpressrecipe 
[39;0m> [K[17:49:17] [Server thread/WARN] [thermalexpansion]: Thermal Expansion received an invalid IMC from chisel! Key was addcompactorpressrecipe 
[39;0m> [K[17:49:17] [Server thread/INFO] [FML]: Injecting itemstacks 
> [K[17:49:17] [Server thread/INFO] [FML]: Itemstack injection complete 
> [K[17:49:17] [Server thread/WARN] [FML]: No types have been added to Biome jeid:error_biome, types have been assigned on a best-effort guess: [PLAINS] 
[39;0m> [K[17:49:19] [Netty Epoll Server IO #1/INFO] [FML]: Disconnecting Player: Server is still starting! Please wait before reconnecting. 
> [K[17:49:20] [Netty Epoll Server IO #2/INFO] [FML]: Disconnecting Player: Server is still starting! Please wait before reconnecting. 
> [K[17:49:20] [Server thread/WARN] [pl.asie.charset.ModCharset]: Found OreDict cobblestone which does not give OreDict stone -> ItemMaterial[chisel:cobblestone;0] 
[39;0m> [K[17:49:20] [Server thread/WARN] [pl.asie.charset.ModCharset]: Found OreDict cobblestone which does not give OreDict stone -> ItemMaterial[chisel:cobblestone;1] 
[39;0m> [K[17:49:20] [Server thread/WARN] [pl.asie.charset.ModCharset]: Found OreDict cobblestone which does not give OreDict stone -> ItemMaterial[chisel:cobblestone;2] 
[39;0m> [K[17:49:20] [Server thread/WARN] [pl.asie.charset.ModCharset]: Found OreDict cobblestone which does not give OreDict stone -> ItemMaterial[chisel:cobblestone;3] 
[39;0m> [K[17:49:20] [Server thread/WARN] [pl.asie.charset.ModCharset]: Found OreDict cobblestone which does not give OreDict stone -> ItemMaterial[chisel:cobblestone;4] 
[39;0m> [K[17:49:20] [Server thread/WARN] [pl.asie.charset.ModCharset]: Found OreDict cobblestone which does not give OreDict stone -> ItemMaterial[chisel:cobblestone;5] 
[39;0m> [K[17:49:20] [Server thread/WARN] [pl.asie.charset.ModCharset]: Found OreDict cobblestone which does not give OreDict stone -> ItemMaterial[chisel:cobblestone;6] 
[39;0m> [K[17:49:20] [Server thread/WARN] [pl.asie.charset.ModCharset]: Found OreDict cobblestone which does not give OreDict stone -> ItemMaterial[chisel:cobblestone;7] 
[39;0m> [K[17:49:20] [Server thread/WARN] [pl.asie.charset.ModCharset]: Found OreDict cobblestone which does not give OreDict stone -> ItemMaterial[chisel:cobblestone;8] 
[39;0m> [K[17:49:20] [Server thread/WARN] [pl.asie.charset.ModCharset]: Found OreDict cobblestone which does not give OreDict stone -> ItemMaterial[chisel:cobblestone;9] 
[39;0m> [K[17:49:20] [Server thread/WARN] [pl.asie.charset.ModCharset]: Found OreDict cobblestone which does not give OreDict stone -> ItemMaterial[chisel:cobblestone;10] 
[39;0m> [K[17:49:20] [Server thread/WARN] [pl.asie.charset.ModCharset]: Found OreDict cobblestone which does not give OreDict stone -> ItemMaterial[chisel:cobblestone;11] 
[39;0m> [K[17:49:20] [Server thread/WARN] [pl.asie.charset.ModCharset]: Found OreDict cobblestone which does not give OreDict stone -> ItemMaterial[chisel:cobblestone;12] 
[39;0m> [K[17:49:20] [Server thread/WARN] [pl.asie.charset.ModCharset]: Found OreDict cobblestone which does not give OreDict stone -> ItemMaterial[chisel:cobblestone;13] 
[39;0m> [K[17:49:20] [Server thread/WARN] [pl.asie.charset.ModCharset]: Found OreDict cobblestone which does not give OreDict stone -> ItemMaterial[chisel:cobblestone;14] 
[39;0m> [K[17:49:20] [Server thread/WARN] [pl.asie.charset.ModCharset]: Found OreDict cobblestone which does not give OreDict stone -> ItemMaterial[chisel:cobblestone;15] 
[39;0m> [K[17:49:20] [Server thread/WARN] [pl.asie.charset.ModCharset]: Found OreDict cobblestone which does not give OreDict stone -> ItemMaterial[chisel:cobblestone1;0] 
[39;0m> [K[17:49:20] [Server thread/WARN] [pl.asie.charset.ModCharset]: Found OreDict cobblestone which does not give OreDict stone -> ItemMaterial[chisel:cobblestone1;1] 
[39;0m> [K[17:49:20] [Server thread/WARN] [pl.asie.charset.ModCharset]: Found OreDict cobblestone which does not give OreDict stone -> ItemMaterial[chisel:cobblestone1;2] 
[39;0m> [K[17:49:20] [Server thread/WARN] [pl.asie.charset.ModCharset]: Found OreDict cobblestone which does not give OreDict stone -> ItemMaterial[chisel:cobblestone1;3] 
[39;0m> [K[17:49:20] [Server thread/WARN] [pl.asie.charset.ModCharset]: Found OreDict cobblestone which does not give OreDict stone -> ItemMaterial[chisel:cobblestone1;4] 
[39;0m> [K[17:49:20] [Server thread/WARN] [pl.asie.charset.ModCharset]: Found OreDict cobblestone which does not give OreDict stone -> ItemMaterial[chisel:cobblestone1;5] 
[39;0m> [K[17:49:20] [Server thread/WARN] [pl.asie.charset.ModCharset]: Found OreDict cobblestone which does not give OreDict stone -> ItemMaterial[chisel:cobblestone1;6] 
[39;0m> [K[17:49:20] [Server thread/WARN] [pl.asie.charset.ModCharset]: Found OreDict cobblestone which does not give OreDict stone -> ItemMaterial[chisel:cobblestone1;7] 
[39;0m> [K[17:49:20] [Server thread/WARN] [pl.asie.charset.ModCharset]: Found OreDict cobblestone which does not give OreDict stone -> ItemMaterial[chisel:cobblestone1;8] 
[39;0m> [K[17:49:20] [Server thread/WARN] [pl.asie.charset.ModCharset]: Found OreDict cobblestone which does not give OreDict stone -> ItemMaterial[chisel:cobblestone1;9] 
[39;0m> [K[17:49:20] [Server thread/WARN] [pl.asie.charset.ModCharset]: Found OreDict cobblestone which does not give OreDict stone -> ItemMaterial[chisel:cobblestone2;0] 
[39;0m> [K[17:49:20] [Server thread/WARN] [pl.asie.charset.ModCharset]: Found OreDict cobblestone which does not give OreDict stone -> ItemMaterial[chisel:cobblestone2;1] 
[39;0m> [K[17:49:20] [Server thread/WARN] [pl.asie.charset.ModCharset]: Found OreDict cobblestone which does not give OreDict stone -> ItemMaterial[chisel:cobblestone2;2] 
[39;0m> [K[17:49:20] [Server thread/WARN] [pl.asie.charset.ModCharset]: Found OreDict cobblestone which does not give OreDict stone -> ItemMaterial[chisel:cobblestone2;3] 
[39;0m> [K[17:49:20] [Server thread/WARN] [pl.asie.charset.ModCharset]: Found OreDict cobblestone which does not give OreDict stone -> ItemMaterial[chisel:cobblestone2;4] 
[39;0m> [K[17:49:20] [Server thread/WARN] [pl.asie.charset.ModCharset]: Found OreDict cobblestone which does not give OreDict stone -> ItemMaterial[chisel:cobblestone2;5] 
[39;0m> [K[17:49:20] [Server thread/WARN] [pl.asie.charset.ModCharset]: Found OreDict cobblestone which does not give OreDict stone -> ItemMaterial[chisel:cobblestone2;6] 
[39;0m> [K[17:49:20] [Server thread/WARN] [pl.asie.charset.ModCharset]: Found OreDict cobblestone which does not give OreDict stone -> ItemMaterial[chisel:cobblestone2;7] 
[39;0m> [K[17:49:20] [Server thread/WARN] [pl.asie.charset.ModCharset]: Found OreDict cobblestone which does not give OreDict stone -> ItemMaterial[chisel:cobblestone2;8] 
[39;0m> [K[17:49:20] [Server thread/WARN] [pl.asie.charset.ModCharset]: Found OreDict cobblestone which does not give OreDict stone -> ItemMaterial[chisel:cobblestone2;9] 
[39;0m> [K[17:49:26] [Server thread/INFO] [pl.asie.charset.ModCharset]: Charset material heuristics time (phase 2): 9266ms 
> [K[17:49:26] [Server thread/INFO] [AbyssalCraft]: Post-initializing integrations! 
> [K[17:49:30] [Server thread/INFO] [Astral Core]: [AstralTransformer] Transforming alm : net.minecraft.enchantment.EnchantmentHelper with 1 patches! 
> [K[17:49:30] [Server thread/INFO] [Astral Core]: [AstralTransformer] Applied patch PATCHMODIFYENCHANTMENTLEVELS 
> [K[17:49:37] [Server thread/INFO] [THAUMCRAFT]: Loaded 22 research entries from thaumcraft:research/alchemy 
> [K[17:49:37] [Server thread/INFO] [THAUMCRAFT]: Loaded 5 research entries from thaumcraft:research/eldritch 
> [K[17:49:37] [Server thread/INFO] [THAUMCRAFT]: Loaded 20 research entries from thaumcraft:research/basics 
> [K[17:49:37] [Server thread/INFO] [THAUMCRAFT]: Loaded 23 research entries from thaumcraft:research/auromancy 
> [K[17:49:37] [Server thread/INFO] [THAUMCRAFT]: Loaded 12 research entries from thaumcraft:research/scans 
> [K[17:49:37] [Server thread/INFO] [THAUMCRAFT]: Loaded 20 research entries from thaumcraft:research/artifice 
> [K[17:49:37] [Server thread/INFO] [THAUMCRAFT]: Loaded 2 research entries from metalchests:research/hungry_metal_chests 
> [K[17:49:37] [Server thread/INFO] [THAUMCRAFT]: Loaded 17 research entries from thaumcraft:research/infusion 
> [K[17:49:37] [Server thread/INFO] [THAUMCRAFT]: Loaded 29 research entries from thaumcraft:research/golemancy 
> [K[17:49:37] [Server thread/INFO] [THAUMCRAFT]: Loaded 11 research entries from rusticthaumaturgy:research/rustic_thaumaturgy 
> [K[17:49:37] [Server thread/INFO] [botania]: The Lexica Botania has 26879 words. 
> [K[17:50:00] [Server thread/INFO] [Ice And Fire]: A brother bound to a love he must hide 
> [K[17:50:00] [Server thread/INFO] [Ice And Fire]: The younger's armor is worn in the mind 
> [K[17:50:00] [Server thread/INFO] [Ice And Fire]: A cold iron throne holds a boy barely grown 
> [K[17:50:00] [Server thread/INFO] [Ice And Fire]: And now it is known 
> [K[17:50:00] [Server thread/INFO] [Ice And Fire]: A claim to the prize, a crown laced in lies 
> [K[17:50:00] [Server thread/INFO] [Ice And Fire]: You win or you die 
> [K[17:50:00] [Server thread/INFO] [Astral Sorcery]: Post compile recipes 
> [K[17:50:00] [Server thread/INFO] [betterbuilderswands]: Added 'minecraft:lapis_ore/0=>1*minecraft:lapis_ore/4=>minecraft:lapis_ore/0' to mapping 
> [K[17:50:00] [Server thread/INFO] [betterbuilderswands]: Added 'minecraft:lit_redstone_ore/0=>1*minecraft:redstone_ore/0=>minecraft:lit_redstone_ore/0' to mapping 
> [K[17:50:00] [Server thread/INFO] [betterbuilderswands]: Added 'minecraft:grass/0=>1*minecraft:grass/0=>minecraft:grass/0' to mapping 
> [K[17:50:00] [Server thread/INFO] [betterbuilderswands]: Added 'minecraft:grass/0=>1*minecraft:dirt/0=>minecraft:dirt/0' to mapping 
> [K[17:50:00] [Server thread/INFO] [betterbuilderswands]: Added 'minecraft:dirt/1=>1*minecraft:dirt/1=>minecraft:dirt/1' to mapping 
> [K[17:50:00] [Server thread/INFO] [betterbuilderswands]: Added 'minecraft:dirt/1=>1*minecraft:dirt/0=>minecraft:dirt/0' to mapping 
> [K[17:50:00] [Server thread/INFO] [betterbuilderswands]: Added 'minecraft:dirt/2=>1*minecraft:dirt/2=>minecraft:dirt/2' to mapping 
> [K[17:50:00] [Server thread/INFO] [betterbuilderswands]: Added 'minecraft:dirt/2=>1*minecraft:dirt/0=>minecraft:dirt/0' to mapping 
> [K[17:50:00] [Server thread/INFO] [reborncore]: Loaded registrys for net.minecraftforge.fml.common.event.FMLPostInitializationEvent in 0ms 
> [K[17:50:03] [Server thread/INFO] [techreborn]: 1227 recipes loaded 
> [K[17:50:03] [Server thread/WARN] [FML]: Potentially Dangerous alternative prefix `minecraft` for name `binnie.tile.machine`, expected `binniecore`. This could be a intended override, but in most cases indicates a broken mod. 
[39;0m> [K[17:50:03] [Server thread/WARN] [FML]: Potentially Dangerous alternative prefix `minecraft` for name `binnie.tile.machine.tesr`, expected `binniecore`. This could be a intended override, but in most cases indicates a broken mod. 
[39;0m> [K[17:50:03] [Server thread/INFO] [rustic]: Initialized Forestry compat module 
> [K[17:50:03] [Server thread/INFO] [STDOUT]: [exnihilocreatio.ExNihiloCreatio:postInit:119]: Loading crt 
> [K[17:50:32] [Server thread/INFO] [immersiveengineering]: Couldn't fully analyze 1xitem.dreadiumsamuraihelmet@32767, missing knowledge for {1xitem.dreadiumhelmet@0=1.0} 
> [K[17:50:32] [Server thread/INFO] [immersiveengineering]: Couldn't fully analyze 1xitem.t2_riot_leggings@32767, missing knowledge for {1xitem.t2_combat_leggings@0=1.0} 
> [K[17:50:32] [Server thread/INFO] [immersiveengineering]: Couldn't fully analyze 1xitem.ij.jetpack@0, missing knowledge for {1xitem.ij.jetpack@0=1.0} 
> [K[17:50:32] [Server thread/INFO] [immersiveengineering]: Couldn't fully analyze 1xitem.corhelmetp@32767, missing knowledge for {1xitem.corhelmet@0=1.0} 
> [K[17:50:32] [Server thread/INFO] [immersiveengineering]: Couldn't fully analyze 1xitem.corlegsp@32767, missing knowledge for {1xitem.corlegs@0=1.0} 
> [K[17:50:32] [Server thread/INFO] [immersiveengineering]: Couldn't fully analyze 1xitem.dreadiumsamuraiplate@32767, missing knowledge for {1xitem.dreadiumplate@0=1.0} 
> [K[17:50:32] [Server thread/INFO] [immersiveengineering]: Couldn't fully analyze 1xitem.techreborn.advancedDrill@32767, missing knowledge for {1xitem.techreborn.diamondDrill@0=1.0} 
> [K[17:50:32] [Server thread/INFO] [immersiveengineering]: Couldn't fully analyze 1xitem.techreborn.diamondDrill@32767, missing knowledge for {1xitem.techreborn.ironDrill@0=1.0} 
> [K[17:50:32] [Server thread/INFO] [immersiveengineering]: Couldn't fully analyze 1xitem.terrasteelChest@32767, missing knowledge for {1xitem.manasteelChest@0=1.0} 
> [K[17:50:32] [Server thread/INFO] [immersiveengineering]: Couldn't fully analyze 1xitem.techreborn.diamondChainsaw@32767, missing knowledge for {1xitem.techreborn.ironChainsaw@0=1.0} 
> [K[17:50:32] [Server thread/INFO] [immersiveengineering]: Couldn't fully analyze 1xitem.techreborn.diamondJackhammer@32767, missing knowledge for {1xitem.techreborn.steelJackhammer@0=1.0} 
> [K[17:50:32] [Server thread/INFO] [immersiveengineering]: Couldn't fully analyze 1xitem.t2_riot_chestplate@32767, missing knowledge for {1xitem.t2_combat_chestplate@0=1.0} 
> [K[17:50:32] [Server thread/INFO] [immersiveengineering]: Couldn't fully analyze 1xitem.techreborn.advancedChainsaw@32767, missing knowledge for {1xitem.techreborn.diamondChainsaw@0=1.0} 
> [K[17:50:32] [Server thread/INFO] [immersiveengineering]: Couldn't fully analyze 1xitem.corplatep@32767, missing knowledge for {1xitem.corplate@0=1.0} 
> [K[17:50:32] [Server thread/INFO] [immersiveengineering]: Couldn't fully analyze 1xitem.terrasteelHelmReveal@32767, missing knowledge for {1xitem.manasteelHelmReveal@0=1.0} 
> [K[17:50:32] [Server thread/INFO] [immersiveengineering]: Couldn't fully analyze 1xitem.t3_exo_chestplate@32767, missing knowledge for {1xitem.t3_combat_chestplate@0=1.0} 
> [K[17:50:32] [Server thread/INFO] [immersiveengineering]: Couldn't fully analyze 1xitem.t3_exo_leggings@32767, missing knowledge for {1xitem.t3_combat_leggings@0=1.0} 
> [K[17:50:32] [Server thread/INFO] [immersiveengineering]: Couldn't fully analyze 1xitem.starSword@32767, missing knowledge for {1xitem.terraSword@0=1.0} 
> [K[17:50:32] [Server thread/INFO] [immersiveengineering]: Couldn't fully analyze 1xitem.terrasteelBoots@32767, missing knowledge for {1xitem.manasteelBoots@0=1.0} 
> [K[17:50:32] [Server thread/INFO] [immersiveengineering]: Couldn't fully analyze 1xitem.terrasteelHelm@32767, missing knowledge for {1xitem.manasteelHelm@0=1.0} 
> [K[17:50:32] [Server thread/INFO] [immersiveengineering]: Couldn't fully analyze 1xitem.t2_riot_helmet@32767, missing knowledge for {1xitem.t2_combat_helmet@0=1.0} 
> [K[17:50:32] [Server thread/INFO] [immersiveengineering]: Couldn't fully analyze 1xitem.terrasteelLegs@32767, missing knowledge for {1xitem.manasteelLegs@0=1.0} 
> [K[17:50:32] [Server thread/INFO] [immersiveengineering]: Couldn't fully analyze 1xitem.techreborn.lapotronpack@32767, missing knowledge for {1xitem.techreborn.lithiumbatpack@0=1.0} 
> [K[17:50:32] [Server thread/INFO] [immersiveengineering]: Couldn't fully analyze 1xtile.immersiveengineering.metal_device1@10, missing knowledge for {1xtile.immersiveengineering.metal_device0@4=1.0} 
> [K[17:50:32] [Server thread/INFO] [immersiveengineering]: Couldn't fully analyze 1xitem.t3_exo_helmet@32767, missing knowledge for {1xitem.t3_combat_helmet@0=1.0} 
> [K[17:50:32] [Server thread/INFO] [immersiveengineering]: Couldn't fully analyze 1xitem.t2_riot_boots@32767, missing knowledge for {1xitem.t2_combat_boots@0=1.0} 
> [K[17:50:32] [Server thread/INFO] [immersiveengineering]: Couldn't fully analyze 1xitem.techreborn.advancedJackhammer@32767, missing knowledge for {1xitem.techreborn.diamondJackhammer@0=1.0} 
> [K[17:50:32] [Server thread/INFO] [immersiveengineering]: Couldn't fully analyze 1xitem.t3_exo_boots@32767, missing knowledge for {1xitem.t3_combat_boots@0=1.0} 
> [K[17:50:32] [Server thread/INFO] [immersiveengineering]: Couldn't fully analyze 1xitem.corbootsp@32767, missing knowledge for {1xitem.corboots@0=1.0} 
> [K[17:50:32] [Server thread/INFO] [immersiveengineering]: Couldn't fully analyze 1xitem.thunderSword@32767, missing knowledge for {1xitem.terraSword@0=1.0} 
> [K[17:50:32] [Server thread/INFO] [STDERR]: [levelup2.skills.SkillRegistry:loadFromJson:368]: java.nio.file.NoSuchFileException: /home/hosting/servers/211912/config/levelup2/json/skills/combat/combat_bonus.json 
> [K[17:50:32] [Server thread/INFO] [STDERR]: [levelup2.skills.SkillRegistry:loadFromJson:368]: at sun.nio.fs.UnixException.translateToIOException(UnixException.java:86) 
> [K[17:50:32] [Server thread/INFO] [STDERR]: [levelup2.skills.SkillRegistry:loadFromJson:368]: at sun.nio.fs.UnixException.rethrowAsIOException(UnixException.java:102) 
> [K[17:50:32] [Server thread/INFO] [STDERR]: [levelup2.skills.SkillRegistry:loadFromJson:368]: at sun.nio.fs.UnixException.rethrowAsIOException(UnixException.java:107) 
> [K[17:50:32] [Server thread/INFO] [STDERR]: [levelup2.skills.SkillRegistry:loadFromJson:368]: at sun.nio.fs.UnixFileSystemProvider.newByteChannel(UnixFileSystemProvider.java:214) 
> [K[17:50:32] [Server thread/INFO] [STDERR]: [levelup2.skills.SkillRegistry:loadFromJson:368]: at java.nio.file.Files.newByteChannel(Files.java:361) 
> [K[17:50:32] [Server thread/INFO] [STDERR]: [levelup2.skills.SkillRegistry:loadFromJson:368]: at java.nio.file.Files.newByteChannel(Files.java:407) 
> [K[17:50:32] [Server thread/INFO] [STDERR]: [levelup2.skills.SkillRegistry:loadFromJson:368]: at java.nio.file.spi.FileSystemProvider.newInputStream(FileSystemProvider.java:384) 
> [K[17:50:32] [Server thread/INFO] [STDERR]: [levelup2.skills.SkillRegistry:loadFromJson:368]: at java.nio.file.Files.newInputStream(Files.java:152) 
> [K[17:50:32] [Server thread/INFO] [STDERR]: [levelup2.skills.SkillRegistry:loadFromJson:368]: at java.nio.file.Files.newBufferedReader(Files.java:2784) 
> [K[17:50:32] [Server thread/INFO] [STDERR]: [levelup2.skills.SkillRegistry:loadFromJson:368]: at java.nio.file.Files.newBufferedReader(Files.java:2816) 
> [K[17:50:32] [Server thread/INFO] [STDERR]: [levelup2.skills.SkillRegistry:loadFromJson:368]: at levelup2.skills.SkillRegistry.loadFromJson(SkillRegistry.java:365) 
> [K[17:50:32] [Server thread/INFO] [STDERR]: [levelup2.skills.SkillRegistry:loadFromJson:368]: at levelup2.skills.SkillRegistry.registerSkillProperties(SkillRegistry.java:351) 
> [K[17:50:32] [Server thread/INFO] [STDERR]: [levelup2.skills.SkillRegistry:loadFromJson:368]: at levelup2.config.LevelUpConfig.registerSkillProperties(LevelUpConfig.java:143) 
> [K[17:50:32] [Server thread/INFO] [STDERR]: [levelup2.skills.SkillRegistry:loadFromJson:368]: at levelup2.LevelUp2.postInit(LevelUp2.java:62) 
> [K[17:50:32] [Server thread/INFO] [STDERR]: [levelup2.skills.SkillRegistry:loadFromJson:368]: at sun.reflect.NativeMethodAccessorImpl.invoke0(Native Method) 
> [K[17:50:32] [Server thread/INFO] [STDERR]: [levelup2.skills.SkillRegistry:loadFromJson:368]: at sun.reflect.NativeMethodAccessorImpl.invoke(NativeMethodAccessorImpl.java:62) 
> [K[17:50:32] [Server thread/INFO] [STDERR]: [levelup2.skills.SkillRegistry:loadFromJson:368]: at sun.reflect.DelegatingMethodAccessorImpl.invoke(DelegatingMethodAccessorImpl.java:43) 
> [K[17:50:32] [Server thread/INFO] [STDERR]: [levelup2.skills.SkillRegistry:loadFromJson:368]: at java.lang.reflect.Method.invoke(Method.java:498) 
> [K[17:50:32] [Server thread/INFO] [STDERR]: [levelup2.skills.SkillRegistry:loadFromJson:368]: at net.minecraftforge.fml.common.FMLModContainer.handleModStateEvent(FMLModContainer.java:637) 
> [K[17:50:32] [Server thread/INFO] [STDERR]: [levelup2.skills.SkillRegistry:loadFromJson:368]: at sun.reflect.GeneratedMethodAccessor10.invoke(Unknown Source) 
> [K[17:50:32] [Server thread/INFO] [STDERR]: [levelup2.skills.SkillRegistry:loadFromJson:368]: at sun.reflect.DelegatingMethodAccessorImpl.invoke(DelegatingMethodAccessorImpl.java:43) 
> [K[17:50:32] [Server thread/INFO] [STDERR]: [levelup2.skills.SkillRegistry:loadFromJson:368]: at java.lang.reflect.Method.invoke(Method.java:498) 
> [K[17:50:32] [Server thread/INFO] [STDERR]: [levelup2.skills.SkillRegistry:loadFromJson:368]: at com.google.common.eventbus.Subscriber.invokeSubscriberMethod(Subscriber.java:91) 
> [K[17:50:32] [Server thread/INFO] [STDERR]: [levelup2.skills.SkillRegistry:loadFromJson:368]: at com.google.common.eventbus.Subscriber$SynchronizedSubscriber.invokeSubscriberMethod(Subscriber.java:150)
> [K[17:50:32] [Server thread/INFO] [STDERR]: [levelup2.skills.SkillRegistry:loadFromJson:368]: at com.google.common.eventbus.Subscriber$1.run(Subscriber.java:76) 
> [K[17:50:32] [Server thread/INFO] [STDERR]: [levelup2.skills.SkillRegistry:loadFromJson:368]: at com.google.common.util.concurrent.MoreExecutors$DirectExecutor.execute(MoreExecutors.java:399) 
> [K[17:50:32] [Server thread/INFO] [STDERR]: [levelup2.skills.SkillRegistry:loadFromJson:368]: at com.google.common.eventbus.Subscriber.dispatchEvent(Subscriber.java:71) 
> [K[17:50:32] [Server thread/INFO] [STDERR]: [levelup2.skills.SkillRegistry:loadFromJson:368]: at com.google.common.eventbus.Dispatcher$PerThreadQueuedDispatcher.dispatch(Dispatcher.java:116) 
> [K[17:50:32] [Server thread/INFO] [STDERR]: [levelup2.skills.SkillRegistry:loadFromJson:368]: at com.google.common.eventbus.EventBus.post(EventBus.java:217) 
> [K[17:50:32] [Server thread/INFO] [STDERR]: [levelup2.skills.SkillRegistry:loadFromJson:368]: at net.minecraftforge.fml.common.LoadController.sendEventToModContainer(LoadController.java:219) 
> [K[17:50:32] [Server thread/INFO] [STDERR]: [levelup2.skills.SkillRegistry:loadFromJson:368]: at net.minecraftforge.fml.common.LoadController.propogateStateMessage(LoadController.java:197) 
> [K[17:50:32] [Server thread/INFO] [STDERR]: [levelup2.skills.SkillRegistry:loadFromJson:368]: at sun.reflect.NativeMethodAccessorImpl.invoke0(Native Method) 
> [K[17:50:32] [Server thread/INFO] [STDERR]: [levelup2.skills.SkillRegistry:loadFromJson:368]: at sun.reflect.NativeMethodAccessorImpl.invoke(NativeMethodAccessorImpl.java:62) 
> [K[17:50:32] [Server thread/INFO] [STDERR]: [levelup2.skills.SkillRegistry:loadFromJson:368]: at sun.reflect.DelegatingMethodAccessorImpl.invoke(DelegatingMethodAccessorImpl.java:43) 
> [K[17:50:32] [Server thread/INFO] [STDERR]: [levelup2.skills.SkillRegistry:loadFromJson:368]: at java.lang.reflect.Method.invoke(Method.java:498) 
> [K[17:50:32] [Server thread/INFO] [STDERR]: [levelup2.skills.SkillRegistry:loadFromJson:368]: at com.google.common.eventbus.Subscriber.invokeSubscriberMethod(Subscriber.java:91) 
> [K[17:50:32] [Server thread/INFO] [STDERR]: [levelup2.skills.SkillRegistry:loadFromJson:368]: at com.google.common.eventbus.Subscriber$SynchronizedSubscriber.invokeSubscriberMethod(Subscriber.java:150)
> [K[17:50:32] [Server thread/INFO] [STDERR]: [levelup2.skills.SkillRegistry:loadFromJson:368]: at com.google.common.eventbus.Subscriber$1.run(Subscriber.java:76) 
> [K[17:50:32] [Server thread/INFO] [STDERR]: [levelup2.skills.SkillRegistry:loadFromJson:368]: at com.google.common.util.concurrent.MoreExecutors$DirectExecutor.execute(MoreExecutors.java:399) 
> [K[17:50:32] [Server thread/INFO] [STDERR]: [levelup2.skills.SkillRegistry:loadFromJson:368]: at com.google.common.eventbus.Subscriber.dispatchEvent(Subscriber.java:71) 
> [K[17:50:32] [Server thread/INFO] [STDERR]: [levelup2.skills.SkillRegistry:loadFromJson:368]: at com.google.common.eventbus.Dispatcher$PerThreadQueuedDispatcher.dispatch(Dispatcher.java:116) 
> [K[17:50:32] [Server thread/INFO] [STDERR]: [levelup2.skills.SkillRegistry:loadFromJson:368]: at com.google.common.eventbus.EventBus.post(EventBus.java:217) 
> [K[17:50:32] [Server thread/INFO] [STDERR]: [levelup2.skills.SkillRegistry:loadFromJson:368]: at net.minecraftforge.fml.common.LoadController.distributeStateMessage(LoadController.java:136) 
> [K[17:50:32] [Server thread/INFO] [STDERR]: [levelup2.skills.SkillRegistry:loadFromJson:368]: at net.minecraftforge.fml.common.Loader.initializeMods(Loader.java:749) 
> [K[17:50:32] [Server thread/INFO] [STDERR]: [levelup2.skills.SkillRegistry:loadFromJson:368]: at net.minecraftforge.fml.server.FMLServerHandler.finishServerLoading(FMLServerHandler.java:108) 
> [K[17:50:32] [Server thread/INFO] [STDERR]: [levelup2.skills.SkillRegistry:loadFromJson:368]: at net.minecraftforge.fml.common.FMLCommonHandler.onServerStarted(FMLCommonHandler.java:338) 
> [K[17:50:32] [Server thread/INFO] [STDERR]: [levelup2.skills.SkillRegistry:loadFromJson:368]: at net.minecraft.server.dedicated.DedicatedServer.func_71197_b(DedicatedServer.java:219) 
> [K[17:50:32] [Server thread/INFO] [STDERR]: [levelup2.skills.SkillRegistry:loadFromJson:368]: at net.minecraft.server.MinecraftServer.run(MinecraftServer.java:486) 
> [K[17:50:32] [Server thread/INFO] [STDERR]: [levelup2.skills.SkillRegistry:loadFromJson:368]: at java.lang.Thread.run(Thread.java:748) 
> [K[17:50:32] [Server thread/INFO] [STDERR]: [levelup2.skills.SkillRegistry:loadFromJson:368]: java.nio.file.NoSuchFileException: /home/hosting/servers/211912/config/levelup2/json/skills/crafting/craft_bonus.json 
> [K[17:50:32] [Server thread/INFO] [STDERR]: [levelup2.skills.SkillRegistry:loadFromJson:368]: at sun.nio.fs.UnixException.translateToIOException(UnixException.java:86) 
> [K[17:50:32] [Server thread/INFO] [STDERR]: [levelup2.skills.SkillRegistry:loadFromJson:368]: at sun.nio.fs.UnixException.rethrowAsIOException(UnixException.java:102) 
> [K[17:50:32] [Server thread/INFO] [STDERR]: [levelup2.skills.SkillRegistry:loadFromJson:368]: at sun.nio.fs.UnixException.rethrowAsIOException(UnixException.java:107) 
> [K[17:50:32] [Server thread/INFO] [STDERR]: [levelup2.skills.SkillRegistry:loadFromJson:368]: at sun.nio.fs.UnixFileSystemProvider.newByteChannel(UnixFileSystemProvider.java:214) 
> [K[17:50:32] [Server thread/INFO] [STDERR]: [levelup2.skills.SkillRegistry:loadFromJson:368]: at java.nio.file.Files.newByteChannel(Files.java:361) 
> [K[17:50:32] [Server thread/INFO] [STDERR]: [levelup2.skills.SkillRegistry:loadFromJson:368]: at java.nio.file.Files.newByteChannel(Files.java:407) 
> [K[17:50:32] [Server thread/INFO] [STDERR]: [levelup2.skills.SkillRegistry:loadFromJson:368]: at java.nio.file.spi.FileSystemProvider.newInputStream(FileSystemProvider.java:384) 
> [K[17:50:32] [Server thread/INFO] [STDERR]: [levelup2.skills.SkillRegistry:loadFromJson:368]: at java.nio.file.Files.newInputStream(Files.java:152) 
> [K[17:50:32] [Server thread/INFO] [STDERR]: [levelup2.skills.SkillRegistry:loadFromJson:368]: at java.nio.file.Files.newBufferedReader(Files.java:2784) 
> [K[17:50:32] [Server thread/INFO] [STDERR]: [levelup2.skills.SkillRegistry:loadFromJson:368]: at java.nio.file.Files.newBufferedReader(Files.java:2816) 
> [K[17:50:32] [Server thread/INFO] [STDERR]: [levelup2.skills.SkillRegistry:loadFromJson:368]: at levelup2.skills.SkillRegistry.loadFromJson(SkillRegistry.java:365) 
> [K[17:50:32] [Server thread/INFO] [STDERR]: [levelup2.skills.SkillRegistry:loadFromJson:368]: at levelup2.skills.SkillRegistry.registerSkillProperties(SkillRegistry.java:351) 
> [K[17:50:32] [Server thread/INFO] [STDERR]: [levelup2.skills.SkillRegistry:loadFromJson:368]: at levelup2.config.LevelUpConfig.registerSkillProperties(LevelUpConfig.java:143) 
> [K[17:50:32] [Server thread/INFO] [STDERR]: [levelup2.skills.SkillRegistry:loadFromJson:368]: at levelup2.LevelUp2.postInit(LevelUp2.java:62) 
> [K[17:50:32] [Server thread/INFO] [STDERR]: [levelup2.skills.SkillRegistry:loadFromJson:368]: at sun.reflect.NativeMethodAccessorImpl.invoke0(Native Method) 
> [K[17:50:32] [Server thread/INFO] [STDERR]: [levelup2.skills.SkillRegistry:loadFromJson:368]: at sun.reflect.NativeMethodAccessorImpl.invoke(NativeMethodAccessorImpl.java:62) 
> [K[17:50:32] [Server thread/INFO] [STDERR]: [levelup2.skills.SkillRegistry:loadFromJson:368]: at sun.reflect.DelegatingMethodAccessorImpl.invoke(DelegatingMethodAccessorImpl.java:43) 
> [K[17:50:32] [Server thread/INFO] [STDERR]: [levelup2.skills.SkillRegistry:loadFromJson:368]: at java.lang.reflect.Method.invoke(Method.java:498) 
> [K[17:50:32] [Server thread/INFO] [STDERR]: [levelup2.skills.SkillRegistry:loadFromJson:368]: at net.minecraftforge.fml.common.FMLModContainer.handleModStateEvent(FMLModContainer.java:637) 
> [K[17:50:32] [Server thread/INFO] [STDERR]: [levelup2.skills.SkillRegistry:loadFromJson:368]: at sun.reflect.GeneratedMethodAccessor10.invoke(Unknown Source) 
> [K[17:50:32] [Server thread/INFO] [STDERR]: [levelup2.skills.SkillRegistry:loadFromJson:368]: at sun.reflect.DelegatingMethodAccessorImpl.invoke(DelegatingMethodAccessorImpl.java:43) 
> [K[17:50:32] [Server thread/INFO] [STDERR]: [levelup2.skills.SkillRegistry:loadFromJson:368]: at java.lang.reflect.Method.invoke(Method.java:498) 
> [K[17:50:32] [Server thread/INFO] [STDERR]: [levelup2.skills.SkillRegistry:loadFromJson:368]: at com.google.common.eventbus.Subscriber.invokeSubscriberMethod(Subscriber.java:91) 
> [K[17:50:32] [Server thread/INFO] [STDERR]: [levelup2.skills.SkillRegistry:loadFromJson:368]: at com.google.common.eventbus.Subscriber$SynchronizedSubscriber.invokeSubscriberMethod(Subscriber.java:150)
> [K[17:50:32] [Server thread/INFO] [STDERR]: [levelup2.skills.SkillRegistry:loadFromJson:368]: at com.google.common.eventbus.Subscriber$1.run(Subscriber.java:76) 
> [K[17:50:32] [Server thread/INFO] [STDERR]: [levelup2.skills.SkillRegistry:loadFromJson:368]: at com.google.common.util.concurrent.MoreExecutors$DirectExecutor.execute(MoreExecutors.java:399) 
> [K[17:50:32] [Server thread/INFO] [STDERR]: [levelup2.skills.SkillRegistry:loadFromJson:368]: at com.google.common.eventbus.Subscriber.dispatchEvent(Subscriber.java:71) 
> [K[17:50:32] [Server thread/INFO] [STDERR]: [levelup2.skills.SkillRegistry:loadFromJson:368]: at com.google.common.eventbus.Dispatcher$PerThreadQueuedDispatcher.dispatch(Dispatcher.java:116) 
> [K[17:50:32] [Server thread/INFO] [STDERR]: [levelup2.skills.SkillRegistry:loadFromJson:368]: at com.google.common.eventbus.EventBus.post(EventBus.java:217) 
> [K[17:50:32] [Server thread/INFO] [STDERR]: [levelup2.skills.SkillRegistry:loadFromJson:368]: at net.minecraftforge.fml.common.LoadController.sendEventToModContainer(LoadController.java:219) 
> [K[17:50:32] [Server thread/INFO] [STDERR]: [levelup2.skills.SkillRegistry:loadFromJson:368]: at net.minecraftforge.fml.common.LoadController.propogateStateMessage(LoadController.java:197) 
> [K[17:50:32] [Server thread/INFO] [STDERR]: [levelup2.skills.SkillRegistry:loadFromJson:368]: at sun.reflect.NativeMethodAccessorImpl.invoke0(Native Method) 
> [K[17:50:32] [Server thread/INFO] [STDERR]: [levelup2.skills.SkillRegistry:loadFromJson:368]: at sun.reflect.NativeMethodAccessorImpl.invoke(NativeMethodAccessorImpl.java:62) 
> [K[17:50:32] [Server thread/INFO] [STDERR]: [levelup2.skills.SkillRegistry:loadFromJson:368]: at sun.reflect.DelegatingMethodAccessorImpl.invoke(DelegatingMethodAccessorImpl.java:43) 
> [K[17:50:32] [Server thread/INFO] [STDERR]: [levelup2.skills.SkillRegistry:loadFromJson:368]: at java.lang.reflect.Method.invoke(Method.java:498) 
> [K[17:50:32] [Server thread/INFO] [STDERR]: [levelup2.skills.SkillRegistry:loadFromJson:368]: at com.google.common.eventbus.Subscriber.invokeSubscriberMethod(Subscriber.java:91) 
> [K[17:50:32] [Server thread/INFO] [STDERR]: [levelup2.skills.SkillRegistry:loadFromJson:368]: at com.google.common.eventbus.Subscriber$SynchronizedSubscriber.invokeSubscriberMethod(Subscriber.java:150)
> [K[17:50:32] [Server thread/INFO] [STDERR]: [levelup2.skills.SkillRegistry:loadFromJson:368]: at com.google.common.eventbus.Subscriber$1.run(Subscriber.java:76) 
> [K[17:50:32] [Server thread/INFO] [STDERR]: [levelup2.skills.SkillRegistry:loadFromJson:368]: at com.google.common.util.concurrent.MoreExecutors$DirectExecutor.execute(MoreExecutors.java:399) 
> [K[17:50:32] [Server thread/INFO] [STDERR]: [levelup2.skills.SkillRegistry:loadFromJson:368]: at com.google.common.eventbus.Subscriber.dispatchEvent(Subscriber.java:71) 
> [K[17:50:32] [Server thread/INFO] [STDERR]: [levelup2.skills.SkillRegistry:loadFromJson:368]: at com.google.common.eventbus.Dispatcher$PerThreadQueuedDispatcher.dispatch(Dispatcher.java:116) 
> [K[17:50:32] [Server thread/INFO] [STDERR]: [levelup2.skills.SkillRegistry:loadFromJson:368]: at com.google.common.eventbus.EventBus.post(EventBus.java:217) 
> [K[17:50:32] [Server thread/INFO] [STDERR]: [levelup2.skills.SkillRegistry:loadFromJson:368]: at net.minecraftforge.fml.common.LoadController.distributeStateMessage(LoadController.java:136) 
> [K[17:50:32] [Server thread/INFO] [STDERR]: [levelup2.skills.SkillRegistry:loadFromJson:368]: at net.minecraftforge.fml.common.Loader.initializeMods(Loader.java:749) 
> [K[17:50:32] [Server thread/INFO] [STDERR]: [levelup2.skills.SkillRegistry:loadFromJson:368]: at net.minecraftforge.fml.server.FMLServerHandler.finishServerLoading(FMLServerHandler.java:108) 
> [K[17:50:32] [Server thread/INFO] [STDERR]: [levelup2.skills.SkillRegistry:loadFromJson:368]: at net.minecraftforge.fml.common.FMLCommonHandler.onServerStarted(FMLCommonHandler.java:338) 
> [K[17:50:32] [Server thread/INFO] [STDERR]: [levelup2.skills.SkillRegistry:loadFromJson:368]: at net.minecraft.server.dedicated.DedicatedServer.func_71197_b(DedicatedServer.java:219) 
> [K[17:50:32] [Server thread/INFO] [STDERR]: [levelup2.skills.SkillRegistry:loadFromJson:368]: at net.minecraft.server.MinecraftServer.run(MinecraftServer.java:486) 
> [K[17:50:32] [Server thread/INFO] [STDERR]: [levelup2.skills.SkillRegistry:loadFromJson:368]: at java.lang.Thread.run(Thread.java:748) 
> [K[17:50:32] [Server thread/INFO] [STDERR]: [levelup2.skills.SkillRegistry:loadFromJson:368]: java.nio.file.NoSuchFileException: /home/hosting/servers/211912/config/levelup2/json/skills/mining/mining_bonus.json 
> [K[17:50:32] [Server thread/INFO] [STDERR]: [levelup2.skills.SkillRegistry:loadFromJson:368]: at sun.nio.fs.UnixException.translateToIOException(UnixException.java:86) 
> [K[17:50:32] [Server thread/INFO] [STDERR]: [levelup2.skills.SkillRegistry:loadFromJson:368]: at sun.nio.fs.UnixException.rethrowAsIOException(UnixException.java:102) 
> [K[17:50:32] [Server thread/INFO] [STDERR]: [levelup2.skills.SkillRegistry:loadFromJson:368]: at sun.nio.fs.UnixException.rethrowAsIOException(UnixException.java:107) 
> [K[17:50:32] [Server thread/INFO] [STDERR]: [levelup2.skills.SkillRegistry:loadFromJson:368]: at sun.nio.fs.UnixFileSystemProvider.newByteChannel(UnixFileSystemProvider.java:214) 
> [K[17:50:32] [Server thread/INFO] [STDERR]: [levelup2.skills.SkillRegistry:loadFromJson:368]: at java.nio.file.Files.newByteChannel(Files.java:361) 
> [K[17:50:32] [Server thread/INFO] [STDERR]: [levelup2.skills.SkillRegistry:loadFromJson:368]: at java.nio.file.Files.newByteChannel(Files.java:407) 
> [K[17:50:32] [Server thread/INFO] [STDERR]: [levelup2.skills.SkillRegistry:loadFromJson:368]: at java.nio.file.spi.FileSystemProvider.newInputStream(FileSystemProvider.java:384) 
> [K[17:50:32] [Server thread/INFO] [STDERR]: [levelup2.skills.SkillRegistry:loadFromJson:368]: at java.nio.file.Files.newInputStream(Files.java:152) 
> [K[17:50:32] [Server thread/INFO] [STDERR]: [levelup2.skills.SkillRegistry:loadFromJson:368]: at java.nio.file.Files.newBufferedReader(Files.java:2784) 
> [K[17:50:32] [Server thread/INFO] [STDERR]: [levelup2.skills.SkillRegistry:loadFromJson:368]: at java.nio.file.Files.newBufferedReader(Files.java:2816) 
> [K[17:50:32] [Server thread/INFO] [STDERR]: [levelup2.skills.SkillRegistry:loadFromJson:368]: at levelup2.skills.SkillRegistry.loadFromJson(SkillRegistry.java:365) 
> [K[17:50:32] [Server thread/INFO] [STDERR]: [levelup2.skills.SkillRegistry:loadFromJson:368]: at levelup2.skills.SkillRegistry.registerSkillProperties(SkillRegistry.java:351) 
> [K[17:50:32] [Server thread/INFO] [STDERR]: [levelup2.skills.SkillRegistry:loadFromJson:368]: at levelup2.config.LevelUpConfig.registerSkillProperties(LevelUpConfig.java:143) 
> [K[17:50:32] [Server thread/INFO] [STDERR]: [levelup2.skills.SkillRegistry:loadFromJson:368]: at levelup2.LevelUp2.postInit(LevelUp2.java:62) 
> [K[17:50:32] [Server thread/INFO] [STDERR]: [levelup2.skills.SkillRegistry:loadFromJson:368]: at sun.reflect.NativeMethodAccessorImpl.invoke0(Native Method) 
> [K[17:50:32] [Server thread/INFO] [STDERR]: [levelup2.skills.SkillRegistry:loadFromJson:368]: at sun.reflect.NativeMethodAccessorImpl.invoke(NativeMethodAccessorImpl.java:62) 
> [K[17:50:32] [Server thread/INFO] [STDERR]: [levelup2.skills.SkillRegistry:loadFromJson:368]: at sun.reflect.DelegatingMethodAccessorImpl.invoke(DelegatingMethodAccessorImpl.java:43) 
> [K[17:50:32] [Server thread/INFO] [STDERR]: [levelup2.skills.SkillRegistry:loadFromJson:368]: at java.lang.reflect.Method.invoke(Method.java:498) 
> [K[17:50:32] [Server thread/INFO] [STDERR]: [levelup2.skills.SkillRegistry:loadFromJson:368]: at net.minecraftforge.fml.common.FMLModContainer.handleModStateEvent(FMLModContainer.java:637) 
> [K[17:50:32] [Server thread/INFO] [STDERR]: [levelup2.skills.SkillRegistry:loadFromJson:368]: at sun.reflect.GeneratedMethodAccessor10.invoke(Unknown Source) 
> [K[17:50:32] [Server thread/INFO] [STDERR]: [levelup2.skills.SkillRegistry:loadFromJson:368]: at sun.reflect.DelegatingMethodAccessorImpl.invoke(DelegatingMethodAccessorImpl.java:43) 
> [K[17:50:32] [Server thread/INFO] [STDERR]: [levelup2.skills.SkillRegistry:loadFromJson:368]: at java.lang.reflect.Method.invoke(Method.java:498) 
> [K[17:50:32] [Server thread/INFO] [STDERR]: [levelup2.skills.SkillRegistry:loadFromJson:368]: at com.google.common.eventbus.Subscriber.invokeSubscriberMethod(Subscriber.java:91) 
> [K[17:50:32] [Server thread/INFO] [STDERR]: [levelup2.skills.SkillRegistry:loadFromJson:368]: at com.google.common.eventbus.Subscriber$SynchronizedSubscriber.invokeSubscriberMethod(Subscriber.java:150)
> [K[17:50:32] [Server thread/INFO] [STDERR]: [levelup2.skills.SkillRegistry:loadFromJson:368]: at com.google.common.eventbus.Subscriber$1.run(Subscriber.java:76) 
> [K[17:50:32] [Server thread/INFO] [STDERR]: [levelup2.skills.SkillRegistry:loadFromJson:368]: at com.google.common.util.concurrent.MoreExecutors$DirectExecutor.execute(MoreExecutors.java:399) 
> [K[17:50:32] [Server thread/INFO] [STDERR]: [levelup2.skills.SkillRegistry:loadFromJson:368]: at com.google.common.eventbus.Subscriber.dispatchEvent(Subscriber.java:71) 
> [K[17:50:32] [Server thread/INFO] [STDERR]: [levelup2.skills.SkillRegistry:loadFromJson:368]: at com.google.common.eventbus.Dispatcher$PerThreadQueuedDispatcher.dispatch(Dispatcher.java:116) 
> [K[17:50:32] [Server thread/INFO] [STDERR]: [levelup2.skills.SkillRegistry:loadFromJson:368]: at com.google.common.eventbus.EventBus.post(EventBus.java:217) 
> [K[17:50:32] [Server thread/INFO] [STDERR]: [levelup2.skills.SkillRegistry:loadFromJson:368]: at net.minecraftforge.fml.common.LoadController.sendEventToModContainer(LoadController.java:219) 
> [K[17:50:32] [Server thread/INFO] [STDERR]: [levelup2.skills.SkillRegistry:loadFromJson:368]: at net.minecraftforge.fml.common.LoadController.propogateStateMessage(LoadController.java:197) 
> [K[17:50:32] [Server thread/INFO] [STDERR]: [levelup2.skills.SkillRegistry:loadFromJson:368]: at sun.reflect.NativeMethodAccessorImpl.invoke0(Native Method) 
> [K[17:50:32] [Server thread/INFO] [STDERR]: [levelup2.skills.SkillRegistry:loadFromJson:368]: at sun.reflect.NativeMethodAccessorImpl.invoke(NativeMethodAccessorImpl.java:62) 
> [K[17:50:32] [Server thread/INFO] [STDERR]: [levelup2.skills.SkillRegistry:loadFromJson:368]: at sun.reflect.DelegatingMethodAccessorImpl.invoke(DelegatingMethodAccessorImpl.java:43) 
> [K[17:50:32] [Server thread/INFO] [STDERR]: [levelup2.skills.SkillRegistry:loadFromJson:368]: at java.lang.reflect.Method.invoke(Method.java:498) 
> [K[17:50:32] [Server thread/INFO] [STDERR]: [levelup2.skills.SkillRegistry:loadFromJson:368]: at com.google.common.eventbus.Subscriber.invokeSubscriberMethod(Subscriber.java:91) 
> [K[17:50:32] [Server thread/INFO] [STDERR]: [levelup2.skills.SkillRegistry:loadFromJson:368]: at com.google.common.eventbus.Subscriber$SynchronizedSubscriber.invokeSubscriberMethod(Subscriber.java:150)
> [K[17:50:32] [Server thread/INFO] [STDERR]: [levelup2.skills.SkillRegistry:loadFromJson:368]: at com.google.common.eventbus.Subscriber$1.run(Subscriber.java:76) 
> [K[17:50:32] [Server thread/INFO] [STDERR]: [levelup2.skills.SkillRegistry:loadFromJson:368]: at com.google.common.util.concurrent.MoreExecutors$DirectExecutor.execute(MoreExecutors.java:399) 
> [K[17:50:32] [Server thread/INFO] [STDERR]: [levelup2.skills.SkillRegistry:loadFromJson:368]: at com.google.common.eventbus.Subscriber.dispatchEvent(Subscriber.java:71) 
> [K[17:50:32] [Server thread/INFO] [STDERR]: [levelup2.skills.SkillRegistry:loadFromJson:368]: at com.google.common.eventbus.Dispatcher$PerThreadQueuedDispatcher.dispatch(Dispatcher.java:116) 
> [K[17:50:32] [Server thread/INFO] [STDERR]: [levelup2.skills.SkillRegistry:loadFromJson:368]: at com.google.common.eventbus.EventBus.post(EventBus.java:217) 
> [K[17:50:32] [Server thread/INFO] [STDERR]: [levelup2.skills.SkillRegistry:loadFromJson:368]: at net.minecraftforge.fml.common.LoadController.distributeStateMessage(LoadController.java:136) 
> [K[17:50:32] [Server thread/INFO] [STDERR]: [levelup2.skills.SkillRegistry:loadFromJson:368]: at net.minecraftforge.fml.common.Loader.initializeMods(Loader.java:749) 
> [K[17:50:32] [Server thread/INFO] [STDERR]: [levelup2.skills.SkillRegistry:loadFromJson:368]: at net.minecraftforge.fml.server.FMLServerHandler.finishServerLoading(FMLServerHandler.java:108) 
> [K[17:50:32] [Server thread/INFO] [STDERR]: [levelup2.skills.SkillRegistry:loadFromJson:368]: at net.minecraftforge.fml.common.FMLCommonHandler.onServerStarted(FMLCommonHandler.java:338) 
> [K[17:50:32] [Server thread/INFO] [STDERR]: [levelup2.skills.SkillRegistry:loadFromJson:368]: at net.minecraft.server.dedicated.DedicatedServer.func_71197_b(DedicatedServer.java:219) 
> [K[17:50:32] [Server thread/INFO] [STDERR]: [levelup2.skills.SkillRegistry:loadFromJson:368]: at net.minecraft.server.MinecraftServer.run(MinecraftServer.java:486) 
> [K[17:50:32] [Server thread/INFO] [STDERR]: [levelup2.skills.SkillRegistry:loadFromJson:368]: at java.lang.Thread.run(Thread.java:748) 
> [K[17:50:32] [Server thread/INFO] [Mekanica]: Fake player readout: UUID = 46e82cd0-d480-3d48-800a-77431ede078e, name = [Mekanica] 
> [K[17:50:32] [Server thread/INFO] [Mekanica]: Finished loading Cardboard Box blacklist (loaded 0 entries) 
> [K[17:50:32] [Server thread/INFO] [Mekanica]: Hooking complete. 
> [K[17:50:32] [Server thread/INFO] [opencomputers]: Done with post init phase. 
> [K[17:50:33] [Server thread/INFO] [thermalexpansion]: Thermal Expansion: Forestry Plugin Enabled. 
> [K[17:50:33] [Server thread/INFO] [thermalexpansion]: Thermal Expansion: Extra Bees Plugin Enabled. 
> [K[17:50:33] [Server thread/INFO] [thermalexpansion]: Thermal Expansion: Extra Trees Plugin Enabled.
> [K[17:50:33] [Server thread/INFO] [thermalexpansion]: Thermal Expansion: AbyssalCraft Plugin Enabled. 
> [K[17:50:33] [Server thread/INFO] [thermalexpansion]: Thermal Expansion: Astral Sorcery Plugin Enabled. 
> [K[17:50:33] [Server thread/INFO] [thermalexpansion]: Thermal Expansion: Chisel Plugin Enabled. 
> [K[17:50:33] [Server thread/INFO] [thermalexpansion]: Thermal Expansion: Ice and Fire Plugin Enabled. 
> [K[17:50:33] [Server thread/INFO] [thermalexpansion]: Thermal Expansion: Immersive Engineering Plugin Enabled. 
> [K[17:50:33] [Server thread/INFO] [thermalexpansion]: Thermal Expansion: Rustic Plugin Enabled. 
> [K[17:50:33] [Server thread/INFO] [thermalexpansion]: Thermal Expansion: Tinkers' Construct Plugin Enabled. 
> [K[17:50:33] [Server thread/INFO] [thermalexpansion]: Thermal Expansion: Tech Reborn Plugin Enabled.
> [K[17:50:33] [Server thread/INFO] [thermalexpansion]: Thermal Expansion: Thaumcraft Plugin Enabled. 
> [K[17:50:35] [Server thread/INFO] [FML]: [ThermalSolars] ThermalSolars -------------- successfully Finished postInit 
> [K[17:50:35] [Server thread/INFO] [worldedit]: WorldEdit for Forge (version 6.1.10-SNAPSHOT) is loaded 
> [K[17:50:35] [Server thread/INFO] [wanionlib]: UniDict: Initializing Module: Integration, Side: Server 
> [K[17:50:35] [Server thread/INFO] [wanionlib]: Crafting Integration: Why so many recipes? I had to deal with at least 265 recipes. 
> [K[17:50:35] [Server thread/INFO] [wanionlib]: Furnace Integration: Some things that you smelted appear to be different now. 
> [K[17:50:35] [Server thread/INFO] [wanionlib]: AbyssalCraft Integration: TransMules Fixes! 
> [K[17:50:35] [Server thread/INFO] [wanionlib]: Forestry Integration: All these bees... they can hurt, you know? 
> [K[17:50:35] [Server thread/INFO] [wanionlib]: Immersive Engineering Integration: The world's engineer appears to be more immersive. 
> [K[17:50:35] [Server thread/INFO] [wanionlib]: Mekanism Integration: All the mekanisms were checked.
> [K[17:50:35] [Server thread/INFO] [wanionlib]: TechReborn Integration: now Tech is truly Reborn. 
> [K[17:50:35] [Server thread/INFO] [wanionlib]: Thermal Expansion Integration: The world seems to be more thermally involved. 
> [K[17:50:35] [Server thread/INFO] [wanionlib]: UniDict: All 8 Integrations took 82ms to finish. at load stage PostInit 
> [K[17:50:35] [Server thread/INFO] [cofhcore]: CoFH Core: Load Complete. 
> [K[17:50:36] [Server thread/WARN] [Caliper]: Unable to parse event listener: ASM: Butterflies & Moths onSyncBreedingTracker(Lforestry/api/core/ForestryEvent$SyncedBreedingTracker;)V. 
[39;0m> [K[17:50:36] [Server thread/INFO] [CoFH World]: Accumulating world generation files from: "/home/hosting/servers/211912/config/cofh/world" 
> [K[17:50:36] [Server thread/INFO] [CoFH World]: Found a total of 7 world generation files. 
> [K[17:50:37] [Server thread/INFO] [CoFH World]: Reading world generation info from: "cofh/world/01_thermalfoundation_ores.json": 
> [K[17:50:37] [Server thread/INFO] [CoFH World]: Reading world generation info from: "cofh/world/03_thermalfoundation_clathrates.json": 
> [K[17:50:37] [Server thread/INFO] [CoFH World]: Reading world generation info from: "cofh/world/vanilla.json": 
> [K[17:50:37] [Server thread/INFO] [CoFH World]: Reading world generation info from: "cofh/world/thermalfoundation_clathrates.json": 
> [K[17:50:37] [Server thread/WARN] [CoFH World]: Using `metadata` (at line: 12) for blocks is deprecated, and will be removed in the future. Use `properties` instead. 
[39;0m> [K[17:50:37] [Server thread/ERROR] [CoFH World]: Error parsing `populate` entry: 'redstone_clathrate' > It is a duplicate. 
[39;0m> [K[17:50:37] [Server thread/WARN] [CoFH World]: Using `metadata` (at line: 44) for blocks is deprecated, and will be removed in the future. Use `properties` instead. 
[39;0m> [K[17:50:37] [Server thread/ERROR] [CoFH World]: Error parsing `populate` entry: 'glowstone_clathrate' > It is a duplicate. 
[39;0m> [K[17:50:37] [Server thread/WARN] [CoFH World]: Using `metadata` (at line: 77) for blocks is deprecated, and will be removed in the future. Use `properties` instead. 
[39;0m> [K[17:50:37] [Server thread/ERROR] [CoFH World]: Error parsing `populate` entry: 'ender_clathrate' > It is a duplicate. 
[39;0m> [K[17:50:37] [Server thread/INFO] [CoFH World]: Reading world generation info from: "cofh/world/thermalfoundation_ores.json": 
> [K[17:50:37] [Server thread/ERROR] [CoFH World]: Error parsing `populate` entry: 'copper' > It is a duplicate. 
[39;0m> [K[17:50:37] [Server thread/WARN] [CoFH World]: Using `metadata` (at line: 32) for blocks is deprecated, and will be removed in the future. Use `properties` instead. 
[39;0m> [K[17:50:37] [Server thread/ERROR] [CoFH World]: Error parsing `populate` entry: 'tin' > It is a duplicate. 
[39;0m> [K[17:50:37] [Server thread/WARN] [CoFH World]: Using `metadata` (at line: 57) for blocks is deprecated, and will be removed in the future. Use `properties` instead. 
[39;0m> [K[17:50:37] [Server thread/WARN] [CoFH World]: Using `metadata` (at line: 62) for blocks is deprecated, and will be removed in the future. Use `properties` instead. 
[39;0m> [K[17:50:37] [Server thread/ERROR] [CoFH World]: Error parsing `populate` entry: 'silver' > It is a duplicate. 
[39;0m> [K[17:50:37] [Server thread/WARN] [CoFH World]: Using `metadata` (at line: 89) for blocks is deprecated, and will be removed in the future. Use `properties` instead. 
[39;0m> [K[17:50:37] [Server thread/WARN] [CoFH World]: Using `metadata` (at line: 94) for blocks is deprecated, and will be removed in the future. Use `properties` instead. 
[39;0m> [K[17:50:37] [Server thread/ERROR] [CoFH World]: Error parsing `populate` entry: 'lead' > It is a duplicate. 
[39;0m> [K[17:50:37] [Server thread/WARN] [CoFH World]: Using `metadata` (at line: 120) for blocks is deprecated, and will be removed in the future. Use `properties` instead. 
[39;0m> [K[17:50:37] [Server thread/ERROR] [CoFH World]: Error parsing `populate` entry: 'nickel' > It is a duplicate. 
[39;0m> [K[17:50:37] [Server thread/ERROR] [CoFH World]: Error parsing `populate` entry: 'copper_ocean' > It is a duplicate. 
[39;0m> [K[17:50:37] [Server thread/ERROR] [CoFH World]: Error parsing `populate` entry: 'copper_high' > It is a duplicate. 
[39;0m> [K[17:50:37] [Server thread/INFO] [CoFH World]: Reading world generation info from: "cofh/world/thermalfoundation_oil.json": 
> [K[17:50:37] [Server thread/WARN] [CoFH World]: Using `metadata` (at line: 40) for blocks is deprecated, and will be removed in the future. Use `properties` instead. 
[39;0m> [K[17:50:37] [Server thread/WARN] [CoFH World]: Using `metadata` (at line: 91) for blocks is deprecated, and will be removed in the future. Use `properties` instead. 
[39;0m> [K[17:50:37] [Server thread/WARN] [CoFH World]: Using `metadata` (at line: 138) for blocks is deprecated, and will be removed in the future. Use `properties` instead. 
[39;0m> [K[17:50:37] [Server thread/INFO] [CoFH World]: Reading world generation info from: "cofh/world/02_thermalfoundation_oil.json": 
> [K[17:50:37] [Server thread/ERROR] [CoFH World]: Error parsing `populate` entry: 'oil_sand_clathrate' > It is a duplicate. 
[39;0m> [K[17:50:37] [Server thread/ERROR] [CoFH World]: Error parsing `populate` entry: 'oil_shale_clathrate' > It is a duplicate. 
[39;0m> [K[17:50:37] [Server thread/ERROR] [CoFH World]: Error parsing `populate` entry: 'oil_sand' > It is a duplicate. 
[39;0m> [K[17:50:37] [Server thread/ERROR] [CoFH World]: Error parsing `populate` entry: 'oil_shale' > It is a duplicate. 
[39;0m> [K[17:50:37] [Server thread/INFO] [CoFH World]: CoFH World: Load Complete. 
> [K[17:50:37] [Server thread/INFO] [thermalfoundation]: [Whitelist] Reading established Whitelist from file. 
> [K[17:50:37] [Server thread/INFO] [thermalfoundation]: Thermal Foundation: Load Complete. 
> [K[17:50:37] [Server thread/INFO] [thermalexpansion]: Thermal Expansion: Load Complete. 
> [K[17:50:37] [Server thread/INFO] [thermalcultivation]: Thermal Cultivation: Load Complete. 
> [K[17:50:37] [Server thread/INFO] [thermaldynamics]: Thermal Dynamics: Load Complete. 
> [K[17:50:37] [Server thread/INFO] [thermalinnovation]: Thermal Innovation: Load Complete. 
> [K[17:50:39] [Server thread/INFO] [FML]: Forge Mod Loader has successfully loaded 209 mods 
> [17:50:39][FINE/CustomNPCs][noppes.npcs.controllers.LinkedNpcController:42] Loading Linked Npcs 
[17:50:39][FINE/CustomNPCs][noppes.npcs.controllers.LinkedNpcController:62] Done loading Linked Npcs 
[K[17:50:40] [Server thread/INFO] [structurize]: Load huts or decorations from jar 
> [K[17:50:40] [Server thread/WARN] [structurize]: loadSchematicsForPrefix: Could not load schematics from /assets/structurize/schematics 
java.nio.file.NoSuchFileException: /assets/structurize/schematics 
at com.sun.nio.zipfs.ZipPath.getAttributes(ZipPath.java:666) ~[zipfs.jar:1.8.0_201] 
at com.sun.nio.zipfs.ZipFileSystemProvider.readAttributes(ZipFileSystemProvider.java:294) ~[zipfs.jar:1.8.0_201] 
at java.nio.file.Files.readAttributes(Files.java:1737) ~[?:1.8.0_201] 
at java.nio.file.FileTreeWalker.getAttributes(FileTreeWalker.java:219) ~[?:1.8.0_201] 
at java.nio.file.FileTreeWalker.visit(FileTreeWalker.java:276) ~[?:1.8.0_201] 
at java.nio.file.FileTreeWalker.walk(FileTreeWalker.java:322) ~[?:1.8.0_201] 
at java.nio.file.FileTreeIterator.<init>(FileTreeIterator.java:72) ~[?:1.8.0_201] 
at java.nio.file.Files.walk(Files.java:3574) ~[?:1.8.0_201] 
at java.nio.file.Files.walk(Files.java:3625) ~[?:1.8.0_201] 
at com.ldtteam.structurize.management.Structures.loadSchematicsForPrefix(Structures.java:274) [Structures.class:?] 
at com.ldtteam.structurize.management.Structures.loadStyleMapsJar(Structures.java:213) [Structures.class:?] 
at com.ldtteam.structurize.management.Structures.loadStyleMaps(Structures.java:152) [Structures.class:?] 
at com.ldtteam.structurize.management.Structures.init(Structures.java:139) [Structures.class:?] 
at com.ldtteam.structurize.Structurize.serverAboutLoad(Structurize.java:160) [Structurize.class:?] 
at sun.reflect.NativeMethodAccessorImpl.invoke0(Native Method) ~[?:1.8.0_201] 
at sun.reflect.NativeMethodAccessorImpl.invoke(NativeMethodAccessorImpl.java:62) ~[?:1.8.0_201] 
at sun.reflect.DelegatingMethodAccessorImpl.invoke(DelegatingMethodAccessorImpl.java:43) ~[?:1.8.0_201]
at java.lang.reflect.Method.invoke(Method.java:498) ~[?:1.8.0_201] 
at net.minecraftforge.fml.common.FMLModContainer.handleModStateEvent(FMLModContainer.java:637) [FMLModContainer.class:?] 
at sun.reflect.GeneratedMethodAccessor10.invoke(Unknown Source) ~[?:?] 
at sun.reflect.DelegatingMethodAccessorImpl.invoke(DelegatingMethodAccessorImpl.java:43) ~[?:1.8.0_201]
at java.lang.reflect.Method.invoke(Method.java:498) ~[?:1.8.0_201] 
at com.google.common.eventbus.Subscriber.invokeSubscriberMethod(Subscriber.java:91) inecraft_server.1.12.2.jar:?] 
at com.google.common.eventbus.Subscriber$SynchronizedSubscriber.invokeSubscriberMethod(Subscriber.java:150) inecraft_server.1.12.2.jar:?] 
at com.google.common.eventbus.Subscriber$1.run(Subscriber.java:76) inecraft_server.1.12.2.jar:?] 
at com.google.common.util.concurrent.MoreExecutors$DirectExecutor.execute(MoreExecutors.java:399) inecraft_server.1.12.2.jar:?] 
at com.google.common.eventbus.Subscriber.dispatchEvent(Subscriber.java:71) inecraft_server.1.12.2.jar:?] 
at com.google.common.eventbus.Dispatcher$PerThreadQueuedDispatcher.dispatch(Dispatcher.java:116) inecraft_server.1.12.2.jar:?] 
at com.google.common.eventbus.EventBus.post(EventBus.java:217) inecraft_server.1.12.2.jar:?] 
at net.minecraftforge.fml.common.LoadController.sendEventToModContainer(LoadController.java:219) [LoadController.class:?] 
at net.minecraftforge.fml.common.LoadController.propogateStateMessage(LoadController.java:197) [LoadController.class:?] 
at sun.reflect.NativeMethodAccessorImpl.invoke0(Native Method) ~[?:1.8.0_201] 
at sun.reflect.NativeMethodAccessorImpl.invoke(NativeMethodAccessorImpl.java:62) ~[?:1.8.0_201] 
at sun.reflect.DelegatingMethodAccessorImpl.invoke(DelegatingMethodAccessorImpl.java:43) ~[?:1.8.0_201]
at java.lang.reflect.Method.invoke(Method.java:498) ~[?:1.8.0_201] 
at com.google.common.eventbus.Subscriber.invokeSubscriberMethod(Subscriber.java:91) inecraft_server.1.12.2.jar:?] 
at com.google.common.eventbus.Subscriber$SynchronizedSubscriber.invokeSubscriberMethod(Subscriber.java:150) inecraft_server.1.12.2.jar:?] 
at com.google.common.eventbus.Subscriber$1.run(Subscriber.java:76) inecraft_server.1.12.2.jar:?] 
at com.google.common.util.concurrent.MoreExecutors$DirectExecutor.execute(MoreExecutors.java:399) inecraft_server.1.12.2.jar:?] 
at com.google.common.eventbus.Subscriber.dispatchEvent(Subscriber.java:71) inecraft_server.1.12.2.jar:?] 
at com.google.common.eventbus.Dispatcher$PerThreadQueuedDispatcher.dispatch(Dispatcher.java:116) inecraft_server.1.12.2.jar:?] 
at com.google.common.eventbus.EventBus.post(EventBus.java:217) inecraft_server.1.12.2.jar:?] 
at net.minecraftforge.fml.common.LoadController.distributeStateMessage(LoadController.java:136) [LoadController.class:?] 
at net.minecraftforge.fml.common.Loader.serverAboutToStart(Loader.java:854) [Loader.class:?] 
at net.minecraftforge.fml.common.FMLCommonHandler.handleServerAboutToStart(FMLCommonHandler.java:292) [FMLCommonHandler.class:?] 
at net.minecraft.server.dedicated.DedicatedServer.init(DedicatedServer.java:268) [nz.class:?] 
at net.minecraft.server.MinecraftServer.run(MinecraftServer.java:486) [MinecraftServer.class:?] 
at java.lang.Thread.run(Thread.java:748) [?:1.8.0_201] 
[39;0m> [K[17:50:40] [Server thread/INFO] [structurize]: Load huts or decorations from jar 
> [K[17:50:44] [Server thread/INFO] [structurize]: Load additionnal huts or decorations from ./structurize/schematics 
> [K[17:50:44] [Server thread/INFO] [structurize]: Load cached schematic from ./structurize/cache 
> [K[17:50:44] [Server thread/INFO] [structurize]: Load cached schematic from ./structurize/cache 
> [K[17:50:44] [Server thread/INFO] inecraft/DedicatedServer]: Preparing level "world" 
> [K[17:50:44] [Server thread/INFO] [FML]: Injecting existing registry data into this server instance 
> [K[17:50:46] [Server thread/INFO] [FML]: Applying holder lookups 
> [K[17:50:46] [Server thread/INFO] [FML]: Holder lookups applied 
> [K[17:50:47] [Server thread/INFO] [FML]: Loading dimension 0 (world) (net.minecraft.server.dedicated.DedicatedServer@5eb56087) 
> [K[17:50:48] [Server thread/INFO] inecraft/AdvancementList]: Loaded 880 advancements 
> [K[17:50:48] [Server thread/INFO] [FML]: Loading dimension -1 (world) (net.minecraft.server.dedicated.DedicatedServer@5eb56087) 
> [K[17:50:48] [Server thread/INFO] [THAUMCRAFT]: Creating aura cache for world -1 
> [K[17:50:48] [Server thread/INFO] inecolonies]: Server UUID 9c7511eb-dccf-41c7-9fae-0edf74c4a939 
> [K[17:50:48] [Server thread/INFO] [Astral Sorcery]: Checking GatewayCache integrity for dimension -1
> [K[17:50:48] [Server thread/INFO] [Astral Sorcery]: GatewayCache checked and fully loaded in 0ms! Collected and checked 0 gateway nodes! 
> [K[17:50:48] [Server thread/INFO] [FML]: Loading dimension 1 (world) (net.minecraft.server.dedicated.DedicatedServer@5eb56087) 
> [K[17:50:48] [Server thread/INFO] [THAUMCRAFT]: Creating aura cache for world 1 
> [K[17:50:48] [Server thread/INFO] [Astral Sorcery]: Checking GatewayCache integrity for dimension 1 
> [K[17:50:48] [Server thread/INFO] [Astral Sorcery]: GatewayCache checked and fully loaded in 0ms! Collected and checked 0 gateway nodes! 
> [K[17:50:49] [Server thread/INFO] [FML]: Loading dimension 50 (world) (net.minecraft.server.dedicated.DedicatedServer@5eb56087) 
> [K[17:50:49] [Server thread/INFO] [THAUMCRAFT]: Creating aura cache for world 50 
> [K[17:50:49] [Server thread/INFO] [Astral Sorcery]: Checking GatewayCache integrity for dimension 50
> [K[17:50:49] [Server thread/INFO] [Astral Sorcery]: GatewayCache checked and fully loaded in 0ms! Collected and checked 0 gateway nodes! 
> [K[17:50:49] [Server thread/INFO] [FML]: Loading dimension 51 (world) (net.minecraft.server.dedicated.DedicatedServer@5eb56087) 
> [K[17:50:49] [Server thread/INFO] [THAUMCRAFT]: Creating aura cache for world 51 
> [K[17:50:49] [Server thread/INFO] [Astral Sorcery]: Checking GatewayCache integrity for dimension 51
> [K[17:50:49] [Server thread/INFO] [Astral Sorcery]: GatewayCache checked and fully loaded in 0ms! Collected and checked 0 gateway nodes! 
> [K[17:50:49] [Server thread/INFO] [FML]: Loading dimension 52 (world) (net.minecraft.server.dedicated.DedicatedServer@5eb56087) 
> [K[17:50:49] [Server thread/INFO] [THAUMCRAFT]: Creating aura cache for world 52 
> [K[17:50:49] [Server thread/INFO] [Astral Sorcery]: Checking GatewayCache integrity for dimension 52
> [K[17:50:49] [Server thread/INFO] [Astral Sorcery]: GatewayCache checked and fully loaded in 0ms! Collected and checked 0 gateway nodes! 
> [K[17:50:49] [Server thread/INFO] [FML]: Loading dimension 53 (world) (net.minecraft.server.dedicated.DedicatedServer@5eb56087) 
> [K[17:50:49] [Server thread/INFO] [THAUMCRAFT]: Creating aura cache for world 53 
> [K[17:50:49] [Server thread/INFO] [Astral Sorcery]: Checking GatewayCache integrity for dimension 53
> [K[17:50:49] [Server thread/INFO] [Astral Sorcery]: GatewayCache checked and fully loaded in 0ms! Collected and checked 0 gateway nodes! 
> [K[17:50:49] [Server thread/INFO] [FML]: Loading dimension -23 (world) (net.minecraft.server.dedicated.DedicatedServer@5eb56087) 
> [K[17:50:49] [Server thread/INFO] [THAUMCRAFT]: Creating aura cache for world -23 
> [K[17:50:49] [Server thread/INFO] [Astral Sorcery]: Checking GatewayCache integrity for dimension -23 
> [K[17:50:49] [Server thread/INFO] [Astral Sorcery]: GatewayCache checked and fully loaded in 0ms! Collected and checked 0 gateway nodes! 
> [K[17:50:49] [Server thread/INFO] [FML]: Loading dimension -34 (world) (net.minecraft.server.dedicated.DedicatedServer@5eb56087) 
> [K[17:50:49] [Server thread/INFO] [THAUMCRAFT]: Creating aura cache for world -34 
> [K[17:50:49] [Server thread/INFO] [Astral Sorcery]: Checking GatewayCache integrity for dimension -34 
> [K[17:50:49] [Server thread/INFO] [Astral Sorcery]: GatewayCache checked and fully loaded in 0ms! Collected and checked 0 gateway nodes! 
> [K[17:50:49] [Server thread/INFO] [THAUMCRAFT]: Creating aura cache for world 0 
> [K[17:50:49] [Server thread/INFO] [FTB Quests]: Loading quests from /home/hosting/servers/211912/config/ftbquests/normal 
> [K[17:50:49] [Server thread/INFO] [FTB Quests]: Loaded 15 chapters, 140 quests, 174 tasks, 157 rewards and 0 variables. In total, 486 objects 
> [K[17:50:50] [Server thread/INFO] inecraft/AdvancementList]: Loaded 880 advancements 
> [K[17:50:50] [Server thread/INFO] [FTB Library]: Reloaded server in 61ms 
> [K[17:50:50] [Server thread/INFO] [Astral Sorcery]: Checking GatewayCache integrity for dimension 0 
> [K[17:50:50] [Server thread/INFO] [Astral Sorcery]: GatewayCache checked and fully loaded in 0ms! Collected and checked 0 gateway nodes! 
> [K[17:50:50] [Server thread/INFO] inecraft/DedicatedServer]: Done (11.265s)! For help, type "help" or "?" 
> [K[17:50:50] [Server thread/INFO] inecraft/DedicatedServer]: Starting GS4 status listener 
> [K[17:50:50] [Query Listener #1/INFO] inecraft/MinecraftServer]: Query running on 89.203.248.17:27895 
> [K[17:50:51] [Server thread/WARN] inecraft/EntityDataManager]: defineId called for: class net.minecraft.entity.player.EntityPlayer from class techguns.capabilities.TGExtendedPlayer 
[39;0m> [K[17:50:51] [Server thread/WARN] inecraft/EntityDataManager]: defineId called for: class net.minecraft.entity.player.EntityPlayer from class techguns.capabilities.TGExtendedPlayer 
[39;0m> [K[17:50:51] [Server thread/WARN] inecraft/EntityDataManager]: defineId called for: class net.minecraft.entity.player.EntityPlayer from class techguns.capabilities.TGExtendedPlayer 
[39;0m> [K[17:50:51] [Server thread/WARN] inecraft/EntityDataManager]: defineId called for: class net.minecraft.entity.player.EntityPlayer from class techguns.capabilities.TGExtendedPlayer 
[39;0m> [17:50:52][FINE/CustomNPCs][noppes.npcs.controllers.DialogController:44] Loading Dialogs 
[17:50:52][FINE/CustomNPCs][noppes.npcs.controllers.DialogController:46] Done loading Dialogs 
[K[17:50:52] [Server thread/INFO] [endertanks]: Loading EnderTank Data 
> [K[17:50:52] [Server thread/WARN] [FTB Utilities]: Command command.cofhcore.cofh (class: cofh.core.command.CommandHandler) has invalid usage language key: /cofh help 
[39;0m> [K[17:50:52] [Server thread/WARN] [FTB Utilities]: Command command.dummycore.tptodimension (class: DummyCore.Utils.CommandTransfer) has invalid usage language key: /tptodimension <player> <dimensionID> <x> <y> <z> 
[39;0m> [K[17:50:52] [Server thread/WARN] [FTB Utilities]: Command command.mtrm.minetweakerrecipemaker (class: net.doubledoordev.mtrm.MTRMCommand) has invalid usage language key: Step 4: PROFIT? 
[39;0m> [K[17:50:52] [Server thread/WARN] [FTB Utilities]: Command command.baubles.baubles (class: baubles.common.event.CommandBaubles) has invalid usage language key: /baubles <action> [<player> [<params>]] 
[39;0m> [K[17:50:52] [Server thread/WARN] [FTB Utilities]: Command command.rpreload (class: com.therandomlabs.randompatches.repackage.com.therandomlabs.randomlib.config.CommandConfigReload) has invalid usage language key: /rpreload 
[39;0m> [K[17:50:52] [Server thread/WARN] [FTB Utilities]: Command command.securitycraft.module (class: net.geforcemods.securitycraft.commands.CommandModule) has invalid usage language key: Usage: /module add <playerName> OR /module remove <playerName> OR /module copy OR /module paste 
[39;0m> [K[17:50:52] [Server thread/WARN] [FTB Utilities]: Command command.excompressum.excompressum (class: net.blay09.mods.excompressum.CommandExCompressum) has invalid usage language key: /excompressum reload 
[39;0m> [K[17:50:52] [Server thread/WARN] [FTB Utilities]: Command command.morpheus.morpheus (class: net.quetzi.morpheus.commands.CommandMorpheus) has invalid usage language key: /morpheus <alert : version> | /morpheus percent <percentage> | /morpheus disable <dimension number> 
[39;0m> [K[17:50:52] [Server thread/WARN] [FTB Utilities]: Command command.astralsorcery.astralsorcery (class: hellfirepvp.astralsorcery.common.cmd.CommandAstralSorcery) has invalid usage language key: /astralsorcery <action> [player] [arguments...] 
[39;0m> [K[17:50:52] [Server thread/WARN] [FTB Utilities]: Command command.crafttweaker.crafttweaker (class: crafttweaker.mc1120.commands.CTChatCommand) has invalid usage language key: /crafttweaker biomeTypes | biomes | blockinfo | blocks | bugs | conflict | copy | discord | docs | dumpzs | enchants | entities | foods | gases | give | hand | help | infuseTypes | inventory | jeiCategories | json | liquids | log | mekrecipes | mods | names | nbt | oredict | potions | recipeNames | recipes | reload | scripts | seeds | syntax | wiki | zslint 
[39;0m> [K[17:50:52] [Server thread/WARN] [FTB Utilities]: Command command.opencomputers.oc_debugwhitelist (class: li.cil.oc.server.command.DebugWhitelistCommand$) has invalid usage language key: oc_debugWhitelist [revoke|add|remove] <player> OR oc_debugWhitelist [revoke|list] 
[39;0m> [K[17:50:52] [Server thread/WARN] [FTB Utilities]: Command command.opencomputers.oc_nanomachines (class: li.cil.oc.server.command.LogNanomachinesCommand$) has invalid usage language key: oc_nanomachines [player] 
[39;0m> [K[17:50:52] [Server thread/WARN] [FTB Utilities]: Command command.mtrm.minetweakerrecipemaker (class: net.doubledoordev.mtrm.MTRMCommand) has invalid usage language key: Step 4: PROFIT? 
[39;0m> [K[17:50:52] [Server thread/WARN] [FTB Utilities]: Command command.conarm.leveluparmor (class: c4.conarm.integrations.tinkertoolleveling.CommandLevelArmor) has invalid usage language key: /levelupArmor while holding a tinker armor in your hand 
[39;0m> [K[17:50:52] [Server thread/WARN] [FTB Utilities]: Command command.betterbuilderswands.wandoops (class: portablejim.bbw.core.OopsCommand) has invalid usage language key: /wandOops 
[39;0m> [K[17:50:52] [Server thread/WARN] [FTB Utilities]: Command command.caliper.caliper.tps (class: net.darkhax.caliper.commands.CommandTPS) has invalid usage language key: /caliper tps 
[39;0m> [K[17:50:52] [Server thread/WARN] [FTB Utilities]: Command command.caliper.caliper.count (class: net.darkhax.caliper.commands.CommandCount) has invalid usage language key: /caliper count entity|tile|ticktile|chunk 
[39;0m> [K[17:50:52] [Server thread/WARN] [FTB Utilities]: Command command.caliper.caliper.recipe (class: net.darkhax.caliper.commands.CommandEmptyRecipe) has invalid usage language key: /caliper recipe book|bookall|normal|normalall 
[39;0m> [K[17:50:52] [Server thread/WARN] [FTB Utilities]: Command command.caliper.caliper.tp (class: net.darkhax.caliper.commands.CommandTeleport) has invalid usage language key: /caliper tp <player> <dimension> 
[39;0m> [K[17:50:52] [Server thread/WARN] [FTB Utilities]: Command command.securitycraft.sc (class: net.geforcemods.securitycraft.commands.CommandSC) has invalid usage language key: Usage: /sc connect OR /sc disconnect OR /sc contact OR /sc resume 
[39;0m> [K[17:50:52] [Server thread/WARN] [FTB Utilities]: Command command.chunkpregenerator.pregen (class: pregenerator.impl.command.PregenBaseCommand) has invalid usage language key: /pregen Allows you to Pregenerate Worlds, Control Structures, Delete Chunks and other things 
[39;0m> [K[17:50:52] [Server thread/WARN] [FTB Utilities]: Command command.terracart.tc (class: com.kreezcraft.terracartreloaded.CommandTC) has invalid usage language key: /tc <vanillacart|vc> <true|false> 
force using the friction based vanilla cart 
[39;0m> [K[17:50:52] [Server thread/WARN] [FTB Utilities]: Command command.minecolonies.minecolonies (class: com.minecolonies.coremod.commands.CommandEntryPoint) has invalid usage language key: /minecolonies <colonies|kill|colony|citizens|rtp|backup|home|loadBackup|raid-tonight|raid-now|check|whoami|whereami|lootGen> 
[39;0m> [K[17:50:52] [Server thread/WARN] [FTB Utilities]: Command command.charset.charset (class: pl.asie.charset.lib.command.CommandCharset) has invalid usage language key: /charset [help, hand, at] 
[39;0m> [K[17:50:52] [Server thread/WARN] [FTB Utilities]: Command command.journeymap.jtp (class: journeymap.common.command.CommandJTP) has invalid usage language key: /jtp <x y z dim> 
[39;0m> [K[17:50:52] [Server thread/WARN] [FTB Utilities]: Command command.terracart.tc (class: com.kreezcraft.terracartreloaded.CommandTC) has invalid usage language key: /tc <vanillacart|vc> <true|false> 
force using the friction based vanilla cart 
[39;0m> [K[17:50:52] [Server thread/WARN] [FTB Utilities]: Command command.crafttweaker.crafttweaker (class: crafttweaker.mc1120.commands.CTChatCommand) has invalid usage language key: /crafttweaker biomeTypes | biomes | blockinfo | blocks | bugs | conflict | copy | discord | docs | dumpzs | enchants | entities | foods | gases | give | hand | help | infuseTypes | inventory | jeiCategories | json | liquids | log | mekrecipes | mods | names | nbt | oredict | potions | recipeNames | recipes | reload | scripts | seeds | syntax | wiki | zslint 
[39;0m> [K[17:50:52] [Server thread/WARN] [FTB Utilities]: Command command.charset.mutter (class: pl.asie.charset.lib.notify.CommandMutter) has invalid usage language key: /mutter [--long] [--show-item] some text. Clears if empty 
[39;0m> [K[17:50:52] [Server thread/WARN] [FTB Utilities]: Command command.rebornstorage.rsmblock (class: me.modmuss50.rebornstorage.lib.CommandBuildMultiBlock) has invalid usage language key: rsmblock <size> 
[39;0m> [K[17:50:52] [Server thread/WARN] [FTB Utilities]: Command command.tinkertoolleveling.leveluptool (class: slimeknights.toolleveling.debug.CommandLevelTool) has invalid usage language key: /levelupTool while holding a tinker tool in your hand 
[39;0m> [K[17:50:52] [Server thread/WARN] [FTB Utilities]: Command command.grandeconomy.pay (class: the_fireplace.grandeconomy.commands.CommandPay) has invalid usage language key: /pay <player> <amount> 
[39;0m> [K[17:50:52] [Server thread/WARN] [FTB Utilities]: Command command.enderstorage.enderstorage.help (class: codechicken.lib.command.help.HelpCommandBase) has invalid usage language key: Displays help for /EnderStorage commands. 
[39;0m> [K[17:50:52] [Server thread/WARN] [FTB Utilities]: Command command.enderstorage.enderstorage.clear (class: codechicken.enderstorage.command.ClearCommand) has invalid usage language key: Provides ability to clear a users EnderStorage. 
[39;0m> [K[17:50:52] [Server thread/WARN] [FTB Utilities]: Command command.enderstorage.enderstorage.help (class: codechicken.lib.command.help.HelpCommandBase) has invalid usage language key: Displays help for /EnderStorage commands. 
[39;0m> [K[17:50:52] [Server thread/WARN] [FTB Utilities]: Command command.enderstorage.enderstorage.clear (class: codechicken.enderstorage.command.ClearCommand) has invalid usage language key: Provides ability to clear a users EnderStorage. 
[39;0m> [K[17:50:52] [Server thread/WARN] [FTB Utilities]: Command command.crafttweaker.crafttweaker (class: crafttweaker.mc1120.commands.CTChatCommand) has invalid usage language key: /crafttweaker biomeTypes | biomes | blockinfo | blocks | bugs | conflict | copy | discord | docs | dumpzs | enchants | entities | foods | gases | give | hand | help | infuseTypes | inventory | jeiCategories | json | liquids | log | mekrecipes | mods | names | nbt | oredict | potions | recipeNames | recipes | reload | scripts | seeds | syntax | wiki | zslint 
[39;0m> [K[17:50:52] [Server thread/WARN] [FTB Utilities]: Command command.discordintegration.discord (class: chikachi.discord.command.CommandDiscord) has invalid usage language key: /discord <config|online|link|unlink|tps|unstuck|uptime> [options] 
[39;0m> [K[17:50:52] [Server thread/WARN] [FTB Utilities]: Command command.enderstorage.enderstorage.help (class: codechicken.lib.command.help.HelpCommandBase) has invalid usage language key: Displays help for /EnderStorage commands. 
[39;0m> [K[17:50:52] [Server thread/WARN] [FTB Utilities]: Command command.enderstorage.enderstorage.clear (class: codechicken.enderstorage.command.ClearCommand) has invalid usage language key: Provides ability to clear a users EnderStorage. 
[39;0m> [K[17:50:52] [Server thread/WARN] [FTB Utilities]: Command command.cyclopscore.flopper (class: org.cyclops.cyclopscore.command.CommandMod) has invalid usage language key: /flopper <config | version> 
[39;0m> [K[17:50:52] [Server thread/WARN] [FTB Utilities]: Command command.forestry.forestry (class: forestry.core.commands.RootCommand) has invalid usage language key: /forestry help 
[39;0m> [K[17:50:52] [Server thread/WARN] [FTB Utilities]: Command command.abyssalcraft.acunlockallknowledge (class: com.shinoow.abyssalcraft.common.command.CommandUnlockAllKnowledge) has invalid usage language key: /acunlockallknowledge 
[39;0m> [K[17:50:52] [Server thread/WARN] [FTB Utilities]: Command command.grandexchange.ge (class: the_fireplace.grandexchange.commands.CommandGe) has invalid usage language key: /ge <command> [parameters] 
[39;0m> [K[17:50:52] [Server thread/WARN] [FTB Utilities]: Command command.structurize.structurize.updateschematics (class: com.ldtteam.structurize.commands.UpdateSchematicsCommand) has invalid usage language key: /structurize updateschematics 
[39;0m> [K[17:50:52] [Server thread/WARN] [FTB Utilities]: Command command.structurize.structurize.scan (class: com.ldtteam.structurize.commands.ScanCommand) has invalid usage language key: /structurize scan <x1> <y1> <z1> <x2> <y2> <z2> [fileName] [blockToReplace > blockReplaceWith]... 
[39;0m> [K[17:50:52] [Server thread/WARN] [FTB Utilities]: Command command.structurize.structurize.linksession.sendmessage (class: com.ldtteam.structurize.commands.LinkSessionCommand$SendMessage) has invalid usage language key: /structurize linksession sendmessage <message> 
[39;0m> [K[17:50:52] [Server thread/WARN] [FTB Utilities]: Command command.structurize.structurize.linksession.addplayer (class: com.ldtteam.structurize.commands.LinkSessionCommand$AddPlayer) has invalid usage language key: /structurize linksession addplayer <nickname> 
[39;0m> [K[17:50:52] [Server thread/WARN] [FTB Utilities]: Command command.structurize.structurize.linksession.removeplayer (class: com.ldtteam.structurize.commands.LinkSessionCommand$RemovePlayer) has invalid usage language key: /structurize linksession removeplayer <nickname> 
[39;0m> [K[17:50:52] [Server thread/WARN] [FTB Utilities]: Command command.structurize.structurize.linksession.leave (class: com.ldtteam.structurize.commands.LinkSessionCommand$Leave) has invalid usage language key: /structurize linksession leave <nickname> 
[39;0m> [K[17:50:52] [Server thread/WARN] [FTB Utilities]: Command command.structurize.structurize.linksession.create (class: com.ldtteam.structurize.commands.LinkSessionCommand$Create) has invalid usage language key: /structurize linksession create 
[39;0m> [K[17:50:52] [Server thread/WARN] [FTB Utilities]: Command command.structurize.structurize.linksession.destroy (class: com.ldtteam.structurize.commands.LinkSessionCommand$Destroy) has invalid usage language key: /structurize linksession destroy 
[39;0m> [K[17:50:52] [Server thread/WARN] [FTB Utilities]: Command command.structurize.structurize.linksession.acceptinvite (class: com.ldtteam.structurize.commands.LinkSessionCommand$AcceptInvite) has invalid usage language key: /structurize linksession acceptinvite 
[39;0m> [K[17:50:52] [Server thread/WARN] [FTB Utilities]: Command command.structurize.structurize.linksession.aboutme (class: com.ldtteam.structurize.commands.LinkSessionCommand$AboutMe) has invalid usage language key: /structurize linksession aboutme 
[39;0m> [K[17:50:52] [Server thread/WARN] [FTB Utilities]: Command command.structurize.structurize.linksession.mutechannel (class: com.ldtteam.structurize.commands.LinkSessionCommand$MuteChannel) has invalid usage language key: /structurize linksession mutechannel 
[39;0m> [K[17:50:52] [Server thread/WARN] [FTB Utilities]: Command command.forestry.forestry (class: forestry.core.commands.RootCommand) has invalid usage language key: /forestry help 
[39;0m> [K[17:50:52] [Server thread/WARN] [FTB Utilities]: Command command.opencomputers.oc_nanomachines (class: li.cil.oc.server.command.LogNanomachinesCommand$) has invalid usage language key: oc_nanomachines [player] 
[39;0m> [K[17:50:52] [Server thread/WARN] [FTB Utilities]: Command command.cyclopscore.cyclopscore (class: org.cyclops.cyclopscore.command.CommandMod) has invalid usage language key: /cyclopscore <ignite | debug | reloadresources | config | version | recursion> 
[39;0m> [K[17:50:52] [Server thread/WARN] [FTB Utilities]: Command command.astralsorcery.astralsorcery (class: hellfirepvp.astralsorcery.common.cmd.CommandAstralSorcery) has invalid usage language key: /astralsorcery <action> [player] [arguments...] 
[39;0m> [K[17:50:52] [Server thread/WARN] [FTB Utilities]: Command command.shadowmc.shadow.help (class: net.shadowfacts.shadowmc.command.CommandHelp) has invalid usage language key: /shadow help <command> 
[39;0m> [K[17:50:52] [Server thread/WARN] [FTB Utilities]: Command command.shadowmc.shadow.calc (class: net.shadowfacts.shadowmc.command.CommandCalc) has invalid usage language key: /shadow calc <expr> 
[39;0m> [K[17:50:52] [Server thread/WARN] [FTB Utilities]: Command command.shadowmc.shadow.killall (class: net.shadowfacts.shadowmc.command.CommandKillAll) has invalid usage language key: /shadow killall <range> 
[39;0m> [K[17:50:52] [Server thread/WARN] [FTB Utilities]: Command command.opencomputers.oc_renderwirelessnetwork (class: li.cil.oc.server.command.WirelessRenderingCommand$) has invalid usage language key: oc_renderWirelessNetwork <boolean> 
[39;0m> [K[17:50:52] [Server thread/WARN] [FTB Utilities]: Command command.opencomputers.oc_preventdisassembling (class: li.cil.oc.server.command.NonDisassemblyAgreementCommand$) has invalid usage language key: oc_preventDisassembling <boolean> 
[39;0m> [K[17:50:52] [Server thread/WARN] [FTB Utilities]: Command command.morpheus.morpheus (class: net.quetzi.morpheus.commands.CommandMorpheus) has invalid usage language key: /morpheus <alert : version> | /morpheus percent <percentage> | /morpheus disable <dimension number> 
[39;0m> [K[17:50:52] [Server thread/WARN] [FTB Utilities]: Command command.grandeconomy.balance (class: the_fireplace.grandeconomy.commands.CommandBalance) has invalid usage language key: /balance 
[39;0m> [K[17:50:52] [Server thread/WARN] [FTB Utilities]: Command command.immersiveengineering.ie.help.clearshaders (class: net.minecraftforge.server.command.CommandTreeHelp$HelpSubCommand) has invalid usage language key: /ie clearshaders [player name] 
[39;0m> [K[17:50:52] [Server thread/WARN] [FTB Utilities]: Command command.immersiveengineering.ie.help.mineral (class: net.minecraftforge.server.command.CommandTreeHelp$HelpSubCommand) has invalid usage language key: Use "/ie mineral help" for more information 
[39;0m> [K[17:50:52] [Server thread/WARN] [FTB Utilities]: Command command.immersiveengineering.ie.clearshaders (class: blusunrize.immersiveengineering.common.util.commands.CommandShaders) has invalid usage language key: /ie clearshaders [player name] 
[39;0m> [K[17:50:52] [Server thread/WARN] [FTB Utilities]: Command command.immersiveengineering.ie.mineral.help.set (class: net.minecraftforge.server.command.CommandTreeHelp$HelpSubCommand) has invalid usage language key: /mineral set <mineral name> (surround the name in <angle brackets> if it contains a space) 
[39;0m> [K[17:50:52] [Server thread/WARN] [FTB Utilities]: Command command.immersiveengineering.ie.mineral.help.setdepletion (class: net.minecraftforge.server.command.CommandTreeHelp$HelpSubCommand) has invalid usage language key: /mineral setDepletion <depletion> 
[39;0m> [K[17:50:52] [Server thread/WARN] [FTB Utilities]: Command command.immersiveengineering.ie.mineral.help.get (class: net.minecraftforge.server.command.CommandTreeHelp$HelpSubCommand) has invalid usage language key: /mineral get 
[39;0m> [K[17:50:52] [Server thread/WARN] [FTB Utilities]: Command command.immersiveengineering.ie.mineral.help.list (class: net.minecraftforge.server.command.CommandTreeHelp$HelpSubCommand) has invalid usage language key: /mineral list 
[39;0m> [K[17:50:52] [Server thread/WARN] [FTB Utilities]: Command command.immersiveengineering.ie.mineral.set (class: blusunrize.immersiveengineering.common.util.commands.CommandMineral$CommandMineralSet) has invalid usage language key: /mineral set <mineral name> (surround the name in <angle brackets> if it contains a space) 
[39;0m> [K[17:50:52] [Server thread/WARN] [FTB Utilities]: Command command.immersiveengineering.ie.mineral.setdepletion (class: blusunrize.immersiveengineering.common.util.commands.CommandMineral$CommandMineralSetDepletion) has invalid usage language key: /mineral setDepletion <depletion> 
[39;0m> [K[17:50:52] [Server thread/WARN] [FTB Utilities]: Command command.immersiveengineering.ie.mineral.get (class: blusunrize.immersiveengineering.common.util.commands.CommandMineral$CommandMineralGet) has invalid usage language key: /mineral get 
[39;0m> [K[17:50:52] [Server thread/WARN] [FTB Utilities]: Command command.immersiveengineering.ie.mineral.list (class: blusunrize.immersiveengineering.common.util.commands.CommandMineral$CommandMineralList) has invalid usage language key: /mineral list 
[39;0m> [K[17:50:52] [Server thread/WARN] [FTB Utilities]: Command command.baubles.baubles (class: baubles.common.event.CommandBaubles) has invalid usage language key: /baubles <action> [<player> [<params>]] 
[39;0m> [K[17:50:52] [Server thread/WARN] [FTB Utilities]: Command command.minecolonies.minecolonies (class: com.minecolonies.coremod.commands.CommandEntryPointNew) has invalid usage language key: /mineColonies <colonies|kill|colony|citizens|rs|rtp|backup|home|raid-tonight|raid-now|check|whoami|whereami|scan|lootGen> 
[39;0m> [K[17:50:52] [Server thread/WARN] [FTB Utilities]: Command command.immersivepetroleum.ip (class: flaxbeard.immersivepetroleum.common.util.CommandHandler) has invalid usage language key: /ip <help|reservoir> 
[39;0m> [K[17:50:52] [Server thread/WARN] [FTB Utilities]: Command command.badwithernocookiereloaded.listen (class: com.kreezcraft.badwithernocookiereloaded.ListenCommand) has invalid usage language key: /listen 
- toggles display of the sound event names in the current text stream 
[39;0m> [K[17:50:52] [Server thread/WARN] [FTB Utilities]: Command command.thaumcraft.thaumcraft (class: thaumcraft.common.lib.CommandThaumcraft) has invalid usage language key: /thaumcraft <action> [<player> [<params>]] 
[39;0m> [K[17:50:52] [Server thread/WARN] [FTB Utilities]: Command command.minecolonies.minecolonies (class: com.minecolonies.coremod.commands.CommandEntryPointNew) has invalid usage language key: /mineColonies <colonies|kill|colony|citizens|rs|rtp|backup|home|raid-tonight|raid-now|check|whoami|whereami|scan|lootGen> 
[39;0m> [K[17:50:52] [Server thread/WARN] [FTB Utilities]: Command command.charset.charset (class: pl.asie.charset.lib.command.CommandCharset) has invalid usage language key: /charset [help, hand, at] 
[39;0m> [K[17:50:52] [Server thread/WARN] [FTB Utilities]: Command command.storagetech.givememory (class: javapower.storagetech.core.CommandGiveMemory) has invalid usage language key: givememory <Item|Fluid> <amount> [k,M,G] 
[39;0m> [K[17:50:52] [Server thread/WARN] [FTB Utilities]: Command command.thaumcraft.thaumcraft (class: thaumcraft.common.lib.CommandThaumcraft) has invalid usage language key: /thaumcraft <action> [<player> [<params>]] 
[39;0m> [K[17:50:52] [Server thread/WARN] [FTB Utilities]: Command command.grandeconomy.wallet (class: the_fireplace.grandeconomy.commands.CommandWallet) has invalid usage language key: /wallet <give|take|set|balance> <player> <amount> 
[39;0m> [K[17:50:52] [Server thread/WARN] [FTB Utilities]: Command command.cctweaked.computercraft (class: dan200.computercraft.shared.command.CommandComputerCraft) has invalid usage language key: /computercraft <help|view|reload|dump|turn-on|tp|track|shutdown|queue> 
[39;0m> [K[17:50:52] [Server thread/WARN] [FTB Utilities]: Command command.immersiverailroading.immersiverailroading (class: cam72cam.immersiverailroading.proxy.IRCommand) has invalid usage language key: Usage: immersiverailroading (reload|debug) 
[39;0m> [K[17:50:52] [Server thread/WARN] [FTB Utilities]: Command command.opencomputers.oc_renderwirelessnetwork (class: li.cil.oc.server.command.WirelessRenderingCommand$) has invalid usage language key: oc_renderWirelessNetwork <boolean> 
[39;0m> [K[17:50:52] [Server thread/WARN] [FTB Utilities]: Command command.minecolonies.minecolonies (class: com.minecolonies.coremod.commands.CommandEntryPointNew) has invalid usage language key: /mineColonies <colonies|kill|colony|citizens|rs|rtp|backup|home|raid-tonight|raid-now|check|whoami|whereami|scan|lootGen> 
[39;0m> [K[17:50:52] [Server thread/WARN] [FTB Utilities]: Command command.badwithernocookiereloaded.listen (class: com.kreezcraft.badwithernocookiereloaded.ListenCommand) has invalid usage language key: /listen 
- toggles display of the sound event names in the current text stream 
[39;0m> [K[17:50:52] [Server thread/WARN] [FTB Utilities]: Command command.opencomputers.oc_senddebugmessage (class: li.cil.oc.server.command.SendDebugMessageCommand$) has invalid usage language key: oc_sendDebugMessage<destinationAddress> essage...] 
[39;0m> [K[17:50:52] [Server thread/WARN] [FTB Utilities]: Command command.minecolonies.minecolonies (class: com.minecolonies.coremod.commands.CommandEntryPointNew) has invalid usage language key: /mineColonies <colonies|kill|colony|citizens|rs|rtp|backup|home|raid-tonight|raid-now|check|whoami|whereami|scan|lootGen> 
[39;0m> [K[17:50:52] [Server thread/WARN] [FTB Utilities]: Command command.crafttweaker.crafttweaker (class: crafttweaker.mc1120.commands.CTChatCommand) has invalid usage language key: /crafttweaker biomeTypes | biomes | blockinfo | blocks | bugs | conflict | copy | discord | docs | dumpzs | enchants | entities | foods | gases | give | hand | help | infuseTypes | inventory | jeiCategories | json | liquids | log | mekrecipes | mods | names | nbt | oredict | potions | recipeNames | recipes | reload | scripts | seeds | syntax | wiki | zslint 
[39;0m> [K[17:50:52] [Server thread/WARN] [FTB Utilities]: Command command.enderstorage.enderstorage.help (class: codechicken.lib.command.help.HelpCommandBase) has invalid usage language key: Displays help for /EnderStorage commands. 
[39;0m> [K[17:50:52] [Server thread/WARN] [FTB Utilities]: Command command.enderstorage.enderstorage.clear (class: codechicken.enderstorage.command.ClearCommand) has invalid usage language key: Provides ability to clear a users EnderStorage. 
[39;0m> [K[17:50:52] [Server thread/WARN] [FTB Utilities]: Command command.cyclopscore.colossalchests (class: org.cyclops.cyclopscore.command.CommandMod) has invalid usage language key: /colossalchests <config | version> 
[39;0m> [K[17:50:52] [Server thread/WARN] [FTB Utilities]: Command command.minecolonies.minecolonies (class: com.minecolonies.coremod.commands.CommandEntryPointNew) has invalid usage language key: /mineColonies <colonies|kill|colony|citizens|rs|rtp|backup|home|raid-tonight|raid-now|check|whoami|whereami|scan|lootGen> 
[39;0m> [K[17:50:52] [Server thread/WARN] [FTB Utilities]: Command command.baubles.baubles (class: baubles.common.event.CommandBaubles) has invalid usage language key: /baubles <action> [<player> [<params>]] 
[39;0m> [K[17:50:52] [Server thread/WARN] [FTB Utilities]: Command command.opencomputers.oc_senddebugmessage (class: li.cil.oc.server.command.SendDebugMessageCommand$) has invalid usage language key: oc_sendDebugMessage<destinationAddress> essage...] 
[39;0m> [K[17:50:52] [Server thread/WARN] [FTB Utilities]: Command command.opencomputers.oc_preventdisassembling (class: li.cil.oc.server.command.NonDisassemblyAgreementCommand$) has invalid usage language key: oc_preventDisassembling <boolean> 
[39;0m> [K[17:50:52] [Server thread/WARN] [FTB Utilities]: Command command.minecolonies.minecolonies (class: com.minecolonies.coremod.commands.CommandEntryPointNew) has invalid usage language key: /mineColonies <colonies|kill|colony|citizens|rs|rtp|backup|home|raid-tonight|raid-now|check|whoami|whereami|scan|lootGen> 
[39;0m> [K[17:50:52] [Server thread/WARN] [FTB Utilities]: Command command.cyclopscore.cyclopscore (class: org.cyclops.cyclopscore.command.CommandMod) has invalid usage language key: /cyclopscore <ignite | debug | reloadresources | config | version | recursion> 
[39;0m> [K[17:50:52] [Server thread/WARN] [FTB Utilities]: Command command.oreexcavation.undo_excavation (class: oreexcavation.core.CommandUndo) has invalid usage language key: /undo_excavation 
[39;0m> [K[17:50:52] [Server thread/WARN] [FTB Utilities]: Command command.minecolonies.minecolonies (class: com.minecolonies.coremod.commands.CommandEntryPoint) has invalid usage language key: /minecolonies <colonies|kill|colony|citizens|rtp|backup|home|loadBackup|raid-tonight|raid-now|check|whoami|whereami|lootGen> 
[39;0m> [K[17:50:52] [Server thread/WARN] [FTB Utilities]: Command command.customnpcs.noppes (class: noppes.npcs.command.CommandNoppes) has invalid usage language key: Use as /noppes subcommand 
[39;0m> [K[17:50:52] [Server thread/WARN] [FTB Utilities]: Command command.laggoggles.laggoggles (class: cf.terminator.laggoggles.command.LagGogglesCommand) has invalid usage language key: /laggoggles
[39;0m> [K[17:50:52] [Server thread/WARN] [FTB Utilities]: Command command.opencomputers.oc_preventdisassembling (class: li.cil.oc.server.command.NonDisassemblyAgreementCommand$) has invalid usage language key: oc_preventDisassembling <boolean> 
[39;0m> [K[17:50:52] [Server thread/WARN] [FTB Utilities]: Command command.badwithernocookiereloaded.listen (class: com.kreezcraft.badwithernocookiereloaded.ListenCommand) has invalid usage language key: /listen 
- toggles display of the sound event names in the current text stream 
[39;0m> [K[17:50:52] [Server thread/INFO] [FTB Utilities]: Overridden 216 commands 
> [K[17:50:53] [Server thread/INFO] [immersiveengineering]: WorldData loading 
> [K[17:50:53] [Server thread/INFO] [immersiveengineering]: WorldData retrieved 
> [K[17:50:53] [Thread-49/INFO] [THAUMCRAFT]: Starting aura thread for dim 0 
> [K[17:50:53] [Server thread/INFO] inecolonies]: Finished discovering saplings 
> [K[17:50:53] [Server thread/INFO] inecolonies]: Finished discovering ores 
> [K[17:50:57] [Server thread/INFO] inecolonies]: Finished discovering compostables 
> [K[17:50:57] [Server thread/INFO] inecolonies]: Finished discovering lucky ores 
> [K[17:50:57] [Server thread/INFO] inecolonies]: Finished initiating sifter config 
> [K[17:50:58] [Server thread/WARN] inecraft/EntityDataManager]: defineId called for: class com.shinoow.abyssalcraft.common.entity.EntityDreadSpawn from class com.shinoow.abyssalcraft.common.entity.EntityChagarothSpawn 
[39;0m> [K[17:50:58] [Server thread/WARN] inecraft/EntityDataManager]: defineId called for: class com.shinoow.abyssalcraft.common.entity.EntityGreaterDreadSpawn from class com.shinoow.abyssalcraft.common.entity.EntityLesserDreadbeast 
[39;0m> [K[17:50:58] [Server thread/WARN] inecraft/EntityDataManager]: defineId called for: class fossilsarcheology.server.entity.prehistoric.EntitySarcosuchus from class fossilsarcheology.server.entity.prehistoric.EntityMegalograptus 
[39;0m> [K[17:50:58] [Server thread/WARN] inecraft/EntityDataManager]: defineId called for: class net.minecraft.entity.item.EntityBoat from class flaxbeard.immersivepetroleum.common.entity.EntitySpeedboat 
[39;0m> [K[17:50:58] [Server thread/WARN] inecraft/EntityDataManager]: defineId called for: class net.minecraft.entity.item.EntityBoat from class flaxbeard.immersivepetroleum.common.entity.EntitySpeedboat 
[39;0m> [K[17:50:59] [Server thread/WARN] inecraft/EntityDataManager]: defineId called for: class net.minecraft.entity.monster.EntityGhast from class techguns.entities.npcs.AttackHelicopter 
[39;0m> [K[17:50:59] [Server thread/WARN] inecraft/EntityDataManager]: defineId called for: class net.minecraft.entity.item.EntityMinecart from class T145.metalchests.entities.EntityMinecartMetalChest 
[39;0m> [K[17:51:00] [Server thread/WARN] inecraft/EntityDataManager]: defineId called for: class li.cil.oc.common.entity.Drone from class li.cil.oc.common.entity.Drone$ 
[39;0m> [K[17:51:00] [Server thread/WARN] inecraft/EntityDataManager]: defineId called for: class li.cil.oc.common.entity.Drone from class li.cil.oc.common.entity.Drone$ 
[39;0m> [K[17:51:00] [Server thread/WARN] inecraft/EntityDataManager]: defineId called for: class li.cil.oc.common.entity.Drone from class li.cil.oc.common.entity.Drone$ 
[39;0m> [K[17:51:00] [Server thread/WARN] inecraft/EntityDataManager]: defineId called for: class li.cil.oc.common.entity.Drone from class li.cil.oc.common.entity.Drone$ 
[39;0m> [K[17:51:00] [Server thread/WARN] inecraft/EntityDataManager]: defineId called for: class li.cil.oc.common.entity.Drone from class li.cil.oc.common.entity.Drone$ 
[39;0m> [K[17:51:00] [Server thread/WARN] inecraft/EntityDataManager]: defineId called for: class li.cil.oc.common.entity.Drone from class li.cil.oc.common.entity.Drone$ 
[39;0m> [K[17:51:00] [Server thread/WARN] inecraft/EntityDataManager]: defineId called for: class li.cil.oc.common.entity.Drone from class li.cil.oc.common.entity.Drone$ 
[39;0m> [K[17:51:00] [Server thread/WARN] inecraft/EntityDataManager]: defineId called for: class li.cil.oc.common.entity.Drone from class li.cil.oc.common.entity.Drone$ 
[39;0m> [K[17:51:00] [Server thread/WARN] inecraft/EntityDataManager]: defineId called for: class li.cil.oc.common.entity.Drone from class li.cil.oc.common.entity.Drone$ 
[39;0m> [K[17:51:00] [Server thread/WARN] inecraft/EntityDataManager]: defineId called for: class li.cil.oc.common.entity.Drone from class li.cil.oc.common.entity.Drone$ 
[39;0m> [K[17:51:00] [Server thread/WARN] inecraft/EntityDataManager]: defineId called for: class li.cil.oc.common.entity.Drone from class li.cil.oc.common.entity.Drone$ 
[39;0m> [K[17:51:00] [Server thread/INFO] [Astral Sorcery]: Load CachedWorldData 'lightnetwork' for world 0 
> [K[17:51:00] [Server thread/INFO] [Astral Sorcery]: Loading of 'lightnetwork' for world 0 finished. 
> [K[17:51:00] [Thread-70/INFO] [THAUMCRAFT]: Starting aura thread for dim -1 
> [K[17:51:00] [Thread-71/INFO] [THAUMCRAFT]: Starting aura thread for dim 1 
> [K[17:51:00] [Thread-72/INFO] [THAUMCRAFT]: Starting aura thread for dim 50 
> [K[17:51:00] [Thread-73/INFO] [THAUMCRAFT]: Starting aura thread for dim 51 
> [K[17:51:00] [Thread-74/INFO] [THAUMCRAFT]: Starting aura thread for dim 52 
> [K[17:51:00] [Thread-75/INFO] [THAUMCRAFT]: Starting aura thread for dim 53 
> [K[17:51:00] [Thread-76/INFO] [THAUMCRAFT]: Starting aura thread for dim -23 
> [K[17:51:00] [Thread-77/INFO] [THAUMCRAFT]: Starting aura thread for dim -34 
> [K[17:51:00] [Server thread/INFO] [THAUMCRAFT]: Removing aura cache for world -1 
> [K[17:51:00] [Server thread/INFO] [FML]: Unloading dimension -1 
> [K[17:51:00] [Server thread/INFO] [THAUMCRAFT]: Removing aura cache for world 1 
> [K[17:51:00] [Server thread/INFO] [FML]: Unloading dimension 1 
> [K[17:51:00] [Server thread/INFO] [THAUMCRAFT]: Removing aura cache for world 50 
> [K[17:51:00] [Server thread/INFO] [FML]: Unloading dimension 50 
> [K[17:51:00] [Server thread/INFO] [THAUMCRAFT]: Removing aura cache for world 51 
> [K[17:51:00] [Server thread/INFO] [FML]: Unloading dimension 51 
> [K[17:51:00] [Server thread/INFO] [THAUMCRAFT]: Removing aura cache for world 52 
> [K[17:51:00] [Server thread/INFO] [FML]: Unloading dimension 52 
> [K[17:51:00] [Server thread/INFO] [THAUMCRAFT]: Removing aura cache for world 53 
> [K[17:51:00] [Server thread/INFO] [FML]: Unloading dimension 53 
> [K[17:51:00] [Server thread/INFO] [THAUMCRAFT]: Removing aura cache for world -23 
> [K[17:51:00] [Server thread/INFO] [FML]: Unloading dimension -23 
> [K[17:51:00] [Server thread/INFO] [THAUMCRAFT]: Removing aura cache for world -34 
> [K[17:51:01] [Server thread/INFO] [FML]: Unloading dimension -34 
> [K[17:51:01] [Server thread/WARN] inecraft/MinecraftServer]: Can't keep up! Did the system time change, or is the server overloaded? Running 7871ms behind, skipping 157 tick(s) 
[39;0m> [K[17:51:02] [Thread-70/INFO] [THAUMCRAFT]: Stopping aura thread for dim -1 
> [K[17:51:02] [Thread-71/INFO] [THAUMCRAFT]: Stopping aura thread for dim 1 
> [K[17:51:02] [Thread-72/INFO] [THAUMCRAFT]: Stopping aura thread for dim 50 
> [K[17:51:02] [Thread-73/INFO] [THAUMCRAFT]: Stopping aura thread for dim 51 
> [K[17:51:02] [Thread-74/INFO] [THAUMCRAFT]: Stopping aura thread for dim 52 
> [K[17:51:02] [Thread-75/INFO] [THAUMCRAFT]: Stopping aura thread for dim 53 
> [K[17:51:02] [Thread-76/INFO] [THAUMCRAFT]: Stopping aura thread for dim -23 
> [K[17:51:02] [Thread-77/INFO] [THAUMCRAFT]: Stopping aura thread for dim -34 
> [K[17:53:34] [User Authenticator #1/INFO] inecraft/NetHandlerLoginServer]: UUID of player KeviN_CZ is f60ad51a-a0e3-49a3-9007-f9c6f3875857 
> [K[17:53:35] [Netty Epoll Server IO #6/INFO] [FML]: Client protocol version 2 
> [K[17:53:35] [Netty Epoll Server IO #6/INFO] [FML]: Client attempting to join with 228 mods : opendisks@0.1.0.3,levelup2@${version},blockdrops@1.4.0,gbook@2.8.3,rusticthaumaturgy@4.4a,mtrm@1.2.2.30,thermalinnovation@0.3.2,craftstudioapi@1.0.0,tc6aspects4jei@0.0.2a,ironjetpacks@1.1.0,thaumicjei@1.6.0,ctm@MC1.12.2-0.3.3.22,reauth@3.6.0,bigbeautifulbuttons@1.12.2-1.1.3,rangedpumps@0.5,forgelin@1.8.2,randompatches@1.12.2-1.15.1.0,llibrary@1.7.19,excompressum@3.0.27,betterbuilderswands@0.13.2,torchoptimizer@1.12.2-2.2.6,morpheus@1.12.2-3.5.106,ftblib@5.4.1.99,waila@1.8.26,guideapi@1.12-2.1.8-63,jeresources@0.9.0.53,acintegration@1.8.1,shetiphiancore@3.5.9,refinedstorage@1.6.14,techreborn@2.22.1.979,soulbottle@1.1,tipthescales@1.0.4,unidict@1.12.2-2.9.2,redstoneflux@2.1.0,vanillafoodpantry@4.3.1,gottagofast@1.1,botania@r1.10-361,fairylights@2.1.6,resourceloader@1.5.3,igwmod@1.4.4-15,morebeautifulplates@1.12.2-1.0.3,abyssalcraft@1.9.7,shadowmc@3.8.0,jepb@1.2.1,lunatriuscore@1.2.0.42,terracart@1.12.2-1.2.3,backpacks16840@3.5.5,furenikusroads@1.0.3,FML@8.0.99.99,obfuscate@0.2.6,thermalexpansion@5.5.3,tombstone@3.3.6,worldedit@6.1.10-SNAPSHOT,cfm@6.2.0,armoryexpansion-custommaterials@1.1.10c,hopperducts@1.5,codechickenlib@3.2.2.353,fastleafdecay@v14,dynamictrees@1.12.2-0.9.5,techreborn_compat@1.0.0,tinkersaddons@1.0.7,wailaharvestability@1.1.12,binniedesign@2.5.1.188,cctweaked@1.82.3,opensecurity@1.0-23,ctgui@1.0.0,commandkeybindings@7.0.1,extrarails@1.3.0,jei@4.15.0.278,leverbuttonlights@1.12.2-1.5,multipiston@@VERSION@,custommainmenu@2.0.9,diamondglass@1.12.2-3.3.18,thermalcultivation@0.3.2,bibliocraft@2.4.5,cosmeticbeds@1.12.2-1.0.2.2,mekanism@1.12.2-1.2.0,thermalfoundation@2.6.2,opencomputers@1.7.4.153,naturescompass@1.5.1,chameleon@1.12-4.1.3,conarm@1.2.3.4,inventorytweaks@1.64+dev.146.2180b27,underphangables@1.0.0,extrabees@2.5.1.188,iceandfire@1.6.1,crafttweaker@4.1.17,thermalsolars@1.12.2 V1.9.4,armoryexpansion@1.1.10c,rpsideas@2.3.0,immersivepetroleum@1.1.9,forge@14.23.5.2836,eplus@5.0.177,minecraft@1.12.2,flopper@1.0.3,tcomplement@${version},ftbquests@1.5.2.151,psi@r1.1-76,immersiveengineering@0.12-89,thermaldynamics@2.5.4,rustic@1.1.0,mantle@1.12-1.3.3.49,openprinter@0.1.0.2,ftbbackups@0.0.0.ftbbackups,jeivillagers@1.0,securitycraft@v1.8.12,autoreglib@1.3-28,dimensionalcake@1.12.2-1.0,structurize@1.12.2-0.10.93-ALPHA,worldeditcuife2@2.1.2-mf-1.12.2-14.23.0.2487,appleskin@1.0.9,recipehandler@0.13,durabilityviewer@1.4,bookworm@1.12.2-2.2.0,tweakersconstruct@1.12.2-1.4.0,metalchests@v4.0.1.g01955d6,cosmeticarmorreworked@1.12.2-v4a,magipsi@1.3,forestry@5.8.2.387,defaultoptions@9.2.8,cyclopscore@1.2.0,astralsorcery@1.10.17,binniecore@2.5.1.188,animania@1.6.2,jecalculation@1.12.2-3.1.4,cofhcore@4.6.2,immersivecables@1.3.2,reborncore@3.13.12.447,controlling@3.0.6,placebo@1.6.0,fencejumper@1.0.5,bookshelf@2.3.577,featuredservers@1.12-1.0.6,ironbackpacks@1.12.2-3.0.8-12,notenoughscaffold@1.8,streams@0.4.7,cofhworld@1.3.0,storagetech@6.0,librarianliblate@4.15,thaumcraft@6.1.BETA26,dynamictreestc@1.12.2-1.4.1e,immersivetech@1.3.10,extratrees@2.5.1.188,exactspawn@1.12-1.2.3.17,stackie@1.6.0.48,charset@0.5.5.7,rebornstorage@1.0.0,tinkertoolleveling@1.12.2-1.1.0.DEV.b23e769,thaumicgrid@1.0.12,crafttweakerjei@2.0.3,endertanks@1.6.8,botany@2.5.1.188,vehicle@0.39.0,openfm@0.1.0.19,helpfixer@1.12.1-1.5.18,trackapi@1.1,harvestables@1.2,oreexcavation@1.4.140,giacomosfoundry@1.3.13,elevatorid@1.3.10,furnaceoverhaul@2.2.0,customnpcs@1.12,morebeautifulbuttons@1.12.2-1.7.3.20,computercraft@1.82.3,immersiverailroading@1.6.1,tramplestopper@1.2.0.4,instantunify@1.1.2,badwithernocookiereloaded@1.12.2-3.3.16,techguns@2.0.1.2,compactdrawers@1.12.2-1.0.5.121,jmh@2.0,cucumber@1.1.3,librarianlib@4.15,equaldragons@1.1,itemfilters@1.0.3.12,witherskelefix@2.6.3,chunkpregenerator@2.1,roleplaycraft@1.12.2-1.3.4,techguns_core@1.12.2-1.0,redstonepaste@1.7.5,waystones@4.0.67,mcp@9.42,diethopper@1.1,journeymap@1.12.2-5.5.5b5,tinkerscompendium@1.4.2.26.2,comforts@1.4.1.2,jeid@1.0.2-26,foamfixcore@7.7.4,tinymobfarm@1.0.5,fossil@8.0.0,moartinkers@0.6.0,tinkersoc@0.6,toastcontrol@1.8.1,landlust@1.12.2-0.3.6,enderstorage@2.4.5.135,farseek@2.3.2,exnihilocreatio@1.12.2-0.4.2,fasterladderclimbing@0.1-146,flammpfeil.slashblade@mc1.12-r22,colossalchests@1.7.1,craftingtweaks@8.1.9,armoryexpansion-conarm@1.1.10c,tconstruct@1.12.2-2.12.0.135,blockout@@VERSION@,dummycore@2.4.112.5.,baubles@1.5.2,dirtdeco@1.12.2-1.6.7,stevescarts@2.4.30.134,genetics@2.5.1.188,resound@1r,vanillafix@1.0.10-SNAPSHOT,growablecells@3.1.0,thaumcomp@0.4.4,fastbench@1.7.0,storagedrawers@1.12-5.3.5,tinker_io@rw2.7.1,minecolonies@1.12.2-0.10.280-ALPHA,laggoggles@FORGE-1.12.2-4.3-HOTFIX,wanionlib@1.12.2-2.2,chisel@MC1.12.2-0.2.1.35,armoryexpansion-iceandfire@1.1.10c,toroquest@1.12.2-5.3,foamfix@0.10.5-1.12.2,itemscroller@0.12.0,tinkersjei@1.2,opencomputers|core@1.7.4.153,refinedstorageaddons@0.4.4,chiselsandbits@14.32
> [K[17:53:35] [Netty Epoll Server IO #6/INFO] [journeymap]: CLIENT 
> [K[17:53:35] [Netty Epoll Server IO #6/INFO] [FML]: Attempting connection with missing mods [bedpatch, caliper, discordintegration, ftbutilities, grandeconomy, grandexchange] at CLIENT 
> [K[17:53:35] [Netty Epoll Server IO #6/INFO] [CodeChickenLib-ConfigSync]: Skipping config sync, No mods have registered a syncable config. 
> [K[17:53:40] [Server thread/INFO] [FML]: [Server thread] Server side modded connection established 
> [K[17:53:40] [Server thread/INFO] [STDOUT]: [net.torocraft.toroquest.civilization.CivilizationHandlers:onLoad:143]: LOAD: {completedQuests:0,reputations:[{civ:"WIND",amount:0},{civ:"EARTH",amount:-1},{civ:"FIRE",amount:0},{civ:"SUN",amount:-5},{civ:"MOON",amount:0},{civ:"WATER",amount:0}],nextQuests:[],quests:[],completedQuestsByProvince:{}} 
> [K[17:53:40] [Server thread/INFO] inecraft/PlayerList]: KeviN_CZ[/37.221.248.247:63525] logged in with entity id 739 at (572.2732460930508, 71.0, 1002.361046628365) 
> [K[17:53:40] [Server thread/INFO] inecraft/DedicatedServer]: KeviN_CZ[39;0m joined the game[39;0m[39;0m 
> [K[17:53:40] [Server thread/INFO] [STDOUT]: [pl.asie.foamfix.coremod.FoamFixTransformer:spliceClasses:137]: Spliced in METHOD: net.minecraft.world.chunk.BlockStateContainer.func_186018_a 
> [K[17:53:41] [Server thread/INFO] [Astral Core]: [AstralTransformer] Transforming pa : net.minecraft.network.NetHandlerPlayServer with 1 patches! 
> [K[17:53:41] [Server thread/INFO] [Astral Core]: [AstralTransformer] Applied patch PATCHSERVEREXTENDENTITYINTERACTREACH 
> [K[17:53:41] [Server thread/INFO] [Gotta Go Fast]: patching net.minecraft.network.NetHandlerPlayServer.processVehicleMove(CPacketVehicleMove) 
> [K[17:53:41] [Server thread/ERROR] [Gotta Go Fast]: Couldn't find the vehicle constant instruction to modify :( 
[39;0m> [K[17:53:41] [Server thread/ERROR] [Gotta Go Fast]: Please report this 
[39;0m> [K[17:53:41] [Server thread/INFO] [Gotta Go Fast]: patching net.minecraft.network.NetHandlerPlayServer.processPlayer(CPacketPlayer) 
> [K[17:53:41] [Server thread/ERROR] [Gotta Go Fast]: Couldn't find the elytra constant instruction to modify :( 
[39;0m> [K[17:53:41] [Server thread/ERROR] [Gotta Go Fast]: Please report this 
[39;0m> [K[17:53:41] [Server thread/ERROR] [Gotta Go Fast]: Couldn't find the player constant instruction to modify :( 
[39;0m> [K[17:53:41] [Server thread/ERROR] [Gotta Go Fast]: Please report this 
[39;0m> [K[17:53:41] [Server thread/ERROR] [Gotta Go Fast]: Couldn't find the processPlayer method (or any of its patch targets) to patch :( 
[39;0m> [K[17:53:41] [Server thread/ERROR] [Gotta Go Fast]: Please report this 
[39;0m> [K[17:53:41] [Server thread/ERROR] [Gotta Go Fast]: Couldn't find the processVehicleMove method (or any of its patch targets) to patch :( 
[39;0m> [K[17:53:41] [Server thread/ERROR] [Gotta Go Fast]: Please report this 
[39;0m> [K[17:53:42] [Server thread/INFO] [structurize]: New Server UUID 9051b9c9-8d52-44ca-b1d2-ae026d177dd3 
> [K[17:53:42] [Server thread/INFO] [Mekanica]: Sent config to 'KeviN_CZ.' 
> [K[17:53:42] [ForkJoinPool-1-worker-43/INFO] [opencomputers]: Starting OpenComputers version check. 
> [K[17:53:42] [Server thread/INFO] [Astral Sorcery]: [Astral Sorcery] Waiting for server synchronization on login for KeviN_CZ... 
> [K[17:53:42] [Server thread/INFO] [Astral Sorcery]: [Astral Sorcery] Synchronizing baseline information to KeviN_CZ 
> [K[17:53:43] [Server thread/WARN] inecraft/MinecraftServer]: Can't keep up! Did the system time change, or is the server overloaded? Running 2417ms behind, skipping 48 tick(s) 
[39;0m> [K[17:53:43] [Server thread/ERROR] [FML]: Exception caught during firing event net.minecraftforge.event.world.ChunkEvent$Load@326c055: 
java.lang.IndexOutOfBoundsException: Index: 0, Size: 0 
at java.util.ArrayList.rangeCheck(ArrayList.java:657) ~[?:1.8.0_201] 
at java.util.ArrayList.get(ArrayList.java:433) ~[?:1.8.0_201] 
at com.minecolonies.api.colony.IColonyTagCapability$Impl.removeColony(IColonyTagCapability.java:120) ~[IColonyTagCapability$Impl.class:?] 
at com.minecolonies.api.util.ChunkLoadStorage.applyToCap(ChunkLoadStorage.java:222) ~[ChunkLoadStorage.class:?] 
at com.minecolonies.coremod.util.ChunkDataHelper.addStorageToChunk(ChunkDataHelper.java:119) ~[ChunkDataHelper.class:?] 
at com.minecolonies.coremod.util.ChunkDataHelper.loadChunk(ChunkDataHelper.java:78) ~[ChunkDataHelper.class:?] 
at com.minecolonies.coremod.event.EventHandler.onChunkLoad(EventHandler.java:159) ~[EventHandler.class:?] 
at net.minecraftforge.fml.common.eventhandler.ASMEventHandler_631_EventHandler_onChunkLoad_Load.invoke(.dynamic) ~[?:?] 
at net.minecraftforge.fml.common.eventhandler.ASMEventHandler.invoke(ASMEventHandler.java:90) ~[ASMEventHandler.class:?] 
at net.minecraftforge.fml.common.eventhandler.EventBus.post(EventBus.java:182) [EventBus.class:?] 
at net.minecraft.world.chunk.Chunk.onLoad(Chunk.java:862) [axw.class:?] 
at net.minecraftforge.common.chunkio.ChunkIOProvider.syncCallback(ChunkIOProvider.java:109) [ChunkIOProvider.class:?] 
at net.minecraftforge.common.chunkio.ChunkIOExecutor.tick(ChunkIOExecutor.java:150) [ChunkIOExecutor.class:?] 
at net.minecraft.server.MinecraftServer.updateTimeLightAndEntities(MinecraftServer.java:728) [MinecraftServer.class:?] 
at net.minecraft.server.dedicated.DedicatedServer.updateTimeLightAndEntities(DedicatedServer.java:397) [nz.class:?] 
at net.minecraft.server.MinecraftServer.tick(MinecraftServer.java:668) [MinecraftServer.class:?] 
at net.minecraft.server.MinecraftServer.run(MinecraftServer.java:526) [MinecraftServer.class:?] 
at java.lang.Thread.run(Thread.java:748) [?:1.8.0_201] 
[39;0m> [K[17:53:43] [Server thread/ERROR] [FML]: Index: 1 Listeners: 
[39;0m> [K[17:53:43] [Server thread/ERROR] [FML]: 0: NORMAL 
[39;0m> [K[17:53:43] [Server thread/ERROR] [FML]: 1: ASM: com.minecolonies.coremod.event.EventHandler@6b835fd8 onChunkLoad(Lnet/minecraftforge/event/world/ChunkEvent$Load;)V 
[39;0m> [K[17:53:43] [Server thread/ERROR] [FML]: 2: ASM: forestry.core.multiblock.MultiblockEventHandler@4ab248c9 onChunkLoad(Lnet/minecraftforge/event/world/ChunkEvent$Load;)V 
[39;0m> [K[17:53:43] [Server thread/ERROR] [FML]: 3: ASM: pregenerator.ChunkPregenerator@476e3a4b onChunkLoad(Lnet/minecraftforge/event/world/ChunkEvent$Load;)V 
[39;0m> [K[17:53:43] [Server thread/ERROR] [FML]: 4: ASM: hellfirepvp.astralsorcery.common.event.listener.EventHandlerIO@4500b660 onChunkLoad(Lnet/minecraftforge/event/world/ChunkEvent$Load;)V 
[39;0m> [K[17:53:43] [Server thread/ERROR] [FML]: 5: ASM: hellfirepvp.astralsorcery.common.starlight.network.TransmissionChunkTracker@2efa7d2c onChLoad(Lnet/minecraftforge/event/world/ChunkEvent$Load;)V 
[39;0m> [K[17:53:43] [Server thread/ERROR] [FML]: 6: ASM: reborncore.common.multiblock.MultiblockEventHandler@1bdaff41 onChunkLoad(Lnet/minecraftforge/event/world/ChunkEvent$Load;)V 
[39;0m> [K[17:53:43] [Server thread/ERROR] [FML]: 7: ASM: reborncore.common.multiblock.MultiblockEventHandler@6e1f90b0 onChunkLoad(Lnet/minecraftforge/event/world/ChunkEvent$Load;)V 
[39;0m> [K[17:53:43] [Server thread/ERROR] [FML]: 8: ASM: mekanism.common.command.CommandChunk@180913ae onChunkLoad(Lnet/minecraftforge/event/world/ChunkEvent$Load;)V 
[39;0m> [K[17:53:43] [Server thread/ERROR] inecraft/MinecraftServer]: Encountered an unexpected exception 
java.lang.IndexOutOfBoundsException: Index: 0, Size: 0 
at java.util.ArrayList.rangeCheck(ArrayList.java:657) ~[?:1.8.0_201] 
at java.util.ArrayList.get(ArrayList.java:433) ~[?:1.8.0_201] 
at com.minecolonies.api.colony.IColonyTagCapability$Impl.removeColony(IColonyTagCapability.java:120) ~[IColonyTagCapability$Impl.class:?] 
at com.minecolonies.api.util.ChunkLoadStorage.applyToCap(ChunkLoadStorage.java:222) ~[ChunkLoadStorage.class:?] 
at com.minecolonies.coremod.util.ChunkDataHelper.addStorageToChunk(ChunkDataHelper.java:119) ~[ChunkDataHelper.class:?] 
at com.minecolonies.coremod.util.ChunkDataHelper.loadChunk(ChunkDataHelper.java:78) ~[ChunkDataHelper.class:?] 
at com.minecolonies.coremod.event.EventHandler.onChunkLoad(EventHandler.java:159) ~[EventHandler.class:?] 
at net.minecraftforge.fml.common.eventhandler.ASMEventHandler_631_EventHandler_onChunkLoad_Load.invoke(.dynamic) ~[?:?] 
at net.minecraftforge.fml.common.eventhandler.ASMEventHandler.invoke(ASMEventHandler.java:90) ~[ASMEventHandler.class:?] 
at net.minecraftforge.fml.common.eventhandler.EventBus.post(EventBus.java:182) ~[EventBus.class:?] 
at net.minecraft.world.chunk.Chunk.onLoad(Chunk.java:862) ~[axw.class:?] 
at net.minecraftforge.common.chunkio.ChunkIOProvider.syncCallback(ChunkIOProvider.java:109) ~[ChunkIOProvider.class:?] 
at net.minecraftforge.common.chunkio.ChunkIOExecutor.tick(ChunkIOExecutor.java:150) ~[ChunkIOExecutor.class:?] 
at net.minecraft.server.MinecraftServer.updateTimeLightAndEntities(MinecraftServer.java:728) ~[MinecraftServer.class:?] 
at net.minecraft.server.dedicated.DedicatedServer.updateTimeLightAndEntities(DedicatedServer.java:397) ~[nz.class:?] 
at net.minecraft.server.MinecraftServer.tick(MinecraftServer.java:668) ~[MinecraftServer.class:?] 
at net.minecraft.server.MinecraftServer.run(MinecraftServer.java:526) [MinecraftServer.class:?] 
at java.lang.Thread.run(Thread.java:748) [?:1.8.0_201] 
[39;0m> [K[17:53:43] [Server thread/WARN] [org.dimdev.utils.ModIdentifier]: Failed to identify net.minecraftforge.fml.common.eventhandler.ASMEventHandler_631_EventHandler_onChunkLoad_Load (untransformed name: net.minecraftforge.fml.common.eventhandler.ASMEventHandler_631_EventHandler_onChunkLoad_Load) 
[39;0m> [K[17:53:43] [Server thread/ERROR] inecraft/MinecraftServer]: This crash report has been saved to: /home/hosting/servers/211912/./crash-reports/crash-2019-05-10_17.53.43-server.txt 
[39;0m> [K[17:53:43] [Server thread/INFO] inecraft/MinecraftServer]: Stopping server 
> [K[17:53:43] [Server thread/INFO] inecraft/MinecraftServer]: Saving players 
> [K[17:53:43] [Server thread/INFO] inecraft/MinecraftServer]: Saving worlds 
> [K[17:53:43] [Server thread/INFO] inecraft/MinecraftServer]: Saving chunks for level 'world'/overworld 
> [K[17:53:43] [Server thread/INFO] [THAUMCRAFT]: Removing aura cache for world 0 
> [K[17:53:43] [Server thread/INFO] [FML]: Unloading dimension 0 
> [K[17:53:43] [ForkJoinPool-1-worker-43/INFO] [opencomputers]: Running the latest OpenComputers version. 
> [K[17:53:43] [Server thread/INFO] [endertanks]: Unloading EnderTank Data 
> [K[17:53:43] [Server thread/INFO] [FML]: The state engine was in incorrect state SERVER_STOPPING and forced into state SERVER_STOPPED. Errors may have been discarded. 
> [K[17:53:43] [Server Shutdown Thread/INFO] inecraft/MinecraftServer]: Stopping server 
> 2019-05-10 17:53:43,981 Server Shutdown Thread ERROR Could not register mbeans java.security.AccessControlException: access denied ("javax.management.MBeanTrustPermission" "register") 
at java.security.AccessControlContext.checkPermission(AccessControlContext.java:472) 
at java.lang.SecurityManager.checkPermission(SecurityManager.java:585) 
at com.sun.jmx.interceptor.DefaultMBeanServerInterceptor.checkMBeanTrustPermission(DefaultMBeanServerInterceptor.java:1848)
at com.sun.jmx.interceptor.DefaultMBeanServerInterceptor.registerMBean(DefaultMBeanServerInterceptor.java:322)
at com.sun.jmx.mbeanserver.JmxMBeanServer.registerMBean(JmxMBeanServer.java:522) 
at org.apache.logging.log4j.core.jmx.Server.register(Server.java:389) 
at org.apache.logging.log4j.core.jmx.Server.reregisterMBeansAfterReconfigure(Server.java:167) 
at org.apache.logging.log4j.core.jmx.Server.reregisterMBeansAfterReconfigure(Server.java:140) 
at org.apache.logging.log4j.core.LoggerContext.setConfiguration(LoggerContext.java:556) 
at org.apache.logging.log4j.core.LoggerContext.reconfigure(LoggerContext.java:617) 
at org.apache.logging.log4j.core.LoggerContext.reconfigure(LoggerContext.java:634) 
at org.apache.logging.log4j.core.LoggerContext.start(LoggerContext.java:229) 
at org.apache.logging.log4j.core.impl.Log4jContextFactory.getContext(Log4jContextFactory.java:242) 
at org.apache.logging.log4j.core.impl.Log4jContextFactory.getContext(Log4jContextFactory.java:45) 
at org.apache.logging.log4j.LogManager.getContext(LogManager.java:174) 
at org.apache.logging.log4j.LogManager.getLogger(LogManager.java:618) 
at farseek.util.Logging$class.$init$(Logging.scala:14) 
at farseek.core.FarseekClassVisitor.<init>(FarseekClassVisitor.scala:17) 
at farseek.core.FarseekClassTransformer.transform(FarseekCoreMod.scala:68) 
at net.minecraftforge.fml.common.asm.ASMTransformerWrapper$TransformerWrapper.transform(ASMTransformerWrapper.java:256)
at net.minecraft.launchwrapper.LaunchClassLoader.runTransformers(LaunchClassLoader.java:279) 
at net.minecraft.launchwrapper.LaunchClassLoader.findClass(LaunchClassLoader.java:176) 
at java.lang.ClassLoader.loadClass(ClassLoader.java:424) 
at java.lang.ClassLoader.loadClass(ClassLoader.java:357) 
at net.minecraft.network.NetworkManager.func_179288_a(NetworkManager.java:198) 
at net.minecraft.network.NetHandlerPlayServer.func_194028_b(NetHandlerPlayServer.java:279) 
at net.minecraft.server.management.PlayerList.func_72392_r(PlayerList.java:1084) 
at net.minecraft.server.MinecraftServer.func_71260_j(MinecraftServer.java:431) 
at net.minecraft.server.MinecraftServer$4.run(MinecraftServer.java:1579) 

2019-05-10 17:53:43,986 Server Shutdown Thread WARN Unable to register Log4j shutdown hook because JVM is shutting down. Using SimpleLogger 
Exception in thread "Server Shutdown Thread"
