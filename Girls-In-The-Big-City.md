## Console Commands

## Bypass "Anti-Cheat"
1. Use [unrpyc](https://github.com/CensoredUsername/unrpyc) to unpack and decompile rpa files in the "game" folder.
2. Open options.rpy
3. change `config.console = False` to `config.console = True`
4. Remove `'shift_O', 'shift_o'` from `config.keymap['panic_screen'] = ['q', 'Q', 'shift_O', 'shift_o']`
5. Now you can use console like always with shift+o


## Unlock gallery
```python
persistent.watched_h_scenes = [1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11, 12, 13, 14, 15, 16, 17, 18, 19, 20, 21, 22, 23, 24, 25, 26, 27, 28, 29, 30, 31, 32, 33, 34, 35, 36, 37, 38, 39, 40, 41, 42, 43, 44, 45, 46, 47, 48, 49, 50, 51, 52, 53, 54]
```

### Wonder Woman
```python
ww.money += 9990  
ww.hp = 110 #Health 110?
```

##### Fight
Following commands doesn't work, becouse the game reset scenes as soon you leave the console.  
```python
bum_fight_counter #(on 3 you get a new ability)
bum.hp = 1
```

##### Add Item
```python
ww.add_item_for_real("First Aid Kit", amount=1) #Theory
```



### Raven
```python
raven.hp  
raven.score_points = 990000  
raven.total_score_points = 990000  
```
