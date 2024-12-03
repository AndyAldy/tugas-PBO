import 'mahasiswa.dart';
import 'matakuliah.dart';
import 'krs.dart';
import 'nilai.dart';
import 'ipk.dart';

void main() {
  // Mahasiswa
  Mahasiswa mhs = Mahasiswa("230103090", "Andy Aldyansyah", 3);

  // Mata Kuliah
  MataKuliah mk1 = MataKuliah("MK001", "Pemrograman Dart", 3);
  MataKuliah mk2 = MataKuliah("MK002", "Matematika Diskrit", 3);
  MataKuliah mk3 = MataKuliah("MK003", "Pemrograman Berorientasi Objek", 3);

  // KRS
  KRS krs = KRS(mhs, [mk1, mk2, mk3]);

  // Cetak KRS
  krs.cetakKRS();

  // Nilai
  Nilai nilai1 = Nilai(mk1, 85);
  Nilai nilai2 = Nilai(mk2, 70);
  Nilai nilai3 = Nilai(mk3, 90);

  List<Nilai> daftarNilai = [nilai1, nilai2, nilai3];

  // Input nilai mahasiswa
  inputNilai(daftarNilai);

  // Hitung IPK
  print("IPK: ${hitungIPK(daftarNilai).toStringAsFixed(3)}");

  // Cetak Transkrip Nilai
  cetakTranskrip(mhs, daftarNilai);
}
