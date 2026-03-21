# Информация

Покупаю сервера у разных хостингов для запуска прокси для Telegram

Для прокси используется https://github.com/telemt/telemt
[Конфиг](https://github.com/Dimasssss/free_telemt_servers/blob/main/config.toml) используемый на всех серверах.

### **Принимаю донаты криптой для добавления и продления серверов:**
- TON (Можно отправлять TON и USDT в сети TON):
```
UQAyIvWts4-gC0b5ouoy_JNDfBEe337c7oOBqpGXFB8fJUzB
```
### **Спасибо:**
- Ivan Morozov - 20$

Можете писать свой ник в коментарии к переводу

### [Итог по хостингам](Reviews.md)

---

## NKtelecom
- Локация: Netherlands - Amsterdam
- Тариф: AMS-CLOUD-60
- Краткое описание тарифа: 4 vCore, 4 Gb ram, 1 Gbit/s
- Цена в месяц: 4.99$
- Оплачен до: 26 марта
- Ссылка:
```bash
tg://proxy?server=s1.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## psb.hosting (2 сервера)
- Локация: Finland
- Тариф: FI-200
- Краткое описание тарифа: 2 vCore, 4 Gb ram, 1 Gbit/s
- Цена в месяц: 12$
- Оплачен до: 25 марта
- Ссылка:
```bash
tg://proxy?server=s2.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## koara.io
- Локация: Германия, Франкфурт-на-Майне
- Тариф: DE-2
- Краткое описание тарифа: 2 vCore, 4 Gb ram, 1 Gbit/s
- Цена в месяц: 639 RUB
- Оплачен до: 25 марта
- Ссылка:
```bash
tg://proxy?server=s3.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## landvps.ru
- Локация: Финляндия
- Тариф: FL-2
- Краткое описание тарифа: 2 vCore, 2 Gb ram, 200 Mbps/s
- Цена в месяц: 800 RUB
- Оплачен до: 26 марта
- Ссылка:
```bash
tg://proxy?server=s4.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## rdp-onedash.ru (2 сервера)
- Локация: Нидерланды
- Тариф: Mini
- Краткое описание тарифа: 2 vCore, 2 Gb ram, 1 Gbit/s
- Цена в месяц: 844 RUB
- Оплачен до: 14 апреля
- Ссылка:
```bash
tg://proxy?server=s5.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## hostvds.com
- Локация: Нидерланды, Амстердам
- Тариф: Burstable
- Краткое описание тарифа: 2 vCore, 4 Gb ram, 10 Gbit/s
- Цена в месяц: €7.98
- Оплачен до: 13 апреля
- Ссылка:
```bash
tg://proxy?server=s6.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## 4vps.su (2 сервера)
- Локация: Польша, Варшава
- Тариф: PL-cx21
- Краткое описание тарифа: 2 vCore, 4 Gb ram, 2 Gbit/s
- Цена в месяц: 770 RUB
- Оплачен до: 16 апреля
- Ссылка:
```bash
tg://proxy?server=s7.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

# Server Metrics 2026-03-21 15:12:47 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 67013.9 (18h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2345601
telemt_connections_bad_total 116529
telemt_connections_current 1340
telemt_connections_me_current 1340
telemt_relay_adaptive_promotions_total 3
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 76776
telemt_upstream_connect_attempt_total 28684
telemt_upstream_connect_success_total 28559
telemt_upstream_connect_fail_total 82
telemt_upstream_connect_attempts_per_request{bucket="1"} 28641
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11891
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16580
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 32
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 56
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 82
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 98
telemt_me_reconnect_attempts_total 1647
telemt_me_reconnect_success_total 658
telemt_me_reader_eof_total 632
telemt_me_idle_close_by_peer_total 632
telemt_me_route_drop_no_conn_total 1983140
telemt_me_route_drop_channel_closed_total 624
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1877898
telemt_me_writer_pick_total{mode="p2c",result="full"} 26
telemt_me_endpoint_quarantine_total 472
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 10
telemt_me_single_endpoint_outage_reconnect_success_total 9
telemt_me_single_endpoint_quarantine_bypass_total 10
telemt_me_single_endpoint_shadow_rotate_total 524
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 44
telemt_desync_total 7347
telemt_desync_full_logged_total 2543
telemt_desync_suppressed_total 4804
telemt_desync_frames_bucket_total{bucket="1_2"} 1607
telemt_desync_frames_bucket_total{bucket="3_10"} 2792
telemt_desync_frames_bucket_total{bucket="gt_10"} 2948
telemt_pool_swap_total 72
telemt_pool_force_close_total 2186
telemt_pool_stale_pick_total 28
telemt_me_writer_close_signal_drop_total 497
telemt_me_draining_writers_reap_progress_total 22919
telemt_me_writer_removed_unexpected_total 610
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1971
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 21342
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 6
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2070
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 116
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 20733
telemt_me_writer_teardown_success_total{mode="normal"} 23313
telemt_me_writer_teardown_noop_total 22925
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 38494
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 39952
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 41235
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 43400
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 45143
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 45976
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 46210
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 46233
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 46237
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 46238
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 46238
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 46238
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 46238
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 215.392050
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 46238
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 497
telemt_me_refill_failed_total 54
telemt_me_writer_restored_same_endpoint_total 566
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 39
telemt_user_connections_total{user="hello"} 1879457
telemt_user_connections_current{user="hello"} 1340
telemt_user_octets_from_client{user="hello"} 26770849957 (24.93 GB)
telemt_user_octets_to_client{user="hello"} 467437083670 (435.33 GB)
telemt_user_msgs_from_client{user="hello"} 7227
telemt_user_msgs_to_client{user="hello"} 6949
telemt_user_unique_ips_current{user="hello"} 556
telemt_user_unique_ips_recent_window{user="hello"} 272
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 67.1 (0h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6057
telemt_connections_bad_total 20
telemt_connections_current 2607
telemt_connections_me_current 2607
telemt_handshake_timeouts_total 2
telemt_upstream_connect_attempt_total 116
telemt_upstream_connect_success_total 103
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 113
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 57
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 45
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_reconnect_attempts_total 2
telemt_me_reconnect_success_total 3
telemt_me_route_drop_no_conn_total 2836
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5618
telemt_me_endpoint_quarantine_total 6
telemt_me_single_endpoint_shadow_rotate_total 8
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 43
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 45
telemt_desync_total 11
telemt_desync_full_logged_total 7
telemt_desync_suppressed_total 4
telemt_desync_frames_bucket_total{bucket="1_2"} 2
telemt_desync_frames_bucket_total{bucket="3_10"} 7
telemt_desync_frames_bucket_total{bucket="gt_10"} 2
telemt_me_draining_writers_reap_progress_total 22
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 22
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 22
telemt_me_writer_teardown_success_total{mode="normal"} 22
telemt_me_writer_teardown_noop_total 22
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 44
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 44
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 44
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 44
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 44
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 44
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 44
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 44
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 44
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 44
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 44
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 44
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 44
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.000368
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 44
telemt_user_connections_total{user="hello"} 5618
telemt_user_connections_current{user="hello"} 2607
telemt_user_octets_from_client{user="hello"} 15527132 (14.81 MB)
telemt_user_octets_to_client{user="hello"} 349748136 (333.55 MB)
telemt_user_unique_ips_current{user="hello"} 989
telemt_user_unique_ips_recent_window{user="hello"} 1301
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 67013.1 (18h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4671000
telemt_connections_bad_total 412774
telemt_connections_current 5507
telemt_connections_me_current 5507
telemt_handshake_timeouts_total 170286
telemt_upstream_connect_attempt_total 24927
telemt_upstream_connect_success_total 24874
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 24879
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11223
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13546
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 99
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 1146
telemt_me_reconnect_success_total 573
telemt_me_reader_eof_total 577
telemt_me_idle_close_by_peer_total 577
telemt_me_route_drop_no_conn_total 2585326
telemt_me_route_drop_channel_closed_total 44
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3824352
telemt_me_endpoint_quarantine_total 424
telemt_me_single_endpoint_outage_enter_total 4
telemt_me_single_endpoint_outage_exit_total 4
telemt_me_single_endpoint_outage_reconnect_attempt_total 4
telemt_me_single_endpoint_outage_reconnect_success_total 4
telemt_me_single_endpoint_quarantine_bypass_total 4
telemt_me_single_endpoint_shadow_rotate_total 508
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 43
telemt_desync_total 15649
telemt_desync_full_logged_total 5278
telemt_desync_suppressed_total 10371
telemt_desync_frames_bucket_total{bucket="1_2"} 3340
telemt_desync_frames_bucket_total{bucket="3_10"} 6169
telemt_desync_frames_bucket_total{bucket="gt_10"} 6140
telemt_pool_swap_total 71
telemt_pool_force_close_total 2298
telemt_pool_stale_pick_total 17
telemt_me_writer_close_signal_drop_total 362
telemt_me_draining_writers_reap_progress_total 22599
telemt_me_writer_removed_unexpected_total 558
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1982
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 20957
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 32
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2102
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 196
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 20301
telemt_me_writer_teardown_success_total{mode="normal"} 22939
telemt_me_writer_teardown_noop_total 22631
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 41888
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 43109
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 43787
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 44655
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 45174
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 45464
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 45569
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 45570
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 45570
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 45570
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 45570
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 45570
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 45570
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 77.805521
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 45570
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 362
telemt_me_refill_failed_total 30
telemt_me_writer_restored_same_endpoint_total 515
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 8
telemt_me_writer_removed_unexpected_minus_restored_total 38
telemt_user_connections_total{user="hello"} 3819657
telemt_user_connections_current{user="hello"} 5507
telemt_user_octets_from_client{user="hello"} 62103437136 (57.84 GB)
telemt_user_octets_to_client{user="hello"} 1267192324276 (1.15 TB)
telemt_user_unique_ips_current{user="hello"} 2023
telemt_user_unique_ips_recent_window{user="hello"} 702
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 67013.2 (18h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3809581
telemt_connections_bad_total 413084
telemt_connections_current 4204
telemt_connections_me_current 4204
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 137414
telemt_upstream_connect_attempt_total 29350
telemt_upstream_connect_success_total 29069
telemt_upstream_connect_fail_total 139
telemt_upstream_connect_attempts_per_request{bucket="1"} 29208
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14989
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13569
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 27
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 484
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 139
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 76
telemt_me_reconnect_attempts_total 1377
telemt_me_reconnect_success_total 598
telemt_me_reader_eof_total 558
telemt_me_idle_close_by_peer_total 558
telemt_me_route_drop_no_conn_total 1195440
telemt_me_route_drop_channel_closed_total 97
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2786761
telemt_me_endpoint_quarantine_total 435
telemt_me_single_endpoint_outage_enter_total 7
telemt_me_single_endpoint_outage_exit_total 7
telemt_me_single_endpoint_outage_reconnect_attempt_total 7
telemt_me_single_endpoint_outage_reconnect_success_total 7
telemt_me_single_endpoint_quarantine_bypass_total 7
telemt_me_single_endpoint_shadow_rotate_total 511
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 48
telemt_desync_total 12950
telemt_desync_full_logged_total 4362
telemt_desync_suppressed_total 8588
telemt_desync_frames_bucket_total{bucket="1_2"} 3239
telemt_desync_frames_bucket_total{bucket="3_10"} 5001
telemt_desync_frames_bucket_total{bucket="gt_10"} 4710
telemt_pool_swap_total 73
telemt_pool_force_close_total 2106
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 208
telemt_me_draining_writers_reap_progress_total 21812
telemt_me_writer_removed_unexpected_total 542
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1883
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 20473
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1960
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 146
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 19706
telemt_me_writer_teardown_success_total{mode="normal"} 22356
telemt_me_writer_teardown_noop_total 21813
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 42485
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 43385
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 43641
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 43929
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 44089
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 44167
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 44169
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 44169
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 44169
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 44169
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 44169
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 44169
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 44169
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 20.456104
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 44169
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 208
telemt_me_refill_failed_total 41
telemt_me_writer_restored_same_endpoint_total 502
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 20
telemt_me_writer_removed_unexpected_minus_restored_total 32
telemt_user_connections_total{user="hello"} 2786628
telemt_user_connections_current{user="hello"} 4204
telemt_user_octets_from_client{user="hello"} 52547207745 (48.94 GB)
telemt_user_octets_to_client{user="hello"} 1299960841715 (1.18 TB)
telemt_user_msgs_from_client{user="hello"} 39229
telemt_user_msgs_to_client{user="hello"} 49019
telemt_user_unique_ips_current{user="hello"} 1498
telemt_user_unique_ips_recent_window{user="hello"} 552
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 66977.3 (18h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3738727
telemt_connections_bad_total 390490
telemt_connections_current 3621
telemt_connections_me_current 3621
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 111872
telemt_upstream_connect_attempt_total 34577
telemt_upstream_connect_success_total 34342
telemt_upstream_connect_fail_total 133
telemt_upstream_connect_attempts_per_request{bucket="1"} 34475
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18270
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14931
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 289
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 852
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 133
telemt_me_keepalive_timeout_total 50
telemt_me_reconnect_attempts_total 1382
telemt_me_reconnect_success_total 650
telemt_me_reader_eof_total 590
telemt_me_idle_close_by_peer_total 590
telemt_me_route_drop_no_conn_total 1301355
telemt_me_route_drop_channel_closed_total 35
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2770093
telemt_me_endpoint_quarantine_total 482
telemt_me_single_endpoint_outage_enter_total 6
telemt_me_single_endpoint_outage_exit_total 6
telemt_me_single_endpoint_outage_reconnect_attempt_total 6
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 6
telemt_me_single_endpoint_shadow_rotate_total 502
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 45
telemt_desync_total 12689
telemt_desync_full_logged_total 4246
telemt_desync_suppressed_total 8443
telemt_desync_frames_bucket_total{bucket="1_2"} 3178
telemt_desync_frames_bucket_total{bucket="3_10"} 4777
telemt_desync_frames_bucket_total{bucket="gt_10"} 4734
telemt_pool_swap_total 71
telemt_pool_force_close_total 2035
telemt_pool_stale_pick_total 1618
telemt_me_writer_close_signal_drop_total 232
telemt_me_draining_writers_reap_progress_total 23240
telemt_me_writer_removed_unexpected_total 562
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1970
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 21868
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1856
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 179
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 21205
telemt_me_writer_teardown_success_total{mode="normal"} 23838
telemt_me_writer_teardown_noop_total 23245
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 45801
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 46547
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 46757
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 46972
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 47072
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 47083
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 47083
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 47083
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 47083
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 47083
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 47083
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 47083
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 47083
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 11.505362
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 47083
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 232
telemt_me_refill_failed_total 41
telemt_me_writer_restored_same_endpoint_total 560
telemt_me_writer_restored_fallback_total 3
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 42
telemt_user_connections_total{user="hello"} 2773982
telemt_user_connections_current{user="hello"} 3621
telemt_user_octets_from_client{user="hello"} 59063001093 (55.01 GB)
telemt_user_octets_to_client{user="hello"} 1286313793048 (1.17 TB)
telemt_user_msgs_from_client{user="hello"} 42436
telemt_user_msgs_to_client{user="hello"} 111361
telemt_user_unique_ips_current{user="hello"} 1415
telemt_user_unique_ips_recent_window{user="hello"} 556
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 67016.4 (18h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 12825457
telemt_connections_bad_total 834887
telemt_connections_current 5990
telemt_connections_me_current 5990
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 391580
telemt_upstream_connect_attempt_total 115755
telemt_upstream_connect_success_total 105869
telemt_upstream_connect_fail_total 8851
telemt_upstream_connect_attempts_per_request{bucket="1"} 114720
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 74262
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 25456
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 792
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5359
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8851
telemt_me_keepalive_timeout_total 102
telemt_me_reconnect_attempts_total 3856
telemt_me_reconnect_success_total 1397
telemt_me_reader_eof_total 976
telemt_me_idle_close_by_peer_total 975
telemt_me_route_drop_no_conn_total 24642041
telemt_me_route_drop_channel_closed_total 84
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 10538421
telemt_me_endpoint_quarantine_total 518
telemt_me_single_endpoint_outage_enter_total 77
telemt_me_single_endpoint_outage_exit_total 77
telemt_me_single_endpoint_outage_reconnect_attempt_total 173
telemt_me_single_endpoint_outage_reconnect_success_total 37
telemt_me_single_endpoint_quarantine_bypass_total 173
telemt_me_single_endpoint_shadow_rotate_total 523
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 44
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 45
telemt_desync_total 18704
telemt_desync_full_logged_total 5871
telemt_desync_suppressed_total 12833
telemt_desync_frames_bucket_total{bucket="1_2"} 4053
telemt_desync_frames_bucket_total{bucket="3_10"} 8226
telemt_desync_frames_bucket_total{bucket="gt_10"} 6425
telemt_pool_swap_total 68
telemt_pool_force_close_total 2213
telemt_pool_stale_pick_total 5
telemt_me_writer_close_signal_drop_total 482
telemt_me_draining_writers_reap_progress_total 21553
telemt_me_writer_removed_unexpected_total 1337
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2852
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 19829
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 11
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1854
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 359
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 19340
telemt_me_writer_teardown_success_total{mode="normal"} 22681
telemt_me_writer_teardown_noop_total 21565
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 39983
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 41483
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 42381
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 43403
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 43992
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 44194
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 44227
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 44229
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 44232
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 44237
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 44237
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 44241
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 44246
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 170.618853
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 44246
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 482
telemt_me_refill_failed_total 87
telemt_me_writer_restored_same_endpoint_total 974
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 113
telemt_me_writer_removed_unexpected_minus_restored_total 353
telemt_user_connections_total{user="hello"} 10614361
telemt_user_connections_current{user="hello"} 5990
telemt_user_octets_from_client{user="hello"} 75881310549 (70.67 GB)
telemt_user_octets_to_client{user="hello"} 790883614613 (736.57 GB)
telemt_user_msgs_from_client{user="hello"} 231133
telemt_user_msgs_to_client{user="hello"} 542131
telemt_user_unique_ips_current{user="hello"} 2134
telemt_user_unique_ips_recent_window{user="hello"} 1233
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 66984.2 (18h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3752206
telemt_connections_bad_total 418382
telemt_connections_current 4324
telemt_connections_me_current 4324
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 81365
telemt_upstream_connect_attempt_total 28264
telemt_upstream_connect_success_total 27954
telemt_upstream_connect_fail_total 266
telemt_upstream_connect_attempts_per_request{bucket="1"} 28220
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13339
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14541
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 73
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 266
telemt_me_reconnect_attempts_total 2681
telemt_me_reconnect_success_total 976
telemt_me_reader_eof_total 970
telemt_me_idle_close_by_peer_total 970
telemt_me_route_drop_no_conn_total 1581658
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 34
telemt_me_route_drop_queue_full_profile_total{profile="high"} 34
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2889429
telemt_me_endpoint_quarantine_total 415
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 11
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 11
telemt_me_single_endpoint_shadow_rotate_total 504
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 25
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 45
telemt_desync_total 13668
telemt_desync_full_logged_total 4757
telemt_desync_suppressed_total 8911
telemt_desync_frames_bucket_total{bucket="1_2"} 2660
telemt_desync_frames_bucket_total{bucket="3_10"} 5392
telemt_desync_frames_bucket_total{bucket="gt_10"} 5616
telemt_pool_swap_total 67
telemt_pool_force_close_total 1948
telemt_pool_stale_pick_total 54
telemt_me_writer_close_signal_drop_total 196
telemt_me_draining_writers_reap_progress_total 23731
telemt_me_writer_removed_unexpected_total 941
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2336
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 22368
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1693
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 255
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 21783
telemt_me_writer_teardown_success_total{mode="normal"} 24704
telemt_me_writer_teardown_noop_total 23732
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 47827
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 48219
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 48393
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 48436
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 48436
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 48436
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 48436
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 48436
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 48436
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 48436
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 48436
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 48436
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 48436
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.380576
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 48436
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 196
telemt_me_refill_failed_total 93
telemt_me_writer_restored_same_endpoint_total 837
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20
telemt_me_writer_removed_unexpected_minus_restored_total 94
telemt_user_connections_total{user="hello"} 2873010
telemt_user_connections_current{user="hello"} 4324
telemt_user_octets_from_client{user="hello"} 75299221744 (70.13 GB)
telemt_user_octets_to_client{user="hello"} 1198735737326 (1.09 TB)
telemt_user_msgs_from_client{user="hello"} 7339
telemt_user_msgs_to_client{user="hello"} 11522
telemt_user_unique_ips_current{user="hello"} 1591
telemt_user_unique_ips_recent_window{user="hello"} 752
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 3819.7 (1h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 630980
telemt_connections_bad_total 14866
telemt_connections_current 3183
telemt_connections_me_current 3183
telemt_handshake_timeouts_total 309260
telemt_upstream_connect_attempt_total 1488
telemt_upstream_connect_success_total 1455
telemt_upstream_connect_fail_total 27
telemt_upstream_connect_attempts_per_request{bucket="1"} 1482
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 670
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 770
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 15
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 27
telemt_me_reconnect_attempts_total 201
telemt_me_reconnect_success_total 72
telemt_me_reader_eof_total 63
telemt_me_idle_close_by_peer_total 63
telemt_me_route_drop_no_conn_total 323201
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 288053
telemt_me_endpoint_quarantine_total 17
telemt_me_single_endpoint_outage_enter_total 1
telemt_me_single_endpoint_outage_exit_total 1
telemt_me_single_endpoint_outage_reconnect_attempt_total 1
telemt_me_single_endpoint_outage_reconnect_success_total 1
telemt_me_single_endpoint_quarantine_bypass_total 1
telemt_me_single_endpoint_shadow_rotate_total 34
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 43
telemt_desync_total 1309
telemt_desync_full_logged_total 425
telemt_desync_suppressed_total 884
telemt_desync_frames_bucket_total{bucket="1_2"} 220
telemt_desync_frames_bucket_total{bucket="3_10"} 503
telemt_desync_frames_bucket_total{bucket="gt_10"} 586
telemt_pool_swap_total 3
telemt_pool_force_close_total 116
telemt_me_writer_close_signal_drop_total 9
telemt_me_draining_writers_reap_progress_total 1216
telemt_me_writer_removed_unexpected_total 64
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 135
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 1145
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 78
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 38
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 1100
telemt_me_writer_teardown_success_total{mode="normal"} 1280
telemt_me_writer_teardown_noop_total 1216
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 2437
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 2454
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 2478
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 2496
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 2496
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 2496
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 2496
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 2496
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 2496
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 2496
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 2496
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 2496
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 2496
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.499746
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 2496
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 9
telemt_me_refill_failed_total 8
telemt_me_writer_restored_same_endpoint_total 63
telemt_me_async_recovery_trigger_total 4
telemt_me_writer_removed_unexpected_minus_restored_total 1
telemt_user_connections_total{user="hello"} 287614
telemt_user_connections_current{user="hello"} 3183
telemt_user_octets_from_client{user="hello"} 8609276808 (8.02 GB)
telemt_user_octets_to_client{user="hello"} 99137589576 (92.33 GB)
telemt_user_unique_ips_current{user="hello"} 1226
telemt_user_unique_ips_recent_window{user="hello"} 853
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 64969.7 (18h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1193234
telemt_connections_bad_total 137871
telemt_connections_current 869
telemt_connections_me_current 869
telemt_handshake_timeouts_total 420531
telemt_upstream_connect_attempt_total 30529
telemt_upstream_connect_success_total 30522
telemt_upstream_connect_attempts_per_request{bucket="1"} 30522
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12522
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17902
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 98
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 1308
telemt_me_reconnect_success_total 541
telemt_me_reader_eof_total 539
telemt_me_idle_close_by_peer_total 539
telemt_me_route_drop_no_conn_total 261679
telemt_me_route_drop_channel_closed_total 23
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 561651
telemt_me_endpoint_quarantine_total 586
telemt_me_single_endpoint_outage_enter_total 7
telemt_me_single_endpoint_outage_exit_total 7
telemt_me_single_endpoint_outage_reconnect_attempt_total 7
telemt_me_single_endpoint_outage_reconnect_success_total 6
telemt_me_single_endpoint_quarantine_bypass_total 7
telemt_me_single_endpoint_shadow_rotate_total 543
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 10
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 37
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 46
telemt_desync_total 3556
telemt_desync_full_logged_total 1296
telemt_desync_suppressed_total 2260
telemt_desync_frames_bucket_total{bucket="1_2"} 652
telemt_desync_frames_bucket_total{bucket="3_10"} 1276
telemt_desync_frames_bucket_total{bucket="gt_10"} 1628
telemt_pool_swap_total 71
telemt_pool_force_close_total 1623
telemt_pool_stale_pick_total 7
telemt_me_writer_close_signal_drop_total 110
telemt_me_draining_writers_reap_progress_total 27328
telemt_me_writer_removed_unexpected_total 512
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2045
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 25808
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1600
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 23
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 25705
telemt_me_writer_teardown_success_total{mode="normal"} 27853
telemt_me_writer_teardown_noop_total 27328
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 54522
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 54975
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 55122
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 55173
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 55181
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 55181
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 55181
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 55181
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 55181
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 55181
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 55181
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 55181
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 55181
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 4.061520
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 55181
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 110
telemt_me_refill_failed_total 40
telemt_me_writer_restored_same_endpoint_total 450
telemt_me_writer_restored_fallback_total 5
telemt_me_writer_removed_unexpected_minus_restored_total 57
telemt_user_connections_total{user="hello"} 561322
telemt_user_connections_current{user="hello"} 869
telemt_user_octets_from_client{user="hello"} 11517172523 (10.73 GB)
telemt_user_octets_to_client{user="hello"} 214222548005 (199.51 GB)
telemt_user_msgs_from_client{user="hello"} 804
telemt_user_msgs_to_client{user="hello"} 1943
telemt_user_unique_ips_current{user="hello"} 339
telemt_user_unique_ips_recent_window{user="hello"} 129
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 66988.3 (18h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4115093
telemt_connections_bad_total 374617
telemt_connections_current 4787
telemt_connections_me_current 4787
telemt_handshake_timeouts_total 136100
telemt_upstream_connect_attempt_total 26769
telemt_upstream_connect_success_total 26657
telemt_upstream_connect_fail_total 77
telemt_upstream_connect_attempts_per_request{bucket="1"} 26734
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13225
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13395
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 36
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 77
telemt_me_reconnect_attempts_total 1144
telemt_me_reconnect_success_total 611
telemt_me_reader_eof_total 577
telemt_me_idle_close_by_peer_total 577
telemt_me_route_drop_no_conn_total 1251335
telemt_me_route_drop_channel_closed_total 33
telemt_me_route_drop_queue_full_total 10
telemt_me_route_drop_queue_full_profile_total{profile="high"} 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3274653
telemt_me_endpoint_quarantine_total 492
telemt_me_single_endpoint_outage_enter_total 8
telemt_me_single_endpoint_outage_exit_total 8
telemt_me_single_endpoint_outage_reconnect_attempt_total 8
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 8
telemt_me_single_endpoint_shadow_rotate_total 513
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 26
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 44
telemt_desync_total 12862
telemt_desync_full_logged_total 4243
telemt_desync_suppressed_total 8619
telemt_desync_frames_bucket_total{bucket="1_2"} 3043
telemt_desync_frames_bucket_total{bucket="3_10"} 4794
telemt_desync_frames_bucket_total{bucket="gt_10"} 5025
telemt_pool_swap_total 74
telemt_pool_force_close_total 1939
telemt_pool_stale_pick_total 2
telemt_me_writer_close_signal_drop_total 222
telemt_me_draining_writers_reap_progress_total 23994
telemt_me_writer_removed_unexpected_total 566
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1919
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 22642
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1896
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 43
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 22055
telemt_me_writer_teardown_success_total{mode="normal"} 24561
telemt_me_writer_teardown_noop_total 23994
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 47822
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 48303
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 48393
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 48511
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 48555
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 48555
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 48555
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 48555
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 48555
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 48555
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 48555
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 48555
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 48555
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 5.693399
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 48555
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 222
telemt_me_refill_failed_total 27
telemt_me_writer_restored_same_endpoint_total 542
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 19
telemt_user_connections_total{user="hello"} 3266344
telemt_user_connections_current{user="hello"} 4787
telemt_user_octets_from_client{user="hello"} 66486004492 (61.92 GB)
telemt_user_octets_to_client{user="hello"} 1540840288044 (1.40 TB)
telemt_user_unique_ips_current{user="hello"} 1707
telemt_user_unique_ips_recent_window{user="hello"} 679
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 66985.1 (18h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3661998
telemt_connections_bad_total 320499
telemt_connections_current 3807
telemt_connections_me_current 3807
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 110594
telemt_upstream_connect_attempt_total 43264
telemt_upstream_connect_success_total 42972
telemt_upstream_connect_fail_total 241
telemt_upstream_connect_attempts_per_request{bucket="1"} 43213
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26570
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15285
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 517
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 600
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 241
telemt_me_reconnect_attempts_total 3828
telemt_me_reconnect_success_total 836
telemt_me_reader_eof_total 733
telemt_me_idle_close_by_peer_total 733
telemt_me_seq_mismatch_total 31
telemt_me_route_drop_no_conn_total 1327581
telemt_me_route_drop_channel_closed_total 100
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2947834
telemt_me_endpoint_quarantine_total 559
telemt_me_single_endpoint_outage_enter_total 19
telemt_me_single_endpoint_outage_exit_total 19
telemt_me_single_endpoint_outage_reconnect_attempt_total 19
telemt_me_single_endpoint_outage_reconnect_success_total 19
telemt_me_single_endpoint_quarantine_bypass_total 19
telemt_me_single_endpoint_shadow_rotate_total 511
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 49
telemt_desync_total 11478
telemt_desync_full_logged_total 3899
telemt_desync_suppressed_total 7579
telemt_desync_frames_bucket_total{bucket="1_2"} 2855
telemt_desync_frames_bucket_total{bucket="3_10"} 4270
telemt_desync_frames_bucket_total{bucket="gt_10"} 4353
telemt_pool_swap_total 72
telemt_pool_force_close_total 1878
telemt_pool_stale_pick_total 358
telemt_me_writer_close_signal_drop_total 209
telemt_me_draining_writers_reap_progress_total 23425
telemt_me_writer_removed_unexpected_total 745
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2278
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 21924
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1724
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 154
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 21547
telemt_me_writer_teardown_success_total{mode="normal"} 24202
telemt_me_writer_teardown_noop_total 23426
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 46770
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 47307
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 47494
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 47619
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 47628
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 47628
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 47628
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 47628
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 47628
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 47628
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 47628
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 47628
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 47628
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 5.959665
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 47628
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 209
telemt_me_refill_failed_total 170
telemt_me_writer_restored_same_endpoint_total 648
telemt_me_writer_restored_fallback_total 40
telemt_me_async_recovery_trigger_total 57
telemt_me_writer_removed_unexpected_minus_restored_total 57
telemt_user_connections_total{user="hello"} 2956381
telemt_user_connections_current{user="hello"} 3807
telemt_user_octets_from_client{user="hello"} 53195756761 (49.54 GB)
telemt_user_octets_to_client{user="hello"} 1268152210828 (1.15 TB)
telemt_user_msgs_from_client{user="hello"} 75721
telemt_user_msgs_to_client{user="hello"} 209236
telemt_user_unique_ips_current{user="hello"} 1488
telemt_user_unique_ips_recent_window{user="hello"} 553
```