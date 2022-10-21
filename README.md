# tugas-1
// Membuat Class by Rahmah
class Data
{
// Atribut class
constructor (nama,alamat,umur,pendidikan) {
this.nama = nama;
this.alamat = alamat;
this.umur = umur;
this.pendidikan = pendidikan;
}
}
var arrayPsn = new Array();
var Antor = new Data ("Antor","Surabaya","23","Universitas Gadjah Mada");
arrayPsn.push(Antor);
var Riko = new Data ("Riko","Purwokkerto","20","Universitas Jebdral Sudirman");
arrayPsn.push(Riko);
console.log(arrayPsn);
