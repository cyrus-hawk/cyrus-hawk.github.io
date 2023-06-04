---

name: Virus drug treatment simulation

description: >
    Treatment of viruses, such as HIV and H1N1, represents a significant
    challenge to modern medicine because of their ability to evolve...

title: Virus drug treatment simulation

---

# Introduction

As you may know from introductory biology classes, the traits of an
organism are determined by its genetic code. When organisms reproduce,
their offspring inherit genetic information from their parents. This
genetic information can be modified through the mixing of the parents'
genetic material or through mutations during genome replication,
introducing diversity into a population.

Viruses 🦠 are no exception. Two characteristics of viruses make them
particularly challenging to treat. First, their replication mechanism
often lacks error-checking mechanisms found in more complex organisms,
leading to a higher rate of mutation. Second, viruses replicate at an
extremely rapid pace (orders of magnitude faster than humans).
Therefore, while we usually associate evolution with long time scales,
virus populations can undergo significant evolutionary changes within
a single patient during treatment.

These two characteristics enable virus populations to quickly acquire
genetic resistance to therapy. In this project, I will utilize
stochastic simulations to explore the impact of introducing drugs 💊
on the virus population. The aim is to determine the most effective
approach to address these treatment challenges within a simplified
model.

# Implementation

To simulate a virus-infected patient within the digital realm, I have
utilized my expertise in stochastic simulation. This approach entails
the use of random variables and probabilistic processes to model the
inherent uncertainty and randomness present in a given process. It
proves particularly valuable when simulating the rapid mutations
observed in viruses.

# Final result

### A patient **without** any treatment

Two simulations are required to assess the effectiveness of the drugs.
The first simulation involves infecting a patient with the virus and
not administering any drugs. The following section illustrates the
details of the first simulation.

![](/assets/images/virus_drug_stochastic_simulation/no_treatment.gif)

The x-axis represents the time unit (e.g., days), while the y-axis
represents the average population of the viruses. The simulation
indicates that as time progresses, the virus population in the
patient's body reaches its maximum limit.

### A patient **with** treatment

To observe the impact of the drugs on the viruses, the patient
initiates drug treatment starting from day 150. It becomes evident
that as the patient begins the medication, the virus population
experiences a significant decrease. However, it should be noted that
certain viruses exhibit resistance to the treatment and remain
unaffected (indicated by the <span style="color: orange;">orange</span>
line). Unfortunately, due to the inherent traits of the viruses, they
eventually develop resistance to the drug through mutation, rendering
the treatment ineffective. This necessitates the need for a new
treatment. The following presents the outcomes in detail.

![](/assets/images/virus_drug_stochastic_simulation/treatment.gif)
