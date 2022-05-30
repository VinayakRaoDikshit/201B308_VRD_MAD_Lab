package com.example.a04_04_vrd_308_anim;

import androidx.appcompat.app.AppCompatActivity;

import android.os.Bundle;
import android.view.View;
import android.widget.ImageView;


public class MainActivity extends AppCompatActivity {
    boolean iswater=true;

    public void change(View view) {
        ImageView imageview1 = findViewById(R.id.imageView);
        ImageView imageview2 = findViewById(R.id.imageView2);


        if (iswater) {
            imageview1.animate().alpha(1).setDuration(3500);
            imageview2.animate().alpha(0).setDuration(3500);
            iswater = false;
        } else {
            imageview1.animate().alpha(0).setDuration(3500);
            imageview2.animate().alpha(1).setDuration(3500);
            iswater= true;
        }
    }

    @Override
    protected void onCreate(Bundle savedInstanceState) {
        super.onCreate(savedInstanceState);
        setContentView(R.layout.activity_main);

    }
}
