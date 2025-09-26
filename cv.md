# VOLHA FILANOVICH 

### Contacts: 
- volha.f@outlook.com
- discord: volhaf
- [linkedin](www.linkedin.com/in/volha-filanovich-355a562b1)

### About Me:


### Skills:
- HTML, HTML5
- CSS, SCSS
- JavaScript (ES6+), TypeScript
- React, Redux (Toolkit)
- Git, GitHub
- Styled Components, Material UI
- Figma, Adobe Photoshop

### Code Examples: 
```
export function Counter ({}:CounterPropsType): any {
    let [count, setCount] = useState(0);
    
        const incClickHandler = () => {
            if (count <= 5) {
                return setCount(count + 1 );
            }}
        const resetClickHandler = () => {
                setCount(0)
            }
            
            return (
                <div className={s.counter}>
                    <div className={count === 5 ? s.max : s.number}>{count}</div>
                    <div className={s.button_conteiner}>
                        <Button
                            onClick={incClickHandler}
                            title={'inc'}
                            disabled={count === 5 }
                            buttonColor={s.onActiveButton}
                        />
                        <Button
                            onClick={resetClickHandler}
                            title={'reset'}
                            disabled={count < 5}
                            buttonColor={s.onActiveButton}
                        />
                    </div>
                </div>
            )
        }
``` 

### Work Experience: 

### Education: 

### Language: 