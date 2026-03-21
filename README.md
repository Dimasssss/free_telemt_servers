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

# Server Metrics 2026-03-21 15:38:30 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 68557.5 (19h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2431661
telemt_connections_bad_total 131135
telemt_connections_current 1401
telemt_connections_me_current 1401
telemt_relay_adaptive_promotions_total 3
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 78048
telemt_upstream_connect_attempt_total 29206
telemt_upstream_connect_success_total 29076
telemt_upstream_connect_fail_total 87
telemt_upstream_connect_attempts_per_request{bucket="1"} 29163
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12061
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16926
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 33
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 56
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 87
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 98
telemt_me_reconnect_attempts_total 1693
telemt_me_reconnect_success_total 668
telemt_me_reader_eof_total 641
telemt_me_idle_close_by_peer_total 641
telemt_me_route_drop_no_conn_total 2114756
telemt_me_route_drop_channel_closed_total 649
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1944868
telemt_me_writer_pick_total{mode="p2c",result="full"} 26
telemt_me_endpoint_quarantine_total 482
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 10
telemt_me_single_endpoint_outage_reconnect_success_total 9
telemt_me_single_endpoint_quarantine_bypass_total 10
telemt_me_single_endpoint_shadow_rotate_total 533
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
telemt_desync_total 7641
telemt_desync_full_logged_total 2639
telemt_desync_suppressed_total 5002
telemt_desync_frames_bucket_total{bucket="1_2"} 1675
telemt_desync_frames_bucket_total{bucket="3_10"} 2906
telemt_desync_frames_bucket_total{bucket="gt_10"} 3060
telemt_pool_swap_total 74
telemt_pool_force_close_total 2215
telemt_pool_stale_pick_total 28
telemt_me_writer_close_signal_drop_total 505
telemt_me_draining_writers_reap_progress_total 23373
telemt_me_writer_removed_unexpected_total 619
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2009
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 21767
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 6
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2096
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 119
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 21158
telemt_me_writer_teardown_success_total{mode="normal"} 23776
telemt_me_writer_teardown_noop_total 23379
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 39156
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 40662
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 41981
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 44230
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 46034
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 46887
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 47127
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 47150
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 47154
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 47155
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 47155
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 47155
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 47155
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 221.238130
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 47155
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 505
telemt_me_refill_failed_total 56
telemt_me_writer_restored_same_endpoint_total 571
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 41
telemt_user_connections_total{user="hello"} 1946315
telemt_user_connections_current{user="hello"} 1401
telemt_user_octets_from_client{user="hello"} 27521744729 (25.63 GB)
telemt_user_octets_to_client{user="hello"} 480332024490 (447.34 GB)
telemt_user_msgs_from_client{user="hello"} 7227
telemt_user_msgs_to_client{user="hello"} 6949
telemt_user_unique_ips_current{user="hello"} 527
telemt_user_unique_ips_recent_window{user="hello"} 236
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 951.6 (0h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 33997
telemt_connections_bad_total 1301
telemt_connections_current 1315
telemt_connections_me_current 1315
telemt_handshake_timeouts_total 813
telemt_upstream_connect_attempt_total 441
telemt_upstream_connect_success_total 435
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 440
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 206
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 228
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_reconnect_attempts_total 3
telemt_me_reconnect_success_total 5
telemt_me_reader_eof_total 2
telemt_me_idle_close_by_peer_total 2
telemt_me_route_drop_no_conn_total 19235
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 29313
telemt_me_endpoint_quarantine_total 6
telemt_me_single_endpoint_shadow_rotate_total 10
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
telemt_me_writers_active_current 45
telemt_me_writers_warm_current 15
telemt_desync_total 80
telemt_desync_full_logged_total 56
telemt_desync_suppressed_total 24
telemt_desync_frames_bucket_total{bucket="1_2"} 21
telemt_desync_frames_bucket_total{bucket="3_10"} 29
telemt_desync_frames_bucket_total{bucket="gt_10"} 30
telemt_me_draining_writers_reap_progress_total 301
telemt_me_writer_removed_unexpected_total 2
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 10
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 293
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 301
telemt_me_writer_teardown_success_total{mode="normal"} 303
telemt_me_writer_teardown_noop_total 301
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 602
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 602
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 604
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 604
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 604
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 604
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 604
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 604
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 604
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 604
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 604
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 604
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 604
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.015851
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 604
telemt_me_writer_restored_same_endpoint_total 2
telemt_user_connections_total{user="hello"} 29270
telemt_user_connections_current{user="hello"} 1315
telemt_user_octets_from_client{user="hello"} 351341236 (335.07 MB)
telemt_user_octets_to_client{user="hello"} 7850708416 (7.31 GB)
telemt_user_unique_ips_current{user="hello"} 841
telemt_user_unique_ips_recent_window{user="hello"} 424
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 68555.4 (19h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4872470
telemt_connections_bad_total 441672
telemt_connections_current 5036
telemt_connections_me_current 5036
telemt_handshake_timeouts_total 173340
telemt_upstream_connect_attempt_total 25412
telemt_upstream_connect_success_total 25357
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 25363
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11413
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13838
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 100
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 1154
telemt_me_reconnect_success_total 580
telemt_me_reader_eof_total 584
telemt_me_idle_close_by_peer_total 584
telemt_me_route_drop_no_conn_total 2700659
telemt_me_route_drop_channel_closed_total 45
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3977352
telemt_me_endpoint_quarantine_total 435
telemt_me_single_endpoint_outage_enter_total 4
telemt_me_single_endpoint_outage_exit_total 4
telemt_me_single_endpoint_outage_reconnect_attempt_total 4
telemt_me_single_endpoint_outage_reconnect_success_total 4
telemt_me_single_endpoint_quarantine_bypass_total 4
telemt_me_single_endpoint_shadow_rotate_total 515
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
telemt_desync_total 16339
telemt_desync_full_logged_total 5500
telemt_desync_suppressed_total 10839
telemt_desync_frames_bucket_total{bucket="1_2"} 3458
telemt_desync_frames_bucket_total{bucket="3_10"} 6453
telemt_desync_frames_bucket_total{bucket="gt_10"} 6428
telemt_pool_swap_total 73
telemt_pool_force_close_total 2342
telemt_pool_stale_pick_total 17
telemt_me_writer_close_signal_drop_total 367
telemt_me_draining_writers_reap_progress_total 23025
telemt_me_writer_removed_unexpected_total 565
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2016
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 21343
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 32
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2144
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 198
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 20683
telemt_me_writer_teardown_success_total{mode="normal"} 23359
telemt_me_writer_teardown_noop_total 23057
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 42655
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 43886
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 44564
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 45451
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 45994
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 46305
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 46415
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 46416
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 46416
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 46416
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 46416
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 46416
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 46416
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 80.979903
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 46416
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 367
telemt_me_refill_failed_total 30
telemt_me_writer_restored_same_endpoint_total 522
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 8
telemt_me_writer_removed_unexpected_minus_restored_total 38
telemt_user_connections_total{user="hello"} 3972562
telemt_user_connections_current{user="hello"} 5036
telemt_user_octets_from_client{user="hello"} 63772540252 (59.39 GB)
telemt_user_octets_to_client{user="hello"} 1312258714900 (1.19 TB)
telemt_user_unique_ips_current{user="hello"} 2061
telemt_user_unique_ips_recent_window{user="hello"} 616
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 68556.6 (19h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3956220
telemt_connections_bad_total 423628
telemt_connections_current 4079
telemt_connections_me_current 4079
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 140110
telemt_upstream_connect_attempt_total 29795
telemt_upstream_connect_success_total 29513
telemt_upstream_connect_fail_total 140
telemt_upstream_connect_attempts_per_request{bucket="1"} 29653
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15161
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13840
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 27
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 485
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 140
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 76
telemt_me_reconnect_attempts_total 1385
telemt_me_reconnect_success_total 605
telemt_me_reader_eof_total 565
telemt_me_idle_close_by_peer_total 565
telemt_me_route_drop_no_conn_total 1245162
telemt_me_route_drop_channel_closed_total 100
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2899091
telemt_me_endpoint_quarantine_total 444
telemt_me_single_endpoint_outage_enter_total 7
telemt_me_single_endpoint_outage_exit_total 7
telemt_me_single_endpoint_outage_reconnect_attempt_total 7
telemt_me_single_endpoint_outage_reconnect_success_total 7
telemt_me_single_endpoint_quarantine_bypass_total 7
telemt_me_single_endpoint_shadow_rotate_total 521
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
telemt_desync_total 13545
telemt_desync_full_logged_total 4539
telemt_desync_suppressed_total 9006
telemt_desync_frames_bucket_total{bucket="1_2"} 3412
telemt_desync_frames_bucket_total{bucket="3_10"} 5219
telemt_desync_frames_bucket_total{bucket="gt_10"} 4914
telemt_pool_swap_total 75
telemt_pool_force_close_total 2141
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 214
telemt_me_draining_writers_reap_progress_total 22205
telemt_me_writer_removed_unexpected_total 549
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1916
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 20840
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1987
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 154
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 20064
telemt_me_writer_teardown_success_total{mode="normal"} 22756
telemt_me_writer_teardown_noop_total 22206
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 43227
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 44146
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 44407
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 44698
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 44872
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 44958
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 44962
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 44962
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 44962
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 44962
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 44962
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 44962
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 44962
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 21.954116
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 44962
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 214
telemt_me_refill_failed_total 41
telemt_me_writer_restored_same_endpoint_total 509
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 20
telemt_me_writer_removed_unexpected_minus_restored_total 32
telemt_user_connections_total{user="hello"} 2898770
telemt_user_connections_current{user="hello"} 4079
telemt_user_octets_from_client{user="hello"} 58234435609 (54.24 GB)
telemt_user_octets_to_client{user="hello"} 1348676708527 (1.23 TB)
telemt_user_msgs_from_client{user="hello"} 39229
telemt_user_msgs_to_client{user="hello"} 49019
telemt_user_unique_ips_current{user="hello"} 1689
telemt_user_unique_ips_recent_window{user="hello"} 755
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 68520.4 (19h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3886207
telemt_connections_bad_total 401193
telemt_connections_current 3375
telemt_connections_me_current 3375
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 117329
telemt_upstream_connect_attempt_total 35065
telemt_upstream_connect_success_total 34829
telemt_upstream_connect_fail_total 133
telemt_upstream_connect_attempts_per_request{bucket="1"} 34962
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18510
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15170
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 294
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 855
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 133
telemt_me_keepalive_timeout_total 50
telemt_me_reconnect_attempts_total 1422
telemt_me_reconnect_success_total 655
telemt_me_reader_eof_total 599
telemt_me_idle_close_by_peer_total 599
telemt_me_route_drop_no_conn_total 1352506
telemt_me_route_drop_channel_closed_total 39
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2885772
telemt_me_endpoint_quarantine_total 487
telemt_me_single_endpoint_outage_enter_total 6
telemt_me_single_endpoint_outage_exit_total 6
telemt_me_single_endpoint_outage_reconnect_attempt_total 6
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 6
telemt_me_single_endpoint_shadow_rotate_total 511
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
telemt_me_writers_active_current 42
telemt_desync_total 13320
telemt_desync_full_logged_total 4422
telemt_desync_suppressed_total 8898
telemt_desync_frames_bucket_total{bucket="1_2"} 3328
telemt_desync_frames_bucket_total{bucket="3_10"} 4996
telemt_desync_frames_bucket_total{bucket="gt_10"} 4996
telemt_pool_swap_total 73
telemt_pool_force_close_total 2068
telemt_pool_stale_pick_total 1618
telemt_me_writer_close_signal_drop_total 236
telemt_me_draining_writers_reap_progress_total 23638
telemt_me_writer_removed_unexpected_total 569
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1996
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 22249
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 6
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1887
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 181
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 21570
telemt_me_writer_teardown_success_total{mode="normal"} 24245
telemt_me_writer_teardown_noop_total 23644
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 46545
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 47307
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 47526
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 47761
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 47875
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 47886
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 47889
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 47889
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 47889
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 47889
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 47889
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 47889
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 47889
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 12.714274
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 47889
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 236
telemt_me_refill_failed_total 43
telemt_me_writer_restored_same_endpoint_total 565
telemt_me_writer_restored_fallback_total 3
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 42
telemt_me_writer_removed_unexpected_minus_restored_total 1
telemt_user_connections_total{user="hello"} 2889588
telemt_user_connections_current{user="hello"} 3375
telemt_user_octets_from_client{user="hello"} 60955577425 (56.77 GB)
telemt_user_octets_to_client{user="hello"} 1335375069596 (1.21 TB)
telemt_user_msgs_from_client{user="hello"} 42436
telemt_user_msgs_to_client{user="hello"} 111361
telemt_user_unique_ips_current{user="hello"} 1260
telemt_user_unique_ips_recent_window{user="hello"} 975
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 68559.6 (19h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 13370605
telemt_connections_bad_total 867511
telemt_connections_current 5700
telemt_connections_me_current 5700
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 403045
telemt_upstream_connect_attempt_total 116218
telemt_upstream_connect_success_total 106311
telemt_upstream_connect_fail_total 8852
telemt_upstream_connect_attempts_per_request{bucket="1"} 115163
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 74451
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 25700
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 792
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5368
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8852
telemt_me_keepalive_timeout_total 102
telemt_me_reconnect_attempts_total 3871
telemt_me_reconnect_success_total 1414
telemt_me_reader_eof_total 984
telemt_me_idle_close_by_peer_total 983
telemt_me_route_drop_no_conn_total 26028765
telemt_me_route_drop_channel_closed_total 88
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 10997437
telemt_me_endpoint_quarantine_total 528
telemt_me_single_endpoint_outage_enter_total 78
telemt_me_single_endpoint_outage_exit_total 78
telemt_me_single_endpoint_outage_reconnect_attempt_total 174
telemt_me_single_endpoint_outage_reconnect_success_total 38
telemt_me_single_endpoint_quarantine_bypass_total 174
telemt_me_single_endpoint_shadow_rotate_total 535
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
telemt_me_writers_active_current 43
telemt_desync_total 19359
telemt_desync_full_logged_total 6059
telemt_desync_suppressed_total 13300
telemt_desync_frames_bucket_total{bucket="1_2"} 4211
telemt_desync_frames_bucket_total{bucket="3_10"} 8539
telemt_desync_frames_bucket_total{bucket="gt_10"} 6609
telemt_pool_swap_total 70
telemt_pool_force_close_total 2252
telemt_pool_stale_pick_total 5
telemt_me_writer_close_signal_drop_total 496
telemt_me_draining_writers_reap_progress_total 21942
telemt_me_writer_removed_unexpected_total 1345
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2894
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 20186
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 11
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1881
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 371
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 19690
telemt_me_writer_teardown_success_total{mode="normal"} 23080
telemt_me_writer_teardown_noop_total 21954
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 40686
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 42225
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 43129
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 44169
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 44764
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 44982
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 45015
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 45017
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 45020
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 45025
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 45025
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 45029
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 45034
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 172.188114
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 45034
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 496
telemt_me_refill_failed_total 87
telemt_me_writer_restored_same_endpoint_total 988
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 130
telemt_me_writer_removed_unexpected_minus_restored_total 347
telemt_user_connections_total{user="hello"} 11072493
telemt_user_connections_current{user="hello"} 5700
telemt_user_octets_from_client{user="hello"} 78088501477 (72.73 GB)
telemt_user_octets_to_client{user="hello"} 808401480945 (752.88 GB)
telemt_user_msgs_from_client{user="hello"} 231133
telemt_user_msgs_to_client{user="hello"} 542131
telemt_user_unique_ips_current{user="hello"} 2001
telemt_user_unique_ips_recent_window{user="hello"} 997
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 68527.2 (19h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3897774
telemt_connections_bad_total 427100
telemt_connections_current 4199
telemt_connections_me_current 4199
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 83898
telemt_upstream_connect_attempt_total 28680
telemt_upstream_connect_success_total 28366
telemt_upstream_connect_fail_total 270
telemt_upstream_connect_attempts_per_request{bucket="1"} 28636
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13514
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14776
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 75
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 270
telemt_me_reconnect_attempts_total 2728
telemt_me_reconnect_success_total 990
telemt_me_reader_eof_total 987
telemt_me_idle_close_by_peer_total 987
telemt_me_route_drop_no_conn_total 1661264
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 34
telemt_me_route_drop_queue_full_profile_total{profile="high"} 34
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3011240
telemt_me_endpoint_quarantine_total 421
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 11
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 11
telemt_me_single_endpoint_shadow_rotate_total 510
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
telemt_me_writers_active_current 47
telemt_me_writers_warm_current 35
telemt_desync_total 14324
telemt_desync_full_logged_total 4977
telemt_desync_suppressed_total 9347
telemt_desync_frames_bucket_total{bucket="1_2"} 2794
telemt_desync_frames_bucket_total{bucket="3_10"} 5688
telemt_desync_frames_bucket_total{bucket="gt_10"} 5842
telemt_pool_swap_total 68
telemt_pool_force_close_total 1980
telemt_pool_stale_pick_total 54
telemt_me_writer_close_signal_drop_total 200
telemt_me_draining_writers_reap_progress_total 24062
telemt_me_writer_removed_unexpected_total 957
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2379
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 22673
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1722
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 258
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 22082
telemt_me_writer_teardown_success_total{mode="normal"} 25052
telemt_me_writer_teardown_noop_total 24063
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 48502
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 48895
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 49072
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 49115
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 49115
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 49115
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 49115
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 49115
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 49115
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 49115
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 49115
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 49115
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 49115
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.415404
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 49115
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 200
telemt_me_refill_failed_total 95
telemt_me_writer_restored_same_endpoint_total 851
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20
telemt_me_writer_removed_unexpected_minus_restored_total 96
telemt_user_connections_total{user="hello"} 2994724
telemt_user_connections_current{user="hello"} 4199
telemt_user_octets_from_client{user="hello"} 78702048948 (73.30 GB)
telemt_user_octets_to_client{user="hello"} 1238520729690 (1.13 TB)
telemt_user_msgs_from_client{user="hello"} 7339
telemt_user_msgs_to_client{user="hello"} 11522
telemt_user_unique_ips_current{user="hello"} 1672
telemt_user_unique_ips_recent_window{user="hello"} 497
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 5362.8 (1h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 856590
telemt_connections_bad_total 23645
telemt_connections_current 3481
telemt_connections_me_current 3481
telemt_handshake_timeouts_total 413195
telemt_upstream_connect_attempt_total 1927
telemt_upstream_connect_success_total 1889
telemt_upstream_connect_fail_total 32
telemt_upstream_connect_attempts_per_request{bucket="1"} 1921
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 853
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1018
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 18
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 32
telemt_me_reconnect_attempts_total 249
telemt_me_reconnect_success_total 84
telemt_me_reader_eof_total 75
telemt_me_idle_close_by_peer_total 75
telemt_me_route_drop_no_conn_total 374900
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 386354
telemt_me_endpoint_quarantine_total 21
telemt_me_single_endpoint_outage_enter_total 1
telemt_me_single_endpoint_outage_exit_total 1
telemt_me_single_endpoint_outage_reconnect_attempt_total 1
telemt_me_single_endpoint_outage_reconnect_success_total 1
telemt_me_single_endpoint_quarantine_bypass_total 1
telemt_me_single_endpoint_shadow_rotate_total 40
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
telemt_desync_total 1845
telemt_desync_full_logged_total 613
telemt_desync_suppressed_total 1232
telemt_desync_frames_bucket_total{bucket="1_2"} 318
telemt_desync_frames_bucket_total{bucket="3_10"} 714
telemt_desync_frames_bucket_total{bucket="gt_10"} 813
telemt_pool_swap_total 4
telemt_pool_force_close_total 143
telemt_me_writer_close_signal_drop_total 11
telemt_me_draining_writers_reap_progress_total 1589
telemt_me_writer_removed_unexpected_total 76
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 163
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 1502
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 105
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 38
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 1446
telemt_me_writer_teardown_success_total{mode="normal"} 1665
telemt_me_writer_teardown_noop_total 1589
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 3171
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 3192
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 3219
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 3254
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 3254
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 3254
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 3254
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 3254
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 3254
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 3254
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 3254
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 3254
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 3254
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.751650
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 3254
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 11
telemt_me_refill_failed_total 10
telemt_me_writer_restored_same_endpoint_total 73
telemt_me_async_recovery_trigger_total 4
telemt_me_writer_removed_unexpected_minus_restored_total 3
telemt_user_connections_total{user="hello"} 385825
telemt_user_connections_current{user="hello"} 3481
telemt_user_octets_from_client{user="hello"} 10882776920 (10.14 GB)
telemt_user_octets_to_client{user="hello"} 141530601340 (131.81 GB)
telemt_user_unique_ips_current{user="hello"} 1426
telemt_user_unique_ips_recent_window{user="hello"} 521
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 66513.5 (18h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1243384
telemt_connections_bad_total 138753
telemt_connections_current 872
telemt_connections_me_current 872
telemt_handshake_timeouts_total 445617
telemt_upstream_connect_attempt_total 31074
telemt_upstream_connect_success_total 31067
telemt_upstream_connect_attempts_per_request{bucket="1"} 31067
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12715
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18250
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 102
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 1318
telemt_me_reconnect_success_total 550
telemt_me_reader_eof_total 551
telemt_me_idle_close_by_peer_total 551
telemt_me_route_drop_no_conn_total 271535
telemt_me_route_drop_channel_closed_total 24
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 583579
telemt_me_endpoint_quarantine_total 589
telemt_me_single_endpoint_outage_enter_total 7
telemt_me_single_endpoint_outage_exit_total 7
telemt_me_single_endpoint_outage_reconnect_attempt_total 7
telemt_me_single_endpoint_outage_reconnect_success_total 6
telemt_me_single_endpoint_quarantine_bypass_total 7
telemt_me_single_endpoint_shadow_rotate_total 556
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
telemt_desync_total 3590
telemt_desync_full_logged_total 1307
telemt_desync_suppressed_total 2283
telemt_desync_frames_bucket_total{bucket="1_2"} 660
telemt_desync_frames_bucket_total{bucket="3_10"} 1293
telemt_desync_frames_bucket_total{bucket="gt_10"} 1637
telemt_pool_swap_total 72
telemt_pool_force_close_total 1683
telemt_pool_stale_pick_total 7
telemt_me_writer_close_signal_drop_total 112
telemt_me_draining_writers_reap_progress_total 27847
telemt_me_writer_removed_unexpected_total 521
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2100
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 26284
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1654
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 29
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 26164
telemt_me_writer_teardown_success_total{mode="normal"} 28384
telemt_me_writer_teardown_noop_total 27847
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 55552
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 56010
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 56161
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 56215
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 56231
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 56231
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 56231
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 56231
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 56231
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 56231
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 56231
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 56231
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 56231
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 4.397475
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 56231
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 112
telemt_me_refill_failed_total 40
telemt_me_writer_restored_same_endpoint_total 459
telemt_me_writer_restored_fallback_total 5
telemt_me_writer_removed_unexpected_minus_restored_total 57
telemt_user_connections_total{user="hello"} 583219
telemt_user_connections_current{user="hello"} 872
telemt_user_octets_from_client{user="hello"} 11924752123 (11.11 GB)
telemt_user_octets_to_client{user="hello"} 223440796777 (208.10 GB)
telemt_user_msgs_from_client{user="hello"} 804
telemt_user_msgs_to_client{user="hello"} 1943
telemt_user_unique_ips_current{user="hello"} 325
telemt_user_unique_ips_recent_window{user="hello"} 137
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 68531.6 (19h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4298158
telemt_connections_bad_total 396430
telemt_connections_current 5088
telemt_connections_me_current 5088
telemt_handshake_timeouts_total 140120
telemt_upstream_connect_attempt_total 27229
telemt_upstream_connect_success_total 27116
telemt_upstream_connect_fail_total 78
telemt_upstream_connect_attempts_per_request{bucket="1"} 27194
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13428
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13651
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 36
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 78
telemt_me_reconnect_attempts_total 1186
telemt_me_reconnect_success_total 616
telemt_me_reader_eof_total 583
telemt_me_idle_close_by_peer_total 583
telemt_me_route_drop_no_conn_total 1307402
telemt_me_route_drop_channel_closed_total 36
telemt_me_route_drop_queue_full_total 11
telemt_me_route_drop_queue_full_profile_total{profile="high"} 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3412497
telemt_me_endpoint_quarantine_total 498
telemt_me_single_endpoint_outage_enter_total 8
telemt_me_single_endpoint_outage_exit_total 8
telemt_me_single_endpoint_outage_reconnect_attempt_total 8
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 8
telemt_me_single_endpoint_shadow_rotate_total 522
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
telemt_desync_total 13348
telemt_desync_full_logged_total 4406
telemt_desync_suppressed_total 8942
telemt_desync_frames_bucket_total{bucket="1_2"} 3158
telemt_desync_frames_bucket_total{bucket="3_10"} 4975
telemt_desync_frames_bucket_total{bucket="gt_10"} 5215
telemt_pool_swap_total 76
telemt_pool_force_close_total 1971
telemt_pool_stale_pick_total 2
telemt_me_writer_close_signal_drop_total 223
telemt_me_draining_writers_reap_progress_total 24394
telemt_me_writer_removed_unexpected_total 571
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1945
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 23022
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1924
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 47
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 22423
telemt_me_writer_teardown_success_total{mode="normal"} 24967
telemt_me_writer_teardown_noop_total 24394
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 48606
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 49101
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 49193
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 49317
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 49361
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 49361
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 49361
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 49361
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 49361
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 49361
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 49361
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 49361
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 49361
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 5.897858
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 49361
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 223
telemt_me_refill_failed_total 29
telemt_me_writer_restored_same_endpoint_total 545
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 21
telemt_user_connections_total{user="hello"} 3404121
telemt_user_connections_current{user="hello"} 5088
telemt_user_octets_from_client{user="hello"} 69172592576 (64.42 GB)
telemt_user_octets_to_client{user="hello"} 1600219474284 (1.46 TB)
telemt_user_unique_ips_current{user="hello"} 1844
telemt_user_unique_ips_recent_window{user="hello"} 653
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 68528.6 (19h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3824940
telemt_connections_bad_total 346128
telemt_connections_current 3672
telemt_connections_me_current 3672
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 117701
telemt_upstream_connect_attempt_total 43747
telemt_upstream_connect_success_total 43451
telemt_upstream_connect_fail_total 245
telemt_upstream_connect_attempts_per_request{bucket="1"} 43696
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26798
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15535
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 517
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 601
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 245
telemt_me_reconnect_attempts_total 3849
telemt_me_reconnect_success_total 855
telemt_me_reader_eof_total 750
telemt_me_idle_close_by_peer_total 750
telemt_me_seq_mismatch_total 32
telemt_me_route_drop_no_conn_total 1386743
telemt_me_route_drop_channel_closed_total 104
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3055691
telemt_me_endpoint_quarantine_total 572
telemt_me_single_endpoint_outage_enter_total 20
telemt_me_single_endpoint_outage_exit_total 20
telemt_me_single_endpoint_outage_reconnect_attempt_total 20
telemt_me_single_endpoint_outage_reconnect_success_total 20
telemt_me_single_endpoint_quarantine_bypass_total 20
telemt_me_single_endpoint_shadow_rotate_total 518
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
telemt_me_writers_active_current 40
telemt_desync_total 11962
telemt_desync_full_logged_total 4063
telemt_desync_suppressed_total 7899
telemt_desync_frames_bucket_total{bucket="1_2"} 2988
telemt_desync_frames_bucket_total{bucket="3_10"} 4446
telemt_desync_frames_bucket_total{bucket="gt_10"} 4528
telemt_pool_swap_total 74
telemt_pool_force_close_total 1907
telemt_pool_stale_pick_total 358
telemt_me_writer_close_signal_drop_total 214
telemt_me_draining_writers_reap_progress_total 23825
telemt_me_writer_removed_unexpected_total 762
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2325
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 22295
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1750
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 157
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 21918
telemt_me_writer_teardown_success_total{mode="normal"} 24620
telemt_me_writer_teardown_noop_total 23826
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 47563
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 48120
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 48311
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 48437
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 48446
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 48446
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 48446
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 48446
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 48446
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 48446
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 48446
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 48446
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 48446
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 6.067357
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 48446
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 214
telemt_me_refill_failed_total 170
telemt_me_writer_restored_same_endpoint_total 664
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 57
telemt_me_writer_removed_unexpected_minus_restored_total 57
telemt_user_connections_total{user="hello"} 3064128
telemt_user_connections_current{user="hello"} 3672
telemt_user_octets_from_client{user="hello"} 55542489485 (51.73 GB)
telemt_user_octets_to_client{user="hello"} 1311006619608 (1.19 TB)
telemt_user_msgs_from_client{user="hello"} 75721
telemt_user_msgs_to_client{user="hello"} 209236
telemt_user_unique_ips_current{user="hello"} 1492
telemt_user_unique_ips_recent_window{user="hello"} 494
```