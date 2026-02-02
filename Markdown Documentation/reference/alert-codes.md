# Alert Codes Quick Reference

**[Home](../index.md) > [Reference](index.md) > Alert Codes**

---

## Overview

This page provides a condensed quick reference of all InnoPick alert codes. For detailed resolution procedures, see the [Alert Reference Guide](../troubleshooting/alert-reference.md).

---

## How to Use This Reference

1. **Find your alert code** in the appropriate category below
2. **Read the brief description**
3. **Click the link** to view detailed resolution procedures

---

## System Alerts

| Code | Description | Details |
|------|-------------|---------|
| **99** | ServoDrive timeout during startup | [View Details](../troubleshooting/alert-reference.md#99---servodrive-time-out-fault-occurred-during-start-up-sys_flt) |
| **400-401** | Communication loopback timeout | [View Details](../troubleshooting/alert-reference.md#400--401---communication-loopback-timeout-sys_flt) |
| **570** | UPS power supply on battery | [View Details](../troubleshooting/alert-reference.md#570---ups-power-supply-on-battery-power-loss) |
| **572** | Air pressure switch off | [View Details](../troubleshooting/alert-reference.md#572---air-pressure-switch-off---no-air-in-system) |
| **573** | Murr module fault | [View Details](../troubleshooting/alert-reference.md#573---inputoutput-murr-module-fault-read-variable-murr_flt) |
| **791** | Motion control thread crashed | [View Details](../troubleshooting/alert-reference.md#791---motion-control-galil-thread-crashed-while-main-thread-was-waiting---critical-fault) |

---

## Storage and Dispense Alerts

| Code | Description | Details |
|------|-------------|---------|
| **109** | Photocell blocked after storing | [View Details](../troubleshooting/alert-reference.md#109---photocell-above-lane-was-still-blocked-after-the-end-of-the-storing-move) |
| **113** | Dispense case too far back | [View Details](../troubleshooting/alert-reference.md#113---buffer-lane-tried-to-dispense-a-case-but-the-case-was-too-far-back) |
| **115** | Dispense case too close to front | [View Details](../troubleshooting/alert-reference.md#115---buffer-lane-tried-to-dispense-a-case-but-the-case-was-too-close-to-the-front) |
| **117** | Dispense case seen too late | [View Details](../troubleshooting/alert-reference.md#117---buffer-lane-tried-to-dispense-a-case-but-the-case-was-too-far-back) |
| **119** | Photocell still blocked after dispensing | [View Details](../troubleshooting/alert-reference.md#119---photocell-still-blocked-after-dispensing) |
| **121** | No case detected during storing | [View Details](../troubleshooting/alert-reference.md#121---photocell-above-lane-never-detected-the-case-during-a-storing-move) |
| **123** | No case detected during dispensing | [View Details](../troubleshooting/alert-reference.md#123---photocell-above-lane-never-detected-the-case-during-a-dispense-move) |

---

## Pop-Up Mechanism Alerts

| Code | Description | Details |
|------|-------------|---------|
| **152** | Pop-up stayed down during store | [View Details](../troubleshooting/alert-reference.md#152---popup-stayed-down-during-store-300) |
| **153** | Pop-up stayed down during dispense | [View Details](../troubleshooting/alert-reference.md#153---popup-stayed-down-during-dispense-301) |
| **154** | Pop-up stayed up after dispense | [View Details](../troubleshooting/alert-reference.md#154---popup-stayed-up-after-dispense-301) |
| **155** | Pop-up never went down before store | [View Details](../troubleshooting/alert-reference.md#155---popup-never-went-down-before-store-300) |
| **156** | Pop-up never went down before dispense | [View Details](../troubleshooting/alert-reference.md#156---popup-never-went-down-before-dispense-301) |
| **525** | Pop-up reached final upper limit | [View Details](../troubleshooting/alert-reference.md#525---pop-up-shaft-reached-final-upper-limit---probably-did-not-engage-the-pop-up-mechanism) |

---

## Clutch Mechanism Alerts

| Code | Description | Details |
|------|-------------|---------|
| **310** | Clutch engagement fault | [View Details](../troubleshooting/alert-reference.md#310---clutch-fault-mechanical-engagement-was-not-successfully-completed-after-15-attempts) |
| **333** | Clutch sensor warning | [View Details](../troubleshooting/alert-reference.md#333---warning-actual-sensor-transition-was-not-seen-but-system-is-assuming-clutch-was-engaged-properly) |
| **334** | Clutch sensor off after transition | [View Details](../troubleshooting/alert-reference.md#334---clutch-fault-prox-sensor-off-after-mechanical-transition-probably-clutch-mechanism-bounce) |
| **340** | Clutch disengagement fault | [View Details](../troubleshooting/alert-reference.md#340---clutch-fault-mechanical-disengagement-was-not-successfully-completed-after-15-attempts) |

---

## Infeed Alerts

| Code | Description | Details |
|------|-------------|---------|
| **512** | Infeed middle photocell not blocked | [View Details](../troubleshooting/alert-reference.md#512---infeed-middle-photocell-was-not-blocked-during-an-infeed-case-move) |
| **515** | Unexpected case at infeed | [View Details](../troubleshooting/alert-reference.md#515---unexpected-case-entering-onto-the-infeed-belts) |
| **517** | Infeed case length too short | [View Details](../troubleshooting/alert-reference.md#517---infeed-cases-length-too-short) |

---

## Photocell and Sensor Alerts

| Code | Description | Details |
|------|-------------|---------|
| **709** | Photocell blocked (I/O check) | [View Details](../troubleshooting/alert-reference.md#709--719---photocell-blocked-plc-io-check-or-clutch-prox-sensor-off-during-routine-io-check) |
| **719** | Clutch prox sensor off (I/O check) | [View Details](../troubleshooting/alert-reference.md#709--719---photocell-blocked-plc-io-check-or-clutch-prox-sensor-off-during-routine-io-check) |

---

## Safety System Alerts

| Code | Description | Details |
|------|-------------|---------|
| **555** | E-Stop condition active | [View Details](../troubleshooting/alert-reference.md#555---e-stop-condition-active---safety-is-disarmed-door-opened-or-e-stop-pressed) |

---

## Outfeed Alerts (No Specific Codes)

| Description | Details |
|-------------|---------|
| Expecting case but none present at outfeed | [View Details](../troubleshooting/alert-reference.md#expecting-a-case-but-there-is-no-case-present-at-the-outfeed) |
| Not expecting case but there is one at outfeed | [View Details](../troubleshooting/alert-reference.md#not-expecting-a-case-but-there-is-a-case-at-the-outfeed) |

---

## Alert Categories Overview

### Critical Alerts (Require Immediate Attention)
- **555**: E-Stop active
- **310, 340**: Clutch faults
- **791**: Motion controller crash
- **572, 573**: System component faults

### Common Operational Alerts
- **119, 121, 123**: Storage/dispense issues
- **515, 517**: Infeed issues
- **709, 719**: Sensor monitoring

### Mechanical Alerts (May Require Maintenance)
- **152-156, 525**: Pop-up mechanism
- **310, 333-334, 340**: Clutch mechanism
- **99**: Servo drive

---

## Alert Pattern Recognition

### Symptom Alerts
These often indicate a larger issue or improper previous recovery:
- **121**: No case detected during store
- **123**: No case detected during dispense
- **Outfeed alerts**: Case present/not present mismatches

**Action:** Review [Alert Guidelines](../troubleshooting/alert-guidelines.md#guideline-4-determine-if-alert-is-stand-alone-or-a-symptom)

### Recurring Alerts
If the same alert occurs repeatedly:
- Underlying problem not fully resolved
- Check for mechanical issues
- Verify configuration settings
- May require maintenance intervention

### Cascading Alerts
Multiple different alerts in sequence:
- May be related to same root cause
- Resolve earliest alert first
- Verify physical matches [Inventory Graph](../main-screens/home-page.md#inventory-graph)
- May indicate offset tracking

---

## Quick Troubleshooting Guide

### Alert Won't Clear?
1. Underlying issue not resolved
2. Check physical conditions
3. Verify sensors are clear
4. Review alert message carefully
5. See [Alert Guidelines](../troubleshooting/alert-guidelines.md)

### Same Alert Keeps Repeating?
1. Root cause not identified
2. Temporary fix applied instead of permanent solution
3. Check for mechanical problems
4. Verify product configuration
5. Contact maintenance if persists

### Multiple Alerts at Once?
1. May be cascading from one root issue
2. Address earliest alert first
3. Verify inventory graph accuracy
4. May need to stop and reassess
5. Document pattern for maintenance

---

## Getting Help

### When to Escalate
Contact supervisor or maintenance when:
- Resolution steps don't work
- Physical damage observed
- Safety concerns present
- Unsure about proper resolution

### What to Document
When reporting alerts:
- Alert code and message
- Time of occurrence
- What was happening when alert occurred
- Steps already taken
- Whether issue is recurring
- Any patterns observed

---

## Related Topics

- [Alert Reference Guide](../troubleshooting/alert-reference.md) - Detailed resolution procedures
- [Alert Guidelines](../troubleshooting/alert-guidelines.md) - General troubleshooting principles
- [Alerts Page](../main-screens/alerts-page.md) - Viewing and managing alerts

---

**Navigation:** [← Reference Section](index.md) 