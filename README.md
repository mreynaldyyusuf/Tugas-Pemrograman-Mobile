# Tugas-Pemrograman-Mobile



import android.app.Activity;
import android.os.Bundle;


import android.view.View;
import android.widget.ImageView;
import android.widget.TextView;

public class page_home_activity extends Activity {

	
	private View _bg__page_home;
	private ImageView foto;
	private ImageView foto_ek1;
	private ImageView foto_ek2;
	private TextView donasi_korban_banjir_kampung_pulo;
	private TextView kampung_pulo_saat_ini_sedang_dilanda_banjir__banjir_ini_sudah_berlangsung_sejak______baca_selengkapnya;
	private TextView ayo_bantu_korban_longsor_yogya;
	private TextView warga_yogya_saat_ini_sedang_dilanda_musibah_longsor__warga_kecamatan______baca_selengkapnya;
	private View rectangle_1;
	private ImageView logo;
	private ImageView line_1;
	private ImageView vector;
	private ImageView vector_ek1;
	private ImageView vector_ek2;

	@Override
	public void onCreate(Bundle savedInstanceState) {

		super.onCreate(savedInstanceState);
		setContentView(R.layout.page_home);

		
		_bg__page_home = (View) findViewById(R.id._bg__page_home);
		foto = (ImageView) findViewById(R.id.foto);
		foto_ek1 = (ImageView) findViewById(R.id.foto_ek1);
		foto_ek2 = (ImageView) findViewById(R.id.foto_ek2);
		donasi_korban_banjir_kampung_pulo = (TextView) findViewById(R.id.donasi_korban_banjir_kampung_pulo);
		kampung_pulo_saat_ini_sedang_dilanda_banjir__banjir_ini_sudah_berlangsung_sejak______baca_selengkapnya = (TextView) findViewById(R.id.kampung_pulo_saat_ini_sedang_dilanda_banjir__banjir_ini_sudah_berlangsung_sejak______baca_selengkapnya);
		ayo_bantu_korban_longsor_yogya = (TextView) findViewById(R.id.ayo_bantu_korban_longsor_yogya);
		warga_yogya_saat_ini_sedang_dilanda_musibah_longsor__warga_kecamatan______baca_selengkapnya = (TextView) findViewById(R.id.warga_yogya_saat_ini_sedang_dilanda_musibah_longsor__warga_kecamatan______baca_selengkapnya);
		rectangle_1 = (View) findViewById(R.id.rectangle_1);
		logo = (ImageView) findViewById(R.id.logo);
		line_1 = (ImageView) findViewById(R.id.line_1);
		vector = (ImageView) findViewById(R.id.vector);
		vector_ek1 = (ImageView) findViewById(R.id.vector_ek1);
		vector_ek2 = (ImageView) findViewById(R.id.vector_ek2);
	
		
		//custom code goes here
	
	}
}
	
	
