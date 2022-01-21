# Android_Toggle_Button_And_Switch
Using Toggle Button and Switch in Android App


# Code

#### 1st Activity 
```
ToggleButton toggleButton;
Switch aSwitch;

toggleButton = findViewById(R.id.toggleButton);
aSwitch = findViewById(R.id.switch1);

          toggleButton.setOnCheckedChangeListener(new CompoundButton.OnCheckedChangeListener() {
            @Override
            public void onCheckedChanged(CompoundButton buttonView, boolean isChecked) {
                if (isChecked)
                    Toast.makeText(getApplicationContext(), "Checked", Toast.LENGTH_SHORT).show();
                else
                    Toast.makeText(getApplicationContext(), "Unchecked", Toast.LENGTH_SHORT).show();
            }
        });

        aSwitch.setOnCheckedChangeListener(new CompoundButton.OnCheckedChangeListener() {
            @Override
            public void onCheckedChanged(CompoundButton buttonView, boolean isChecked) {
                if (isChecked)
                    Toast.makeText(getApplicationContext(), "Switch Checked", Toast.LENGTH_SHORT).show();
                else
                    Toast.makeText(getApplicationContext(), "Switch Unchecked", Toast.LENGTH_SHORT).show();
            }
        });
```

# App Highlight

<img src="app_images/Toggle Switch Code.png" width="1000" /><br>

<img src="app_images/Toggle Switch App1.png" width="300" /> <img src="app_images/Toggle Switch App2.png" width="300" /> <img src="app_images/Toggle Switch App3.png" width="300" /><br>
