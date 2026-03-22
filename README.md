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

# Server Metrics 2026-03-22 05:09:11 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 28969.0 (8h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 486650
telemt_connections_bad_total 32870
telemt_connections_current 1240
telemt_connections_me_current 1240
telemt_handshake_timeouts_total 26682
telemt_upstream_connect_attempt_total 12017
telemt_upstream_connect_success_total 12016
telemt_upstream_connect_attempts_per_request{bucket="1"} 12016
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4252
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7738
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 15
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_me_reconnect_attempts_total 317
telemt_me_reconnect_success_total 187
telemt_me_reader_eof_total 183
telemt_me_idle_close_by_peer_total 183
telemt_me_route_drop_no_conn_total 102650
telemt_me_route_drop_channel_closed_total 21
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 401690
telemt_me_endpoint_quarantine_total 227
telemt_me_single_endpoint_shadow_rotate_total 241
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 6
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
telemt_desync_total 3610
telemt_desync_full_logged_total 982
telemt_desync_suppressed_total 2628
telemt_desync_frames_bucket_total{bucket="1_2"} 1223
telemt_desync_frames_bucket_total{bucket="3_10"} 1384
telemt_desync_frames_bucket_total{bucket="gt_10"} 1003
telemt_pool_swap_total 32
telemt_pool_force_close_total 815
telemt_me_writer_close_signal_drop_total 68
telemt_me_draining_writers_reap_progress_total 10842
telemt_me_writer_removed_unexpected_total 181
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 737
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 10278
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 810
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 10027
telemt_me_writer_teardown_success_total{mode="normal"} 11015
telemt_me_writer_teardown_noop_total 10843
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 21152
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 21510
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 21665
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 21780
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 21840
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 21858
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 21858
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 21858
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 21858
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 21858
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 21858
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 21858
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 21858
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 7.586796
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 21858
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 68
telemt_me_refill_failed_total 7
telemt_me_writer_restored_same_endpoint_total 170
telemt_me_writer_removed_unexpected_minus_restored_total 11
telemt_user_connections_total{user="hello"} 400748
telemt_user_connections_current{user="hello"} 1240
telemt_user_octets_from_client{user="hello"} 5479446396 (5.10 GB)
telemt_user_octets_to_client{user="hello"} 141697364352 (131.97 GB)
telemt_user_unique_ips_current{user="hello"} 511
telemt_user_unique_ips_recent_window{user="hello"} 178
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 42335.9 (11h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 941574
telemt_connections_bad_total 68711
telemt_connections_current 1124
telemt_connections_me_current 1124
telemt_handshake_timeouts_total 32289
telemt_upstream_connect_attempt_total 22709
telemt_upstream_connect_success_total 22394
telemt_upstream_connect_fail_total 284
telemt_upstream_connect_attempts_per_request{bucket="1"} 22678
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11464
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10882
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 48
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 284
telemt_me_reconnect_attempts_total 1670
telemt_me_reconnect_success_total 623
telemt_me_reader_eof_total 543
telemt_me_idle_close_by_peer_total 543
telemt_me_route_drop_no_conn_total 368772
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 736644
telemt_me_endpoint_quarantine_total 400
telemt_me_single_endpoint_outage_enter_total 21
telemt_me_single_endpoint_outage_exit_total 21
telemt_me_single_endpoint_outage_reconnect_attempt_total 21
telemt_me_single_endpoint_outage_reconnect_success_total 21
telemt_me_single_endpoint_quarantine_bypass_total 21
telemt_me_single_endpoint_shadow_rotate_total 342
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
telemt_me_writers_warm_current 4
telemt_desync_total 3186
telemt_desync_full_logged_total 1836
telemt_desync_suppressed_total 1350
telemt_desync_frames_bucket_total{bucket="1_2"} 668
telemt_desync_frames_bucket_total{bucket="3_10"} 1226
telemt_desync_frames_bucket_total{bucket="gt_10"} 1292
telemt_pool_swap_total 45
telemt_pool_force_close_total 1178
telemt_me_writer_close_signal_drop_total 86
telemt_me_draining_writers_reap_progress_total 17531
telemt_me_writer_removed_unexpected_total 518
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1490
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 16571
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1156
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 22
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 16353
telemt_me_writer_teardown_success_total{mode="normal"} 18061
telemt_me_writer_teardown_noop_total 17531
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 35017
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 35355
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 35479
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 35578
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 35590
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 35592
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 35592
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 35592
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 35592
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 35592
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 35592
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 35592
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 35592
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 4.083265
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 35592
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 86
telemt_me_refill_failed_total 54
telemt_me_writer_restored_same_endpoint_total 466
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 40
telemt_user_connections_total{user="hello"} 738394
telemt_user_connections_current{user="hello"} 1124
telemt_user_octets_from_client{user="hello"} 11809519907 (11.00 GB)
telemt_user_octets_to_client{user="hello"} 268054970910 (249.65 GB)
telemt_user_msgs_from_client{user="hello"} 6021
telemt_user_msgs_to_client{user="hello"} 9976
telemt_user_unique_ips_current{user="hello"} 711
telemt_user_unique_ips_recent_window{user="hello"} 368
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 117196.1 (32h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8167676
telemt_connections_bad_total 703059
telemt_connections_current 2107
telemt_connections_me_current 2107
telemt_handshake_timeouts_total 266672
telemt_upstream_connect_attempt_total 43724
telemt_upstream_connect_success_total 43646
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 43654
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19765
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23694
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 181
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 1642
telemt_me_reconnect_success_total 858
telemt_me_reader_eof_total 866
telemt_me_idle_close_by_peer_total 866
telemt_me_route_drop_no_conn_total 4615092
telemt_me_route_drop_channel_closed_total 67
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6566464
telemt_me_endpoint_quarantine_total 752
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 882
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 28
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
telemt_desync_total 27666
telemt_desync_full_logged_total 9210
telemt_desync_suppressed_total 18456
telemt_desync_frames_bucket_total{bucket="1_2"} 5977
telemt_desync_frames_bucket_total{bucket="3_10"} 10825
telemt_desync_frames_bucket_total{bucket="gt_10"} 10864
telemt_pool_swap_total 127
telemt_pool_force_close_total 4174
telemt_pool_stale_pick_total 17
telemt_me_writer_close_signal_drop_total 631
telemt_me_draining_writers_reap_progress_total 39914
telemt_me_writer_removed_unexpected_total 834
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3308
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 36969
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 40
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3930
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 244
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 35740
telemt_me_writer_teardown_success_total{mode="normal"} 40277
telemt_me_writer_teardown_noop_total 39958
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 73678
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 75619
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 76670
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 78255
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 79350
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 79934
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 80224
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 80235
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 80235
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 80235
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 80235
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 80235
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 80235
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 166.422897
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 80235
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 631
telemt_me_refill_failed_total 41
telemt_me_writer_restored_same_endpoint_total 765
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 8
telemt_me_writer_removed_unexpected_minus_restored_total 64
telemt_user_connections_total{user="hello"} 6558044
telemt_user_connections_current{user="hello"} 2107
telemt_user_octets_from_client{user="hello"} 111221642960 (103.58 GB)
telemt_user_octets_to_client{user="hello"} 2220278918684 (2.02 TB)
telemt_user_unique_ips_current{user="hello"} 908
telemt_user_unique_ips_recent_window{user="hello"} 787
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 117197.2 (32h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6734273
telemt_connections_bad_total 599350
telemt_connections_current 2492
telemt_connections_me_current 2492
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 223929
telemt_upstream_connect_attempt_total 47641
telemt_upstream_connect_success_total 47242
telemt_upstream_connect_fail_total 202
telemt_upstream_connect_attempts_per_request{bucket="1"} 47444
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 23345
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23306
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 33
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 558
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 202
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 116
telemt_me_reconnect_attempts_total 2044
telemt_me_reconnect_success_total 922
telemt_me_reader_eof_total 899
telemt_me_idle_close_by_peer_total 899
telemt_me_route_drop_no_conn_total 2321599
telemt_me_route_drop_channel_closed_total 286
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5034962
telemt_me_endpoint_quarantine_total 742
telemt_me_single_endpoint_outage_enter_total 8
telemt_me_single_endpoint_outage_exit_total 8
telemt_me_single_endpoint_outage_reconnect_attempt_total 8
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 8
telemt_me_single_endpoint_shadow_rotate_total 904
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 31
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
telemt_desync_total 23415
telemt_desync_full_logged_total 8021
telemt_desync_suppressed_total 15394
telemt_desync_frames_bucket_total{bucket="1_2"} 5621
telemt_desync_frames_bucket_total{bucket="3_10"} 9089
telemt_desync_frames_bucket_total{bucket="gt_10"} 8705
telemt_pool_swap_total 128
telemt_pool_force_close_total 3794
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 389
telemt_me_draining_writers_reap_progress_total 38322
telemt_me_writer_removed_unexpected_total 879
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3171
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 35972
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 6
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3576
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 218
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 34528
telemt_me_writer_teardown_success_total{mode="normal"} 39143
telemt_me_writer_teardown_noop_total 38328
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 74009
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 75647
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 76254
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 76851
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 77266
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 77451
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 77471
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 77471
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 77471
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 77471
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 77471
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 77471
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 77471
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 49.373193
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 77471
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 389
telemt_me_refill_failed_total 60
telemt_me_writer_restored_same_endpoint_total 804
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20
telemt_me_writer_removed_unexpected_minus_restored_total 65
telemt_user_connections_total{user="hello"} 4956486
telemt_user_connections_current{user="hello"} 2492
telemt_user_octets_from_client{user="hello"} 145510866817 (135.52 GB)
telemt_user_octets_to_client{user="hello"} 2365448322635 (2.15 TB)
telemt_user_msgs_from_client{user="hello"} 39229
telemt_user_msgs_to_client{user="hello"} 49019
telemt_user_unique_ips_current{user="hello"} 987
telemt_user_unique_ips_recent_window{user="hello"} 790
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 117160.9 (32h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6584180
telemt_connections_bad_total 559579
telemt_connections_current 2446
telemt_connections_me_current 2446
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 218743
telemt_upstream_connect_attempt_total 54120
telemt_upstream_connect_success_total 53581
telemt_upstream_connect_fail_total 143
telemt_upstream_connect_attempts_per_request{bucket="1"} 53724
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26786
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 24885
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 725
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1185
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 143
telemt_me_keepalive_timeout_total 72
telemt_me_reconnect_attempts_total 2402
telemt_me_reconnect_success_total 1062
telemt_me_reader_eof_total 997
telemt_me_idle_close_by_peer_total 997
telemt_me_route_drop_no_conn_total 2319572
telemt_me_route_drop_channel_closed_total 138
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4895755
telemt_me_endpoint_quarantine_total 837
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 11
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 11
telemt_me_single_endpoint_shadow_rotate_total 872
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 41
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
telemt_desync_total 23326
telemt_desync_full_logged_total 7905
telemt_desync_suppressed_total 15421
telemt_desync_frames_bucket_total{bucket="1_2"} 5686
telemt_desync_frames_bucket_total{bucket="3_10"} 8943
telemt_desync_frames_bucket_total{bucket="gt_10"} 8697
telemt_pool_swap_total 126
telemt_pool_force_close_total 3636
telemt_pool_stale_pick_total 1618
telemt_me_writer_close_signal_drop_total 412
telemt_me_draining_writers_reap_progress_total 39396
telemt_me_writer_removed_unexpected_total 987
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3382
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 37021
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 12
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3399
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 237
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 35760
telemt_me_writer_teardown_success_total{mode="normal"} 40403
telemt_me_writer_teardown_noop_total 39408
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 76948
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 78448
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 78941
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 79468
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 79723
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 79778
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 79811
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 79811
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 79811
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 79811
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 79811
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 79811
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 79811
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 33.772537
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 79811
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 412
telemt_me_refill_failed_total 74
telemt_me_writer_restored_same_endpoint_total 928
telemt_me_writer_restored_fallback_total 5
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 42
telemt_me_writer_removed_unexpected_minus_restored_total 54
telemt_user_connections_total{user="hello"} 4890421
telemt_user_connections_current{user="hello"} 2446
telemt_user_octets_from_client{user="hello"} 136664750131 (127.28 GB)
telemt_user_octets_to_client{user="hello"} 2234351019343 (2.03 TB)
telemt_user_msgs_from_client{user="hello"} 44246
telemt_user_msgs_to_client{user="hello"} 113178
telemt_user_unique_ips_current{user="hello"} 1020
telemt_user_unique_ips_recent_window{user="hello"} 497
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 117199.7 (32h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 21078718
telemt_connections_bad_total 1778736
telemt_connections_current 3949
telemt_connections_me_current 3949
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 640375
telemt_upstream_connect_attempt_total 204770
telemt_upstream_connect_success_total 186431
telemt_upstream_connect_fail_total 16479
telemt_upstream_connect_attempts_per_request{bucket="1"} 202910
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 130918
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 45337
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1224
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8952
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 16479
telemt_me_keepalive_timeout_total 398
telemt_me_reconnect_attempts_total 65266
telemt_me_reconnect_success_total 2484
telemt_me_reader_eof_total 1573
telemt_me_idle_close_by_peer_total 1572
telemt_me_route_drop_no_conn_total 39937382
telemt_me_route_drop_channel_closed_total 129
telemt_me_route_drop_queue_full_total 13
telemt_me_route_drop_queue_full_profile_total{profile="high"} 13
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 16943948
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 5
telemt_me_endpoint_quarantine_total 911
telemt_me_single_endpoint_outage_enter_total 144
telemt_me_single_endpoint_outage_exit_total 144
telemt_me_single_endpoint_outage_reconnect_attempt_total 297
telemt_me_single_endpoint_outage_reconnect_success_total 76
telemt_me_single_endpoint_quarantine_bypass_total 297
telemt_me_single_endpoint_shadow_rotate_total 920
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 68
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
telemt_desync_total 32785
telemt_desync_full_logged_total 9895
telemt_desync_suppressed_total 22890
telemt_desync_frames_bucket_total{bucket="1_2"} 7142
telemt_desync_frames_bucket_total{bucket="3_10"} 14543
telemt_desync_frames_bucket_total{bucket="gt_10"} 11100
telemt_pool_swap_total 121
telemt_pool_force_close_total 3888
telemt_pool_stale_pick_total 29
telemt_me_writer_close_signal_drop_total 841
telemt_me_draining_writers_reap_progress_total 36973
telemt_me_writer_removed_unexpected_total 2310
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4964
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 34066
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 24
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3330
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 558
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 33085
telemt_me_writer_teardown_success_total{mode="normal"} 39030
telemt_me_writer_teardown_noop_total 37000
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 68976
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 71573
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 72903
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 74632
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 75586
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 75928
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 76011
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 76013
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 76016
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 76021
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 76021
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 76025
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 76030
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 217.376246
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 76030
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 841
telemt_me_refill_failed_total 3811
telemt_me_writer_restored_same_endpoint_total 1704
telemt_me_writer_restored_fallback_total 22
telemt_me_no_writer_failfast_total 666
telemt_me_async_recovery_trigger_total 14678
telemt_me_writer_removed_unexpected_minus_restored_total 584
telemt_user_connections_total{user="hello"} 17078543
telemt_user_connections_current{user="hello"} 3949
telemt_user_octets_from_client{user="hello"} 250120539548 (232.94 GB)
telemt_user_octets_to_client{user="hello"} 1311908628779 (1.19 TB)
telemt_user_msgs_from_client{user="hello"} 398569
telemt_user_msgs_to_client{user="hello"} 788102
telemt_user_unique_ips_current{user="hello"} 1562
telemt_user_unique_ips_recent_window{user="hello"} 619
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 117167.5 (32h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6356346
telemt_connections_bad_total 609185
telemt_connections_current 2657
telemt_connections_me_current 2657
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 134358
telemt_upstream_connect_attempt_total 62648
telemt_upstream_connect_success_total 61921
telemt_upstream_connect_fail_total 620
telemt_upstream_connect_attempts_per_request{bucket="1"} 62541
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 35722
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 25839
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 359
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 620
telemt_me_reconnect_attempts_total 69881
telemt_me_reconnect_success_total 1876
telemt_me_reader_eof_total 1649
telemt_me_idle_close_by_peer_total 1648
telemt_me_route_drop_no_conn_total 2456535
telemt_me_route_drop_channel_closed_total 10
telemt_me_route_drop_queue_full_total 39
telemt_me_route_drop_queue_full_profile_total{profile="high"} 39
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4937471
telemt_me_endpoint_quarantine_total 796
telemt_me_single_endpoint_outage_enter_total 23
telemt_me_single_endpoint_outage_exit_total 23
telemt_me_single_endpoint_outage_reconnect_attempt_total 24
telemt_me_single_endpoint_outage_reconnect_success_total 23
telemt_me_single_endpoint_quarantine_bypass_total 24
telemt_me_single_endpoint_shadow_rotate_total 890
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 34
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
telemt_desync_total 24661
telemt_desync_full_logged_total 8637
telemt_desync_suppressed_total 16024
telemt_desync_frames_bucket_total{bucket="1_2"} 4863
telemt_desync_frames_bucket_total{bucket="3_10"} 9524
telemt_desync_frames_bucket_total{bucket="gt_10"} 10274
telemt_pool_swap_total 122
telemt_pool_force_close_total 3463
telemt_pool_stale_pick_total 54
telemt_me_writer_close_signal_drop_total 410
telemt_me_draining_writers_reap_progress_total 41436
telemt_me_writer_removed_unexpected_total 1685
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4194
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 38959
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3057
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 406
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 37973
telemt_me_writer_teardown_success_total{mode="normal"} 43153
telemt_me_writer_teardown_noop_total 41437
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 83242
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 84109
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 84401
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 84558
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 84587
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 84590
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 84590
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 84590
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 84590
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 84590
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 84590
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 84590
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 84590
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 8.862458
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 84590
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 410
telemt_me_refill_failed_total 4213
telemt_me_writer_restored_same_endpoint_total 1566
telemt_me_writer_restored_fallback_total 38
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7313
telemt_me_writer_removed_unexpected_minus_restored_total 81
telemt_user_connections_total{user="hello"} 4929668
telemt_user_connections_current{user="hello"} 2657
telemt_user_octets_from_client{user="hello"} 128711782156 (119.87 GB)
telemt_user_octets_to_client{user="hello"} 2044938752802 (1.86 TB)
telemt_user_msgs_from_client{user="hello"} 77823
telemt_user_msgs_to_client{user="hello"} 338392
telemt_user_unique_ips_current{user="hello"} 1183
telemt_user_unique_ips_recent_window{user="hello"} 352
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 54003.3 (15h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4329572
telemt_connections_bad_total 181784
telemt_connections_current 2266
telemt_connections_me_current 2266
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 1708915
telemt_upstream_connect_attempt_total 31420
telemt_upstream_connect_success_total 31211
telemt_upstream_connect_fail_total 202
telemt_upstream_connect_attempts_per_request{bucket="1"} 31413
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19024
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12104
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 83
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 202
telemt_me_reconnect_attempts_total 46077
telemt_me_reconnect_success_total 1028
telemt_me_reader_eof_total 718
telemt_me_idle_close_by_peer_total 718
telemt_me_route_drop_no_conn_total 1092554
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2142923
telemt_me_endpoint_quarantine_total 387
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 50
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 50
telemt_me_single_endpoint_shadow_rotate_total 416
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
telemt_me_floor_cap_block_total 23
telemt_me_floor_swap_idle_failed_total 23
telemt_desync_total 11645
telemt_desync_full_logged_total 3993
telemt_desync_suppressed_total 7652
telemt_desync_frames_bucket_total{bucket="1_2"} 2237
telemt_desync_frames_bucket_total{bucket="3_10"} 4464
telemt_desync_frames_bucket_total{bucket="gt_10"} 4944
telemt_pool_swap_total 58
telemt_pool_force_close_total 1696
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 150
telemt_me_draining_writers_reap_progress_total 20087
telemt_me_writer_removed_unexpected_total 789
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1730
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 19175
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1489
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 207
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 18391
telemt_me_writer_teardown_success_total{mode="normal"} 20905
telemt_me_writer_teardown_noop_total 20089
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 40457
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 40747
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 40888
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 40994
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 40994
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 40994
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 40994
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 40994
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 40994
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 40994
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 40994
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 40994
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 40994
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.563942
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 40994
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 150
telemt_me_refill_failed_total 2617
telemt_me_writer_restored_same_endpoint_total 917
telemt_me_writer_restored_fallback_total 14
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4264
telemt_user_connections_total{user="hello"} 2145634
telemt_user_connections_current{user="hello"} 2266
telemt_user_octets_from_client{user="hello"} 57790179080 (53.82 GB)
telemt_user_octets_to_client{user="hello"} 936132707262 (871.84 GB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 1053
telemt_user_unique_ips_recent_window{user="hello"} 326
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 34974.2 (9h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 246788
telemt_connections_bad_total 1898
telemt_connections_current 492
telemt_connections_me_current 492
telemt_handshake_timeouts_total 6435
telemt_upstream_connect_attempt_total 16906
telemt_upstream_connect_success_total 16863
telemt_upstream_connect_fail_total 39
telemt_upstream_connect_attempts_per_request{bucket="1"} 16902
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7108
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9662
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 93
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 39
telemt_me_reconnect_attempts_total 410
telemt_me_reconnect_success_total 232
telemt_me_reader_eof_total 233
telemt_me_idle_close_by_peer_total 233
telemt_me_route_drop_no_conn_total 68949
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 219609
telemt_me_endpoint_quarantine_total 338
telemt_me_single_endpoint_outage_enter_total 1
telemt_me_single_endpoint_outage_exit_total 1
telemt_me_single_endpoint_outage_reconnect_attempt_total 1
telemt_me_single_endpoint_outage_reconnect_success_total 1
telemt_me_single_endpoint_quarantine_bypass_total 1
telemt_me_single_endpoint_shadow_rotate_total 303
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 5
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
telemt_desync_total 1209
telemt_desync_full_logged_total 329
telemt_desync_suppressed_total 880
telemt_desync_frames_bucket_total{bucket="1_2"} 424
telemt_desync_frames_bucket_total{bucket="3_10"} 463
telemt_desync_frames_bucket_total{bucket="gt_10"} 322
telemt_pool_swap_total 38
telemt_pool_force_close_total 846
telemt_me_writer_close_signal_drop_total 30
telemt_me_draining_writers_reap_progress_total 15305
telemt_me_writer_removed_unexpected_total 222
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 969
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 14569
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 844
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 14459
telemt_me_writer_teardown_success_total{mode="normal"} 15538
telemt_me_writer_teardown_noop_total 15305
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 30588
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 30815
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 30833
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 30843
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 30843
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 30843
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 30843
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 30843
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 30843
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 30843
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 30843
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 30843
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 30843
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 1.226239
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 30843
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 30
telemt_me_refill_failed_total 10
telemt_me_writer_restored_same_endpoint_total 201
telemt_me_writer_restored_fallback_total 1
telemt_me_writer_removed_unexpected_minus_restored_total 20
telemt_user_connections_total{user="hello"} 219255
telemt_user_connections_current{user="hello"} 492
telemt_user_octets_from_client{user="hello"} 3690880120 (3.44 GB)
telemt_user_octets_to_client{user="hello"} 135087338640 (125.81 GB)
telemt_user_unique_ips_current{user="hello"} 222
telemt_user_unique_ips_recent_window{user="hello"} 85
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 117172.2 (32h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7704498
telemt_connections_bad_total 768134
telemt_connections_current 3061
telemt_connections_me_current 3061
telemt_handshake_timeouts_total 219159
telemt_upstream_connect_attempt_total 46240
telemt_upstream_connect_success_total 46070
telemt_upstream_connect_fail_total 133
telemt_upstream_connect_attempts_per_request{bucket="1"} 46203
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 22779
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23250
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 40
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 133
telemt_me_reconnect_attempts_total 1685
telemt_me_reconnect_success_total 902
telemt_me_reader_eof_total 896
telemt_me_idle_close_by_peer_total 896
telemt_me_route_drop_no_conn_total 2191194
telemt_me_route_drop_channel_closed_total 52
telemt_me_route_drop_queue_full_total 23
telemt_me_route_drop_queue_full_profile_total{profile="high"} 23
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5740546
telemt_me_endpoint_quarantine_total 841
telemt_me_single_endpoint_outage_enter_total 8
telemt_me_single_endpoint_outage_exit_total 8
telemt_me_single_endpoint_outage_reconnect_attempt_total 8
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 8
telemt_me_single_endpoint_shadow_rotate_total 900
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 32
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
telemt_desync_total 22458
telemt_desync_full_logged_total 7397
telemt_desync_suppressed_total 15061
telemt_desync_frames_bucket_total{bucket="1_2"} 5626
telemt_desync_frames_bucket_total{bucket="3_10"} 8154
telemt_desync_frames_bucket_total{bucket="gt_10"} 8678
telemt_pool_swap_total 130
telemt_pool_force_close_total 3438
telemt_pool_stale_pick_total 3
telemt_me_writer_close_signal_drop_total 406
telemt_me_draining_writers_reap_progress_total 41713
telemt_me_writer_removed_unexpected_total 859
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3255
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 39344
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3350
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 88
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 38275
telemt_me_writer_teardown_success_total{mode="normal"} 42599
telemt_me_writer_teardown_noop_total 41715
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 82922
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 83845
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 84026
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 84226
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 84314
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 84314
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 84314
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 84314
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 84314
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 84314
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 84314
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 84314
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 84314
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 10.813399
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 84314
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 406
telemt_me_refill_failed_total 41
telemt_me_writer_restored_same_endpoint_total 807
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 44
telemt_user_connections_total{user="hello"} 5715220
telemt_user_connections_current{user="hello"} 3061
telemt_user_octets_from_client{user="hello"} 113282305140 (105.50 GB)
telemt_user_octets_to_client{user="hello"} 2669437121296 (2.43 TB)
telemt_user_unique_ips_current{user="hello"} 1252
telemt_user_unique_ips_recent_window{user="hello"} 393
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 117168.5 (32h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6682565
telemt_connections_bad_total 654134
telemt_connections_current 2614
telemt_connections_me_current 2614
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 181571
telemt_upstream_connect_attempt_total 62088
telemt_upstream_connect_success_total 61619
telemt_upstream_connect_fail_total 409
telemt_upstream_connect_attempts_per_request{bucket="1"} 62028
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 35631
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 24854
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 518
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 616
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 409
telemt_me_reconnect_attempts_total 5769
telemt_me_reconnect_success_total 1272
telemt_me_reader_eof_total 1142
telemt_me_idle_close_by_peer_total 1142
telemt_me_seq_mismatch_total 54
telemt_me_route_drop_no_conn_total 2244827
telemt_me_route_drop_channel_closed_total 191
telemt_me_route_drop_queue_full_total 12
telemt_me_route_drop_queue_full_profile_total{profile="high"} 12
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5107193
telemt_me_endpoint_quarantine_total 928
telemt_me_single_endpoint_outage_enter_total 29
telemt_me_single_endpoint_outage_exit_total 29
telemt_me_single_endpoint_outage_reconnect_attempt_total 29
telemt_me_single_endpoint_outage_reconnect_success_total 27
telemt_me_single_endpoint_quarantine_bypass_total 29
telemt_me_single_endpoint_shadow_rotate_total 899
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 33
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
telemt_desync_total 21207
telemt_desync_full_logged_total 7068
telemt_desync_suppressed_total 14139
telemt_desync_frames_bucket_total{bucket="1_2"} 5360
telemt_desync_frames_bucket_total{bucket="3_10"} 7761
telemt_desync_frames_bucket_total{bucket="gt_10"} 8086
telemt_pool_swap_total 128
telemt_pool_force_close_total 3387
telemt_pool_stale_pick_total 358
telemt_me_writer_close_signal_drop_total 403
telemt_me_draining_writers_reap_progress_total 40282
telemt_me_writer_removed_unexpected_total 1154
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3811
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 37682
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3164
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 223
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 36895
telemt_me_writer_teardown_success_total{mode="normal"} 41493
telemt_me_writer_teardown_noop_total 40286
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 80060
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 81146
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 81544
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 81741
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 81779
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 81779
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 81779
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 81779
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 81779
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 81779
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 81779
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 81779
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 81779
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 11.556358
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 81779
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 403
telemt_me_refill_failed_total 259
telemt_me_writer_restored_same_endpoint_total 995
telemt_me_writer_restored_fallback_total 72
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 82
telemt_me_writer_removed_unexpected_minus_restored_total 87
telemt_user_connections_total{user="hello"} 5109922
telemt_user_connections_current{user="hello"} 2614
telemt_user_octets_from_client{user="hello"} 96087026741 (89.49 GB)
telemt_user_octets_to_client{user="hello"} 2202867840304 (2.00 TB)
telemt_user_msgs_from_client{user="hello"} 75721
telemt_user_msgs_to_client{user="hello"} 209236
telemt_user_unique_ips_current{user="hello"} 1145
telemt_user_unique_ips_recent_window{user="hello"} 328
```