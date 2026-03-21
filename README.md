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

# Server Metrics 2026-03-21 09:31:11 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 46518.2 (12h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1302057
telemt_connections_bad_total 66946
telemt_connections_current 1653
telemt_connections_me_current 1653
telemt_handshake_timeouts_total 53102
telemt_upstream_connect_attempt_total 18258
telemt_upstream_connect_success_total 18177
telemt_upstream_connect_fail_total 57
telemt_upstream_connect_attempts_per_request{bucket="1"} 18234
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6533
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11595
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 12
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 37
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 57
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 55
telemt_me_reconnect_attempts_total 767
telemt_me_reconnect_success_total 324
telemt_me_reader_eof_total 331
telemt_me_idle_close_by_peer_total 331
telemt_me_route_drop_no_conn_total 718123
telemt_me_route_drop_channel_closed_total 215
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 981189
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_endpoint_quarantine_total 329
telemt_me_single_endpoint_outage_enter_total 2
telemt_me_single_endpoint_outage_exit_total 2
telemt_me_single_endpoint_outage_reconnect_attempt_total 2
telemt_me_single_endpoint_outage_reconnect_success_total 2
telemt_me_single_endpoint_quarantine_bypass_total 2
telemt_me_single_endpoint_shadow_rotate_total 373
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
telemt_me_writers_active_current 45
telemt_desync_total 4128
telemt_desync_full_logged_total 1412
telemt_desync_suppressed_total 2716
telemt_desync_frames_bucket_total{bucket="1_2"} 865
telemt_desync_frames_bucket_total{bucket="3_10"} 1617
telemt_desync_frames_bucket_total{bucket="gt_10"} 1646
telemt_pool_swap_total 51
telemt_pool_force_close_total 1431
telemt_pool_stale_pick_total 12
telemt_me_writer_close_signal_drop_total 198
telemt_me_draining_writers_reap_progress_total 16361
telemt_me_writer_removed_unexpected_total 310
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1266
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 15306
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1409
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 22
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 14930
telemt_me_writer_teardown_success_total{mode="normal"} 16572
telemt_me_writer_teardown_noop_total 16362
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 29885
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 30596
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 31054
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 31857
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 32532
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 32830
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 32929
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 32934
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 32934
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 32934
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 32934
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 32934
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 32934
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 80.340436
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 32934
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 198
telemt_me_refill_failed_total 25
telemt_me_writer_restored_same_endpoint_total 284
telemt_me_writer_restored_fallback_total 3
telemt_me_async_recovery_trigger_total 2
telemt_me_writer_removed_unexpected_minus_restored_total 23
telemt_user_connections_total{user="hello"} 980390
telemt_user_connections_current{user="hello"} 1653
telemt_user_octets_from_client{user="hello"} 14009671055 (13.05 GB)
telemt_user_octets_to_client{user="hello"} 274695358967 (255.83 GB)
telemt_user_msgs_from_client{user="hello"} 295
telemt_user_msgs_to_client{user="hello"} 249
telemt_user_unique_ips_current{user="hello"} 561
telemt_user_unique_ips_recent_window{user="hello"} 237
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 46519.5 (12h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3247158
telemt_connections_bad_total 364214
telemt_connections_current 4531
telemt_connections_me_current 4531
telemt_handshake_timeouts_total 97412
telemt_upstream_connect_attempt_total 16756
telemt_upstream_connect_success_total 16680
telemt_upstream_connect_fail_total 52
telemt_upstream_connect_attempts_per_request{bucket="1"} 16732
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6913
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9711
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 56
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 52
telemt_me_reconnect_attempts_total 983
telemt_me_reconnect_success_total 377
telemt_me_reader_eof_total 372
telemt_me_idle_close_by_peer_total 371
telemt_me_route_drop_no_conn_total 1266849
telemt_me_route_drop_channel_closed_total 3
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2147447
telemt_me_endpoint_quarantine_total 296
telemt_me_single_endpoint_outage_enter_total 4
telemt_me_single_endpoint_outage_exit_total 4
telemt_me_single_endpoint_outage_reconnect_attempt_total 4
telemt_me_single_endpoint_outage_reconnect_success_total 4
telemt_me_single_endpoint_quarantine_bypass_total 4
telemt_me_single_endpoint_shadow_rotate_total 360
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
telemt_desync_total 9355
telemt_desync_full_logged_total 3142
telemt_desync_suppressed_total 6213
telemt_desync_frames_bucket_total{bucket="1_2"} 1901
telemt_desync_frames_bucket_total{bucket="3_10"} 3676
telemt_desync_frames_bucket_total{bucket="gt_10"} 3778
telemt_pool_swap_total 50
telemt_pool_force_close_total 1516
telemt_me_writer_close_signal_drop_total 178
telemt_me_draining_writers_reap_progress_total 14980
telemt_me_writer_removed_unexpected_total 348
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1380
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 13945
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1426
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 90
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 13464
telemt_me_writer_teardown_success_total{mode="normal"} 15325
telemt_me_writer_teardown_noop_total 14980
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 28938
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 29498
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 29795
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 30176
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 30299
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 30305
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 30305
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 30305
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 30305
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 30305
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 30305
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 30305
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 30305
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 14.995592
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 30305
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 178
telemt_me_refill_failed_total 34
telemt_me_writer_restored_same_endpoint_total 303
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 6
telemt_me_writer_removed_unexpected_minus_restored_total 39
telemt_user_connections_total{user="hello"} 2143259
telemt_user_connections_current{user="hello"} 4531
telemt_user_octets_from_client{user="hello"} 30767902604 (28.65 GB)
telemt_user_octets_to_client{user="hello"} 759309889436 (707.16 GB)
telemt_user_unique_ips_current{user="hello"} 1649
telemt_user_unique_ips_recent_window{user="hello"} 664
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 46515.9 (12h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2363151
telemt_connections_bad_total 278993
telemt_connections_current 4073
telemt_connections_me_current 4073
telemt_handshake_timeouts_total 85505
telemt_upstream_connect_attempt_total 18209
telemt_upstream_connect_success_total 18198
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 18199
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8233
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9912
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 53
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 612
telemt_me_reconnect_success_total 344
telemt_me_reader_eof_total 357
telemt_me_idle_close_by_peer_total 357
telemt_me_route_drop_no_conn_total 930820
telemt_me_route_drop_channel_closed_total 13
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1844717
telemt_me_endpoint_quarantine_total 308
telemt_me_single_endpoint_outage_enter_total 2
telemt_me_single_endpoint_outage_exit_total 2
telemt_me_single_endpoint_outage_reconnect_attempt_total 2
telemt_me_single_endpoint_outage_reconnect_success_total 2
telemt_me_single_endpoint_quarantine_bypass_total 2
telemt_me_single_endpoint_shadow_rotate_total 364
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 16
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
telemt_desync_total 7821
telemt_desync_full_logged_total 2745
telemt_desync_suppressed_total 5076
telemt_desync_frames_bucket_total{bucket="1_2"} 1651
telemt_desync_frames_bucket_total{bucket="3_10"} 3049
telemt_desync_frames_bucket_total{bucket="gt_10"} 3121
telemt_pool_swap_total 50
telemt_pool_force_close_total 1479
telemt_pool_stale_pick_total 16
telemt_me_writer_close_signal_drop_total 195
telemt_me_draining_writers_reap_progress_total 16554
telemt_me_writer_removed_unexpected_total 337
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1361
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 15427
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 10
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1398
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 81
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 15075
telemt_me_writer_teardown_success_total{mode="normal"} 16788
telemt_me_writer_teardown_noop_total 16564
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 31315
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 32072
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 32451
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 32953
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 33215
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 33321
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 33352
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 33352
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 33352
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 33352
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 33352
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 33352
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 33352
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 34.252798
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 33352
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 195
telemt_me_refill_failed_total 13
telemt_me_writer_restored_same_endpoint_total 307
telemt_me_writer_restored_fallback_total 5
telemt_me_writer_removed_unexpected_minus_restored_total 25
telemt_user_connections_total{user="hello"} 1841664
telemt_user_connections_current{user="hello"} 4073
telemt_user_octets_from_client{user="hello"} 28690732248 (26.72 GB)
telemt_user_octets_to_client{user="hello"} 713597819848 (664.59 GB)
telemt_user_unique_ips_current{user="hello"} 1532
telemt_user_unique_ips_recent_window{user="hello"} 638
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 46517.2 (12h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1950661
telemt_connections_bad_total 228241
telemt_connections_current 3377
telemt_connections_me_current 3377
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 82379
telemt_upstream_connect_attempt_total 23126
telemt_upstream_connect_success_total 22891
telemt_upstream_connect_fail_total 125
telemt_upstream_connect_attempts_per_request{bucket="1"} 23016
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12183
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10294
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 27
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 387
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 125
telemt_me_keepalive_timeout_total 16
telemt_me_reconnect_attempts_total 990
telemt_me_reconnect_success_total 435
telemt_me_reader_eof_total 402
telemt_me_idle_close_by_peer_total 402
telemt_me_route_drop_no_conn_total 556442
telemt_me_route_drop_channel_closed_total 41
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1358507
telemt_me_endpoint_quarantine_total 329
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 367
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
telemt_me_writers_active_current 45
telemt_desync_total 6349
telemt_desync_full_logged_total 2175
telemt_desync_suppressed_total 4174
telemt_desync_frames_bucket_total{bucket="1_2"} 1562
telemt_desync_frames_bucket_total{bucket="3_10"} 2532
telemt_desync_frames_bucket_total{bucket="gt_10"} 2255
telemt_pool_swap_total 50
telemt_pool_force_close_total 1363
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 87
telemt_me_draining_writers_reap_progress_total 16422
telemt_me_writer_removed_unexpected_total 395
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1318
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 15513
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1282
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 81
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 15059
telemt_me_writer_teardown_success_total{mode="normal"} 16831
telemt_me_writer_teardown_noop_total 16423
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 32664
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 33041
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 33124
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 33191
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 33234
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 33252
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 33254
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 33254
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 33254
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 33254
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 33254
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 33254
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 33254
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 5.796781
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 33254
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 87
telemt_me_refill_failed_total 29
telemt_me_writer_restored_same_endpoint_total 365
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 10
telemt_me_writer_removed_unexpected_minus_restored_total 26
telemt_user_connections_total{user="hello"} 1360580
telemt_user_connections_current{user="hello"} 3377
telemt_user_octets_from_client{user="hello"} 27866675609 (25.95 GB)
telemt_user_octets_to_client{user="hello"} 656131929639 (611.07 GB)
telemt_user_msgs_from_client{user="hello"} 39229
telemt_user_msgs_to_client{user="hello"} 49019
telemt_user_unique_ips_current{user="hello"} 1297
telemt_user_unique_ips_recent_window{user="hello"} 473
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 46481.3 (12h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1886295
telemt_connections_bad_total 218900
telemt_connections_current 3366
telemt_connections_me_current 3366
telemt_handshake_timeouts_total 61802
telemt_upstream_connect_attempt_total 19205
telemt_upstream_connect_success_total 19173
telemt_upstream_connect_attempts_per_request{bucket="1"} 19173
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8608
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10512
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 14
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 39
telemt_me_reconnect_attempts_total 579
telemt_me_reconnect_success_total 400
telemt_me_reader_eof_total 360
telemt_me_idle_close_by_peer_total 360
telemt_me_route_drop_no_conn_total 522695
telemt_me_route_drop_channel_closed_total 13
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1358057
telemt_me_endpoint_quarantine_total 359
telemt_me_single_endpoint_outage_enter_total 1
telemt_me_single_endpoint_outage_exit_total 1
telemt_me_single_endpoint_outage_reconnect_attempt_total 1
telemt_me_single_endpoint_quarantine_bypass_total 1
telemt_me_single_endpoint_shadow_rotate_total 358
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
telemt_me_writers_active_current 67
telemt_desync_total 6275
telemt_desync_full_logged_total 2199
telemt_desync_suppressed_total 4076
telemt_desync_frames_bucket_total{bucket="1_2"} 1637
telemt_desync_frames_bucket_total{bucket="3_10"} 2425
telemt_desync_frames_bucket_total{bucket="gt_10"} 2213
telemt_pool_swap_total 50
telemt_pool_force_close_total 1323
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 117
telemt_me_draining_writers_reap_progress_total 17270
telemt_me_writer_removed_unexpected_total 335
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1271
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 16363
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1264
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 59
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 15947
telemt_me_writer_teardown_success_total{mode="normal"} 17634
telemt_me_writer_teardown_noop_total 17273
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 34327
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 34699
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 34801
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 34888
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 34907
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 34907
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 34907
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 34907
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 34907
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 34907
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 34907
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 34907
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 34907
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.901005
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 34907
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 117
telemt_me_refill_failed_total 10
telemt_me_writer_restored_same_endpoint_total 353
telemt_me_writer_restored_fallback_total 2
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 33
telemt_user_connections_total{user="hello"} 1355718
telemt_user_connections_current{user="hello"} 3366
telemt_user_octets_from_client{user="hello"} 32080940680 (29.88 GB)
telemt_user_octets_to_client{user="hello"} 673266407000 (627.03 GB)
telemt_user_unique_ips_current{user="hello"} 1280
telemt_user_unique_ips_recent_window{user="hello"} 495
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 46520.6 (12h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5485240
telemt_connections_bad_total 284398
telemt_connections_current 5446
telemt_connections_me_current 5446
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 223718
telemt_upstream_connect_attempt_total 45129
telemt_upstream_connect_success_total 43115
telemt_upstream_connect_fail_total 1380
telemt_upstream_connect_attempts_per_request{bucket="1"} 44495
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 29709
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12122
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1284
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1380
telemt_me_keepalive_timeout_total 55
telemt_me_reconnect_attempts_total 2562
telemt_me_reconnect_success_total 931
telemt_me_reader_eof_total 671
telemt_me_idle_close_by_peer_total 670
telemt_me_route_drop_no_conn_total 8905171
telemt_me_route_drop_channel_closed_total 36
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4637627
telemt_me_endpoint_quarantine_total 368
telemt_me_single_endpoint_outage_enter_total 44
telemt_me_single_endpoint_outage_exit_total 44
telemt_me_single_endpoint_outage_reconnect_attempt_total 87
telemt_me_single_endpoint_outage_reconnect_success_total 21
telemt_me_single_endpoint_quarantine_bypass_total 87
telemt_me_single_endpoint_shadow_rotate_total 366
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
telemt_desync_total 9579
telemt_desync_full_logged_total 3154
telemt_desync_suppressed_total 6425
telemt_desync_frames_bucket_total{bucket="1_2"} 2112
telemt_desync_frames_bucket_total{bucket="3_10"} 4130
telemt_desync_frames_bucket_total{bucket="gt_10"} 3337
telemt_pool_swap_total 47
telemt_pool_force_close_total 1458
telemt_me_writer_close_signal_drop_total 261
telemt_me_draining_writers_reap_progress_total 15892
telemt_me_writer_removed_unexpected_total 895
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1960
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 14754
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 6
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1252
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 206
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 14434
telemt_me_writer_teardown_success_total{mode="normal"} 16714
telemt_me_writer_teardown_noop_total 15898
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 30161
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 31020
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 31595
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 32175
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 32491
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 32602
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 32612
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 32612
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 32612
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 32612
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 32612
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 32612
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 32612
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 35.622946
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 32612
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 261
telemt_me_refill_failed_total 63
telemt_me_writer_restored_same_endpoint_total 660
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 61
telemt_me_writer_removed_unexpected_minus_restored_total 227
telemt_user_connections_total{user="hello"} 4659461
telemt_user_connections_current{user="hello"} 5446
telemt_user_octets_from_client{user="hello"} 45823283974 (42.68 GB)
telemt_user_octets_to_client{user="hello"} 564041213118 (525.30 GB)
telemt_user_msgs_from_client{user="hello"} 103363
telemt_user_msgs_to_client{user="hello"} 429893
telemt_user_unique_ips_current{user="hello"} 1940
telemt_user_unique_ips_recent_window{user="hello"} 1138
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 46488.3 (12h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1930260
telemt_connections_bad_total 249314
telemt_connections_current 3333
telemt_connections_me_current 3333
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 37367
telemt_upstream_connect_attempt_total 20638
telemt_upstream_connect_success_total 20433
telemt_upstream_connect_fail_total 186
telemt_upstream_connect_attempts_per_request{bucket="1"} 20619
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9918
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10470
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 45
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 186
telemt_me_reconnect_attempts_total 1917
telemt_me_reconnect_success_total 589
telemt_me_reader_eof_total 597
telemt_me_idle_close_by_peer_total 597
telemt_me_route_drop_no_conn_total 564474
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1442982
telemt_me_endpoint_quarantine_total 288
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 9
telemt_me_single_endpoint_outage_reconnect_success_total 9
telemt_me_single_endpoint_quarantine_bypass_total 9
telemt_me_single_endpoint_shadow_rotate_total 365
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
telemt_desync_total 6574
telemt_desync_full_logged_total 2402
telemt_desync_suppressed_total 4172
telemt_desync_frames_bucket_total{bucket="1_2"} 1285
telemt_desync_frames_bucket_total{bucket="3_10"} 2654
telemt_desync_frames_bucket_total{bucket="gt_10"} 2635
telemt_pool_swap_total 49
telemt_pool_force_close_total 1283
telemt_pool_stale_pick_total 54
telemt_me_writer_close_signal_drop_total 93
telemt_me_draining_writers_reap_progress_total 17096
telemt_me_writer_removed_unexpected_total 574
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1514
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 16179
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1199
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 84
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 15813
telemt_me_writer_teardown_success_total{mode="normal"} 17693
telemt_me_writer_teardown_noop_total 17096
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 34497
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 34675
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 34777
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 34789
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 34789
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 34789
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 34789
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 34789
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 34789
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 34789
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 34789
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 34789
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 34789
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 1.575605
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 34789
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 93
telemt_me_refill_failed_total 72
telemt_me_writer_restored_same_endpoint_total 492
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 75
telemt_user_connections_total{user="hello"} 1439624
telemt_user_connections_current{user="hello"} 3333
telemt_user_octets_from_client{user="hello"} 26425224584 (24.61 GB)
telemt_user_octets_to_client{user="hello"} 666343445946 (620.58 GB)
telemt_user_msgs_from_client{user="hello"} 7339
telemt_user_msgs_to_client{user="hello"} 11522
telemt_user_unique_ips_current{user="hello"} 1341
telemt_user_unique_ips_recent_window{user="hello"} 543
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 46482.7 (12h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2653922
telemt_connections_bad_total 153717
telemt_connections_current 3328
telemt_connections_me_current 3328
telemt_handshake_timeouts_total 1066132
telemt_upstream_connect_attempt_total 19434
telemt_upstream_connect_success_total 19400
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 19403
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8720
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10400
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 280
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_reconnect_attempts_total 515
telemt_me_reconnect_success_total 295
telemt_me_reader_eof_total 296
telemt_me_idle_close_by_peer_total 296
telemt_me_route_drop_no_conn_total 498650
telemt_me_route_drop_channel_closed_total 3
telemt_me_route_drop_queue_full_total 10
telemt_me_route_drop_queue_full_profile_total{profile="high"} 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1278818
telemt_me_endpoint_quarantine_total 361
telemt_me_single_endpoint_shadow_rotate_total 369
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
telemt_me_writers_active_current 44
telemt_desync_total 6354
telemt_desync_full_logged_total 2241
telemt_desync_suppressed_total 4113
telemt_desync_frames_bucket_total{bucket="1_2"} 1125
telemt_desync_frames_bucket_total{bucket="3_10"} 2551
telemt_desync_frames_bucket_total{bucket="gt_10"} 2678
telemt_pool_swap_total 51
telemt_pool_force_close_total 1239
telemt_me_writer_close_signal_drop_total 99
telemt_me_draining_writers_reap_progress_total 17419
telemt_me_writer_removed_unexpected_total 286
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1100
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 16624
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1222
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 17
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 16180
telemt_me_writer_teardown_success_total{mode="normal"} 17724
telemt_me_writer_teardown_noop_total 17419
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 34987
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 35100
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 35135
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 35143
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 35143
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 35143
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 35143
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 35143
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 35143
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 35143
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 35143
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 35143
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 35143
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.869110
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 35143
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 99
telemt_me_refill_failed_total 11
telemt_me_writer_restored_same_endpoint_total 262
telemt_me_writer_restored_fallback_total 2
telemt_me_writer_removed_unexpected_minus_restored_total 22
telemt_user_connections_total{user="hello"} 1274626
telemt_user_connections_current{user="hello"} 3328
telemt_user_octets_from_client{user="hello"} 22488989812 (20.94 GB)
telemt_user_octets_to_client{user="hello"} 635277903936 (591.65 GB)
telemt_user_unique_ips_current{user="hello"} 1333
telemt_user_unique_ips_recent_window{user="hello"} 499
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 44474.1 (12h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 566965
telemt_connections_bad_total 19953
telemt_connections_current 668
telemt_connections_me_current 668
telemt_handshake_timeouts_total 207902
telemt_upstream_connect_attempt_total 21817
telemt_upstream_connect_success_total 21815
telemt_upstream_connect_attempts_per_request{bucket="1"} 21815
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9092
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12671
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 52
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 916
telemt_me_reconnect_success_total 364
telemt_me_reader_eof_total 361
telemt_me_idle_close_by_peer_total 361
telemt_me_route_drop_no_conn_total 120042
telemt_me_route_drop_channel_closed_total 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 295071
telemt_me_endpoint_quarantine_total 432
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 4
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 382
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 7
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
telemt_me_writers_active_current 47
telemt_desync_total 1873
telemt_desync_full_logged_total 754
telemt_desync_suppressed_total 1119
telemt_desync_frames_bucket_total{bucket="1_2"} 357
telemt_desync_frames_bucket_total{bucket="3_10"} 742
telemt_desync_frames_bucket_total{bucket="gt_10"} 774
telemt_pool_swap_total 49
telemt_pool_force_close_total 1060
telemt_pool_stale_pick_total 7
telemt_me_writer_close_signal_drop_total 64
telemt_me_draining_writers_reap_progress_total 19452
telemt_me_writer_removed_unexpected_total 342
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1408
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 18390
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1058
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 18392
telemt_me_writer_teardown_success_total{mode="normal"} 19798
telemt_me_writer_teardown_noop_total 19452
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 38931
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 39181
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 39230
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 39250
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 39250
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 39250
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 39250
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 39250
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 39250
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 39250
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 39250
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 39250
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 39250
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 1.810762
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 39250
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 64
telemt_me_refill_failed_total 28
telemt_me_writer_restored_same_endpoint_total 298
telemt_me_writer_restored_fallback_total 4
telemt_me_writer_removed_unexpected_minus_restored_total 40
telemt_user_connections_total{user="hello"} 295229
telemt_user_connections_current{user="hello"} 668
telemt_user_octets_from_client{user="hello"} 4343497699 (4.05 GB)
telemt_user_octets_to_client{user="hello"} 117514966045 (109.44 GB)
telemt_user_msgs_from_client{user="hello"} 804
telemt_user_msgs_to_client{user="hello"} 1943
telemt_user_unique_ips_current{user="hello"} 256
telemt_user_unique_ips_recent_window{user="hello"} 101
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 46492.4 (12h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1990374
telemt_connections_bad_total 173417
telemt_connections_current 4062
telemt_connections_me_current 4062
telemt_handshake_timeouts_total 50554
telemt_upstream_connect_attempt_total 20131
telemt_upstream_connect_success_total 20044
telemt_upstream_connect_fail_total 57
telemt_upstream_connect_attempts_per_request{bucket="1"} 20101
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10024
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9995
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 24
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 57
telemt_me_reconnect_attempts_total 743
telemt_me_reconnect_success_total 433
telemt_me_reader_eof_total 401
telemt_me_idle_close_by_peer_total 401
telemt_me_route_drop_no_conn_total 488994
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1573909
telemt_me_endpoint_quarantine_total 367
telemt_me_single_endpoint_outage_enter_total 4
telemt_me_single_endpoint_outage_exit_total 4
telemt_me_single_endpoint_outage_reconnect_attempt_total 4
telemt_me_single_endpoint_outage_reconnect_success_total 4
telemt_me_single_endpoint_quarantine_bypass_total 4
telemt_me_single_endpoint_shadow_rotate_total 367
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 16
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
telemt_desync_total 6218
telemt_desync_full_logged_total 2097
telemt_desync_suppressed_total 4121
telemt_desync_frames_bucket_total{bucket="1_2"} 1521
telemt_desync_frames_bucket_total{bucket="3_10"} 2345
telemt_desync_frames_bucket_total{bucket="gt_10"} 2352
telemt_pool_swap_total 51
telemt_pool_force_close_total 1256
telemt_pool_stale_pick_total 2
telemt_me_writer_close_signal_drop_total 116
telemt_me_draining_writers_reap_progress_total 18128
telemt_me_writer_removed_unexpected_total 400
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1338
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 17199
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1233
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 23
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 16872
telemt_me_writer_teardown_success_total{mode="normal"} 18537
telemt_me_writer_teardown_noop_total 18128
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 36360
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 36545
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 36589
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 36665
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 36665
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 36665
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 36665
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 36665
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 36665
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 36665
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 36665
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 36665
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 36665
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 2.370253
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 36665
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 116
telemt_me_refill_failed_total 16
telemt_me_writer_restored_same_endpoint_total 389
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 6
telemt_user_connections_total{user="hello"} 1568448
telemt_user_connections_current{user="hello"} 4062
telemt_user_octets_from_client{user="hello"} 35272299792 (32.85 GB)
telemt_user_octets_to_client{user="hello"} 730036767176 (679.90 GB)
telemt_user_unique_ips_current{user="hello"} 1445
telemt_user_unique_ips_recent_window{user="hello"} 549
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 46489.1 (12h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1878123
telemt_connections_bad_total 153056
telemt_connections_current 3449
telemt_connections_me_current 3449
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 46237
telemt_upstream_connect_attempt_total 28803
telemt_upstream_connect_success_total 28595
telemt_upstream_connect_fail_total 166
telemt_upstream_connect_attempts_per_request{bucket="1"} 28761
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18048
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10508
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 38
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 166
telemt_me_reconnect_attempts_total 2939
telemt_me_reconnect_success_total 597
telemt_me_reader_eof_total 522
telemt_me_idle_close_by_peer_total 522
telemt_me_seq_mismatch_total 24
telemt_me_route_drop_no_conn_total 505723
telemt_me_route_drop_channel_closed_total 29
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1507076
telemt_me_endpoint_quarantine_total 419
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 11
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 11
telemt_me_single_endpoint_shadow_rotate_total 366
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 14
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
telemt_desync_total 5806
telemt_desync_full_logged_total 1932
telemt_desync_suppressed_total 3874
telemt_desync_frames_bucket_total{bucket="1_2"} 1600
telemt_desync_frames_bucket_total{bucket="3_10"} 2136
telemt_desync_frames_bucket_total{bucket="gt_10"} 2070
telemt_pool_swap_total 50
telemt_pool_force_close_total 1229
telemt_me_writer_close_signal_drop_total 106
telemt_me_draining_writers_reap_progress_total 17430
telemt_me_writer_removed_unexpected_total 530
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1590
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 16396
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1153
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 76
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 16201
telemt_me_writer_teardown_success_total{mode="normal"} 17986
telemt_me_writer_teardown_noop_total 17431
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 34991
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 35213
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 35342
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 35411
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 35417
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 35417
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 35417
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 35417
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 35417
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 35417
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 35417
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 35417
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 35417
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.348928
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 35417
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 106
telemt_me_refill_failed_total 133
telemt_me_writer_restored_same_endpoint_total 461
telemt_me_writer_restored_fallback_total 30
telemt_me_async_recovery_trigger_total 45
telemt_me_writer_removed_unexpected_minus_restored_total 39
telemt_user_connections_total{user="hello"} 1510970
telemt_user_connections_current{user="hello"} 3449
telemt_user_octets_from_client{user="hello"} 23803640711 (22.17 GB)
telemt_user_octets_to_client{user="hello"} 671728842383 (625.60 GB)
telemt_user_msgs_from_client{user="hello"} 40992
telemt_user_msgs_to_client{user="hello"} 110751
telemt_user_unique_ips_current{user="hello"} 1350
telemt_user_unique_ips_recent_window{user="hello"} 495
```