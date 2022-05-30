package com.example.myapplication;

import androidx.appcompat.app.AppCompatActivity;

import android.os.Bundle;
import android.view.View;
import android.widget.ImageView;

import java.security.KeyStore;

public class MainActivity extends AppCompatActivity
{
    boolean isRahul = true;
    public void change(View view)
    {

        ImageView iv=findViewById(R.id.imageView4);
        if(isRahul)
        {
            iv.setImageResource(R.drawable.img);
            isRahul=false;
        }
        else
        {
            iv.setImageResource(R.drawable.overview__bcphzsdb4fpu_og);
            isRahul=true;
        }

    }
    @Override
    protected void onCreate(Bundle savedInstanceState)
    {
        super.onCreate(savedInstanceState);
        setContentView(R.layout.activity_main);
    }
}
