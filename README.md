Build version: 2.23.13.76 
Build date: 2023-09-13 02:31:04 
Current date: 2023-10-04 22:46:59 
Device: Xiaomi M2007J20CG 
OS version: Android 12 (SDK 31) 
Name: WhatsApp v9.82.1
Package name: com.whatsapp 
Language: en 

Stack trace: 
java.lang.RuntimeException: Unable to start activity ComponentInfo{com.whatsapp/mbmodsd.mbmodsw.mbsettings.yo.MBThemes}: java.lang.SecurityException: Permission Denial: opening provider com.android.providers.downloads.DownloadStorageProvider from ProcessRecord{3d35280 17043:com.whatsapp/u0a251} (pid=17043, uid=10251) requires that you obtain access using ACTION_OPEN_DOCUMENT or related APIs
	at android.app.ActivityThread.performLaunchActivity(ActivityThread.java:3771)
	at android.app.ActivityThread.handleLaunchActivity(ActivityThread.java:3938)
	at android.app.servertransaction.LaunchActivityItem.execute(LaunchActivityItem.java:103)
	at android.app.servertransaction.TransactionExecutor.executeCallbacks(TransactionExecutor.java:135)
	at android.app.servertransaction.TransactionExecutor.execute(TransactionExecutor.java:95)
	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:2291)
	at android.os.Handler.dispatchMessage(Handler.java:106)
	at android.os.Looper.loopOnce(Looper.java:210)
	at android.os.Looper.loop(Looper.java:299)
	at android.app.ActivityThread.main(ActivityThread.java:8319)
	at java.lang.reflect.Method.invoke(Native Method)
	at com.android.internal.os.RuntimeInit$MethodAndArgsCaller.run(RuntimeInit.java:556)
	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1038)
Caused by: java.lang.SecurityException: Permission Denial: opening provider com.android.providers.downloads.DownloadStorageProvider from ProcessRecord{3d35280 17043:com.whatsapp/u0a251} (pid=17043, uid=10251) requires that you obtain access using ACTION_OPEN_DOCUMENT or related APIs
	at android.os.Parcel.createExceptionOrNull(Parcel.java:2426)
	at android.os.Parcel.createException(Parcel.java:2410)
	at android.os.Parcel.readException(Parcel.java:2393)
	at android.os.Parcel.readException(Parcel.java:2335)
	at android.app.IActivityManager$Stub$Proxy.getContentProvider(IActivityManager.java:6097)
	at android.app.ActivityThread.acquireProvider(ActivityThread.java:7415)
	at android.app.ContextImpl$ApplicationContentResolver.acquireUnstableProvider(ContextImpl.java:3363)
	at android.content.ContentResolver.acquireUnstableProvider(ContentResolver.java:2529)
	at android.content.ContentResolver.openTypedAssetFileDescriptor(ContentResolver.java:2013)
	at android.content.ContentResolver.openAssetFileDescriptor(ContentResolver.java:1844)
	at android.content.ContentResolver.openInputStream(ContentResolver.java:1520)
	at mbmodsd.mbmodsw.mbsettings.yo.MBThemes.gFFCU(Native Method)
	at mbmodsd.mbmodsw.mbsettings.yo.MBThemes.f(Native Method)
	at mbmodsd.mbmodsw.mbsettings.yo.MBThemes.onCreate(Native Method)
	at android.app.Activity.performCreate(Activity.java:8163)
	at android.app.Activity.performCreate(Activity.java:8130)
	at android.app.Instrumentation.callActivityOnCreate(Instrumentation.java:1330)
	at android.app.ActivityThread.performLaunchActivity(ActivityThread.java:3744)
	... 12 more
Caused by: android.os.RemoteException: Remote stack trace:
	at com.android.server.am.ContentProviderHelper.checkAssociationAndPermissionLocked(ContentProviderHelper.java:645)
	at com.android.server.am.ContentProviderHelper.getContentProviderImpl(ContentProviderHelper.java:241)
	at com.android.server.am.ContentProviderHelper.getContentProvider(ContentProviderHelper.java:125)
	at com.android.server.am.ActivityManagerService.getContentProvider(ActivityManagerService.java:6290)
	at android.app.IActivityManager$Stub.onTransact(IActivityManager.java:2553)



