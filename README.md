hereflutter pub add flutter_dotenvimport 'package:flutter_dotenv/flutter_dotenv.dart';

final secretKey = dotenv.env['OWA_KEYSTORE_BASE64'];void main() async {
  await dotenv.load();
  runApp(MyApp());
}.env
