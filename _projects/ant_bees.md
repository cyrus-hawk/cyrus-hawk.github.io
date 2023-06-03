---

name: Ants vs. SomeBees

description: >
    A Tower Defense (TD) game where ants try to defend their colony
    against adversarial bees...

title: Ants vs. SomeBees

asset_loc: ../assets/images/ant_bees/

---

# Introduction

In this project, I have combined functional and object-oriented
programming paradigms to implement the required functionalities for a
<a href="https://secure.wikimedia.org/wikipedia/en/wiki/Tower_defense"
target="_blank">tower defense</a> game called "Ants vs. SomeBees." The
player assumes the role of the ant queen, responsible for populating
the colony with brave ants. These ants have the crucial task of
protecting their queen from the invasion of evil bees seeking to take
over the territory.

The game is composed of a series of turns. During each turn, new bees
may enter the ant colony, followed by the placement of new ants to
defend the colony. Finally, all insects (ants, followed by bees) take
individual actions. Bees attempt to either move towards the end of the
tunnel or sting ants that obstruct their path. On the other hand, ants
perform various actions based on their type, such as collecting food
or hurling leaves at the bees. The game concludes when either a bee
reaches the ant queen or the entire bee fleet has been defeated.

# Ant army

Each ant possesses unique attributes that make them special. The
following is a list of ants along with their special traits.

<table>
    <tr>
        <td>
            <img src="/assets/images/ant_bees/ant_harvester.gif">
            <br />
            <br />
            Harvester
            <br />
            <em>Food cost:</em> 2
            <br />
            <em>Armor:</em> 1
        </td>
        <td>
            <img src="/assets/images/ant_bees/ant_thrower.gif">
            <br />
            <br />
            Thrower
            <br />
            <em>Food cost:</em> 3
            <br />
            <em>Armor:</em> 1
        </td>
        <td>
            <img src="/assets/images/ant_bees/ant_shortthrower.gif">
            <br />
            <br />
            Short Thrower
            <br />
            <em>Food cost:</em> 2
            <br />
            <em>Armor:</em> 1
       </td>
        <td>
            <img src="/assets/images/ant_bees/ant_longthrower.gif">
            <br />
            <br />
            Long Thrower
            <br />
            <em>Food cost:</em> 2
            <br />
            <em>Armor:</em> 1
        </td>
        <td>
            <img src="/assets/images/ant_bees/ant_fire.gif">
            <br />
            <br />
            Fire Thrower
            <br />
            <em>Food cost:</em> 5
            <br />
            <em>Armor:</em> 3
        </td>
        <td>
            <img src="/assets/images/ant_bees/ant_hungry.gif">
            <br />
            <br />
            Hungry
            <br />
            <em>Food cost:</em> 4
            <br />
            <em>Armor:</em> 1
        </td>
    </tr>
    <tr>
        <td>
            <img src="/assets/images/ant_bees/ant_ninja.gif">
            <br />
            <br />
            Ninja
            <br />
            <em>Food cost:</em> 5
            <br />
            <em>Armor:</em> 1
        </td>
        <td>
            <img src="/assets/images/ant_bees/ant_wall.gif">
            <br />
            <br />
            Wall Defender
            <br />
            <em>Food cost:</em> 4
            <br />
            <em>Armor:</em> 4
        </td>
        <td>
            <img src="/assets/images/ant_bees/ant_bodyguard.gif">
            <br />
            <br />
            Body Guard
            <br />
            <em>Food cost:</em> 4
            <br />
            <em>Armor:</em> 2
        </td>
        <td>
            <img src="/assets/images/ant_bees/ant_tank.gif">
            <br />
            <br />
            Tank Operator
            <br />
            <em>Food cost:</em> 6
            <br />
            <em>Armor:</em> 2
        </td>
        <td>
            <img src="/assets/images/ant_bees/ant_scuba.gif">
            <br />
            <br />
            Scuba Thrower
            <br />
            <em>Food cost:</em> 6
            <br />
            <em>Armor:</em> 1
        </td>
        <td>
            <img src="/assets/images/ant_bees/ant_queen.gif">
            <br />
            <br />
            The Queen
            <br />
            <em>Food cost:</em> 7
            <br />
            <em>Armor:</em> 1
        </td>
    </tr>
    <tr>
        <td>
            <img src="/assets/images/ant_bees/ant_laser.gif">
            <br />
            <br />
            Laser Shooter
            <br />
            <em>Food cost:</em> 10
            <br />
            <em>Armor:</em> 1
        </td>
    </tr>
</table>

# Final result

Here is the demo of the game once all of the ant combatants have been
implemented.

![](/assets/images/ant_bees/gameplay.gif)

