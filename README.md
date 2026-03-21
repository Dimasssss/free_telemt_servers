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

# Server Metrics 2026-03-21 13:36:19 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 61226.2 (17h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2022784
telemt_connections_bad_total 101125
telemt_connections_current 1561
telemt_connections_me_current 1561
telemt_handshake_timeouts_total 72950
telemt_upstream_connect_attempt_total 23470
telemt_upstream_connect_success_total 23355
telemt_upstream_connect_fail_total 77
telemt_upstream_connect_attempts_per_request{bucket="1"} 23432
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8262
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15013
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 30
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 50
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 77
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 92
telemt_me_reconnect_attempts_total 1321
telemt_me_reconnect_success_total 536
telemt_me_reader_eof_total 519
telemt_me_idle_close_by_peer_total 519
telemt_me_route_drop_no_conn_total 1501641
telemt_me_route_drop_channel_closed_total 504
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1596877
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_endpoint_quarantine_total 428
telemt_me_single_endpoint_outage_enter_total 6
telemt_me_single_endpoint_outage_exit_total 6
telemt_me_single_endpoint_outage_reconnect_attempt_total 6
telemt_me_single_endpoint_outage_reconnect_success_total 6
telemt_me_single_endpoint_quarantine_bypass_total 6
telemt_me_single_endpoint_shadow_rotate_total 480
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 20
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
telemt_me_writers_warm_current 3
telemt_desync_total 6302
telemt_desync_full_logged_total 2170
telemt_desync_suppressed_total 4132
telemt_desync_frames_bucket_total{bucket="1_2"} 1408
telemt_desync_frames_bucket_total{bucket="3_10"} 2384
telemt_desync_frames_bucket_total{bucket="gt_10"} 2510
telemt_pool_swap_total 66
telemt_pool_force_close_total 1963
telemt_pool_stale_pick_total 14
telemt_me_writer_close_signal_drop_total 374
telemt_me_draining_writers_reap_progress_total 20986
telemt_me_writer_removed_unexpected_total 499
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1724
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 19586
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1893
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 70
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 19023
telemt_me_writer_teardown_success_total{mode="normal"} 21310
telemt_me_writer_teardown_noop_total 20991
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 36268
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 37432
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 38443
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 40149
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 41464
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 42086
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 42282
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 42300
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 42300
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 42301
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 42301
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 42301
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 42301
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 166.416297
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 42301
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 374
telemt_me_refill_failed_total 42
telemt_me_writer_restored_same_endpoint_total 463
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 8
telemt_me_writer_removed_unexpected_minus_restored_total 32
telemt_user_connections_total{user="hello"} 1595660
telemt_user_connections_current{user="hello"} 1561
telemt_user_octets_from_client{user="hello"} 23837385755 (22.20 GB)
telemt_user_octets_to_client{user="hello"} 416933060999 (388.30 GB)
telemt_user_msgs_from_client{user="hello"} 295
telemt_user_msgs_to_client{user="hello"} 249
telemt_user_unique_ips_current{user="hello"} 594
telemt_user_unique_ips_recent_window{user="hello"} 220
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 779.4 (0h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 99093
telemt_connections_bad_total 4524
telemt_connections_current 4434
telemt_connections_me_current 4434
telemt_handshake_timeouts_total 3039
telemt_upstream_connect_attempt_total 290
telemt_upstream_connect_success_total 289
telemt_upstream_connect_attempts_per_request{bucket="1"} 289
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 127
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 149
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 13
telemt_me_reconnect_attempts_total 5
telemt_me_reconnect_success_total 9
telemt_me_reader_eof_total 4
telemt_me_idle_close_by_peer_total 4
telemt_me_route_drop_no_conn_total 41619
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 86218
telemt_me_endpoint_quarantine_total 4
telemt_me_single_endpoint_shadow_rotate_total 8
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
telemt_me_writers_active_current 47
telemt_desync_total 326
telemt_desync_full_logged_total 111
telemt_desync_suppressed_total 215
telemt_desync_frames_bucket_total{bucket="1_2"} 68
telemt_desync_frames_bucket_total{bucket="3_10"} 111
telemt_desync_frames_bucket_total{bucket="gt_10"} 147
telemt_me_draining_writers_reap_progress_total 182
telemt_me_writer_removed_unexpected_total 4
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 179
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 182
telemt_me_writer_teardown_success_total{mode="normal"} 186
telemt_me_writer_teardown_noop_total 182
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 368
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 368
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 368
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 368
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 368
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 368
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 368
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 368
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 368
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 368
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 368
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 368
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 368
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.004797
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 368
telemt_me_writer_restored_same_endpoint_total 4
telemt_user_connections_total{user="hello"} 86155
telemt_user_connections_current{user="hello"} 4434
telemt_user_octets_from_client{user="hello"} 831903404 (793.36 MB)
telemt_user_octets_to_client{user="hello"} 18910098520 (17.61 GB)
telemt_user_unique_ips_current{user="hello"} 1500
telemt_user_unique_ips_recent_window{user="hello"} 717
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 61224.3 (17h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4018456
telemt_connections_bad_total 391778
telemt_connections_current 5185
telemt_connections_me_current 5185
telemt_handshake_timeouts_total 154767
telemt_upstream_connect_attempt_total 23229
telemt_upstream_connect_success_total 23191
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 23196
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10497
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12606
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 82
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 896
telemt_me_reconnect_success_total 525
telemt_me_reader_eof_total 522
telemt_me_idle_close_by_peer_total 522
telemt_me_route_drop_no_conn_total 2032469
telemt_me_route_drop_channel_closed_total 39
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3240904
telemt_me_endpoint_quarantine_total 383
telemt_me_single_endpoint_outage_enter_total 3
telemt_me_single_endpoint_outage_exit_total 3
telemt_me_single_endpoint_outage_reconnect_attempt_total 3
telemt_me_single_endpoint_outage_reconnect_success_total 3
telemt_me_single_endpoint_quarantine_bypass_total 3
telemt_me_single_endpoint_shadow_rotate_total 466
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
telemt_me_writers_active_current 95
telemt_me_writers_warm_current 3
telemt_desync_total 13667
telemt_desync_full_logged_total 4632
telemt_desync_suppressed_total 9035
telemt_desync_frames_bucket_total{bucket="1_2"} 2891
telemt_desync_frames_bucket_total{bucket="3_10"} 5374
telemt_desync_frames_bucket_total{bucket="gt_10"} 5402
telemt_pool_swap_total 64
telemt_pool_force_close_total 2022
telemt_pool_stale_pick_total 16
telemt_me_writer_close_signal_drop_total 313
telemt_me_draining_writers_reap_progress_total 21030
telemt_me_writer_removed_unexpected_total 505
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1820
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 19524
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 18
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1871
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 151
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 19008
telemt_me_writer_teardown_success_total{mode="normal"} 21344
telemt_me_writer_teardown_noop_total 21048
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 39186
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 40312
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 40910
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 41655
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 42097
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 42314
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 42392
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 42392
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 42392
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 42392
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 42392
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 42392
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 42392
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 62.617048
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 42392
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 313
telemt_me_refill_failed_total 18
telemt_me_writer_restored_same_endpoint_total 477
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 8
telemt_me_writer_removed_unexpected_minus_restored_total 23
telemt_user_connections_total{user="hello"} 3236891
telemt_user_connections_current{user="hello"} 5185
telemt_user_octets_from_client{user="hello"} 52881876336 (49.25 GB)
telemt_user_octets_to_client{user="hello"} 1114965727720 (1.01 TB)
telemt_user_unique_ips_current{user="hello"} 2059
telemt_user_unique_ips_recent_window{user="hello"} 624
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 61225.1 (17h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3283310
telemt_connections_bad_total 365183
telemt_connections_current 3858
telemt_connections_me_current 3858
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 124117
telemt_upstream_connect_attempt_total 27614
telemt_upstream_connect_success_total 27340
telemt_upstream_connect_fail_total 134
telemt_upstream_connect_attempts_per_request{bucket="1"} 27474
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14215
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12621
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 27
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 477
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 134
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 76
telemt_me_reconnect_attempts_total 1163
telemt_me_reconnect_success_total 548
telemt_me_reader_eof_total 512
telemt_me_idle_close_by_peer_total 512
telemt_me_route_drop_no_conn_total 1021812
telemt_me_route_drop_channel_closed_total 82
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2367579
telemt_me_endpoint_quarantine_total 396
telemt_me_single_endpoint_outage_enter_total 6
telemt_me_single_endpoint_outage_exit_total 6
telemt_me_single_endpoint_outage_reconnect_attempt_total 6
telemt_me_single_endpoint_outage_reconnect_success_total 6
telemt_me_single_endpoint_quarantine_bypass_total 6
telemt_me_single_endpoint_shadow_rotate_total 466
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
telemt_me_writers_active_current 46
telemt_me_writers_warm_current 3
telemt_desync_total 10815
telemt_desync_full_logged_total 3670
telemt_desync_suppressed_total 7145
telemt_desync_frames_bucket_total{bucket="1_2"} 2701
telemt_desync_frames_bucket_total{bucket="3_10"} 4160
telemt_desync_frames_bucket_total{bucket="gt_10"} 3954
telemt_pool_swap_total 66
telemt_pool_force_close_total 1856
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 165
telemt_me_draining_writers_reap_progress_total 20275
telemt_me_writer_removed_unexpected_total 498
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1717
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 19078
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1733
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 123
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 18419
telemt_me_writer_teardown_success_total{mode="normal"} 20795
telemt_me_writer_teardown_noop_total 20276
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 39728
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 40435
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 40645
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 40896
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 41025
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 41069
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 41071
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 41071
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 41071
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 41071
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 41071
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 41071
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 41071
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 15.365973
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 41071
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 165
telemt_me_refill_failed_total 32
telemt_me_writer_restored_same_endpoint_total 462
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 30
telemt_user_connections_total{user="hello"} 2368355
telemt_user_connections_current{user="hello"} 3858
telemt_user_octets_from_client{user="hello"} 44392599025 (41.34 GB)
telemt_user_octets_to_client{user="hello"} 1115542864891 (1.01 TB)
telemt_user_msgs_from_client{user="hello"} 39229
telemt_user_msgs_to_client{user="hello"} 49019
telemt_user_unique_ips_current{user="hello"} 1483
telemt_user_unique_ips_recent_window{user="hello"} 524
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 61189.1 (16h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3192432
telemt_connections_bad_total 340199
telemt_connections_current 3631
telemt_connections_me_current 3631
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 92526
telemt_upstream_connect_attempt_total 32789
telemt_upstream_connect_success_total 32562
telemt_upstream_connect_fail_total 133
telemt_upstream_connect_attempts_per_request{bucket="1"} 32695
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17470
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13969
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 278
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 845
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 133
telemt_me_keepalive_timeout_total 50
telemt_me_reconnect_attempts_total 1278
telemt_me_reconnect_success_total 618
telemt_me_reader_eof_total 562
telemt_me_idle_close_by_peer_total 562
telemt_me_route_drop_no_conn_total 982594
telemt_me_route_drop_channel_closed_total 30
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2336371
telemt_me_endpoint_quarantine_total 444
telemt_me_single_endpoint_outage_enter_total 4
telemt_me_single_endpoint_outage_exit_total 4
telemt_me_single_endpoint_outage_reconnect_attempt_total 4
telemt_me_single_endpoint_outage_reconnect_success_total 3
telemt_me_single_endpoint_quarantine_bypass_total 4
telemt_me_single_endpoint_shadow_rotate_total 456
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 19
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
telemt_desync_total 10861
telemt_desync_full_logged_total 3612
telemt_desync_suppressed_total 7249
telemt_desync_frames_bucket_total{bucket="1_2"} 2761
telemt_desync_frames_bucket_total{bucket="3_10"} 4096
telemt_desync_frames_bucket_total{bucket="gt_10"} 4004
telemt_pool_swap_total 64
telemt_pool_force_close_total 1809
telemt_pool_stale_pick_total 1618
telemt_me_writer_close_signal_drop_total 211
telemt_me_draining_writers_reap_progress_total 21625
telemt_me_writer_removed_unexpected_total 535
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1824
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 20371
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1646
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 163
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 19816
telemt_me_writer_teardown_success_total{mode="normal"} 22195
telemt_me_writer_teardown_noop_total 21629
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 42780
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 43450
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 43608
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 43764
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 43823
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 43824
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 43824
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 43824
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 43824
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 43824
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 43824
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 43824
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 43824
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 7.715181
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 43824
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 211
telemt_me_refill_failed_total 38
telemt_me_writer_restored_same_endpoint_total 539
telemt_me_writer_restored_fallback_total 3
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 42
telemt_user_connections_total{user="hello"} 2341174
telemt_user_connections_current{user="hello"} 3631
telemt_user_octets_from_client{user="hello"} 51611881901 (48.07 GB)
telemt_user_octets_to_client{user="hello"} 1112966446328 (1.01 TB)
telemt_user_msgs_from_client{user="hello"} 42436
telemt_user_msgs_to_client{user="hello"} 111361
telemt_user_unique_ips_current{user="hello"} 1397
telemt_user_unique_ips_recent_window{user="hello"} 518
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 61228.4 (17h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10839537
telemt_connections_bad_total 735059
telemt_connections_current 5768
telemt_connections_me_current 5768
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 344675
telemt_upstream_connect_attempt_total 90186
telemt_upstream_connect_success_total 84933
telemt_upstream_connect_fail_total 4334
telemt_upstream_connect_attempts_per_request{bucket="1"} 89267
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 61209
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20595
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3129
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4334
telemt_me_keepalive_timeout_total 74
telemt_me_reconnect_attempts_total 3551
telemt_me_reconnect_success_total 1240
telemt_me_reader_eof_total 894
telemt_me_idle_close_by_peer_total 893
telemt_me_route_drop_no_conn_total 20134332
telemt_me_route_drop_channel_closed_total 69
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8911818
telemt_me_endpoint_quarantine_total 458
telemt_me_single_endpoint_outage_enter_total 67
telemt_me_single_endpoint_outage_exit_total 67
telemt_me_single_endpoint_outage_reconnect_attempt_total 152
telemt_me_single_endpoint_outage_reconnect_success_total 29
telemt_me_single_endpoint_quarantine_bypass_total 152
telemt_me_single_endpoint_shadow_rotate_total 479
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 36
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
telemt_me_writers_warm_current 3
telemt_desync_total 16557
telemt_desync_full_logged_total 5296
telemt_desync_suppressed_total 11261
telemt_desync_frames_bucket_total{bucket="1_2"} 3538
telemt_desync_frames_bucket_total{bucket="3_10"} 7250
telemt_desync_frames_bucket_total{bucket="gt_10"} 5769
telemt_pool_swap_total 61
telemt_pool_force_close_total 2016
telemt_pool_stale_pick_total 5
telemt_me_writer_close_signal_drop_total 407
telemt_me_draining_writers_reap_progress_total 19980
telemt_me_writer_removed_unexpected_total 1204
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2591
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 18424
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 10
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1685
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 331
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 17964
telemt_me_writer_teardown_success_total{mode="normal"} 21015
telemt_me_writer_teardown_noop_total 19990
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 37301
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 38618
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 39424
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 40307
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 40818
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 40982
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 41003
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 41005
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 41005
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 41005
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 41005
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 41005
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 41005
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 56.315310
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 41005
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 407
telemt_me_refill_failed_total 83
telemt_me_writer_restored_same_endpoint_total 879
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 63
telemt_me_writer_removed_unexpected_minus_restored_total 316
telemt_user_connections_total{user="hello"} 8969216
telemt_user_connections_current{user="hello"} 5768
telemt_user_octets_from_client{user="hello"} 68030921921 (63.36 GB)
telemt_user_octets_to_client{user="hello"} 725450219972 (675.63 GB)
telemt_user_msgs_from_client{user="hello"} 173886
telemt_user_msgs_to_client{user="hello"} 472410
telemt_user_unique_ips_current{user="hello"} 1980
telemt_user_unique_ips_recent_window{user="hello"} 1049
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 61195.8 (16h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3216720
telemt_connections_bad_total 370543
telemt_connections_current 3653
telemt_connections_me_current 3653
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 71184
telemt_upstream_connect_attempt_total 26227
telemt_upstream_connect_success_total 25942
telemt_upstream_connect_fail_total 255
telemt_upstream_connect_attempts_per_request{bucket="1"} 26197
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12418
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13460
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 64
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 255
telemt_me_reconnect_attempts_total 2531
telemt_me_reconnect_success_total 902
telemt_me_reader_eof_total 895
telemt_me_idle_close_by_peer_total 895
telemt_me_route_drop_no_conn_total 1241077
telemt_me_route_drop_channel_closed_total 7
telemt_me_route_drop_queue_full_total 33
telemt_me_route_drop_queue_full_profile_total{profile="high"} 33
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2452587
telemt_me_endpoint_quarantine_total 383
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 11
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 11
telemt_me_single_endpoint_shadow_rotate_total 461
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 24
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
telemt_me_writers_active_current 46
telemt_desync_total 11471
telemt_desync_full_logged_total 3974
telemt_desync_suppressed_total 7497
telemt_desync_frames_bucket_total{bucket="1_2"} 2223
telemt_desync_frames_bucket_total{bucket="3_10"} 4568
telemt_desync_frames_bucket_total{bucket="gt_10"} 4680
telemt_pool_swap_total 61
telemt_pool_force_close_total 1741
telemt_pool_stale_pick_total 54
telemt_me_writer_close_signal_drop_total 163
telemt_me_draining_writers_reap_progress_total 21932
telemt_me_writer_removed_unexpected_total 865
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2126
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 20701
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1527
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 214
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 20191
telemt_me_writer_teardown_success_total{mode="normal"} 22827
telemt_me_writer_teardown_noop_total 21933
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 44251
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 44568
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 44730
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 44760
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 44760
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 44760
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 44760
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 44760
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 44760
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 44760
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 44760
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 44760
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 44760
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 2.827432
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 44760
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 163
telemt_me_refill_failed_total 89
telemt_me_writer_restored_same_endpoint_total 767
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20
telemt_me_writer_removed_unexpected_minus_restored_total 88
telemt_user_connections_total{user="hello"} 2437241
telemt_user_connections_current{user="hello"} 3653
telemt_user_octets_from_client{user="hello"} 49845242476 (46.42 GB)
telemt_user_octets_to_client{user="hello"} 1059113050330 (986.38 GB)
telemt_user_msgs_from_client{user="hello"} 7339
telemt_user_msgs_to_client{user="hello"} 11522
telemt_user_unique_ips_current{user="hello"} 1496
telemt_user_unique_ips_recent_window{user="hello"} 673
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 61190.6 (16h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4927865
telemt_connections_bad_total 242511
telemt_connections_current 3629
telemt_connections_me_current 3629
telemt_handshake_timeouts_total 2174945
telemt_upstream_connect_attempt_total 24190
telemt_upstream_connect_success_total 24156
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 24159
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10797
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13069
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 290
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_reconnect_attempts_total 1016
telemt_me_reconnect_success_total 432
telemt_me_reader_eof_total 442
telemt_me_idle_close_by_peer_total 442
telemt_me_route_drop_no_conn_total 1148292
telemt_me_route_drop_channel_closed_total 5
telemt_me_route_drop_queue_full_total 13
telemt_me_route_drop_queue_full_profile_total{profile="high"} 13
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2214447
telemt_me_endpoint_quarantine_total 451
telemt_me_single_endpoint_outage_enter_total 2
telemt_me_single_endpoint_outage_exit_total 2
telemt_me_single_endpoint_outage_reconnect_attempt_total 2
telemt_me_single_endpoint_outage_reconnect_success_total 2
telemt_me_single_endpoint_quarantine_bypass_total 2
telemt_me_single_endpoint_shadow_rotate_total 473
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
telemt_desync_total 10530
telemt_desync_full_logged_total 3720
telemt_desync_suppressed_total 6810
telemt_desync_frames_bucket_total{bucket="1_2"} 1947
telemt_desync_frames_bucket_total{bucket="3_10"} 4172
telemt_desync_frames_bucket_total{bucket="gt_10"} 4411
telemt_pool_swap_total 66
telemt_pool_force_close_total 1684
telemt_me_writer_close_signal_drop_total 148
telemt_me_draining_writers_reap_progress_total 21645
telemt_me_writer_removed_unexpected_total 424
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1480
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 20616
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1627
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 57
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 19961
telemt_me_writer_teardown_success_total{mode="normal"} 22096
telemt_me_writer_teardown_noop_total 21645
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 43449
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 43653
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 43725
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 43741
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 43741
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 43741
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 43741
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 43741
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 43741
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 43741
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 43741
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 43741
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 43741
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 1.581191
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 43741
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 148
telemt_me_refill_failed_total 32
telemt_me_writer_restored_same_endpoint_total 376
telemt_me_writer_restored_fallback_total 2
telemt_me_writer_removed_unexpected_minus_restored_total 46
telemt_user_connections_total{user="hello"} 2207621
telemt_user_connections_current{user="hello"} 3629
telemt_user_octets_from_client{user="hello"} 45257258780 (42.15 GB)
telemt_user_octets_to_client{user="hello"} 1027120721276 (956.58 GB)
telemt_user_unique_ips_current{user="hello"} 1528
telemt_user_unique_ips_recent_window{user="hello"} 662
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 59182.2 (16h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1057090
telemt_connections_bad_total 133515
telemt_connections_current 725
telemt_connections_me_current 725
telemt_handshake_timeouts_total 368680
telemt_upstream_connect_attempt_total 27799
telemt_upstream_connect_success_total 27797
telemt_upstream_connect_attempts_per_request{bucket="1"} 27797
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11431
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16283
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 83
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 1190
telemt_me_reconnect_success_total 461
telemt_me_reader_eof_total 460
telemt_me_idle_close_by_peer_total 460
telemt_me_route_drop_no_conn_total 220930
telemt_me_route_drop_channel_closed_total 14
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 485131
telemt_me_endpoint_quarantine_total 548
telemt_me_single_endpoint_outage_enter_total 7
telemt_me_single_endpoint_outage_exit_total 7
telemt_me_single_endpoint_outage_reconnect_attempt_total 7
telemt_me_single_endpoint_outage_reconnect_success_total 6
telemt_me_single_endpoint_quarantine_bypass_total 7
telemt_me_single_endpoint_shadow_rotate_total 499
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
telemt_desync_total 3203
telemt_desync_full_logged_total 1191
telemt_desync_suppressed_total 2012
telemt_desync_frames_bucket_total{bucket="1_2"} 558
telemt_desync_frames_bucket_total{bucket="3_10"} 1144
telemt_desync_frames_bucket_total{bucket="gt_10"} 1501
telemt_pool_swap_total 65
telemt_pool_force_close_total 1473
telemt_pool_stale_pick_total 7
telemt_me_writer_close_signal_drop_total 103
telemt_me_draining_writers_reap_progress_total 24914
telemt_me_writer_removed_unexpected_total 434
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1833
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 23526
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1470
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 23441
telemt_me_writer_teardown_success_total{mode="normal"} 25359
telemt_me_writer_teardown_noop_total 24914
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 49712
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 50128
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 50235
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 50265
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 50273
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 50273
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 50273
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 50273
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 50273
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 50273
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 50273
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 50273
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 50273
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.329393
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 50273
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 103
telemt_me_refill_failed_total 38
telemt_me_writer_restored_same_endpoint_total 374
telemt_me_writer_restored_fallback_total 5
telemt_me_writer_removed_unexpected_minus_restored_total 55
telemt_user_connections_total{user="hello"} 484919
telemt_user_connections_current{user="hello"} 725
telemt_user_octets_from_client{user="hello"} 8765347659 (8.16 GB)
telemt_user_octets_to_client{user="hello"} 185316998829 (172.59 GB)
telemt_user_msgs_from_client{user="hello"} 804
telemt_user_msgs_to_client{user="hello"} 1943
telemt_user_unique_ips_current{user="hello"} 297
telemt_user_unique_ips_recent_window{user="hello"} 121
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 61200.3 (17h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3487146
telemt_connections_bad_total 326472
telemt_connections_current 4347
telemt_connections_me_current 4347
telemt_handshake_timeouts_total 105181
telemt_upstream_connect_attempt_total 24994
telemt_upstream_connect_success_total 24890
telemt_upstream_connect_fail_total 72
telemt_upstream_connect_attempts_per_request{bucket="1"} 24962
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12390
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12469
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 30
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 72
telemt_me_reconnect_attempts_total 1018
telemt_me_reconnect_success_total 570
telemt_me_reader_eof_total 531
telemt_me_idle_close_by_peer_total 531
telemt_me_route_drop_no_conn_total 1011227
telemt_me_route_drop_channel_closed_total 26
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2756088
telemt_me_endpoint_quarantine_total 463
telemt_me_single_endpoint_outage_enter_total 8
telemt_me_single_endpoint_outage_exit_total 8
telemt_me_single_endpoint_outage_reconnect_attempt_total 8
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 8
telemt_me_single_endpoint_shadow_rotate_total 470
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 24
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
telemt_me_writers_active_current 46
telemt_desync_total 11065
telemt_desync_full_logged_total 3636
telemt_desync_suppressed_total 7429
telemt_desync_frames_bucket_total{bucket="1_2"} 2631
telemt_desync_frames_bucket_total{bucket="3_10"} 4113
telemt_desync_frames_bucket_total{bucket="gt_10"} 4321
telemt_pool_swap_total 67
telemt_pool_force_close_total 1731
telemt_pool_stale_pick_total 2
telemt_me_writer_close_signal_drop_total 187
telemt_me_draining_writers_reap_progress_total 22444
telemt_me_writer_removed_unexpected_total 521
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1742
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 21222
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1700
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 31
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 20713
telemt_me_writer_teardown_success_total{mode="normal"} 22964
telemt_me_writer_teardown_noop_total 22444
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 44801
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 45195
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 45275
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 45385
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 45408
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 45408
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 45408
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 45408
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 45408
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 45408
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 45408
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 45408
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 45408
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 4.635866
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 45408
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 187
telemt_me_refill_failed_total 22
telemt_me_writer_restored_same_endpoint_total 503
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 13
telemt_user_connections_total{user="hello"} 2748729
telemt_user_connections_current{user="hello"} 4347
telemt_user_octets_from_client{user="hello"} 58337214832 (54.33 GB)
telemt_user_octets_to_client{user="hello"} 1292924252212 (1.18 TB)
telemt_user_unique_ips_current{user="hello"} 1599
telemt_user_unique_ips_recent_window{user="hello"} 593
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 61197.1 (16h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3128447
telemt_connections_bad_total 259411
telemt_connections_current 3890
telemt_connections_me_current 3890
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 92121
telemt_upstream_connect_attempt_total 41176
telemt_upstream_connect_success_total 40910
telemt_upstream_connect_fail_total 221
telemt_upstream_connect_attempts_per_request{bucket="1"} 41131
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 25650
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14157
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 516
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 587
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 221
telemt_me_reconnect_attempts_total 3496
telemt_me_reconnect_success_total 742
telemt_me_reader_eof_total 648
telemt_me_idle_close_by_peer_total 648
telemt_me_seq_mismatch_total 30
telemt_me_route_drop_no_conn_total 1055221
telemt_me_route_drop_channel_closed_total 78
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2519743
telemt_me_endpoint_quarantine_total 520
telemt_me_single_endpoint_outage_enter_total 16
telemt_me_single_endpoint_outage_exit_total 16
telemt_me_single_endpoint_outage_reconnect_attempt_total 16
telemt_me_single_endpoint_outage_reconnect_success_total 16
telemt_me_single_endpoint_quarantine_bypass_total 16
telemt_me_single_endpoint_shadow_rotate_total 470
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 19
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
telemt_me_writers_active_current 41
telemt_desync_total 9743
telemt_desync_full_logged_total 3334
telemt_desync_suppressed_total 6409
telemt_desync_frames_bucket_total{bucket="1_2"} 2484
telemt_desync_frames_bucket_total{bucket="3_10"} 3598
telemt_desync_frames_bucket_total{bucket="gt_10"} 3661
telemt_pool_swap_total 66
telemt_pool_force_close_total 1678
telemt_me_writer_close_signal_drop_total 173
telemt_me_draining_writers_reap_progress_total 21601
telemt_me_writer_removed_unexpected_total 660
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2045
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 20246
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1567
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 111
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 19923
telemt_me_writer_teardown_success_total{mode="normal"} 22291
telemt_me_writer_teardown_noop_total 21602
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 43205
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 43621
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 43776
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 43885
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 43893
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 43893
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 43893
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 43893
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 43893
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 43893
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 43893
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 43893
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 43893
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 4.925086
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 43893
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 173
telemt_me_refill_failed_total 156
telemt_me_writer_restored_same_endpoint_total 566
telemt_me_writer_restored_fallback_total 39
telemt_me_async_recovery_trigger_total 53
telemt_me_writer_removed_unexpected_minus_restored_total 55
telemt_user_connections_total{user="hello"} 2529063
telemt_user_connections_current{user="hello"} 3890
telemt_user_octets_from_client{user="hello"} 46470844617 (43.28 GB)
telemt_user_octets_to_client{user="hello"} 1102675165804 (1.00 TB)
telemt_user_msgs_from_client{user="hello"} 75721
telemt_user_msgs_to_client{user="hello"} 209236
telemt_user_unique_ips_current{user="hello"} 1544
telemt_user_unique_ips_recent_window{user="hello"} 547
```