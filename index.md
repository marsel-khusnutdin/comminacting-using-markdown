# Header

## Smaller header

### The smallest header

![Confused Travolta](https://i.kym-cdn.com/entries/icons/mobile/000/019/277/confusedtravolta.jpg)

#### SQL query

```
CREATE TABLE IF NOT EXISTS `Print_jobs`.`operation_types` (
  `operation_type` ENUM('Bid date', 'Quote approved date', 'POs issued date', 'Invoice date', 'Paid in full date') NOT NULL,
  `stage` ENUM('Quoting', 'Production', 'Billing', 'Collection', 'Closed') NOT NULL,
  PRIMARY KEY (`operation_type`))
ENGINE = InnoDB;
```

#### To-do list

- [x] Turn on GitHub Pages
- [x] Outline my portfolio
- [ ] Introduce myself to the world
