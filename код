class SmartComponent {
    constructor(name) {
        this.name = name;
    }
    turnon() {
        console.log(`${this.name} увімкнено.`);
    }
    turnoff() {
        console.log(`${this.name} вимкнено.`);
    }
}

class Light extends SmartComponent {
    constructor() {
        super("Світильник");
    }
}

class Blinds extends SmartComponent {
    constructor() {
        super("Жалюзі");
    }
}

class SmartHome {
    constructor() {
        this.components = [];
    }
    addComponent(component) {
        this.components.push(component);
    }
}

const smartHome = new SmartHome();
const light = new Light();
const blinds = new Blinds();

smartHome.addComponent(light);
smartHome.addComponent(blinds);

light.turnon();
blinds.turnoff();
