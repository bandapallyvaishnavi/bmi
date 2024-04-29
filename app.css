window.onload = () =>
 {
    const button = document.querySelector('#btn');
    button.addEventListener('click',calculateBmi)
    
     
 }
 

 function calculateBmi()
 {
    const height = document.querySelector ('#height').value;
    const weight = document.querySelector ('#weight').value;
    const result = document.querySelector ('#result');
    
    
       if(!height || isNaN(height) || height < 0) {
        result.ineerText = "please provide a valid height";
        return;
       } else if(!weight || isNaN(weight) || weight < 0 ) {
        result.innerText = "please provide a valid weight";
        return;
       }
      
       const bmi = (weight / ((height*height) / 10000)).toFixed(2);

     if (bmi < 18.5) {
       result.innerText = `under weight: ${bmi},
       HEALTH GUIDANCE:UNDERWEIGHT
       1.Increase Caloric Intake
      2.Focus on Nutrient-Dense Foods
      3.Protein-Rich Foods
      4.Healthy Fats
      5.Complex Carbohydrates
      6.Regular Meals and Snacks
      7.Address Underlying Causes`;
      }else if (bmi >=18.5 && bmi < 24.9) {
     result.innerText = `normal: ${bmi},
     HEALTH GUIDANCE:normal weight
      keep it up and contiue your healthy diet 
       "\uD83D\uDE0A"`;
      } else if (bmi >=25 && bmi < 29.9){
      result.innerText = `overweight: ${bmi},
       HEALTH GUIDANCE:OVERWEIGHT
      1.Calorie Control
     2.Balanced Macronutrients
     3.Meal Timing and Frequency
     4.Hydration
     5.Healthy Snacking Options`;
      }else if (bmi >=30 && bmi < 34.9) {
       result.innerText = `obesity (class 1): ${bmi},
        HEALTH GUIDANCE:OBESITY CLASS 1
       1.Calorie Deficit
      2.Balanced Macronutrients
      3.Meal Timing and Frequency
      4.Hydration
      5.Fiber-Rich Foods
      `;
      } else if (bmi >=35 && bmi < 39.9){
        result.innerText = `obsity (class 2): ${bmi},
         HEALTH GUIDANCE:OBESITY CLASS 2
        1.Portion Control and Mindful Eating
       2.Food Journaling:
       3.Meal Timing and Frequency
       4.Hydration
       5.Fiber-Rich Foods
       `;
       }else  {
      result.innerText = `Extreme obesity: ${bmi},
      HEALTH GUIDANCE: EXTREME OBESITY
      1.Surgical Options
     2.Physical Activity
     3.Caloric Deficit
     4.Hydration
     5.Fiber-Rich Foods`;
     }
     }
     function fun1()
     {
        console.write(no);
     }
    
    
     
    




