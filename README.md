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

# Server Metrics 2026-03-21 07:03:46 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 37659.8 (10h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 829566
telemt_connections_bad_total 44339
telemt_connections_current 1473
telemt_connections_me_current 1473
telemt_handshake_timeouts_total 40138
telemt_upstream_connect_attempt_total 15163
telemt_upstream_connect_success_total 15095
telemt_upstream_connect_fail_total 45
telemt_upstream_connect_attempts_per_request{bucket="1"} 15140
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5232
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9817
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 10
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 36
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 45
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 11
telemt_me_reconnect_attempts_total 466
telemt_me_reconnect_success_total 244
telemt_me_reader_eof_total 256
telemt_me_idle_close_by_peer_total 256
telemt_me_route_drop_no_conn_total 271853
telemt_me_route_drop_channel_closed_total 93
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 614773
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_endpoint_quarantine_total 265
telemt_me_single_endpoint_outage_enter_total 1
telemt_me_single_endpoint_outage_exit_total 1
telemt_me_single_endpoint_outage_reconnect_attempt_total 1
telemt_me_single_endpoint_outage_reconnect_success_total 1
telemt_me_single_endpoint_quarantine_bypass_total 1
telemt_me_single_endpoint_shadow_rotate_total 310
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 13
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
telemt_desync_total 2686
telemt_desync_full_logged_total 978
telemt_desync_suppressed_total 1708
telemt_desync_frames_bucket_total{bucket="1_2"} 559
telemt_desync_frames_bucket_total{bucket="3_10"} 1053
telemt_desync_frames_bucket_total{bucket="gt_10"} 1074
telemt_pool_swap_total 41
telemt_pool_force_close_total 1127
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 103
telemt_me_draining_writers_reap_progress_total 13665
telemt_me_writer_removed_unexpected_total 241
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1006
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 12858
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1122
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 12538
telemt_me_writer_teardown_success_total{mode="normal"} 13864
telemt_me_writer_teardown_noop_total 13666
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 26002
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 26453
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 26625
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 26951
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 27322
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 27468
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 27525
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 27530
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 27530
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 27530
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 27530
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 27530
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 27530
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 42.457630
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 27530
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 103
telemt_me_refill_failed_total 12
telemt_me_writer_restored_same_endpoint_total 221
telemt_me_writer_restored_fallback_total 3
telemt_me_writer_removed_unexpected_minus_restored_total 17
telemt_user_connections_total{user="hello"} 614035
telemt_user_connections_current{user="hello"} 1473
telemt_user_octets_from_client{user="hello"} 7299656888 (6.80 GB)
telemt_user_octets_to_client{user="hello"} 194500563964 (181.14 GB)
telemt_user_unique_ips_current{user="hello"} 529
telemt_user_unique_ips_recent_window{user="hello"} 241
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 37660.9 (10h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2076051
telemt_connections_bad_total 227063
telemt_connections_current 4453
telemt_connections_me_current 4453
telemt_handshake_timeouts_total 64501
telemt_upstream_connect_attempt_total 14099
telemt_upstream_connect_success_total 14035
telemt_upstream_connect_fail_total 44
telemt_upstream_connect_attempts_per_request{bucket="1"} 14079
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5757
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8237
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 41
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 44
telemt_me_reconnect_attempts_total 776
telemt_me_reconnect_success_total 280
telemt_me_reader_eof_total 289
telemt_me_idle_close_by_peer_total 289
telemt_me_route_drop_no_conn_total 422409
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1259935
telemt_me_endpoint_quarantine_total 244
telemt_me_single_endpoint_outage_enter_total 1
telemt_me_single_endpoint_outage_exit_total 1
telemt_me_single_endpoint_outage_reconnect_attempt_total 1
telemt_me_single_endpoint_outage_reconnect_success_total 1
telemt_me_single_endpoint_quarantine_bypass_total 1
telemt_me_single_endpoint_shadow_rotate_total 301
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 7
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
telemt_desync_total 5358
telemt_desync_full_logged_total 1870
telemt_desync_suppressed_total 3488
telemt_desync_frames_bucket_total{bucket="1_2"} 1093
telemt_desync_frames_bucket_total{bucket="3_10"} 2112
telemt_desync_frames_bucket_total{bucket="gt_10"} 2153
telemt_pool_swap_total 40
telemt_pool_force_close_total 1190
telemt_me_writer_close_signal_drop_total 123
telemt_me_draining_writers_reap_progress_total 12659
telemt_me_writer_removed_unexpected_total 270
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1113
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 11808
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1134
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 56
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 11469
telemt_me_writer_teardown_success_total{mode="normal"} 12921
telemt_me_writer_teardown_noop_total 12659
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 24673
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 25038
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 25238
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 25505
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 25578
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 25580
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 25580
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 25580
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 25580
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 25580
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 25580
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 25580
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 25580
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 9.592103
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 25580
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 123
telemt_me_refill_failed_total 27
telemt_me_writer_restored_same_endpoint_total 237
telemt_me_writer_restored_fallback_total 1
telemt_me_async_recovery_trigger_total 2
telemt_me_writer_removed_unexpected_minus_restored_total 32
telemt_user_connections_total{user="hello"} 1256897
telemt_user_connections_current{user="hello"} 4453
telemt_user_octets_from_client{user="hello"} 17347088836 (16.16 GB)
telemt_user_octets_to_client{user="hello"} 519606396800 (483.92 GB)
telemt_user_unique_ips_current{user="hello"} 1566
telemt_user_unique_ips_recent_window{user="hello"} 643
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 37657.4 (10h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1394474
telemt_connections_bad_total 161501
telemt_connections_current 3723
telemt_connections_me_current 3723
telemt_handshake_timeouts_total 64074
telemt_upstream_connect_attempt_total 15232
telemt_upstream_connect_success_total 15222
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 15223
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6922
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8255
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 45
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 418
telemt_me_reconnect_success_total 246
telemt_me_reader_eof_total 255
telemt_me_idle_close_by_peer_total 255
telemt_me_route_drop_no_conn_total 350159
telemt_me_route_drop_channel_closed_total 5
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1083819
telemt_me_endpoint_quarantine_total 268
telemt_me_single_endpoint_outage_enter_total 2
telemt_me_single_endpoint_outage_exit_total 2
telemt_me_single_endpoint_outage_reconnect_attempt_total 2
telemt_me_single_endpoint_outage_reconnect_success_total 2
telemt_me_single_endpoint_quarantine_bypass_total 2
telemt_me_single_endpoint_shadow_rotate_total 300
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 11
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
telemt_desync_total 4342
telemt_desync_full_logged_total 1571
telemt_desync_suppressed_total 2771
telemt_desync_frames_bucket_total{bucket="1_2"} 970
telemt_desync_frames_bucket_total{bucket="3_10"} 1671
telemt_desync_frames_bucket_total{bucket="gt_10"} 1701
telemt_pool_swap_total 41
telemt_pool_force_close_total 1128
telemt_pool_stale_pick_total 16
telemt_me_writer_close_signal_drop_total 129
telemt_me_draining_writers_reap_progress_total 13873
telemt_me_writer_removed_unexpected_total 237
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1071
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 12976
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1118
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 10
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 12745
telemt_me_writer_teardown_success_total{mode="normal"} 14047
telemt_me_writer_teardown_noop_total 13876
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 26556
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 27093
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 27370
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 27747
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 27884
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 27915
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 27923
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 27923
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 27923
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 27923
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 27923
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 27923
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 27923
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 18.108979
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 27923
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 129
telemt_me_refill_failed_total 8
telemt_me_writer_restored_same_endpoint_total 212
telemt_me_writer_restored_fallback_total 5
telemt_me_writer_removed_unexpected_minus_restored_total 20
telemt_user_connections_total{user="hello"} 1081593
telemt_user_connections_current{user="hello"} 3723
telemt_user_octets_from_client{user="hello"} 14858714604 (13.84 GB)
telemt_user_octets_to_client{user="hello"} 477324292428 (444.54 GB)
telemt_user_unique_ips_current{user="hello"} 1393
telemt_user_unique_ips_recent_window{user="hello"} 574
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 37663.8 (10h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1216409
telemt_connections_bad_total 156547
telemt_connections_current 2660
telemt_connections_me_current 2660
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 57791
telemt_upstream_connect_attempt_total 20055
telemt_upstream_connect_success_total 19847
telemt_upstream_connect_fail_total 117
telemt_upstream_connect_attempts_per_request{bucket="1"} 19964
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10736
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8716
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 23
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 372
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 117
telemt_me_keepalive_timeout_total 16
telemt_me_reconnect_attempts_total 682
telemt_me_reconnect_success_total 287
telemt_me_reader_eof_total 281
telemt_me_idle_close_by_peer_total 281
telemt_me_route_drop_no_conn_total 333889
telemt_me_route_drop_channel_closed_total 18
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 830858
telemt_me_endpoint_quarantine_total 271
telemt_me_single_endpoint_outage_enter_total 1
telemt_me_single_endpoint_outage_exit_total 1
telemt_me_single_endpoint_outage_reconnect_attempt_total 1
telemt_me_single_endpoint_outage_reconnect_success_total 1
telemt_me_single_endpoint_quarantine_bypass_total 1
telemt_me_single_endpoint_shadow_rotate_total 303
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 8
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
telemt_me_writers_active_current 42
telemt_desync_total 3757
telemt_desync_full_logged_total 1369
telemt_desync_suppressed_total 2388
telemt_desync_frames_bucket_total{bucket="1_2"} 818
telemt_desync_frames_bucket_total{bucket="3_10"} 1605
telemt_desync_frames_bucket_total{bucket="gt_10"} 1334
telemt_pool_swap_total 41
telemt_pool_force_close_total 1042
telemt_me_writer_close_signal_drop_total 53
telemt_me_draining_writers_reap_progress_total 13748
telemt_me_writer_removed_unexpected_total 272
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1030
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 13004
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1022
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 20
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 12706
telemt_me_writer_teardown_success_total{mode="normal"} 14034
telemt_me_writer_teardown_noop_total 13749
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 27507
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 27696
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 27739
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 27753
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 27783
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 27783
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 27783
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 27783
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 27783
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 27783
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 27783
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 27783
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 27783
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 2.243719
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 27783
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 53
telemt_me_refill_failed_total 21
telemt_me_writer_restored_same_endpoint_total 245
telemt_me_writer_restored_fallback_total 3
telemt_me_async_recovery_trigger_total 4
telemt_me_writer_removed_unexpected_minus_restored_total 24
telemt_user_connections_total{user="hello"} 833992
telemt_user_connections_current{user="hello"} 2660
telemt_user_octets_from_client{user="hello"} 14573268785 (13.57 GB)
telemt_user_octets_to_client{user="hello"} 391436541403 (364.55 GB)
telemt_user_msgs_from_client{user="hello"} 39229
telemt_user_msgs_to_client{user="hello"} 49019
telemt_user_unique_ips_current{user="hello"} 959
telemt_user_unique_ips_recent_window{user="hello"} 453
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 37622.5 (10h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1154712
telemt_connections_bad_total 143667
telemt_connections_current 3009
telemt_connections_me_current 3009
telemt_handshake_timeouts_total 41947
telemt_upstream_connect_attempt_total 15931
telemt_upstream_connect_success_total 15922
telemt_upstream_connect_attempts_per_request{bucket="1"} 15922
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7070
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8837
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_me_reconnect_attempts_total 282
telemt_me_reconnect_success_total 237
telemt_me_reader_eof_total 234
telemt_me_idle_close_by_peer_total 234
telemt_me_route_drop_no_conn_total 239203
telemt_me_route_drop_channel_closed_total 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 818809
telemt_me_endpoint_quarantine_total 308
telemt_me_single_endpoint_shadow_rotate_total 299
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 11
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
telemt_desync_total 3929
telemt_desync_full_logged_total 1438
telemt_desync_suppressed_total 2491
telemt_desync_frames_bucket_total{bucket="1_2"} 980
telemt_desync_frames_bucket_total{bucket="3_10"} 1520
telemt_desync_frames_bucket_total{bucket="gt_10"} 1429
telemt_pool_swap_total 41
telemt_pool_force_close_total 1021
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 64
telemt_me_draining_writers_reap_progress_total 14439
telemt_me_writer_removed_unexpected_total 215
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 953
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 13721
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1011
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 10
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 13418
telemt_me_writer_teardown_success_total{mode="normal"} 14674
telemt_me_writer_teardown_noop_total 14440
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 28885
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 29037
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 29074
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 29114
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 29114
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 29114
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 29114
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 29114
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 29114
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 29114
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 29114
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 29114
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 29114
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 1.519896
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 29114
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 64
telemt_me_refill_failed_total 2
telemt_me_writer_restored_same_endpoint_total 211
telemt_me_writer_restored_fallback_total 1
telemt_me_async_recovery_trigger_total 2
telemt_me_writer_removed_unexpected_minus_restored_total 3
telemt_user_connections_total{user="hello"} 817271
telemt_user_connections_current{user="hello"} 3009
telemt_user_octets_from_client{user="hello"} 20350288824 (18.95 GB)
telemt_user_octets_to_client{user="hello"} 424942697800 (395.76 GB)
telemt_user_unique_ips_current{user="hello"} 1192
telemt_user_unique_ips_recent_window{user="hello"} 445
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 37677.0 (10h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2559202
telemt_connections_bad_total 175398
telemt_connections_current 5015
telemt_connections_me_current 5015
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 158236
telemt_upstream_connect_attempt_total 41371
telemt_upstream_connect_success_total 39524
telemt_upstream_connect_fail_total 1324
telemt_upstream_connect_attempts_per_request{bucket="1"} 40848
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 28155
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10142
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1227
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1324
telemt_me_reconnect_attempts_total 1805
telemt_me_reconnect_success_total 586
telemt_me_reader_eof_total 396
telemt_me_idle_close_by_peer_total 395
telemt_me_route_drop_no_conn_total 2421827
telemt_me_route_drop_channel_closed_total 25
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2038807
telemt_me_endpoint_quarantine_total 297
telemt_me_single_endpoint_outage_enter_total 36
telemt_me_single_endpoint_outage_exit_total 36
telemt_me_single_endpoint_outage_reconnect_attempt_total 78
telemt_me_single_endpoint_outage_reconnect_success_total 16
telemt_me_single_endpoint_quarantine_bypass_total 78
telemt_me_single_endpoint_shadow_rotate_total 301
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 17
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
telemt_desync_total 4926
telemt_desync_full_logged_total 1805
telemt_desync_suppressed_total 3121
telemt_desync_frames_bucket_total{bucket="1_2"} 1124
telemt_desync_frames_bucket_total{bucket="3_10"} 2099
telemt_desync_frames_bucket_total{bucket="gt_10"} 1703
telemt_pool_swap_total 40
telemt_pool_force_close_total 1113
telemt_me_writer_close_signal_drop_total 163
telemt_me_draining_writers_reap_progress_total 12833
telemt_me_writer_removed_unexpected_total 567
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1443
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 11926
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1045
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 68
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 11720
telemt_me_writer_teardown_success_total{mode="normal"} 13369
telemt_me_writer_teardown_noop_total 12837
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 24775
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 25223
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 25613
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 25962
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 26111
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 26199
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 26206
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 26206
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 26206
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 26206
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 26206
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 26206
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 26206
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 21.719131
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 26206
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 163
telemt_me_refill_failed_total 45
telemt_me_writer_restored_same_endpoint_total 380
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 6
telemt_me_writer_removed_unexpected_minus_restored_total 179
telemt_user_connections_total{user="hello"} 2061884
telemt_user_connections_current{user="hello"} 5015
telemt_user_octets_from_client{user="hello"} 34166033862 (31.82 GB)
telemt_user_octets_to_client{user="hello"} 464869965914 (432.94 GB)
telemt_user_msgs_from_client{user="hello"} 103363
telemt_user_msgs_to_client{user="hello"} 429893
telemt_user_unique_ips_current{user="hello"} 1715
telemt_user_unique_ips_recent_window{user="hello"} 1034
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 37629.5 (10h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1231983
telemt_connections_bad_total 172504
telemt_connections_current 3299
telemt_connections_me_current 3299
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 26180
telemt_upstream_connect_attempt_total 17503
telemt_upstream_connect_success_total 17351
telemt_upstream_connect_fail_total 137
telemt_upstream_connect_attempts_per_request{bucket="1"} 17488
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8548
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8766
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 37
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 137
telemt_me_reconnect_attempts_total 1447
telemt_me_reconnect_success_total 386
telemt_me_reader_eof_total 396
telemt_me_idle_close_by_peer_total 396
telemt_me_route_drop_no_conn_total 301581
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 890821
telemt_me_endpoint_quarantine_total 245
telemt_me_single_endpoint_outage_enter_total 8
telemt_me_single_endpoint_outage_exit_total 8
telemt_me_single_endpoint_outage_reconnect_attempt_total 8
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 8
telemt_me_single_endpoint_shadow_rotate_total 301
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 17
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
telemt_me_writers_active_current 87
telemt_desync_total 3703
telemt_desync_full_logged_total 1404
telemt_desync_suppressed_total 2299
telemt_desync_frames_bucket_total{bucket="1_2"} 711
telemt_desync_frames_bucket_total{bucket="3_10"} 1499
telemt_desync_frames_bucket_total{bucket="gt_10"} 1493
telemt_pool_swap_total 40
telemt_pool_force_close_total 956
telemt_me_writer_close_signal_drop_total 60
telemt_me_draining_writers_reap_progress_total 14384
telemt_me_writer_removed_unexpected_total 376
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1119
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 13661
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 949
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 13428
telemt_me_writer_teardown_success_total{mode="normal"} 14780
telemt_me_writer_teardown_noop_total 14384
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 28963
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 29073
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 29164
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 29164
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 29164
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 29164
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 29164
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 29164
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 29164
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 29164
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 29164
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 29164
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 29164
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 1.065442
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 29164
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 60
telemt_me_refill_failed_total 60
telemt_me_writer_restored_same_endpoint_total 307
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 2
telemt_me_writer_removed_unexpected_minus_restored_total 63
telemt_user_connections_total{user="hello"} 888434
telemt_user_connections_current{user="hello"} 3299
telemt_user_octets_from_client{user="hello"} 14785300588 (13.77 GB)
telemt_user_octets_to_client{user="hello"} 441921494694 (411.57 GB)
telemt_user_msgs_from_client{user="hello"} 7339
telemt_user_msgs_to_client{user="hello"} 11522
telemt_user_unique_ips_current{user="hello"} 1285
telemt_user_unique_ips_recent_window{user="hello"} 519
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 37623.9 (10h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1586260
telemt_connections_bad_total 99441
telemt_connections_current 2510
telemt_connections_me_current 2510
telemt_handshake_timeouts_total 578218
telemt_upstream_connect_attempt_total 16574
telemt_upstream_connect_success_total 16547
telemt_upstream_connect_attempts_per_request{bucket="1"} 16547
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7427
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8857
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 263
telemt_me_reconnect_attempts_total 352
telemt_me_reconnect_success_total 246
telemt_me_reader_eof_total 255
telemt_me_idle_close_by_peer_total 255
telemt_me_route_drop_no_conn_total 262712
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 792375
telemt_me_endpoint_quarantine_total 318
telemt_me_single_endpoint_shadow_rotate_total 307
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 7
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
telemt_me_writers_active_current 42
telemt_desync_total 3601
telemt_desync_full_logged_total 1272
telemt_desync_suppressed_total 2329
telemt_desync_frames_bucket_total{bucket="1_2"} 655
telemt_desync_frames_bucket_total{bucket="3_10"} 1472
telemt_desync_frames_bucket_total{bucket="gt_10"} 1474
telemt_pool_swap_total 41
telemt_pool_force_close_total 947
telemt_me_writer_close_signal_drop_total 57
telemt_me_draining_writers_reap_progress_total 14854
telemt_me_writer_removed_unexpected_total 239
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 879
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 14231
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 939
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 8
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 13907
telemt_me_writer_teardown_success_total{mode="normal"} 15110
telemt_me_writer_teardown_noop_total 14854
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 29871
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 29936
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 29964
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 29964
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 29964
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 29964
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 29964
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 29964
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 29964
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 29964
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 29964
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 29964
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 29964
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.543056
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 29964
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 57
telemt_me_refill_failed_total 5
telemt_me_writer_restored_same_endpoint_total 221
telemt_me_writer_restored_fallback_total 2
telemt_me_writer_removed_unexpected_minus_restored_total 16
telemt_user_connections_total{user="hello"} 789391
telemt_user_connections_current{user="hello"} 2510
telemt_user_octets_from_client{user="hello"} 12681427244 (11.81 GB)
telemt_user_octets_to_client{user="hello"} 405338083272 (377.50 GB)
telemt_user_unique_ips_current{user="hello"} 987
telemt_user_unique_ips_recent_window{user="hello"} 473
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 35615.4 (9h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 305644
telemt_connections_bad_total 11505
telemt_connections_current 627
telemt_connections_me_current 627
telemt_handshake_timeouts_total 83943
telemt_upstream_connect_attempt_total 18070
telemt_upstream_connect_success_total 18068
telemt_upstream_connect_attempts_per_request{bucket="1"} 18068
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7622
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10409
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 37
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 584
telemt_me_reconnect_success_total 272
telemt_me_reader_eof_total 277
telemt_me_idle_close_by_peer_total 277
telemt_me_route_drop_no_conn_total 71983
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 193172
telemt_me_endpoint_quarantine_total 352
telemt_me_single_endpoint_outage_enter_total 4
telemt_me_single_endpoint_outage_exit_total 4
telemt_me_single_endpoint_outage_reconnect_attempt_total 4
telemt_me_single_endpoint_outage_reconnect_success_total 3
telemt_me_single_endpoint_quarantine_bypass_total 4
telemt_me_single_endpoint_shadow_rotate_total 309
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 5
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
telemt_me_writers_active_current 44
telemt_desync_total 1175
telemt_desync_full_logged_total 550
telemt_desync_suppressed_total 625
telemt_desync_frames_bucket_total{bucket="1_2"} 221
telemt_desync_frames_bucket_total{bucket="3_10"} 498
telemt_desync_frames_bucket_total{bucket="gt_10"} 456
telemt_pool_swap_total 39
telemt_pool_force_close_total 800
telemt_me_writer_close_signal_drop_total 47
telemt_me_draining_writers_reap_progress_total 16119
telemt_me_writer_removed_unexpected_total 261
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1117
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 15264
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 800
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 15319
telemt_me_writer_teardown_success_total{mode="normal"} 16381
telemt_me_writer_teardown_noop_total 16119
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 32280
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 32456
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 32493
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 32500
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 32500
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 32500
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 32500
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 32500
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 32500
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 32500
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 32500
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 32500
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 32500
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 1.184632
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 32500
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 47
telemt_me_refill_failed_total 16
telemt_me_writer_restored_same_endpoint_total 233
telemt_me_writer_restored_fallback_total 1
telemt_me_writer_removed_unexpected_minus_restored_total 27
telemt_user_connections_total{user="hello"} 193386
telemt_user_connections_current{user="hello"} 627
telemt_user_octets_from_client{user="hello"} 2147434195 (2.00 GB)
telemt_user_octets_to_client{user="hello"} 82589436461 (76.92 GB)
telemt_user_msgs_from_client{user="hello"} 804
telemt_user_msgs_to_client{user="hello"} 1943
telemt_user_unique_ips_current{user="hello"} 258
telemt_user_unique_ips_recent_window{user="hello"} 118
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 37633.8 (10h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1255640
telemt_connections_bad_total 92798
telemt_connections_current 3485
telemt_connections_me_current 3485
telemt_handshake_timeouts_total 34051
telemt_upstream_connect_attempt_total 17025
telemt_upstream_connect_success_total 16947
telemt_upstream_connect_fail_total 49
telemt_upstream_connect_attempts_per_request{bucket="1"} 16996
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8488
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8435
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 23
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 49
telemt_me_reconnect_attempts_total 585
telemt_me_reconnect_success_total 339
telemt_me_reader_eof_total 324
telemt_me_idle_close_by_peer_total 324
telemt_me_route_drop_no_conn_total 274289
telemt_me_route_drop_channel_closed_total 3
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 981537
telemt_me_endpoint_quarantine_total 311
telemt_me_single_endpoint_outage_enter_total 2
telemt_me_single_endpoint_outage_exit_total 2
telemt_me_single_endpoint_outage_reconnect_attempt_total 2
telemt_me_single_endpoint_outage_reconnect_success_total 2
telemt_me_single_endpoint_quarantine_bypass_total 2
telemt_me_single_endpoint_shadow_rotate_total 302
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 9
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
telemt_desync_total 3916
telemt_desync_full_logged_total 1307
telemt_desync_suppressed_total 2609
telemt_desync_frames_bucket_total{bucket="1_2"} 1024
telemt_desync_frames_bucket_total{bucket="3_10"} 1471
telemt_desync_frames_bucket_total{bucket="gt_10"} 1421
telemt_pool_swap_total 41
telemt_pool_force_close_total 960
telemt_pool_stale_pick_total 2
telemt_me_writer_close_signal_drop_total 73
telemt_me_draining_writers_reap_progress_total 15368
telemt_me_writer_removed_unexpected_total 325
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1070
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 14630
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 959
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 14408
telemt_me_writer_teardown_success_total{mode="normal"} 15700
telemt_me_writer_teardown_noop_total 15368
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 30900
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 31008
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 31026
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 31068
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 31068
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 31068
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 31068
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 31068
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 31068
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 31068
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 31068
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 31068
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 31068
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 1.222032
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 31068
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 73
telemt_me_refill_failed_total 12
telemt_me_writer_restored_same_endpoint_total 311
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 4
telemt_me_writer_removed_unexpected_minus_restored_total 10
telemt_user_connections_total{user="hello"} 977200
telemt_user_connections_current{user="hello"} 3485
telemt_user_octets_from_client{user="hello"} 14680957304 (13.67 GB)
telemt_user_octets_to_client{user="hello"} 441263876304 (410.96 GB)
telemt_user_unique_ips_current{user="hello"} 1240
telemt_user_unique_ips_recent_window{user="hello"} 482
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 37630.6 (10h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1194154
telemt_connections_bad_total 77917
telemt_connections_current 3155
telemt_connections_me_current 3155
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 31231
telemt_upstream_connect_attempt_total 25593
telemt_upstream_connect_success_total 25412
telemt_upstream_connect_fail_total 141
telemt_upstream_connect_attempts_per_request{bucket="1"} 25553
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16499
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8889
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 24
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 141
telemt_me_reconnect_attempts_total 2516
telemt_me_reconnect_success_total 460
telemt_me_reader_eof_total 400
telemt_me_idle_close_by_peer_total 400
telemt_me_seq_mismatch_total 24
telemt_me_route_drop_no_conn_total 279495
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 953897
telemt_me_endpoint_quarantine_total 376
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 9
telemt_me_single_endpoint_outage_reconnect_success_total 9
telemt_me_single_endpoint_quarantine_bypass_total 9
telemt_me_single_endpoint_shadow_rotate_total 301
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
telemt_me_writers_active_current 42
telemt_desync_total 3729
telemt_desync_full_logged_total 1173
telemt_desync_suppressed_total 2556
telemt_desync_frames_bucket_total{bucket="1_2"} 1109
telemt_desync_frames_bucket_total{bucket="3_10"} 1375
telemt_desync_frames_bucket_total{bucket="gt_10"} 1245
telemt_pool_swap_total 41
telemt_pool_force_close_total 934
telemt_me_writer_close_signal_drop_total 77
telemt_me_draining_writers_reap_progress_total 14602
telemt_me_writer_removed_unexpected_total 412
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1274
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 13762
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 914
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 20
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 13668
telemt_me_writer_teardown_success_total{mode="normal"} 15036
telemt_me_writer_teardown_noop_total 14602
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 29430
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 29544
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 29609
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 29638
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 29638
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 29638
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 29638
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 29638
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 29638
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 29638
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 29638
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 29638
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 29638
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 1.466725
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 29638
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 77
telemt_me_refill_failed_total 117
telemt_me_writer_restored_same_endpoint_total 341
telemt_me_writer_restored_fallback_total 28
telemt_me_async_recovery_trigger_total 39
telemt_me_writer_removed_unexpected_minus_restored_total 43
telemt_user_connections_total{user="hello"} 958581
telemt_user_connections_current{user="hello"} 3155
telemt_user_octets_from_client{user="hello"} 12289587731 (11.45 GB)
telemt_user_octets_to_client{user="hello"} 422219122175 (393.22 GB)
telemt_user_msgs_from_client{user="hello"} 40992
telemt_user_msgs_to_client{user="hello"} 110751
telemt_user_unique_ips_current{user="hello"} 1126
telemt_user_unique_ips_recent_window{user="hello"} 469
```