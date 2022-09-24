# Android_Toggle_Button_And_Switch
Using Toggle Button and Switch in Android App

This topic is a part of [My Complete Andorid Course](https://github.com/ananddasani/Android_Apps)

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

![Toggle Switch App1](https://user-images.githubusercontent.com/74413402/192092770-30ee2dcd-1415-4347-b5ef-c3731cdb06ed.png)
![Toggle Switch App2](https://user-images.githubusercontent.com/74413402/192092772-1a1c5f74-0e1f-4e8a-b99d-8d9aae49ccaa.png)
![Toggle Switch App3](https://user-images.githubusercontent.com/74413402/192092773-ad8ae869-a750-4aca-91f6-e73f4850a75e.png)
![Toggle Switch Code](https://user-images.githubusercontent.com/74413402/192092775-242fe4af-892d-47e6-86c0-232e172ac0ad.png)
