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

# Server Metrics 2026-03-21 06:58:28 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 37353.0 (10h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 815491
telemt_connections_bad_total 43842
telemt_connections_current 1329
telemt_connections_me_current 1329
telemt_handshake_timeouts_total 39850
telemt_upstream_connect_attempt_total 15090
telemt_upstream_connect_success_total 15022
telemt_upstream_connect_fail_total 45
telemt_upstream_connect_attempts_per_request{bucket="1"} 15067
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5216
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9760
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 10
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 36
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 45
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 11
telemt_me_reconnect_attempts_total 466
telemt_me_reconnect_success_total 244
telemt_me_reader_eof_total 256
telemt_me_idle_close_by_peer_total 256
telemt_me_route_drop_no_conn_total 267297
telemt_me_route_drop_channel_closed_total 81
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 605530
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_endpoint_quarantine_total 265
telemt_me_single_endpoint_outage_enter_total 1
telemt_me_single_endpoint_outage_exit_total 1
telemt_me_single_endpoint_outage_reconnect_attempt_total 1
telemt_me_single_endpoint_outage_reconnect_success_total 1
telemt_me_single_endpoint_quarantine_bypass_total 1
telemt_me_single_endpoint_shadow_rotate_total 309
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
telemt_desync_total 2660
telemt_desync_full_logged_total 964
telemt_desync_suppressed_total 1696
telemt_desync_frames_bucket_total{bucket="1_2"} 553
telemt_desync_frames_bucket_total{bucket="3_10"} 1046
telemt_desync_frames_bucket_total{bucket="gt_10"} 1061
telemt_pool_swap_total 41
telemt_pool_force_close_total 1127
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 103
telemt_me_draining_writers_reap_progress_total 13592
telemt_me_writer_removed_unexpected_total 241
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1006
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 12785
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1122
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 12465
telemt_me_writer_teardown_success_total{mode="normal"} 13791
telemt_me_writer_teardown_noop_total 13593
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 25864
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 26312
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 26484
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 26807
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 27176
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 27322
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 27379
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 27384
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 27384
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 27384
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 27384
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 27384
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 27384
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 42.329513
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 27384
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 103
telemt_me_refill_failed_total 12
telemt_me_writer_restored_same_endpoint_total 221
telemt_me_writer_restored_fallback_total 3
telemt_me_writer_removed_unexpected_minus_restored_total 17
telemt_user_connections_total{user="hello"} 604783
telemt_user_connections_current{user="hello"} 1329
telemt_user_octets_from_client{user="hello"} 7153523800 (6.66 GB)
telemt_user_octets_to_client{user="hello"} 191186545172 (178.06 GB)
telemt_user_unique_ips_current{user="hello"} 509
telemt_user_unique_ips_recent_window{user="hello"} 204
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 37354.0 (10h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2046907
telemt_connections_bad_total 225406
telemt_connections_current 3875
telemt_connections_me_current 3875
telemt_handshake_timeouts_total 63621
telemt_upstream_connect_attempt_total 14032
telemt_upstream_connect_success_total 13968
telemt_upstream_connect_fail_total 44
telemt_upstream_connect_attempts_per_request{bucket="1"} 14012
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5729
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8199
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 40
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 44
telemt_me_reconnect_attempts_total 774
telemt_me_reconnect_success_total 279
telemt_me_reader_eof_total 288
telemt_me_idle_close_by_peer_total 288
telemt_me_route_drop_no_conn_total 410517
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1236703
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
telemt_desync_total 5241
telemt_desync_full_logged_total 1830
telemt_desync_suppressed_total 3411
telemt_desync_frames_bucket_total{bucket="1_2"} 1066
telemt_desync_frames_bucket_total{bucket="3_10"} 2078
telemt_desync_frames_bucket_total{bucket="gt_10"} 2097
telemt_pool_swap_total 40
telemt_pool_force_close_total 1190
telemt_me_writer_close_signal_drop_total 123
telemt_me_draining_writers_reap_progress_total 12598
telemt_me_writer_removed_unexpected_total 269
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1111
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 11748
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1134
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 56
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 11408
telemt_me_writer_teardown_success_total{mode="normal"} 12859
telemt_me_writer_teardown_noop_total 12598
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 24550
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 24915
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 25115
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 25382
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 25455
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 25457
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 25457
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 25457
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 25457
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 25457
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 25457
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 25457
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 25457
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 9.590944
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 25457
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 123
telemt_me_refill_failed_total 27
telemt_me_writer_restored_same_endpoint_total 236
telemt_me_writer_restored_fallback_total 1
telemt_me_async_recovery_trigger_total 2
telemt_me_writer_removed_unexpected_minus_restored_total 32
telemt_user_connections_total{user="hello"} 1233656
telemt_user_connections_current{user="hello"} 3875
telemt_user_octets_from_client{user="hello"} 17081991896 (15.91 GB)
telemt_user_octets_to_client{user="hello"} 510352019844 (475.30 GB)
telemt_user_unique_ips_current{user="hello"} 1440
telemt_user_unique_ips_recent_window{user="hello"} 528
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 37350.3 (10h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1369791
telemt_connections_bad_total 160851
telemt_connections_current 3280
telemt_connections_me_current 3280
telemt_handshake_timeouts_total 63266
telemt_upstream_connect_attempt_total 15170
telemt_upstream_connect_success_total 15160
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 15161
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6900
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8216
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 44
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 418
telemt_me_reconnect_success_total 246
telemt_me_reader_eof_total 255
telemt_me_idle_close_by_peer_total 255
telemt_me_route_drop_no_conn_total 338307
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1062318
telemt_me_endpoint_quarantine_total 268
telemt_me_single_endpoint_outage_enter_total 2
telemt_me_single_endpoint_outage_exit_total 2
telemt_me_single_endpoint_outage_reconnect_attempt_total 2
telemt_me_single_endpoint_outage_reconnect_success_total 2
telemt_me_single_endpoint_quarantine_bypass_total 2
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
telemt_desync_total 4273
telemt_desync_full_logged_total 1547
telemt_desync_suppressed_total 2726
telemt_desync_frames_bucket_total{bucket="1_2"} 953
telemt_desync_frames_bucket_total{bucket="3_10"} 1649
telemt_desync_frames_bucket_total{bucket="gt_10"} 1671
telemt_pool_swap_total 41
telemt_pool_force_close_total 1128
telemt_pool_stale_pick_total 16
telemt_me_writer_close_signal_drop_total 129
telemt_me_draining_writers_reap_progress_total 13811
telemt_me_writer_removed_unexpected_total 237
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1071
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 12914
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1118
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 10
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 12683
telemt_me_writer_teardown_success_total{mode="normal"} 13985
telemt_me_writer_teardown_noop_total 13814
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 26436
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 26969
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 27246
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 27623
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 27760
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 27791
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 27799
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 27799
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 27799
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 27799
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 27799
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 27799
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 27799
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 18.101903
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 27799
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 129
telemt_me_refill_failed_total 8
telemt_me_writer_restored_same_endpoint_total 212
telemt_me_writer_restored_fallback_total 5
telemt_me_writer_removed_unexpected_minus_restored_total 20
telemt_user_connections_total{user="hello"} 1060096
telemt_user_connections_current{user="hello"} 3280
telemt_user_octets_from_client{user="hello"} 14610836644 (13.61 GB)
telemt_user_octets_to_client{user="hello"} 468715818112 (436.53 GB)
telemt_user_unique_ips_current{user="hello"} 1221
telemt_user_unique_ips_recent_window{user="hello"} 395
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 37355.1 (10h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1187374
telemt_connections_bad_total 156223
telemt_connections_current 2801
telemt_connections_me_current 2801
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 57347
telemt_upstream_connect_attempt_total 19991
telemt_upstream_connect_success_total 19797
telemt_upstream_connect_fail_total 117
telemt_upstream_connect_attempts_per_request{bucket="1"} 19914
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10727
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8679
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 20
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 371
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 117
telemt_me_keepalive_timeout_total 5
telemt_me_reconnect_attempts_total 682
telemt_me_reconnect_success_total 287
telemt_me_reader_eof_total 281
telemt_me_idle_close_by_peer_total 281
telemt_me_route_drop_no_conn_total 268463
telemt_me_route_drop_channel_closed_total 16
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 804596
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
telemt_desync_total 3612
telemt_desync_full_logged_total 1331
telemt_desync_suppressed_total 2281
telemt_desync_frames_bucket_total{bucket="1_2"} 780
telemt_desync_frames_bucket_total{bucket="3_10"} 1552
telemt_desync_frames_bucket_total{bucket="gt_10"} 1280
telemt_pool_swap_total 41
telemt_pool_force_close_total 1042
telemt_me_writer_close_signal_drop_total 53
telemt_me_draining_writers_reap_progress_total 13702
telemt_me_writer_removed_unexpected_total 272
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1030
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 12958
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1022
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 20
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 12660
telemt_me_writer_teardown_success_total{mode="normal"} 13988
telemt_me_writer_teardown_noop_total 13703
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 27415
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 27604
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 27647
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 27661
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 27691
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 27691
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 27691
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 27691
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 27691
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 27691
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 27691
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 27691
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 27691
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 2.242945
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 27691
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 53
telemt_me_refill_failed_total 21
telemt_me_writer_restored_same_endpoint_total 245
telemt_me_writer_restored_fallback_total 3
telemt_me_async_recovery_trigger_total 4
telemt_me_writer_removed_unexpected_minus_restored_total 24
telemt_user_connections_total{user="hello"} 807743
telemt_user_connections_current{user="hello"} 2801
telemt_user_octets_from_client{user="hello"} 14407305105 (13.42 GB)
telemt_user_octets_to_client{user="hello"} 388372142695 (361.70 GB)
telemt_user_msgs_from_client{user="hello"} 39229
telemt_user_msgs_to_client{user="hello"} 49019
telemt_user_unique_ips_current{user="hello"} 976
telemt_user_unique_ips_recent_window{user="hello"} 373
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 37315.6 (10h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1132353
telemt_connections_bad_total 141075
telemt_connections_current 2388
telemt_connections_me_current 2388
telemt_handshake_timeouts_total 41411
telemt_upstream_connect_attempt_total 15849
telemt_upstream_connect_success_total 15840
telemt_upstream_connect_attempts_per_request{bucket="1"} 15840
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7033
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8792
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_me_reconnect_attempts_total 282
telemt_me_reconnect_success_total 237
telemt_me_reader_eof_total 234
telemt_me_idle_close_by_peer_total 234
telemt_me_route_drop_no_conn_total 232377
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 801451
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
telemt_me_writers_active_current 42
telemt_desync_total 3839
telemt_desync_full_logged_total 1414
telemt_desync_suppressed_total 2425
telemt_desync_frames_bucket_total{bucket="1_2"} 958
telemt_desync_frames_bucket_total{bucket="3_10"} 1485
telemt_desync_frames_bucket_total{bucket="gt_10"} 1396
telemt_pool_swap_total 41
telemt_pool_force_close_total 1021
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 64
telemt_me_draining_writers_reap_progress_total 14357
telemt_me_writer_removed_unexpected_total 215
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 949
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 13643
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1011
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 10
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 13336
telemt_me_writer_teardown_success_total{mode="normal"} 14592
telemt_me_writer_teardown_noop_total 14358
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 28721
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 28873
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 28910
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 28950
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 28950
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 28950
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 28950
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 28950
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 28950
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 28950
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 28950
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 28950
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 28950
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 1.518066
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 28950
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 64
telemt_me_refill_failed_total 2
telemt_me_writer_restored_same_endpoint_total 211
telemt_me_writer_restored_fallback_total 1
telemt_me_async_recovery_trigger_total 2
telemt_me_writer_removed_unexpected_minus_restored_total 3
telemt_user_connections_total{user="hello"} 799910
telemt_user_connections_current{user="hello"} 2388
telemt_user_octets_from_client{user="hello"} 19839908684 (18.48 GB)
telemt_user_octets_to_client{user="hello"} 415861962820 (387.30 GB)
telemt_user_unique_ips_current{user="hello"} 977
telemt_user_unique_ips_recent_window{user="hello"} 392
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 37355.0 (10h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2470832
telemt_connections_bad_total 174034
telemt_connections_current 4443
telemt_connections_me_current 4443
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 155555
telemt_upstream_connect_attempt_total 41287
telemt_upstream_connect_success_total 39441
telemt_upstream_connect_fail_total 1324
telemt_upstream_connect_attempts_per_request{bucket="1"} 40765
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 28121
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10093
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1227
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1324
telemt_me_reconnect_attempts_total 1800
telemt_me_reconnect_success_total 582
telemt_me_reader_eof_total 392
telemt_me_idle_close_by_peer_total 391
telemt_me_route_drop_no_conn_total 2247098
telemt_me_route_drop_channel_closed_total 25
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1960860
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
telemt_me_writers_active_current 43
telemt_desync_total 4794
telemt_desync_full_logged_total 1765
telemt_desync_suppressed_total 3029
telemt_desync_frames_bucket_total{bucket="1_2"} 1097
telemt_desync_frames_bucket_total{bucket="3_10"} 2038
telemt_desync_frames_bucket_total{bucket="gt_10"} 1659
telemt_pool_swap_total 40
telemt_pool_force_close_total 1113
telemt_me_writer_close_signal_drop_total 163
telemt_me_draining_writers_reap_progress_total 12771
telemt_me_writer_removed_unexpected_total 563
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1438
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 11865
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1045
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 68
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 11658
telemt_me_writer_teardown_success_total{mode="normal"} 13303
telemt_me_writer_teardown_noop_total 12775
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 24654
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 25095
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 25485
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 25834
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 25983
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 26071
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 26078
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 26078
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 26078
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 26078
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 26078
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 26078
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 26078
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 21.703445
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 26078
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 163
telemt_me_refill_failed_total 45
telemt_me_writer_restored_same_endpoint_total 376
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 6
telemt_me_writer_removed_unexpected_minus_restored_total 179
telemt_user_connections_total{user="hello"} 1983940
telemt_user_connections_current{user="hello"} 4443
telemt_user_octets_from_client{user="hello"} 33904450926 (31.58 GB)
telemt_user_octets_to_client{user="hello"} 460999814054 (429.34 GB)
telemt_user_msgs_from_client{user="hello"} 103363
telemt_user_msgs_to_client{user="hello"} 429893
telemt_user_unique_ips_current{user="hello"} 1590
telemt_user_unique_ips_recent_window{user="hello"} 793
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 37322.6 (10h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1210464
telemt_connections_bad_total 169870
telemt_connections_current 2888
telemt_connections_me_current 2888
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 25834
telemt_upstream_connect_attempt_total 17331
telemt_upstream_connect_success_total 17179
telemt_upstream_connect_fail_total 137
telemt_upstream_connect_attempts_per_request{bucket="1"} 17316
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8471
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8671
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 37
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 137
telemt_me_reconnect_attempts_total 1442
telemt_me_reconnect_success_total 381
telemt_me_reader_eof_total 391
telemt_me_idle_close_by_peer_total 391
telemt_me_route_drop_no_conn_total 292209
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 873545
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
telemt_me_writers_active_current 86
telemt_desync_total 3620
telemt_desync_full_logged_total 1376
telemt_desync_suppressed_total 2244
telemt_desync_frames_bucket_total{bucket="1_2"} 691
telemt_desync_frames_bucket_total{bucket="3_10"} 1466
telemt_desync_frames_bucket_total{bucket="gt_10"} 1463
telemt_pool_swap_total 40
telemt_pool_force_close_total 956
telemt_me_writer_close_signal_drop_total 60
telemt_me_draining_writers_reap_progress_total 14218
telemt_me_writer_removed_unexpected_total 371
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1111
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 13498
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 949
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 13262
telemt_me_writer_teardown_success_total{mode="normal"} 14609
telemt_me_writer_teardown_noop_total 14218
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 28626
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 28736
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 28827
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 28827
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 28827
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 28827
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 28827
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 28827
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 28827
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 28827
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 28827
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 28827
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 28827
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 1.063946
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 28827
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 60
telemt_me_refill_failed_total 60
telemt_me_writer_restored_same_endpoint_total 302
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 2
telemt_me_writer_removed_unexpected_minus_restored_total 63
telemt_user_connections_total{user="hello"} 871158
telemt_user_connections_current{user="hello"} 2888
telemt_user_octets_from_client{user="hello"} 14465326748 (13.47 GB)
telemt_user_octets_to_client{user="hello"} 433686044842 (403.90 GB)
telemt_user_msgs_from_client{user="hello"} 7339
telemt_user_msgs_to_client{user="hello"} 11522
telemt_user_unique_ips_current{user="hello"} 1205
telemt_user_unique_ips_recent_window{user="hello"} 341
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 37317.0 (10h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1548860
telemt_connections_bad_total 97439
telemt_connections_current 2126
telemt_connections_me_current 2126
telemt_handshake_timeouts_total 559470
telemt_upstream_connect_attempt_total 16504
telemt_upstream_connect_success_total 16477
telemt_upstream_connect_attempts_per_request{bucket="1"} 16477
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7393
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8822
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 262
telemt_me_reconnect_attempts_total 348
telemt_me_reconnect_success_total 243
telemt_me_reader_eof_total 251
telemt_me_idle_close_by_peer_total 251
telemt_me_route_drop_no_conn_total 254753
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 776611
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
telemt_me_writers_active_current 43
telemt_desync_total 3524
telemt_desync_full_logged_total 1242
telemt_desync_suppressed_total 2282
telemt_desync_frames_bucket_total{bucket="1_2"} 635
telemt_desync_frames_bucket_total{bucket="3_10"} 1438
telemt_desync_frames_bucket_total{bucket="gt_10"} 1451
telemt_pool_swap_total 41
telemt_pool_force_close_total 947
telemt_me_writer_close_signal_drop_total 57
telemt_me_draining_writers_reap_progress_total 14797
telemt_me_writer_removed_unexpected_total 235
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 875
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 14174
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 939
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 8
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 13850
telemt_me_writer_teardown_success_total{mode="normal"} 15049
telemt_me_writer_teardown_noop_total 14797
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 29753
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 29818
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 29846
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 29846
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 29846
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 29846
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 29846
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 29846
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 29846
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 29846
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 29846
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 29846
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 29846
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.542763
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 29846
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 57
telemt_me_refill_failed_total 5
telemt_me_writer_restored_same_endpoint_total 218
telemt_me_writer_restored_fallback_total 2
telemt_me_writer_removed_unexpected_minus_restored_total 15
telemt_user_connections_total{user="hello"} 773628
telemt_user_connections_current{user="hello"} 2126
telemt_user_octets_from_client{user="hello"} 12473345108 (11.62 GB)
telemt_user_octets_to_client{user="hello"} 399054748256 (371.65 GB)
telemt_user_unique_ips_current{user="hello"} 843
telemt_user_unique_ips_recent_window{user="hello"} 354
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 35308.3 (9h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 298285
telemt_connections_bad_total 11391
telemt_connections_current 497
telemt_connections_me_current 497
telemt_handshake_timeouts_total 81413
telemt_upstream_connect_attempt_total 17946
telemt_upstream_connect_success_total 17945
telemt_upstream_connect_attempts_per_request{bucket="1"} 17945
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7576
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10333
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 36
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 582
telemt_me_reconnect_success_total 271
telemt_me_reader_eof_total 276
telemt_me_idle_close_by_peer_total 276
telemt_me_route_drop_no_conn_total 70596
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 189271
telemt_me_endpoint_quarantine_total 352
telemt_me_single_endpoint_outage_enter_total 4
telemt_me_single_endpoint_outage_exit_total 4
telemt_me_single_endpoint_outage_reconnect_attempt_total 4
telemt_me_single_endpoint_outage_reconnect_success_total 3
telemt_me_single_endpoint_quarantine_bypass_total 4
telemt_me_single_endpoint_shadow_rotate_total 307
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 41
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 44
telemt_desync_total 1148
telemt_desync_full_logged_total 540
telemt_desync_suppressed_total 608
telemt_desync_frames_bucket_total{bucket="1_2"} 215
telemt_desync_frames_bucket_total{bucket="3_10"} 485
telemt_desync_frames_bucket_total{bucket="gt_10"} 448
telemt_pool_swap_total 39
telemt_pool_force_close_total 778
telemt_me_writer_close_signal_drop_total 47
telemt_me_draining_writers_reap_progress_total 15996
telemt_me_writer_removed_unexpected_total 260
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1113
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 15144
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 778
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 15218
telemt_me_writer_teardown_success_total{mode="normal"} 16257
telemt_me_writer_teardown_noop_total 15996
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 32046
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 32221
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 32251
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 32253
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 32253
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 32253
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 32253
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 32253
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 32253
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 32253
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 32253
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 32253
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 32253
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 1.045045
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 32253
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 47
telemt_me_refill_failed_total 16
telemt_me_writer_restored_same_endpoint_total 232
telemt_me_writer_restored_fallback_total 1
telemt_me_writer_removed_unexpected_minus_restored_total 27
telemt_user_connections_total{user="hello"} 189499
telemt_user_connections_current{user="hello"} 497
telemt_user_octets_from_client{user="hello"} 2088133875 (1.94 GB)
telemt_user_octets_to_client{user="hello"} 81179030217 (75.60 GB)
telemt_user_msgs_from_client{user="hello"} 804
telemt_user_msgs_to_client{user="hello"} 1943
telemt_user_unique_ips_current{user="hello"} 222
telemt_user_unique_ips_recent_window{user="hello"} 96
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 37326.9 (10h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1230899
telemt_connections_bad_total 89221
telemt_connections_current 3204
telemt_connections_me_current 3204
telemt_handshake_timeouts_total 33495
telemt_upstream_connect_attempt_total 16955
telemt_upstream_connect_success_total 16877
telemt_upstream_connect_fail_total 49
telemt_upstream_connect_attempts_per_request{bucket="1"} 16926
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8451
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8402
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 23
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 49
telemt_me_reconnect_attempts_total 585
telemt_me_reconnect_success_total 339
telemt_me_reader_eof_total 324
telemt_me_idle_close_by_peer_total 324
telemt_me_route_drop_no_conn_total 266724
telemt_me_route_drop_channel_closed_total 3
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 961842
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
telemt_desync_total 3856
telemt_desync_full_logged_total 1285
telemt_desync_suppressed_total 2571
telemt_desync_frames_bucket_total{bucket="1_2"} 1013
telemt_desync_frames_bucket_total{bucket="3_10"} 1450
telemt_desync_frames_bucket_total{bucket="gt_10"} 1393
telemt_pool_swap_total 41
telemt_pool_force_close_total 960
telemt_pool_stale_pick_total 2
telemt_me_writer_close_signal_drop_total 73
telemt_me_draining_writers_reap_progress_total 15298
telemt_me_writer_removed_unexpected_total 325
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1069
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 14561
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 959
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 14338
telemt_me_writer_teardown_success_total{mode="normal"} 15630
telemt_me_writer_teardown_noop_total 15298
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 30760
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 30868
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 30886
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 30928
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 30928
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 30928
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 30928
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 30928
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 30928
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 30928
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 30928
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 30928
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 30928
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 1.220279
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 30928
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 73
telemt_me_refill_failed_total 12
telemt_me_writer_restored_same_endpoint_total 311
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 4
telemt_me_writer_removed_unexpected_minus_restored_total 10
telemt_user_connections_total{user="hello"} 957509
telemt_user_connections_current{user="hello"} 3204
telemt_user_octets_from_client{user="hello"} 14445682028 (13.45 GB)
telemt_user_octets_to_client{user="hello"} 433454741728 (403.69 GB)
telemt_user_unique_ips_current{user="hello"} 1155
telemt_user_unique_ips_recent_window{user="hello"} 400
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 37323.5 (10h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1172884
telemt_connections_bad_total 75353
telemt_connections_current 2842
telemt_connections_me_current 2842
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 30609
telemt_upstream_connect_attempt_total 25517
telemt_upstream_connect_success_total 25336
telemt_upstream_connect_fail_total 141
telemt_upstream_connect_attempts_per_request{bucket="1"} 25477
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16466
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8846
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 24
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 141
telemt_me_reconnect_attempts_total 2516
telemt_me_reconnect_success_total 460
telemt_me_reader_eof_total 400
telemt_me_idle_close_by_peer_total 400
telemt_me_seq_mismatch_total 24
telemt_me_route_drop_no_conn_total 272404
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 936740
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
telemt_desync_total 3651
telemt_desync_full_logged_total 1151
telemt_desync_suppressed_total 2500
telemt_desync_frames_bucket_total{bucket="1_2"} 1095
telemt_desync_frames_bucket_total{bucket="3_10"} 1344
telemt_desync_frames_bucket_total{bucket="gt_10"} 1212
telemt_pool_swap_total 41
telemt_pool_force_close_total 934
telemt_me_writer_close_signal_drop_total 77
telemt_me_draining_writers_reap_progress_total 14526
telemt_me_writer_removed_unexpected_total 412
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1272
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 13688
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 914
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 20
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 13592
telemt_me_writer_teardown_success_total{mode="normal"} 14960
telemt_me_writer_teardown_noop_total 14526
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 29278
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 29392
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 29457
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 29486
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 29486
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 29486
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 29486
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 29486
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 29486
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 29486
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 29486
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 29486
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 29486
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 1.465017
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 29486
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 77
telemt_me_refill_failed_total 117
telemt_me_writer_restored_same_endpoint_total 341
telemt_me_writer_restored_fallback_total 28
telemt_me_async_recovery_trigger_total 39
telemt_me_writer_removed_unexpected_minus_restored_total 43
telemt_user_connections_total{user="hello"} 941401
telemt_user_connections_current{user="hello"} 2842
telemt_user_octets_from_client{user="hello"} 12053363283 (11.23 GB)
telemt_user_octets_to_client{user="hello"} 413774881955 (385.36 GB)
telemt_user_msgs_from_client{user="hello"} 40992
telemt_user_msgs_to_client{user="hello"} 110751
telemt_user_unique_ips_current{user="hello"} 997
telemt_user_unique_ips_recent_window{user="hello"} 374
```