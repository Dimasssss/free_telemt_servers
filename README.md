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

# Server Metrics 2026-03-21 15:48:39 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 69166.7 (19h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2460666
telemt_connections_bad_total 140657
telemt_connections_current 1373
telemt_connections_me_current 1373
telemt_relay_adaptive_promotions_total 3
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 78255
telemt_upstream_connect_attempt_total 29397
telemt_upstream_connect_success_total 29267
telemt_upstream_connect_fail_total 87
telemt_upstream_connect_attempts_per_request{bucket="1"} 29354
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12133
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17044
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 33
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 57
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 87
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 98
telemt_me_reconnect_attempts_total 1698
telemt_me_reconnect_success_total 673
telemt_me_reader_eof_total 646
telemt_me_idle_close_by_peer_total 646
telemt_me_route_drop_no_conn_total 2120888
telemt_me_route_drop_channel_closed_total 652
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1963022
telemt_me_writer_pick_total{mode="p2c",result="full"} 26
telemt_me_endpoint_quarantine_total 482
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 10
telemt_me_single_endpoint_outage_reconnect_success_total 9
telemt_me_single_endpoint_quarantine_bypass_total 10
telemt_me_single_endpoint_shadow_rotate_total 538
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
telemt_me_writers_active_current 47
telemt_desync_total 7762
telemt_desync_full_logged_total 2678
telemt_desync_suppressed_total 5084
telemt_desync_frames_bucket_total{bucket="1_2"} 1697
telemt_desync_frames_bucket_total{bucket="3_10"} 2951
telemt_desync_frames_bucket_total{bucket="gt_10"} 3114
telemt_pool_swap_total 74
telemt_pool_force_close_total 2243
telemt_pool_stale_pick_total 28
telemt_me_writer_close_signal_drop_total 505
telemt_me_draining_writers_reap_progress_total 23565
telemt_me_writer_removed_unexpected_total 624
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2031
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 21942
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 6
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2124
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 119
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 21322
telemt_me_writer_teardown_success_total{mode="normal"} 23973
telemt_me_writer_teardown_noop_total 23571
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 39537
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 41050
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 42370
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 44619
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 46423
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 47276
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 47516
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 47539
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 47543
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 47544
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 47544
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 47544
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 47544
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 221.278267
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 47544
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 505
telemt_me_refill_failed_total 56
telemt_me_writer_restored_same_endpoint_total 576
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 41
telemt_user_connections_total{user="hello"} 1964459
telemt_user_connections_current{user="hello"} 1373
telemt_user_octets_from_client{user="hello"} 27834376409 (25.92 GB)
telemt_user_octets_to_client{user="hello"} 485816490298 (452.45 GB)
telemt_user_msgs_from_client{user="hello"} 7227
telemt_user_msgs_to_client{user="hello"} 6949
telemt_user_unique_ips_current{user="hello"} 528
telemt_user_unique_ips_recent_window{user="hello"} 231
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 292.3 (0h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9773
telemt_connections_bad_total 1043
telemt_connections_current 814
telemt_connections_me_current 814
telemt_handshake_timeouts_total 199
telemt_upstream_connect_attempt_total 172
telemt_upstream_connect_success_total 172
telemt_upstream_connect_attempts_per_request{bucket="1"} 172
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 84
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 87
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_route_drop_no_conn_total 3740
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 7915
telemt_me_endpoint_quarantine_total 6
telemt_me_single_endpoint_shadow_rotate_total 8
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 1
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
telemt_desync_total 32
telemt_desync_full_logged_total 16
telemt_desync_suppressed_total 16
telemt_desync_frames_bucket_total{bucket="1_2"} 8
telemt_desync_frames_bucket_total{bucket="3_10"} 16
telemt_desync_frames_bucket_total{bucket="gt_10"} 8
telemt_me_draining_writers_reap_progress_total 86
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 84
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 86
telemt_me_writer_teardown_success_total{mode="normal"} 86
telemt_me_writer_teardown_noop_total 86
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 171
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 172
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 172
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 172
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 172
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 172
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 172
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 172
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 172
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 172
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 172
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 172
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 172
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.001881
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 172
telemt_user_connections_total{user="hello"} 7918
telemt_user_connections_current{user="hello"} 814
telemt_user_octets_from_client{user="hello"} 50322724 (47.99 MB)
telemt_user_octets_to_client{user="hello"} 1912917244 (1.78 GB)
telemt_user_unique_ips_current{user="hello"} 551
telemt_user_unique_ips_recent_window{user="hello"} 781
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 69164.1 (19h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4956894
telemt_connections_bad_total 443977
telemt_connections_current 5491
telemt_connections_me_current 5491
telemt_handshake_timeouts_total 174737
telemt_upstream_connect_attempt_total 25561
telemt_upstream_connect_success_total 25506
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 25512
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11475
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13925
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 100
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 1157
telemt_me_reconnect_success_total 582
telemt_me_reader_eof_total 587
telemt_me_idle_close_by_peer_total 587
telemt_me_route_drop_no_conn_total 2807058
telemt_me_route_drop_channel_closed_total 46
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4052935
telemt_me_endpoint_quarantine_total 435
telemt_me_single_endpoint_outage_enter_total 4
telemt_me_single_endpoint_outage_exit_total 4
telemt_me_single_endpoint_outage_reconnect_attempt_total 4
telemt_me_single_endpoint_outage_reconnect_success_total 4
telemt_me_single_endpoint_quarantine_bypass_total 4
telemt_me_single_endpoint_shadow_rotate_total 520
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
telemt_me_writers_active_current 44
telemt_desync_total 16643
telemt_desync_full_logged_total 5608
telemt_desync_suppressed_total 11035
telemt_desync_frames_bucket_total{bucket="1_2"} 3511
telemt_desync_frames_bucket_total{bucket="3_10"} 6574
telemt_desync_frames_bucket_total{bucket="gt_10"} 6558
telemt_pool_swap_total 73
telemt_pool_force_close_total 2378
telemt_pool_stale_pick_total 17
telemt_me_writer_close_signal_drop_total 372
telemt_me_draining_writers_reap_progress_total 23192
telemt_me_writer_removed_unexpected_total 567
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2031
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 21493
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 32
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2180
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 198
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 20814
telemt_me_writer_teardown_success_total{mode="normal"} 23524
telemt_me_writer_teardown_noop_total 23224
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 42942
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 44176
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 44854
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 45742
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 46286
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 46602
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 46746
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 46748
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 46748
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 46748
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 46748
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 46748
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 46748
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 87.818830
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 46748
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 372
telemt_me_refill_failed_total 30
telemt_me_writer_restored_same_endpoint_total 524
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 8
telemt_me_writer_removed_unexpected_minus_restored_total 38
telemt_user_connections_total{user="hello"} 4048060
telemt_user_connections_current{user="hello"} 5491
telemt_user_octets_from_client{user="hello"} 65210045640 (60.73 GB)
telemt_user_octets_to_client{user="hello"} 1327308046472 (1.21 TB)
telemt_user_unique_ips_current{user="hello"} 2113
telemt_user_unique_ips_recent_window{user="hello"} 831
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 69165.6 (19h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4014782
telemt_connections_bad_total 425645
telemt_connections_current 3721
telemt_connections_me_current 3721
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 141169
telemt_upstream_connect_attempt_total 29935
telemt_upstream_connect_success_total 29648
telemt_upstream_connect_fail_total 140
telemt_upstream_connect_attempts_per_request{bucket="1"} 29788
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15207
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13920
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 27
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 494
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 140
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 99
telemt_me_reconnect_attempts_total 1388
telemt_me_reconnect_success_total 608
telemt_me_reader_eof_total 570
telemt_me_idle_close_by_peer_total 570
telemt_me_route_drop_no_conn_total 1264770
telemt_me_route_drop_channel_closed_total 103
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2949517
telemt_me_endpoint_quarantine_total 444
telemt_me_single_endpoint_outage_enter_total 7
telemt_me_single_endpoint_outage_exit_total 7
telemt_me_single_endpoint_outage_reconnect_attempt_total 7
telemt_me_single_endpoint_outage_reconnect_success_total 7
telemt_me_single_endpoint_quarantine_bypass_total 7
telemt_me_single_endpoint_shadow_rotate_total 526
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
telemt_me_writers_active_current 45
telemt_desync_total 13786
telemt_desync_full_logged_total 4606
telemt_desync_suppressed_total 9180
telemt_desync_frames_bucket_total{bucket="1_2"} 3464
telemt_desync_frames_bucket_total{bucket="3_10"} 5319
telemt_desync_frames_bucket_total{bucket="gt_10"} 5003
telemt_pool_swap_total 75
telemt_pool_force_close_total 2174
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 219
telemt_me_draining_writers_reap_progress_total 22342
telemt_me_writer_removed_unexpected_total 553
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1929
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 20966
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2020
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 154
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 20168
telemt_me_writer_teardown_success_total{mode="normal"} 22895
telemt_me_writer_teardown_noop_total 22343
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 43437
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 44392
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 44660
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 44968
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 45148
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 45234
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 45238
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 45238
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 45238
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 45238
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 45238
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 45238
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 45238
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 22.598344
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 45238
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 219
telemt_me_refill_failed_total 41
telemt_me_writer_restored_same_endpoint_total 512
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 20
telemt_me_writer_removed_unexpected_minus_restored_total 33
telemt_user_connections_total{user="hello"} 2949093
telemt_user_connections_current{user="hello"} 3721
telemt_user_octets_from_client{user="hello"} 62110829013 (57.85 GB)
telemt_user_octets_to_client{user="hello"} 1366547043871 (1.24 TB)
telemt_user_msgs_from_client{user="hello"} 39229
telemt_user_msgs_to_client{user="hello"} 49019
telemt_user_unique_ips_current{user="hello"} 1517
telemt_user_unique_ips_recent_window{user="hello"} 590
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 69129.5 (19h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3945270
telemt_connections_bad_total 408203
telemt_connections_current 3883
telemt_connections_me_current 3883
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 119604
telemt_upstream_connect_attempt_total 35216
telemt_upstream_connect_success_total 34978
telemt_upstream_connect_fail_total 133
telemt_upstream_connect_attempts_per_request{bucket="1"} 35111
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18574
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15252
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 294
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 858
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 133
telemt_me_keepalive_timeout_total 50
telemt_me_reconnect_attempts_total 1435
telemt_me_reconnect_success_total 661
telemt_me_reader_eof_total 603
telemt_me_idle_close_by_peer_total 603
telemt_me_route_drop_no_conn_total 1369906
telemt_me_route_drop_channel_closed_total 41
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2931304
telemt_me_endpoint_quarantine_total 489
telemt_me_single_endpoint_outage_enter_total 7
telemt_me_single_endpoint_outage_exit_total 7
telemt_me_single_endpoint_outage_reconnect_attempt_total 7
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 7
telemt_me_single_endpoint_shadow_rotate_total 517
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 23
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
telemt_desync_total 13548
telemt_desync_full_logged_total 4494
telemt_desync_suppressed_total 9054
telemt_desync_frames_bucket_total{bucket="1_2"} 3388
telemt_desync_frames_bucket_total{bucket="3_10"} 5088
telemt_desync_frames_bucket_total{bucket="gt_10"} 5072
telemt_pool_swap_total 73
telemt_pool_force_close_total 2099
telemt_pool_stale_pick_total 1618
telemt_me_writer_close_signal_drop_total 238
telemt_me_draining_writers_reap_progress_total 23785
telemt_me_writer_removed_unexpected_total 573
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2012
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 22384
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 6
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1918
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 181
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 21686
telemt_me_writer_teardown_success_total{mode="normal"} 24396
telemt_me_writer_teardown_noop_total 23791
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 46836
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 47605
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 47824
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 48059
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 48173
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 48184
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 48187
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 48187
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 48187
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 48187
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 48187
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 48187
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 48187
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 12.741533
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 48187
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 238
telemt_me_refill_failed_total 43
telemt_me_writer_restored_same_endpoint_total 569
telemt_me_writer_restored_fallback_total 3
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 42
telemt_me_writer_removed_unexpected_minus_restored_total 1
telemt_user_connections_total{user="hello"} 2935029
telemt_user_connections_current{user="hello"} 3883
telemt_user_octets_from_client{user="hello"} 64060365977 (59.66 GB)
telemt_user_octets_to_client{user="hello"} 1354103796208 (1.23 TB)
telemt_user_msgs_from_client{user="hello"} 42436
telemt_user_msgs_to_client{user="hello"} 111361
telemt_user_unique_ips_current{user="hello"} 1536
telemt_user_unique_ips_recent_window{user="hello"} 552
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 69168.8 (19h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 13580800
telemt_connections_bad_total 880248
telemt_connections_current 5453
telemt_connections_me_current 5453
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 407382
telemt_upstream_connect_attempt_total 116347
telemt_upstream_connect_success_total 106436
telemt_upstream_connect_fail_total 8852
telemt_upstream_connect_attempts_per_request{bucket="1"} 115288
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 74501
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 25775
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 792
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5368
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8852
telemt_me_keepalive_timeout_total 102
telemt_me_reconnect_attempts_total 3873
telemt_me_reconnect_success_total 1416
telemt_me_reader_eof_total 986
telemt_me_idle_close_by_peer_total 985
telemt_me_route_drop_no_conn_total 26591877
telemt_me_route_drop_channel_closed_total 89
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 11177683
telemt_me_endpoint_quarantine_total 529
telemt_me_single_endpoint_outage_enter_total 78
telemt_me_single_endpoint_outage_exit_total 78
telemt_me_single_endpoint_outage_reconnect_attempt_total 174
telemt_me_single_endpoint_outage_reconnect_success_total 38
telemt_me_single_endpoint_quarantine_bypass_total 174
telemt_me_single_endpoint_shadow_rotate_total 540
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
telemt_desync_total 19678
telemt_desync_full_logged_total 6153
telemt_desync_suppressed_total 13525
telemt_desync_frames_bucket_total{bucket="1_2"} 4278
telemt_desync_frames_bucket_total{bucket="3_10"} 8683
telemt_desync_frames_bucket_total{bucket="gt_10"} 6717
telemt_pool_swap_total 70
telemt_pool_force_close_total 2280
telemt_pool_stale_pick_total 5
telemt_me_writer_close_signal_drop_total 500
telemt_me_draining_writers_reap_progress_total 22078
telemt_me_writer_removed_unexpected_total 1347
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2902
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 20316
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 11
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1909
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 371
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 19798
telemt_me_writer_teardown_success_total{mode="normal"} 23218
telemt_me_writer_teardown_noop_total 22090
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 40903
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 42461
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 43374
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 44437
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 45038
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 45256
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 45289
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 45291
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 45294
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 45299
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 45299
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 45303
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 45308
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 172.892260
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 45308
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 500
telemt_me_refill_failed_total 87
telemt_me_writer_restored_same_endpoint_total 990
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 130
telemt_me_writer_removed_unexpected_minus_restored_total 347
telemt_user_connections_total{user="hello"} 11252508
telemt_user_connections_current{user="hello"} 5452
telemt_user_octets_from_client{user="hello"} 78886985473 (73.47 GB)
telemt_user_octets_to_client{user="hello"} 814283529281 (758.36 GB)
telemt_user_msgs_from_client{user="hello"} 231133
telemt_user_msgs_to_client{user="hello"} 542131
telemt_user_unique_ips_current{user="hello"} 2058
telemt_user_unique_ips_recent_window{user="hello"} 1117
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 69136.7 (19h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3946620
telemt_connections_bad_total 429445
telemt_connections_current 4496
telemt_connections_me_current 4496
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 85165
telemt_upstream_connect_attempt_total 28988
telemt_upstream_connect_success_total 28674
telemt_upstream_connect_fail_total 270
telemt_upstream_connect_attempts_per_request{bucket="1"} 28944
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13632
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14966
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 75
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 270
telemt_me_reconnect_attempts_total 2770
telemt_me_reconnect_success_total 1031
telemt_me_reader_eof_total 1032
telemt_me_idle_close_by_peer_total 1032
telemt_me_route_drop_no_conn_total 1684319
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 34
telemt_me_route_drop_queue_full_profile_total{profile="high"} 34
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3052482
telemt_me_endpoint_quarantine_total 421
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 11
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 11
telemt_me_single_endpoint_shadow_rotate_total 515
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
telemt_me_writers_active_current 86
telemt_desync_total 14652
telemt_desync_full_logged_total 5091
telemt_desync_suppressed_total 9561
telemt_desync_frames_bucket_total{bucket="1_2"} 2851
telemt_desync_frames_bucket_total{bucket="3_10"} 5824
telemt_desync_frames_bucket_total{bucket="gt_10"} 5977
telemt_pool_swap_total 68
telemt_pool_force_close_total 1981
telemt_pool_stale_pick_total 54
telemt_me_writer_close_signal_drop_total 201
telemt_me_draining_writers_reap_progress_total 24296
telemt_me_writer_removed_unexpected_total 1001
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2430
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 22901
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1723
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 258
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 22315
telemt_me_writer_teardown_success_total{mode="normal"} 25331
telemt_me_writer_teardown_noop_total 24297
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 49015
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 49408
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 49585
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 49628
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 49628
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 49628
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 49628
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 49628
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 49628
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 49628
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 49628
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 49628
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 49628
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.420128
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 49628
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 201
telemt_me_refill_failed_total 95
telemt_me_writer_restored_same_endpoint_total 892
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20
telemt_me_writer_removed_unexpected_minus_restored_total 99
telemt_user_connections_total{user="hello"} 3035971
telemt_user_connections_current{user="hello"} 4496
telemt_user_octets_from_client{user="hello"} 79674693340 (74.20 GB)
telemt_user_octets_to_client{user="hello"} 1255034090098 (1.14 TB)
telemt_user_msgs_from_client{user="hello"} 7339
telemt_user_msgs_to_client{user="hello"} 11522
telemt_user_unique_ips_current{user="hello"} 1871
telemt_user_unique_ips_recent_window{user="hello"} 597
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 5972.0 (1h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 941094
telemt_connections_bad_total 28426
telemt_connections_current 3177
telemt_connections_me_current 3177
telemt_handshake_timeouts_total 448316
telemt_upstream_connect_attempt_total 2142
telemt_upstream_connect_success_total 2103
telemt_upstream_connect_fail_total 33
telemt_upstream_connect_attempts_per_request{bucket="1"} 2136
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 948
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1136
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 19
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 33
telemt_me_reconnect_attempts_total 253
telemt_me_reconnect_success_total 88
telemt_me_reader_eof_total 79
telemt_me_idle_close_by_peer_total 79
telemt_me_route_drop_no_conn_total 392648
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 426367
telemt_me_endpoint_quarantine_total 24
telemt_me_single_endpoint_outage_enter_total 1
telemt_me_single_endpoint_outage_exit_total 1
telemt_me_single_endpoint_outage_reconnect_attempt_total 1
telemt_me_single_endpoint_outage_reconnect_success_total 1
telemt_me_single_endpoint_quarantine_bypass_total 1
telemt_me_single_endpoint_shadow_rotate_total 46
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
telemt_desync_total 2106
telemt_desync_full_logged_total 686
telemt_desync_suppressed_total 1420
telemt_desync_frames_bucket_total{bucket="1_2"} 379
telemt_desync_frames_bucket_total{bucket="3_10"} 803
telemt_desync_frames_bucket_total{bucket="gt_10"} 924
telemt_pool_swap_total 5
telemt_pool_force_close_total 172
telemt_me_writer_close_signal_drop_total 13
telemt_me_draining_writers_reap_progress_total 1779
telemt_me_writer_removed_unexpected_total 80
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 173
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 1686
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 133
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 39
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 1607
telemt_me_writer_teardown_success_total{mode="normal"} 1859
telemt_me_writer_teardown_noop_total 1779
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 3547
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 3575
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 3603
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 3638
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 3638
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 3638
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 3638
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 3638
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 3638
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 3638
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 3638
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 3638
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 3638
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.789723
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 3638
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 13
telemt_me_refill_failed_total 10
telemt_me_writer_restored_same_endpoint_total 77
telemt_me_async_recovery_trigger_total 4
telemt_me_writer_removed_unexpected_minus_restored_total 3
telemt_user_connections_total{user="hello"} 425746
telemt_user_connections_current{user="hello"} 3177
telemt_user_octets_from_client{user="hello"} 11495222336 (10.71 GB)
telemt_user_octets_to_client{user="hello"} 158157276648 (147.30 GB)
telemt_user_unique_ips_current{user="hello"} 1264
telemt_user_unique_ips_recent_window{user="hello"} 568
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 67122.3 (18h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1260926
telemt_connections_bad_total 140351
telemt_connections_current 801
telemt_connections_me_current 801
telemt_handshake_timeouts_total 452328
telemt_upstream_connect_attempt_total 31321
telemt_upstream_connect_success_total 31314
telemt_upstream_connect_attempts_per_request{bucket="1"} 31314
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12815
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18397
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 102
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 1342
telemt_me_reconnect_success_total 567
telemt_me_reader_eof_total 564
telemt_me_idle_close_by_peer_total 564
telemt_me_route_drop_no_conn_total 275712
telemt_me_route_drop_channel_closed_total 24
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 592377
telemt_me_endpoint_quarantine_total 600
telemt_me_single_endpoint_outage_enter_total 8
telemt_me_single_endpoint_outage_exit_total 8
telemt_me_single_endpoint_outage_reconnect_attempt_total 8
telemt_me_single_endpoint_outage_reconnect_success_total 7
telemt_me_single_endpoint_quarantine_bypass_total 8
telemt_me_single_endpoint_shadow_rotate_total 562
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 10
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
telemt_desync_total 3621
telemt_desync_full_logged_total 1313
telemt_desync_suppressed_total 2308
telemt_desync_frames_bucket_total{bucket="1_2"} 666
telemt_desync_frames_bucket_total{bucket="3_10"} 1303
telemt_desync_frames_bucket_total{bucket="gt_10"} 1652
telemt_pool_swap_total 73
telemt_pool_force_close_total 1711
telemt_pool_stale_pick_total 7
telemt_me_writer_close_signal_drop_total 114
telemt_me_draining_writers_reap_progress_total 28059
telemt_me_writer_removed_unexpected_total 534
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2129
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 26480
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1682
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 29
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 26348
telemt_me_writer_teardown_success_total{mode="normal"} 28609
telemt_me_writer_teardown_noop_total 28059
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 55961
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 56434
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 56597
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 56652
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 56668
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 56668
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 56668
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 56668
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 56668
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 56668
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 56668
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 56668
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 56668
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 4.537554
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 56668
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 114
telemt_me_refill_failed_total 40
telemt_me_writer_restored_same_endpoint_total 472
telemt_me_writer_restored_fallback_total 5
telemt_me_writer_removed_unexpected_minus_restored_total 57
telemt_user_connections_total{user="hello"} 591990
telemt_user_connections_current{user="hello"} 801
telemt_user_octets_from_client{user="hello"} 12301646359 (11.46 GB)
telemt_user_octets_to_client{user="hello"} 227696373393 (212.06 GB)
telemt_user_msgs_from_client{user="hello"} 804
telemt_user_msgs_to_client{user="hello"} 1943
telemt_user_unique_ips_current{user="hello"} 297
telemt_user_unique_ips_recent_window{user="hello"} 114
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 69140.7 (19h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4380853
telemt_connections_bad_total 404134
telemt_connections_current 4835
telemt_connections_me_current 4835
telemt_handshake_timeouts_total 142344
telemt_upstream_connect_attempt_total 27384
telemt_upstream_connect_success_total 27271
telemt_upstream_connect_fail_total 78
telemt_upstream_connect_attempts_per_request{bucket="1"} 27349
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13505
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13729
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 36
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 78
telemt_me_reconnect_attempts_total 1189
telemt_me_reconnect_success_total 618
telemt_me_reader_eof_total 585
telemt_me_idle_close_by_peer_total 585
telemt_me_route_drop_no_conn_total 1326772
telemt_me_route_drop_channel_closed_total 36
telemt_me_route_drop_queue_full_total 11
telemt_me_route_drop_queue_full_profile_total{profile="high"} 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3466479
telemt_me_endpoint_quarantine_total 498
telemt_me_single_endpoint_outage_enter_total 8
telemt_me_single_endpoint_outage_exit_total 8
telemt_me_single_endpoint_outage_reconnect_attempt_total 8
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 8
telemt_me_single_endpoint_shadow_rotate_total 527
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
telemt_me_writers_active_current 43
telemt_desync_total 13516
telemt_desync_full_logged_total 4475
telemt_desync_suppressed_total 9041
telemt_desync_frames_bucket_total{bucket="1_2"} 3200
telemt_desync_frames_bucket_total{bucket="3_10"} 5025
telemt_desync_frames_bucket_total{bucket="gt_10"} 5291
telemt_pool_swap_total 76
telemt_pool_force_close_total 2002
telemt_pool_stale_pick_total 2
telemt_me_writer_close_signal_drop_total 224
telemt_me_draining_writers_reap_progress_total 24562
telemt_me_writer_removed_unexpected_total 573
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1961
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 23176
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1955
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 47
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 22560
telemt_me_writer_teardown_success_total{mode="normal"} 25137
telemt_me_writer_teardown_noop_total 24562
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 48941
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 49439
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 49531
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 49655
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 49699
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 49699
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 49699
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 49699
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 49699
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 49699
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 49699
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 49699
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 49699
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 5.911804
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 49699
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 224
telemt_me_refill_failed_total 29
telemt_me_writer_restored_same_endpoint_total 547
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 21
telemt_user_connections_total{user="hello"} 3458025
telemt_user_connections_current{user="hello"} 4835
telemt_user_octets_from_client{user="hello"} 69995532736 (65.19 GB)
telemt_user_octets_to_client{user="hello"} 1624250429304 (1.48 TB)
telemt_user_unique_ips_current{user="hello"} 1760
telemt_user_unique_ips_recent_window{user="hello"} 690
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 69137.3 (19h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3886553
telemt_connections_bad_total 356003
telemt_connections_current 3817
telemt_connections_me_current 3817
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 119638
telemt_upstream_connect_attempt_total 43887
telemt_upstream_connect_success_total 43591
telemt_upstream_connect_fail_total 245
telemt_upstream_connect_attempts_per_request{bucket="1"} 43836
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26865
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15607
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 517
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 602
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 245
telemt_me_reconnect_attempts_total 3862
telemt_me_reconnect_success_total 861
telemt_me_reader_eof_total 753
telemt_me_idle_close_by_peer_total 753
telemt_me_seq_mismatch_total 33
telemt_me_route_drop_no_conn_total 1411314
telemt_me_route_drop_channel_closed_total 104
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3101100
telemt_me_endpoint_quarantine_total 574
telemt_me_single_endpoint_outage_enter_total 20
telemt_me_single_endpoint_outage_exit_total 20
telemt_me_single_endpoint_outage_reconnect_attempt_total 20
telemt_me_single_endpoint_outage_reconnect_success_total 20
telemt_me_single_endpoint_quarantine_bypass_total 20
telemt_me_single_endpoint_shadow_rotate_total 524
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 23
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
telemt_desync_total 12122
telemt_desync_full_logged_total 4109
telemt_desync_suppressed_total 8013
telemt_desync_frames_bucket_total{bucket="1_2"} 3029
telemt_desync_frames_bucket_total{bucket="3_10"} 4498
telemt_desync_frames_bucket_total{bucket="gt_10"} 4595
telemt_pool_swap_total 74
telemt_pool_force_close_total 1935
telemt_pool_stale_pick_total 358
telemt_me_writer_close_signal_drop_total 214
telemt_me_draining_writers_reap_progress_total 23974
telemt_me_writer_removed_unexpected_total 766
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2345
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 22428
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1778
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 157
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 22039
telemt_me_writer_teardown_success_total{mode="normal"} 24773
telemt_me_writer_teardown_noop_total 23975
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 47852
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 48418
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 48611
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 48739
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 48748
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 48748
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 48748
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 48748
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 48748
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 48748
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 48748
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 48748
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 48748
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 6.150692
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 48748
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 214
telemt_me_refill_failed_total 170
telemt_me_writer_restored_same_endpoint_total 667
telemt_me_writer_restored_fallback_total 42
telemt_me_async_recovery_trigger_total 57
telemt_me_writer_removed_unexpected_minus_restored_total 57
telemt_user_connections_total{user="hello"} 3109454
telemt_user_connections_current{user="hello"} 3817
telemt_user_octets_from_client{user="hello"} 56456636761 (52.58 GB)
telemt_user_octets_to_client{user="hello"} 1327822195288 (1.21 TB)
telemt_user_msgs_from_client{user="hello"} 75721
telemt_user_msgs_to_client{user="hello"} 209236
telemt_user_unique_ips_current{user="hello"} 1511
telemt_user_unique_ips_recent_window{user="hello"} 538
```