User actions: 
2023-10-04 22:46:19: MBThemes created
Build version: 2.23.13.76 
Build date: 2023-09-13 02:31:04 
Current date: 2023-10-04 22:46:59 
Device: Xiaomi M2007J20CG 
OS version: Android 12 (SDK 31) 
Name: WhatsApp v9.82.1
Package name: com.whatsapp 
Language: en 

Stack trace: 
java.lang.RuntimeException: Unable to start activity ComponentInfo{com.whatsapp/mbmodsd.mbmodsw.mbsettings.yo.MBThemes}: java.lang.SecurityException: Permission Denial: opening provider com.android.providers.downloads.DownloadStorageProvider from ProcessRecord{3d35280 17043:com.whatsapp/u0a251} (pid=17043, uid=10251) requires that you obtain access using ACTION_OPEN_DOCUMENT or related APIs
	at android.app.ActivityThread.performLaunchActivity(ActivityThread.java:3771)
	at android.app.ActivityThread.handleLaunchActivity(ActivityThread.java:3938)
	at android.app.servertransaction.LaunchActivityItem.execute(LaunchActivityItem.java:103)
	at android.app.servertransaction.TransactionExecutor.executeCallbacks(TransactionExecutor.java:135)
	at android.app.servertransaction.TransactionExecutor.execute(TransactionExecutor.java:95)
	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:2291)
	at android.os.Handler.dispatchMessage(Handler.java:106)
	at android.os.Looper.loopOnce(Looper.java:210)
	at android.os.Looper.loop(Looper.java:299)
	at android.app.ActivityThread.main(ActivityThread.java:8319)
	at java.lang.reflect.Method.invoke(Native Method)
	at com.android.internal.os.RuntimeInit$MethodAndArgsCaller.run(RuntimeInit.java:556)
	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1038)
Caused by: java.lang.SecurityException: Permission Denial: opening provider com.android.providers.downloads.DownloadStorageProvider from ProcessRecord{3d35280 17043:com.whatsapp/u0a251} (pid=17043, uid=10251) requires that you obtain access using ACTION_OPEN_DOCUMENT or related APIs
	at android.os.Parcel.createExceptionOrNull(Parcel.java:2426)
	at android.os.Parcel.createException(Parcel.java:2410)
	at android.os.Parcel.readException(Parcel.java:2393)
	at android.os.Parcel.readException(Parcel.java:2335)
	at android.app.IActivityManager$Stub$Proxy.getContentProvider(IActivityManager.java:6097)
	at android.app.ActivityThread.acquireProvider(ActivityThread.java:7415)
	at android.app.ContextImpl$ApplicationContentResolver.acquireUnstableProvider(ContextImpl.java:3363)
	at android.content.ContentResolver.acquireUnstableProvider(ContentResolver.java:2529)
	at android.content.ContentResolver.openTypedAssetFileDescriptor(ContentResolver.java:2013)
	at android.content.ContentResolver.openAssetFileDescriptor(ContentResolver.java:1844)
	at android.content.ContentResolver.openInputStream(ContentResolver.java:1520)
	at mbmodsd.mbmodsw.mbsettings.yo.MBThemes.gFFCU(Native Method)
	at mbmodsd.mbmodsw.mbsettings.yo.MBThemes.f(Native Method)
	at mbmodsd.mbmodsw.mbsettings.yo.MBThemes.onCreate(Native Method)
	at android.app.Activity.performCreate(Activity.java:8163)
	at android.app.Activity.performCreate(Activity.java:8130)
	at android.app.Instrumentation.callActivityOnCreate(Instrumentation.java:1330)
	at android.app.ActivityThread.performLaunchActivity(ActivityThread.java:3744)
	... 12 more
Caused by: android.os.RemoteException: Remote stack trace:
	at com.android.server.am.ContentProviderHelper.checkAssociationAndPermissionLocked(ContentProviderHelper.java:645)
	at com.android.server.am.ContentProviderHelper.getContentProviderImpl(ContentProviderHelper.java:241)
	at com.android.server.am.ContentProviderHelper.getContentProvider(ContentProviderHelper.java:125)
	at com.android.server.am.ActivityManagerService.getContentProvider(ActivityManagerService.java:6290)
	at android.app.IActivityManager$Stub.onTransact(IActivityManager.java:2553)



User actions: 
2023-10-04 2350:19: MBThemes created
