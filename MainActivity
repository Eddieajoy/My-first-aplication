package com.example.myapplicationhello

import androidx.appcompat.app.AppCompatActivity
import android.os.Bundle
import android.widget.Button
import android.widget.EditText
import android.widget.Toast

class MainActivity : AppCompatActivity() {
    override fun onCreate(savedInstanceState: Bundle?) {
        super.onCreate(savedInstanceState)
        setContentView(R.layout.activity_main)

        val escribirtexto:EditText=findViewById(R.id.escribirtexto)
        val boton:Button=findViewById(R.id.boton)

        // using button click listener
        boton.setOnClickListener{
            //getting message from the editText
            val message=escribirtexto.text.toString()
            Toast.makeText(this,message,Toast.LENGTH_SHORT).show()
        }
    }
}
