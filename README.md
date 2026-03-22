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

_Можете писать свой ник в коментарии к переводу_

### [Итог по хостингам](Reviews.md)

---

## NKtelecom
- Локация: Netherlands - Amsterdam
- Тариф: AMS-CLOUD-60
- Краткое описание тарифа: 4 vCore, 4 Gb ram, 1 Gbit/s
- Цена в месяц: 4.99$
- Оплачен до: 26 апреля
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
- Ссылка:
```bash
tg://proxy?server=s5.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## hostvds.com
- Локация: Франция, Париж
- Тариф: Highload-2
- Краткое описание тарифа: 2 vCore, 8 Gb ram, 10 Gbit/s
- Цена в месяц: €12.57
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

# Server Metrics 2026-03-22 17:46:05 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 74381.8 (20h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2689152
telemt_connections_bad_total 150228
telemt_connections_current 1522
telemt_connections_me_current 1522
telemt_handshake_timeouts_total 92246
telemt_upstream_connect_attempt_total 27382
telemt_upstream_connect_success_total 27381
telemt_upstream_connect_attempts_per_request{bucket="1"} 27381
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9490
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17805
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 63
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 23
telemt_me_keepalive_failed_total 4
telemt_me_keepalive_timeout_total 150
telemt_me_reconnect_attempts_total 1119
telemt_me_reconnect_success_total 471
telemt_me_reader_eof_total 473
telemt_me_idle_close_by_peer_total 473
telemt_me_route_drop_no_conn_total 2215750
telemt_me_route_drop_channel_closed_total 922
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2291943
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_endpoint_quarantine_total 507
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 582
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
telemt_desync_total 10596
telemt_desync_full_logged_total 3351
telemt_desync_suppressed_total 7245
telemt_desync_frames_bucket_total{bucket="1_2"} 2837
telemt_desync_frames_bucket_total{bucket="3_10"} 3938
telemt_desync_frames_bucket_total{bucket="gt_10"} 3821
telemt_pool_swap_total 82
telemt_pool_force_close_total 2542
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 517
telemt_me_draining_writers_reap_progress_total 25010
telemt_me_writer_removed_unexpected_total 459
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1830
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 23409
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 10
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2490
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 52
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 22468
telemt_me_writer_teardown_success_total{mode="normal"} 25239
telemt_me_writer_teardown_noop_total 25020
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 40258
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 42103
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 43891
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 46982
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 49035
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 49971
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 50255
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 50259
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 50259
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 50259
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 50259
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 50259
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 50259
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 247.935639
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 50259
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 517
telemt_me_refill_failed_total 34
telemt_me_writer_restored_same_endpoint_total 416
telemt_me_writer_restored_fallback_total 1
telemt_me_writer_removed_unexpected_minus_restored_total 42
telemt_user_connections_total{user="hello"} 2288171
telemt_user_connections_current{user="hello"} 1522
telemt_user_octets_from_client{user="hello"} 33770007128 (31.45 GB)
telemt_user_octets_to_client{user="hello"} 605552528708 (563.96 GB)
telemt_user_unique_ips_current{user="hello"} 589
telemt_user_unique_ips_recent_window{user="hello"} 203
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 87749.0 (24h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3693694
telemt_connections_bad_total 334864
telemt_connections_current 753
telemt_connections_me_current 753
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 4
telemt_handshake_timeouts_total 93698
telemt_upstream_connect_attempt_total 54139
telemt_upstream_connect_success_total 53466
telemt_upstream_connect_fail_total 593
telemt_upstream_connect_attempts_per_request{bucket="1"} 54059
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 30722
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22570
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 174
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 593
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 6258
telemt_me_reconnect_success_total 2266
telemt_me_reader_eof_total 2197
telemt_me_idle_close_by_peer_total 2197
telemt_me_route_drop_no_conn_total 3562546
telemt_me_route_drop_channel_closed_total 36
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2930355
telemt_me_endpoint_quarantine_total 694
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_outage_enter_total 39
telemt_me_single_endpoint_outage_exit_total 39
telemt_me_single_endpoint_outage_reconnect_attempt_total 39
telemt_me_single_endpoint_outage_reconnect_success_total 38
telemt_me_single_endpoint_quarantine_bypass_total 39
telemt_me_single_endpoint_shadow_rotate_total 678
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
telemt_me_writers_active_current 43
telemt_desync_total 11535
telemt_desync_full_logged_total 6446
telemt_desync_suppressed_total 5089
telemt_desync_frames_bucket_total{bucket="1_2"} 2680
telemt_desync_frames_bucket_total{bucket="3_10"} 4530
telemt_desync_frames_bucket_total{bucket="gt_10"} 4325
telemt_pool_swap_total 83
telemt_pool_force_close_total 2495
telemt_pool_stale_pick_total 3
telemt_me_writer_close_signal_drop_total 210
telemt_me_draining_writers_reap_progress_total 34807
telemt_me_writer_removed_unexpected_total 2148
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4154
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 32811
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2133
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 362
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 32312
telemt_me_writer_teardown_success_total{mode="normal"} 36965
telemt_me_writer_teardown_noop_total 34807
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 70015
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 71120
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 71400
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 71706
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 71757
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 71770
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 71772
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 71772
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 71772
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 71772
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 71772
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 71772
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 71772
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 13.278145
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 71772
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 210
telemt_me_refill_failed_total 158
telemt_me_writer_restored_same_endpoint_total 1956
telemt_me_writer_restored_fallback_total 25
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 167
telemt_user_connections_total{user="hello"} 2941249
telemt_user_connections_current{user="hello"} 753
telemt_user_octets_from_client{user="hello"} 37725413635 (35.13 GB)
telemt_user_octets_to_client{user="hello"} 671104428438 (625.01 GB)
telemt_user_msgs_from_client{user="hello"} 42816
telemt_user_msgs_to_client{user="hello"} 172415
telemt_user_unique_ips_current{user="hello"} 464
telemt_user_unique_ips_recent_window{user="hello"} 242
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 162608.5 (45h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 15587431
telemt_connections_bad_total 1489896
telemt_connections_current 2203
telemt_connections_me_current 2203
telemt_relay_adaptive_promotions_total 19
telemt_relay_adaptive_hard_promotions_total 19
telemt_handshake_timeouts_total 382281
telemt_upstream_connect_attempt_total 72991
telemt_upstream_connect_success_total 72894
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 72911
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 36542
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 34667
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1678
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 2703
telemt_me_reconnect_success_total 1391
telemt_me_reader_eof_total 1329
telemt_me_idle_close_by_peer_total 1327
telemt_me_route_drop_no_conn_total 13871977
telemt_me_route_drop_channel_closed_total 140
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 12426447
telemt_me_endpoint_quarantine_total 1020
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 11
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 11
telemt_me_single_endpoint_shadow_rotate_total 1210
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 41
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
telemt_me_writers_active_current 43
telemt_desync_total 50929
telemt_desync_full_logged_total 15985
telemt_desync_suppressed_total 34944
telemt_desync_frames_bucket_total{bucket="1_2"} 11374
telemt_desync_frames_bucket_total{bucket="3_10"} 19877
telemt_desync_frames_bucket_total{bucket="gt_10"} 19678
telemt_pool_swap_total 175
telemt_pool_force_close_total 5937
telemt_pool_stale_pick_total 19
telemt_me_writer_close_signal_drop_total 959
telemt_me_draining_writers_reap_progress_total 53441
telemt_me_writer_removed_unexpected_total 1283
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4669
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 49346
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 42
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 8
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5475
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 462
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 47504
telemt_me_writer_teardown_success_total{mode="normal"} 54015
telemt_me_writer_teardown_noop_total 53491
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 97202
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 100509
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 102132
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 104323
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 105903
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 106909
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 107467
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 107497
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 107498
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 107502
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 107504
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 107506
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 107506
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 304.652530
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 107506
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 959
telemt_me_refill_failed_total 72
telemt_me_writer_restored_same_endpoint_total 1196
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 22
telemt_me_writer_removed_unexpected_minus_restored_total 80
telemt_user_connections_total{user="hello"} 12427393
telemt_user_connections_current{user="hello"} 2203
telemt_user_octets_from_client{user="hello"} 179522162213 (167.19 GB)
telemt_user_octets_to_client{user="hello"} 3238968141187 (2.95 TB)
telemt_user_msgs_from_client{user="hello"} 57811
telemt_user_msgs_to_client{user="hello"} 118217
telemt_user_unique_ips_current{user="hello"} 907
telemt_user_unique_ips_recent_window{user="hello"} 261
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 162608.9 (45h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11240428
telemt_connections_bad_total 1097422
telemt_connections_current 1417
telemt_connections_me_current 1417
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 336843
telemt_upstream_connect_attempt_total 85405
telemt_upstream_connect_success_total 84205
telemt_upstream_connect_fail_total 838
telemt_upstream_connect_attempts_per_request{bucket="1"} 85043
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 45761
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 34574
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 169
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3701
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 838
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 187
telemt_me_reconnect_attempts_total 4044
telemt_me_reconnect_success_total 1675
telemt_me_reader_eof_total 1543
telemt_me_idle_close_by_peer_total 1543
telemt_me_route_drop_no_conn_total 4415442
telemt_me_route_drop_channel_closed_total 489
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8378318
telemt_me_endpoint_quarantine_total 1026
telemt_me_single_endpoint_outage_enter_total 27
telemt_me_single_endpoint_outage_exit_total 27
telemt_me_single_endpoint_outage_reconnect_attempt_total 32
telemt_me_single_endpoint_outage_reconnect_success_total 25
telemt_me_single_endpoint_quarantine_bypass_total 32
telemt_me_single_endpoint_shadow_rotate_total 1229
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 45
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
telemt_desync_total 37256
telemt_desync_full_logged_total 12535
telemt_desync_suppressed_total 24721
telemt_desync_frames_bucket_total{bucket="1_2"} 9160
telemt_desync_frames_bucket_total{bucket="3_10"} 14346
telemt_desync_frames_bucket_total{bucket="gt_10"} 13750
telemt_pool_swap_total 172
telemt_pool_force_close_total 5364
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 684
telemt_me_draining_writers_reap_progress_total 51848
telemt_me_writer_removed_unexpected_total 1583
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4807
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 48467
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 23
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4866
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 498
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 46484
telemt_me_writer_teardown_success_total{mode="normal"} 53274
telemt_me_writer_teardown_noop_total 51871
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 98734
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 101743
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 102844
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 103975
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 104721
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 105060
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 105135
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 105137
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 105143
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 105145
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 105145
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 105145
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 105145
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 101.946720
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 105145
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 684
telemt_me_refill_failed_total 128
telemt_me_writer_restored_same_endpoint_total 1435
telemt_me_writer_restored_fallback_total 15
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 216
telemt_me_writer_removed_unexpected_minus_restored_total 133
telemt_user_connections_total{user="hello"} 8316816
telemt_user_connections_current{user="hello"} 1417
telemt_user_octets_from_client{user="hello"} 207767915517 (193.50 GB)
telemt_user_octets_to_client{user="hello"} 3748134164298 (3.41 TB)
telemt_user_msgs_from_client{user="hello"} 113340
telemt_user_msgs_to_client{user="hello"} 116189
telemt_user_unique_ips_current{user="hello"} 545
telemt_user_unique_ips_recent_window{user="hello"} 199
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 162573.8 (45h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10596202
telemt_connections_bad_total 913379
telemt_connections_current 1388
telemt_connections_me_current 1388
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 339513
telemt_upstream_connect_attempt_total 70556
telemt_upstream_connect_success_total 69560
telemt_upstream_connect_fail_total 182
telemt_upstream_connect_attempts_per_request{bucket="1"} 69742
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 32931
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 33116
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1413
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2100
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 182
telemt_me_keepalive_timeout_total 1383
telemt_me_reconnect_attempts_total 4791
telemt_me_reconnect_success_total 1936
telemt_me_reader_eof_total 1688
telemt_me_idle_close_by_peer_total 1687
telemt_me_route_drop_no_conn_total 5176188
telemt_me_route_drop_channel_closed_total 368
telemt_me_route_drop_queue_full_total 9
telemt_me_route_drop_queue_full_profile_total{profile="high"} 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 7997140
telemt_me_endpoint_quarantine_total 1107
telemt_me_single_endpoint_outage_enter_total 32
telemt_me_single_endpoint_outage_exit_total 32
telemt_me_single_endpoint_outage_reconnect_attempt_total 33
telemt_me_single_endpoint_outage_reconnect_success_total 27
telemt_me_single_endpoint_quarantine_bypass_total 33
telemt_me_single_endpoint_shadow_rotate_total 1197
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 56
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
telemt_desync_total 36799
telemt_desync_full_logged_total 12167
telemt_desync_suppressed_total 24632
telemt_desync_frames_bucket_total{bucket="1_2"} 9303
telemt_desync_frames_bucket_total{bucket="3_10"} 14076
telemt_desync_frames_bucket_total{bucket="gt_10"} 13420
telemt_pool_swap_total 170
telemt_pool_force_close_total 5290
telemt_pool_stale_pick_total 1619
telemt_me_writer_close_signal_drop_total 688
telemt_me_draining_writers_reap_progress_total 52154
telemt_me_writer_removed_unexpected_total 1830
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5227
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 48670
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 25
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 46
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4748
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 542
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 46864
telemt_me_writer_teardown_success_total{mode="normal"} 53897
telemt_me_writer_teardown_noop_total 52225
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 100596
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 103124
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 104031
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 105072
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 105643
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 105855
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 105983
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 106014
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 106022
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 106035
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 106068
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 106071
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 106122
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3172.209379
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 106122
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 688
telemt_me_refill_failed_total 151
telemt_me_writer_restored_same_endpoint_total 1675
telemt_me_writer_restored_fallback_total 10
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 68
telemt_me_writer_removed_unexpected_minus_restored_total 145
telemt_user_connections_total{user="hello"} 7989920
telemt_user_connections_current{user="hello"} 1388
telemt_user_octets_from_client{user="hello"} 184627154493 (171.95 GB)
telemt_user_octets_to_client{user="hello"} 3324331291853 (3.02 TB)
telemt_user_msgs_from_client{user="hello"} 46485
telemt_user_msgs_to_client{user="hello"} 113805
telemt_user_unique_ips_current{user="hello"} 554
telemt_user_unique_ips_recent_window{user="hello"} 159
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 32853.0 (9h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10418670
telemt_connections_bad_total 637827
telemt_connections_current 2294
telemt_connections_me_current 2294
telemt_relay_adaptive_promotions_total 8
telemt_relay_adaptive_hard_promotions_total 8
telemt_handshake_timeouts_total 204442
telemt_upstream_connect_attempt_total 41537
telemt_upstream_connect_success_total 39442
telemt_upstream_connect_fail_total 1482
telemt_upstream_connect_attempts_per_request{bucket="1"} 40924
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20316
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11821
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1389
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5916
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1482
telemt_me_keepalive_timeout_total 975
telemt_me_reconnect_attempts_total 6163
telemt_me_reconnect_success_total 791
telemt_me_reader_eof_total 494
telemt_me_idle_close_by_peer_total 494
telemt_me_route_drop_no_conn_total 25046098
telemt_me_route_drop_channel_closed_total 52
telemt_me_route_drop_queue_full_total 27
telemt_me_route_drop_queue_full_profile_total{profile="high"} 27
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8661390
telemt_me_endpoint_quarantine_total 209
telemt_me_single_endpoint_outage_enter_total 59
telemt_me_single_endpoint_outage_exit_total 59
telemt_me_single_endpoint_outage_reconnect_attempt_total 110
telemt_me_single_endpoint_outage_reconnect_success_total 32
telemt_me_single_endpoint_quarantine_bypass_total 110
telemt_me_single_endpoint_shadow_rotate_total 260
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
telemt_me_writers_active_current 46
telemt_desync_total 13747
telemt_desync_full_logged_total 3579
telemt_desync_suppressed_total 10168
telemt_desync_frames_bucket_total{bucket="1_2"} 2538
telemt_desync_frames_bucket_total{bucket="3_10"} 5573
telemt_desync_frames_bucket_total{bucket="gt_10"} 5636
telemt_pool_swap_total 32
telemt_pool_force_close_total 1215
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 385
telemt_me_draining_writers_reap_progress_total 9225
telemt_me_writer_removed_unexpected_total 697
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1452
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 8432
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 933
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 282
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 8010
telemt_me_writer_teardown_success_total{mode="normal"} 9884
telemt_me_writer_teardown_noop_total 9230
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 16194
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 17564
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 18045
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 18658
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 18959
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 19065
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 19114
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 19114
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 19114
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 19114
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 19114
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 19114
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 19114
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 42.170216
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 19114
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 385
telemt_me_refill_failed_total 297
telemt_me_writer_restored_same_endpoint_total 530
telemt_me_writer_restored_fallback_total 4
telemt_me_no_writer_failfast_total 86
telemt_me_async_recovery_trigger_total 3059
telemt_me_writer_removed_unexpected_minus_restored_total 163
telemt_user_connections_total{user="hello"} 8683085
telemt_user_connections_current{user="hello"} 2294
telemt_user_octets_from_client{user="hello"} 73342033771 (68.31 GB)
telemt_user_octets_to_client{user="hello"} 372403858241 (346.83 GB)
telemt_user_msgs_from_client{user="hello"} 57283
telemt_user_msgs_to_client{user="hello"} 45481
telemt_user_unique_ips_current{user="hello"} 838
telemt_user_unique_ips_recent_window{user="hello"} 295
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 162579.6 (45h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10422139
telemt_connections_bad_total 876926
telemt_connections_current 1907
telemt_connections_me_current 1907
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 231074
telemt_upstream_connect_attempt_total 99275
telemt_upstream_connect_success_total 98246
telemt_upstream_connect_fail_total 874
telemt_upstream_connect_attempts_per_request{bucket="1"} 99120
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 60408
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 36283
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 238
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1317
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 874
telemt_me_keepalive_timeout_total 11
telemt_me_reconnect_attempts_total 72103
telemt_me_reconnect_success_total 2676
telemt_me_reader_eof_total 2378
telemt_me_idle_close_by_peer_total 2376
telemt_me_route_drop_no_conn_total 5114078
telemt_me_route_drop_channel_closed_total 22
telemt_me_route_drop_queue_full_total 46
telemt_me_route_drop_queue_full_profile_total{profile="high"} 46
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8222857
telemt_me_endpoint_quarantine_total 1089
telemt_me_single_endpoint_outage_enter_total 38
telemt_me_single_endpoint_outage_exit_total 38
telemt_me_single_endpoint_outage_reconnect_attempt_total 40
telemt_me_single_endpoint_outage_reconnect_success_total 38
telemt_me_single_endpoint_quarantine_bypass_total 40
telemt_me_single_endpoint_shadow_rotate_total 1212
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 49
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
telemt_desync_total 43300
telemt_desync_full_logged_total 14777
telemt_desync_suppressed_total 28523
telemt_desync_frames_bucket_total{bucket="1_2"} 8811
telemt_desync_frames_bucket_total{bucket="3_10"} 16692
telemt_desync_frames_bucket_total{bucket="gt_10"} 17797
telemt_pool_swap_total 166
telemt_pool_force_close_total 4935
telemt_pool_stale_pick_total 69
telemt_me_writer_close_signal_drop_total 617
telemt_me_draining_writers_reap_progress_total 55270
telemt_me_writer_removed_unexpected_total 2419
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5913
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 51799
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4249
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 686
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 50335
telemt_me_writer_teardown_success_total{mode="normal"} 57712
telemt_me_writer_teardown_noop_total 55271
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 110964
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 112283
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 112667
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 112939
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 112973
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 112976
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 112976
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 112979
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 112983
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 112983
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 112983
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 112983
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 112983
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 16.600686
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 112983
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 617
telemt_me_refill_failed_total 4279
telemt_me_writer_restored_same_endpoint_total 2244
telemt_me_writer_restored_fallback_total 46
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7365
telemt_me_writer_removed_unexpected_minus_restored_total 129
telemt_user_connections_total{user="hello"} 8226545
telemt_user_connections_current{user="hello"} 1907
telemt_user_octets_from_client{user="hello"} 186821717329 (173.99 GB)
telemt_user_octets_to_client{user="hello"} 3106966365032 (2.83 TB)
telemt_user_msgs_from_client{user="hello"} 160634
telemt_user_msgs_to_client{user="hello"} 619200
telemt_user_unique_ips_current{user="hello"} 732
telemt_user_unique_ips_recent_window{user="hello"} 252
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 99415.7 (27h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10894592
telemt_connections_bad_total 416763
telemt_connections_current 1626
telemt_connections_me_current 1626
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 4536415
telemt_upstream_connect_attempt_total 47485
telemt_upstream_connect_success_total 47129
telemt_upstream_connect_fail_total 347
telemt_upstream_connect_attempts_per_request{bucket="1"} 47476
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26213
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20747
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 169
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 347
telemt_me_reconnect_attempts_total 48235
telemt_me_reconnect_success_total 1569
telemt_me_reader_eof_total 1227
telemt_me_idle_close_by_peer_total 1226
telemt_me_route_drop_no_conn_total 3964795
telemt_me_route_drop_channel_closed_total 12
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5234730
telemt_me_endpoint_quarantine_total 644
telemt_me_single_endpoint_outage_enter_total 18
telemt_me_single_endpoint_outage_exit_total 18
telemt_me_single_endpoint_outage_reconnect_attempt_total 58
telemt_me_single_endpoint_outage_reconnect_success_total 18
telemt_me_single_endpoint_quarantine_bypass_total 58
telemt_me_single_endpoint_shadow_rotate_total 749
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
telemt_me_floor_cap_block_total 23
telemt_me_floor_swap_idle_failed_total 23
telemt_desync_total 29156
telemt_desync_full_logged_total 9883
telemt_desync_suppressed_total 19273
telemt_desync_frames_bucket_total{bucket="1_2"} 5884
telemt_desync_frames_bucket_total{bucket="3_10"} 11508
telemt_desync_frames_bucket_total{bucket="gt_10"} 11764
telemt_pool_swap_total 105
telemt_pool_force_close_total 3223
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 335
telemt_me_draining_writers_reap_progress_total 34264
telemt_me_writer_removed_unexpected_total 1287
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3073
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 32511
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2801
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 422
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 31041
telemt_me_writer_teardown_success_total{mode="normal"} 35584
telemt_me_writer_teardown_noop_total 34271
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 68663
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 69356
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 69628
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 69855
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 69855
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 69855
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 69855
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 69855
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 69855
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 69855
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 69855
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 69855
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 69855
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 8.139252
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 69855
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 335
telemt_me_refill_failed_total 2712
telemt_me_writer_restored_same_endpoint_total 1393
telemt_me_writer_restored_fallback_total 16
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4330
telemt_user_connections_total{user="hello"} 5227952
telemt_user_connections_current{user="hello"} 1626
telemt_user_octets_from_client{user="hello"} 112991141528 (105.23 GB)
telemt_user_octets_to_client{user="hello"} 1987098181266 (1.81 TB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 594
telemt_user_unique_ips_recent_window{user="hello"} 224
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 80386.9 (22h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1135457
telemt_connections_bad_total 18955
telemt_connections_current 1115
telemt_connections_me_current 1115
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 21147
telemt_upstream_connect_attempt_total 38903
telemt_upstream_connect_success_total 38788
telemt_upstream_connect_fail_total 89
telemt_upstream_connect_attempts_per_request{bucket="1"} 38877
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17585
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20597
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 606
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 89
telemt_me_reconnect_attempts_total 1752
telemt_me_reconnect_success_total 745
telemt_me_reader_eof_total 721
telemt_me_idle_close_by_peer_total 721
telemt_me_route_drop_no_conn_total 396784
telemt_me_route_drop_channel_closed_total 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1010272
telemt_me_endpoint_quarantine_total 683
telemt_me_single_endpoint_outage_enter_total 8
telemt_me_single_endpoint_outage_exit_total 8
telemt_me_single_endpoint_outage_reconnect_attempt_total 9
telemt_me_single_endpoint_outage_reconnect_success_total 7
telemt_me_single_endpoint_quarantine_bypass_total 9
telemt_me_single_endpoint_shadow_rotate_total 663
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 15
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
telemt_desync_total 5836
telemt_desync_full_logged_total 1781
telemt_desync_suppressed_total 4055
telemt_desync_frames_bucket_total{bucket="1_2"} 1370
telemt_desync_frames_bucket_total{bucket="3_10"} 2294
telemt_desync_frames_bucket_total{bucket="gt_10"} 2172
telemt_pool_swap_total 86
telemt_pool_force_close_total 2208
telemt_me_writer_close_signal_drop_total 126
telemt_me_draining_writers_reap_progress_total 32287
telemt_me_writer_removed_unexpected_total 695
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2501
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 30509
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2125
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 83
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 30079
telemt_me_writer_teardown_success_total{mode="normal"} 33010
telemt_me_writer_teardown_noop_total 32290
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 64611
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 65104
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 65268
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 65300
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 65300
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 65300
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 65300
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 65300
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 65300
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 65300
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 65300
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 65300
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 65300
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.839237
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 65300
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 126
telemt_me_refill_failed_total 55
telemt_me_writer_restored_same_endpoint_total 635
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 46
telemt_user_connections_total{user="hello"} 1006655
telemt_user_connections_current{user="hello"} 1115
telemt_user_octets_from_client{user="hello"} 18504535045 (17.23 GB)
telemt_user_octets_to_client{user="hello"} 432492902655 (402.79 GB)
telemt_user_msgs_from_client{user="hello"} 18894
telemt_user_msgs_to_client{user="hello"} 38815
telemt_user_unique_ips_current{user="hello"} 412
telemt_user_unique_ips_recent_window{user="hello"} 176
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 162584.7 (45h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 12703556
telemt_connections_bad_total 1473143
telemt_connections_current 1980
telemt_connections_me_current 1980
telemt_handshake_timeouts_total 356630
telemt_upstream_connect_attempt_total 61193
telemt_upstream_connect_success_total 60898
telemt_upstream_connect_fail_total 188
telemt_upstream_connect_attempts_per_request{bucket="1"} 61086
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 30028
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 30786
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 82
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 188
telemt_me_reconnect_attempts_total 2407
telemt_me_reconnect_success_total 1271
telemt_me_reader_eof_total 1234
telemt_me_idle_close_by_peer_total 1234
telemt_me_route_drop_no_conn_total 4281926
telemt_me_route_drop_channel_closed_total 121
telemt_me_route_drop_queue_full_total 37
telemt_me_route_drop_queue_full_profile_total{profile="high"} 37
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9611492
telemt_me_endpoint_quarantine_total 1085
telemt_me_single_endpoint_outage_enter_total 12
telemt_me_single_endpoint_outage_exit_total 12
telemt_me_single_endpoint_outage_reconnect_attempt_total 13
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 13
telemt_me_single_endpoint_shadow_rotate_total 1215
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 41
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
telemt_me_writers_active_current 45
telemt_desync_total 39470
telemt_desync_full_logged_total 12882
telemt_desync_suppressed_total 26588
telemt_desync_frames_bucket_total{bucket="1_2"} 9403
telemt_desync_frames_bucket_total{bucket="3_10"} 14603
telemt_desync_frames_bucket_total{bucket="gt_10"} 15464
telemt_pool_swap_total 180
telemt_pool_force_close_total 4965
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 635
telemt_me_draining_writers_reap_progress_total 55070
telemt_me_writer_removed_unexpected_total 1186
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4534
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 51756
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4791
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 174
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 50105
telemt_me_writer_teardown_success_total{mode="normal"} 56290
telemt_me_writer_teardown_noop_total 55072
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 108918
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 110539
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 110899
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 111229
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 111349
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 111362
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 111362
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 111362
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 111362
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 111362
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 111362
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 111362
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 111362
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 18.525146
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 111362
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 635
telemt_me_refill_failed_total 60
telemt_me_writer_restored_same_endpoint_total 1110
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 44
telemt_me_writer_removed_unexpected_minus_restored_total 64
telemt_user_connections_total{user="hello"} 9579633
telemt_user_connections_current{user="hello"} 1980
telemt_user_octets_from_client{user="hello"} 187701585184 (174.81 GB)
telemt_user_octets_to_client{user="hello"} 4230250132200 (3.85 TB)
telemt_user_unique_ips_current{user="hello"} 670
telemt_user_unique_ips_recent_window{user="hello"} 221
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 162581.3 (45h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11022876
telemt_connections_bad_total 1232896
telemt_connections_current 1553
telemt_connections_me_current 1553
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 286515
telemt_upstream_connect_attempt_total 87282
telemt_upstream_connect_success_total 86533
telemt_upstream_connect_fail_total 578
telemt_upstream_connect_attempts_per_request{bucket="1"} 87111
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 47519
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 36053
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 910
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2051
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 578
telemt_me_reconnect_attempts_total 9162
telemt_me_reconnect_success_total 2182
telemt_me_reader_eof_total 2035
telemt_me_idle_close_by_peer_total 2035
telemt_me_seq_mismatch_total 76
telemt_me_route_drop_no_conn_total 5500390
telemt_me_route_drop_channel_closed_total 351
telemt_me_route_drop_queue_full_total 19
telemt_me_route_drop_queue_full_profile_total{profile="high"} 19
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8527317
telemt_me_endpoint_quarantine_total 1238
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_outage_enter_total 42
telemt_me_single_endpoint_outage_exit_total 42
telemt_me_single_endpoint_outage_reconnect_attempt_total 42
telemt_me_single_endpoint_outage_reconnect_success_total 40
telemt_me_single_endpoint_quarantine_bypass_total 42
telemt_me_single_endpoint_shadow_rotate_total 1216
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 51
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
telemt_desync_total 38810
telemt_desync_full_logged_total 12533
telemt_desync_suppressed_total 26277
telemt_desync_frames_bucket_total{bucket="1_2"} 9667
telemt_desync_frames_bucket_total{bucket="3_10"} 14451
telemt_desync_frames_bucket_total{bucket="gt_10"} 14692
telemt_pool_swap_total 171
telemt_pool_force_close_total 4793
telemt_pool_stale_pick_total 360
telemt_me_writer_close_signal_drop_total 618
telemt_me_draining_writers_reap_progress_total 54710
telemt_me_writer_removed_unexpected_total 2062
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5723
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 51119
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4337
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 456
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 49917
telemt_me_writer_teardown_success_total{mode="normal"} 56842
telemt_me_writer_teardown_noop_total 54715
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 108995
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 110676
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 111190
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 111507
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 111557
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 111557
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 111557
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 111557
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 111557
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 111557
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 111557
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 111557
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 111557
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 16.755527
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 111557
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 618
telemt_me_refill_failed_total 358
telemt_me_writer_restored_same_endpoint_total 1775
telemt_me_writer_restored_fallback_total 104
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 128
telemt_me_writer_removed_unexpected_minus_restored_total 183
telemt_user_connections_total{user="hello"} 8533162
telemt_user_connections_current{user="hello"} 1553
telemt_user_octets_from_client{user="hello"} 149882889913 (139.59 GB)
telemt_user_octets_to_client{user="hello"} 3268922557103 (2.97 TB)
telemt_user_msgs_from_client{user="hello"} 100726
telemt_user_msgs_to_client{user="hello"} 247529
telemt_user_unique_ips_current{user="hello"} 599
telemt_user_unique_ips_recent_window{user="hello"} 218
```