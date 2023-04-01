lib/fragments/MoreFragment.dart:145:33: Error: The method 'DownloadItemScreen' isn't defined for the class 'MoreFragmentState'.
 - 'MoreFragmentState' is from 'package:streamit_flutter/fragments/MoreFragment.dart' ('lib/fragments/MoreFragment.dart').
Try correcting the name to the name of an existing method, or defining a method named 'DownloadItemScreen'.
                                DownloadItemScreen().launch(context);
                                ^^^^^^^^^^^^^^^^^^
lib/screens/MovieDetailScreen.dart:440:39: Error: The method 'DownloadVideoFromLinkWidget' isn't defined for the class 'MovieDetailScreenState'.
 - 'MovieDetailScreenState' is from 'package:streamit_flutter/screens/MovieDetailScreen.dart' ('lib/screens/MovieDetailScreen.dart').
Try correcting the name to the name of an existing method, or defining a method named 'DownloadVideoFromLinkWidget'.
                                      DownloadVideoFromLinkWidget(
                                      ^^^^^^^^^^^^^^^^^^^^^^^^^^^
lib/screens/DownloadItemScreen.dart:28:52: Error: Too many positional arguments: 1 allowed, but 2 found.
Try removing the extra positional arguments.
    final encrypter = encrypt.Encrypter(encrypt.AES(key, iv));
                                                   ^
../../AppData/Local/Pub/Cache/hosted/pub.dev/encrypt-5.0.1/lib/src/algorithms/aes.dart:11:3: Context: Found this candidate, but the arguments don't match.
  AES(this.key, {this.mode = AESMode.sic, this.padding = 'PKCS7'})
  ^^^
lib/screens/DownloadItemScreen.dart:29:55: Error: The argument type 'List<int>' can't be assigned to the parameter type 'Encrypted'.
 - 'List' is from 'dart:core'.
 - 'Encrypted' is from 'package:encrypt/encrypt.dart' ('../../AppData/Local/Pub/Cache/hosted/pub.dev/encrypt-5.0.1/lib/encrypt.dart').
    List<int> decryptedBytes = encrypter.decryptBytes(videoBytes);
                                                      ^
lib/screens/DownloadItemScreen.dart:57:18: Error: The method 'VideoPlayer' isn't defined for the class '_PlayState'.
 - '_PlayState' is from 'package:streamit_flutter/screens/DownloadItemScreen.dart' ('lib/screens/DownloadItemScreen.dart').
Try correcting the name to the name of an existing method, or defining a method named 'VideoPlayer'.
          child: VideoPlayer(FileVideoPlayerController.file(File(_videoPath))),
                 ^^^^^^^^^^^
lib/screens/DownloadItemScreen.dart:57:30: Error: The getter 'FileVideoPlayerController' isn't defined for the class '_PlayState'.
 - '_PlayState' is from 'package:streamit_flutter/screens/DownloadItemScreen.dart' ('lib/screens/DownloadItemScreen.dart').
Try correcting the name to the name of an existing getter, or defining a getter or field named 'FileVideoPlayerController'.
          child: VideoPlayer(FileVideoPlayerController.file(File(_videoPath))),
                             ^^^^^^^^^^^^^^^^^^^^^^^^^
lib/screens/download_file/DownloadFileScreen.dart:55:13: Error: The method 'launch' isn't defined for the class '_DownloadPageState'.
 - '_DownloadPageState' is from 'package:streamit_flutter/screens/download_file/DownloadFileScreen.dart' ('lib/screens/download_file/DownloadFileScreen.dart').    
Try correcting the name to the name of an existing method, or defining a method named 'launch'.
      await launch(uri.toString());
            ^^^^^^
lib/screens/EpisodeDetailScreen.dart:337:37: Error: The method 'DownloadVideoFromLinkWidget' isn't defined for the class 'EpisodeDetailScreenState'.
 - 'EpisodeDetailScreenState' is from 'package:streamit_flutter/screens/EpisodeDetailScreen.dart' ('lib/screens/EpisodeDetailScreen.dart').
Try correcting the name to the name of an existing method, or defining a method named 'DownloadVideoFromLinkWidget'.
                                    DownloadVideoFromLinkWidget(
                                    ^^^^^^^^^^^^^^^^^^^^^^^^^^^
lib/screens/DownloadItemScreen.dart:14:10: Error: Field '_videoPath' should be initialized because its type 'String' doesn't allow null.
  String _videoPath;
         ^^^^^^^^^^
Target kernel_snapshot failed: Exception


FAILURE: Build failed with an exception.

* Where:
Script 'C:\flutter\packages\flutter_tools\gradle\flutter.gradle' line: 1151

* What went wrong:
Execution failed for task ':app:compileFlutterBuildRelease'.
> Process 'command 'C:\flutter\bin\flutter.bat'' finished with non-zero exit value 1

* Try:
> Run with --stacktrace option to get the stack trace.
> Run with --info or --debug option to get more log output.
> Run with --scan to get full insights.

* Get more help at https://help.gradle.org

BUILD FAILED in 7m 52s
Running Gradle task 'assembleRelease'...                          480.1s
Gradle task assembleRelease failed with exit code 1
