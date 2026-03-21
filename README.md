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

# Server Metrics 2026-03-21 11:38:55 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 54182.3 (15h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1656042
telemt_connections_bad_total 83827
telemt_connections_current 1600
telemt_connections_me_current 1600
telemt_handshake_timeouts_total 66020
telemt_upstream_connect_attempt_total 21175
telemt_upstream_connect_success_total 21068
telemt_upstream_connect_fail_total 69
telemt_upstream_connect_attempts_per_request{bucket="1"} 21137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7495
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13497
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 26
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 50
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 69
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 56
telemt_me_reconnect_attempts_total 1088
telemt_me_reconnect_success_total 480
telemt_me_reader_eof_total 464
telemt_me_idle_close_by_peer_total 464
telemt_me_route_drop_no_conn_total 1006796
telemt_me_route_drop_channel_closed_total 391
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1275599
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_endpoint_quarantine_total 381
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 430
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
telemt_me_writers_active_current 49
telemt_desync_total 5192
telemt_desync_full_logged_total 1826
telemt_desync_suppressed_total 3366
telemt_desync_frames_bucket_total{bucket="1_2"} 1097
telemt_desync_frames_bucket_total{bucket="3_10"} 2002
telemt_desync_frames_bucket_total{bucket="gt_10"} 2093
telemt_pool_swap_total 59
telemt_pool_force_close_total 1702
telemt_pool_stale_pick_total 12
telemt_me_writer_close_signal_drop_total 306
telemt_me_draining_writers_reap_progress_total 18881
telemt_me_writer_removed_unexpected_total 444
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1549
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 17635
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1638
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 64
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 17179
telemt_me_writer_teardown_success_total{mode="normal"} 19184
telemt_me_writer_teardown_noop_total 18885
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 33387
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 34367
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 35153
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 36486
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 37479
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 37905
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 38060
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 38068
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 38068
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 38069
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 38069
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 38069
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 38069
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 123.367580
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 38069
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 306
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 418
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 8
telemt_me_writer_removed_unexpected_minus_restored_total 22
telemt_user_connections_total{user="hello"} 1274681
telemt_user_connections_current{user="hello"} 1600
telemt_user_octets_from_client{user="hello"} 18073896703 (16.83 GB)
telemt_user_octets_to_client{user="hello"} 349407669299 (325.41 GB)
telemt_user_msgs_from_client{user="hello"} 295
telemt_user_msgs_to_client{user="hello"} 249
telemt_user_unique_ips_current{user="hello"} 602
telemt_user_unique_ips_recent_window{user="hello"} 267
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 2073.6 (0h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 131966
telemt_connections_bad_total 7267
telemt_connections_current 889
telemt_connections_me_current 889
telemt_handshake_timeouts_total 4714
telemt_upstream_connect_attempt_total 754
telemt_upstream_connect_success_total 753
telemt_upstream_connect_attempts_per_request{bucket="1"} 753
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 332
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 417
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_me_reconnect_attempts_total 13
telemt_me_reconnect_success_total 14
telemt_me_reader_eof_total 18
telemt_me_idle_close_by_peer_total 18
telemt_me_route_drop_no_conn_total 83611
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 112320
telemt_me_endpoint_quarantine_total 12
telemt_me_single_endpoint_shadow_rotate_total 20
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 3
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
telemt_desync_total 454
telemt_desync_full_logged_total 199
telemt_desync_suppressed_total 255
telemt_desync_frames_bucket_total{bucket="1_2"} 95
telemt_desync_frames_bucket_total{bucket="3_10"} 180
telemt_desync_frames_bucket_total{bucket="gt_10"} 179
telemt_pool_swap_total 2
telemt_pool_force_close_total 60
telemt_me_writer_close_signal_drop_total 7
telemt_me_draining_writers_reap_progress_total 602
telemt_me_writer_removed_unexpected_total 14
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 56
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 564
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 59
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 542
telemt_me_writer_teardown_success_total{mode="normal"} 620
telemt_me_writer_teardown_noop_total 602
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 1178
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 1210
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 1212
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 1222
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 1222
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 1222
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 1222
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 1222
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 1222
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 1222
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 1222
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 1222
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 1222
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.309721
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 1222
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 7
telemt_me_writer_restored_same_endpoint_total 12
telemt_me_writer_restored_fallback_total 1
telemt_me_writer_removed_unexpected_minus_restored_total 1
telemt_user_connections_total{user="hello"} 112270
telemt_user_connections_current{user="hello"} 889
telemt_user_octets_from_client{user="hello"} 1368410004 (1.27 GB)
telemt_user_octets_to_client{user="hello"} 28214094492 (26.28 GB)
telemt_user_unique_ips_current{user="hello"} 603
telemt_user_unique_ips_recent_window{user="hello"} 368
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 54180.4 (15h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3182258
telemt_connections_bad_total 342265
telemt_connections_current 4145
telemt_connections_me_current 4145
telemt_handshake_timeouts_total 116537
telemt_upstream_connect_attempt_total 20639
telemt_upstream_connect_success_total 20626
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 20627
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9341
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11225
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 60
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 726
telemt_me_reconnect_success_total 388
telemt_me_reader_eof_total 401
telemt_me_idle_close_by_peer_total 401
telemt_me_route_drop_no_conn_total 1382453
telemt_me_route_drop_channel_closed_total 25
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2535178
telemt_me_endpoint_quarantine_total 356
telemt_me_single_endpoint_outage_enter_total 3
telemt_me_single_endpoint_outage_exit_total 3
telemt_me_single_endpoint_outage_reconnect_attempt_total 3
telemt_me_single_endpoint_outage_reconnect_success_total 3
telemt_me_single_endpoint_quarantine_bypass_total 3
telemt_me_single_endpoint_shadow_rotate_total 418
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
telemt_me_writers_active_current 42
telemt_desync_total 11121
telemt_desync_full_logged_total 3747
telemt_desync_suppressed_total 7374
telemt_desync_frames_bucket_total{bucket="1_2"} 2340
telemt_desync_frames_bucket_total{bucket="3_10"} 4341
telemt_desync_frames_bucket_total{bucket="gt_10"} 4440
telemt_pool_swap_total 59
telemt_pool_force_close_total 1776
telemt_pool_stale_pick_total 16
telemt_me_writer_close_signal_drop_total 250
telemt_me_draining_writers_reap_progress_total 18754
telemt_me_writer_removed_unexpected_total 378
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1545
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 17447
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 13
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1678
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 98
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 16978
telemt_me_writer_teardown_success_total{mode="normal"} 18992
telemt_me_writer_teardown_noop_total 18767
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 35171
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 36068
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 36549
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 37179
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 37542
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 37713
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 37759
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 37759
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 37759
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 37759
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 37759
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 37759
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 37759
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 47.969931
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 37759
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 250
telemt_me_refill_failed_total 17
telemt_me_writer_restored_same_endpoint_total 344
telemt_me_writer_restored_fallback_total 5
telemt_me_writer_removed_unexpected_minus_restored_total 29
telemt_user_connections_total{user="hello"} 2531649
telemt_user_connections_current{user="hello"} 4145
telemt_user_octets_from_client{user="hello"} 41527789864 (38.68 GB)
telemt_user_octets_to_client{user="hello"} 919727287008 (856.56 GB)
telemt_user_unique_ips_current{user="hello"} 1621
telemt_user_unique_ips_recent_window{user="hello"} 588
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 54181.6 (15h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2636149
telemt_connections_bad_total 292022
telemt_connections_current 3475
telemt_connections_me_current 3475
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 108709
telemt_upstream_connect_attempt_total 25550
telemt_upstream_connect_success_total 25291
telemt_upstream_connect_fail_total 131
telemt_upstream_connect_attempts_per_request{bucket="1"} 25422
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13276
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11555
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 27
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 433
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 131
telemt_me_keepalive_timeout_total 40
telemt_me_reconnect_attempts_total 1070
telemt_me_reconnect_success_total 499
telemt_me_reader_eof_total 460
telemt_me_idle_close_by_peer_total 460
telemt_me_route_drop_no_conn_total 777705
telemt_me_route_drop_channel_closed_total 66
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1861073
telemt_me_endpoint_quarantine_total 366
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 417
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
telemt_desync_total 8495
telemt_desync_full_logged_total 2911
telemt_desync_suppressed_total 5584
telemt_desync_frames_bucket_total{bucket="1_2"} 2122
telemt_desync_frames_bucket_total{bucket="3_10"} 3325
telemt_desync_frames_bucket_total{bucket="gt_10"} 3048
telemt_pool_swap_total 59
telemt_pool_force_close_total 1612
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 131
telemt_me_draining_writers_reap_progress_total 18485
telemt_me_writer_removed_unexpected_total 450
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1553
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 17400
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1502
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 110
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 16873
telemt_me_writer_teardown_success_total{mode="normal"} 18953
telemt_me_writer_teardown_noop_total 18486
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 36521
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 37060
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 37201
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 37340
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 37413
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 37437
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 37439
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 37439
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 37439
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 37439
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 37439
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 37439
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 37439
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 9.190289
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 37439
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 131
telemt_me_refill_failed_total 30
telemt_me_writer_restored_same_endpoint_total 418
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 26
telemt_user_connections_total{user="hello"} 1862556
telemt_user_connections_current{user="hello"} 3475
telemt_user_octets_from_client{user="hello"} 35751418929 (33.30 GB)
telemt_user_octets_to_client{user="hello"} 894519193207 (833.09 GB)
telemt_user_msgs_from_client{user="hello"} 39229
telemt_user_msgs_to_client{user="hello"} 49019
telemt_user_unique_ips_current{user="hello"} 1420
telemt_user_unique_ips_recent_window{user="hello"} 469
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 54145.4 (15h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2571576
telemt_connections_bad_total 291554
telemt_connections_current 3280
telemt_connections_me_current 3280
telemt_handshake_timeouts_total 77209
telemt_upstream_connect_attempt_total 21975
telemt_upstream_connect_success_total 21915
telemt_upstream_connect_attempts_per_request{bucket="1"} 21915
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9875
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11925
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 34
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 81
telemt_me_keepalive_timeout_total 20
telemt_me_reconnect_attempts_total 790
telemt_me_reconnect_success_total 536
telemt_me_reader_eof_total 478
telemt_me_idle_close_by_peer_total 478
telemt_me_route_drop_no_conn_total 751475
telemt_me_route_drop_channel_closed_total 25
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1852489
telemt_me_endpoint_quarantine_total 415
telemt_me_single_endpoint_outage_enter_total 4
telemt_me_single_endpoint_outage_exit_total 4
telemt_me_single_endpoint_outage_reconnect_attempt_total 4
telemt_me_single_endpoint_outage_reconnect_success_total 3
telemt_me_single_endpoint_quarantine_bypass_total 4
telemt_me_single_endpoint_shadow_rotate_total 411
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
telemt_me_writers_active_current 43
telemt_desync_total 8724
telemt_desync_full_logged_total 2933
telemt_desync_suppressed_total 5791
telemt_desync_frames_bucket_total{bucket="1_2"} 2309
telemt_desync_frames_bucket_total{bucket="3_10"} 3318
telemt_desync_frames_bucket_total{bucket="gt_10"} 3097
telemt_pool_swap_total 58
telemt_pool_force_close_total 1588
telemt_pool_stale_pick_total 1618
telemt_me_writer_close_signal_drop_total 164
telemt_me_draining_writers_reap_progress_total 19651
telemt_me_writer_removed_unexpected_total 453
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1568
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 18569
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1467
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 121
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 18063
telemt_me_writer_teardown_success_total{mode="normal"} 20137
telemt_me_writer_teardown_noop_total 19654
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 38992
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 39517
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 39640
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 39762
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 39791
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 39791
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 39791
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 39791
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 39791
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 39791
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 39791
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 39791
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 39791
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 5.465965
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 39791
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 164
telemt_me_refill_failed_total 14
telemt_me_writer_restored_same_endpoint_total 462
telemt_me_writer_restored_fallback_total 3
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 33
telemt_user_connections_total{user="hello"} 1849654
telemt_user_connections_current{user="hello"} 3280
telemt_user_octets_from_client{user="hello"} 42339172732 (39.43 GB)
telemt_user_octets_to_client{user="hello"} 902055310784 (840.10 GB)
telemt_user_unique_ips_current{user="hello"} 1300
telemt_user_unique_ips_recent_window{user="hello"} 464
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 54184.7 (15h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8212376
telemt_connections_bad_total 553149
telemt_connections_current 5209
telemt_connections_me_current 5209
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 288319
telemt_upstream_connect_attempt_total 63942
telemt_upstream_connect_success_total 60230
telemt_upstream_connect_fail_total 2946
telemt_upstream_connect_attempts_per_request{bucket="1"} 63176
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 42207
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15658
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2365
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2946
telemt_me_keepalive_timeout_total 59
telemt_me_reconnect_attempts_total 3201
telemt_me_reconnect_success_total 1096
telemt_me_reader_eof_total 795
telemt_me_idle_close_by_peer_total 794
telemt_me_route_drop_no_conn_total 14376487
telemt_me_route_drop_channel_closed_total 56
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6834236
telemt_me_endpoint_quarantine_total 425
telemt_me_single_endpoint_outage_enter_total 58
telemt_me_single_endpoint_outage_exit_total 58
telemt_me_single_endpoint_outage_reconnect_attempt_total 121
telemt_me_single_endpoint_outage_reconnect_success_total 28
telemt_me_single_endpoint_quarantine_bypass_total 121
telemt_me_single_endpoint_shadow_rotate_total 427
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
telemt_me_writers_active_current 41
telemt_desync_total 12956
telemt_desync_full_logged_total 4178
telemt_desync_suppressed_total 8778
telemt_desync_frames_bucket_total{bucket="1_2"} 2815
telemt_desync_frames_bucket_total{bucket="3_10"} 5722
telemt_desync_frames_bucket_total{bucket="gt_10"} 4419
telemt_pool_swap_total 55
telemt_pool_force_close_total 1697
telemt_pool_stale_pick_total 5
telemt_me_writer_close_signal_drop_total 352
telemt_me_draining_writers_reap_progress_total 18050
telemt_me_writer_removed_unexpected_total 1061
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2318
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 16689
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 9
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1446
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 251
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 16353
telemt_me_writer_teardown_success_total{mode="normal"} 19007
telemt_me_writer_teardown_noop_total 18059
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 34068
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 35122
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 35779
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 36481
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 36903
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 37048
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 37064
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 37066
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 37066
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 37066
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 37066
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 37066
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 37066
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 46.549710
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 37066
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 352
telemt_me_refill_failed_total 80
telemt_me_writer_restored_same_endpoint_total 772
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 61
telemt_me_writer_removed_unexpected_minus_restored_total 281
telemt_user_connections_total{user="hello"} 6869919
telemt_user_connections_current{user="hello"} 5209
telemt_user_octets_from_client{user="hello"} 56674886112 (52.78 GB)
telemt_user_octets_to_client{user="hello"} 649752949479 (605.13 GB)
telemt_user_msgs_from_client{user="hello"} 129175
telemt_user_msgs_to_client{user="hello"} 449473
telemt_user_unique_ips_current{user="hello"} 1866
telemt_user_unique_ips_recent_window{user="hello"} 1010
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 54152.3 (15h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2594374
telemt_connections_bad_total 317811
telemt_connections_current 3402
telemt_connections_me_current 3402
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 57542
telemt_upstream_connect_attempt_total 23438
telemt_upstream_connect_success_total 23182
telemt_upstream_connect_fail_total 230
telemt_upstream_connect_attempts_per_request{bucket="1"} 23412
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11157
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11976
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 49
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 230
telemt_me_reconnect_attempts_total 2300
telemt_me_reconnect_success_total 765
telemt_me_reader_eof_total 758
telemt_me_idle_close_by_peer_total 758
telemt_me_route_drop_no_conn_total 893377
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 33
telemt_me_route_drop_queue_full_profile_total{profile="high"} 33
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1961894
telemt_me_endpoint_quarantine_total 344
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 11
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 11
telemt_me_single_endpoint_shadow_rotate_total 415
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
telemt_desync_total 8948
telemt_desync_full_logged_total 3225
telemt_desync_suppressed_total 5723
telemt_desync_frames_bucket_total{bucket="1_2"} 1725
telemt_desync_frames_bucket_total{bucket="3_10"} 3608
telemt_desync_frames_bucket_total{bucket="gt_10"} 3615
telemt_pool_swap_total 56
telemt_pool_force_close_total 1517
telemt_pool_stale_pick_total 54
telemt_me_writer_close_signal_drop_total 133
telemt_me_draining_writers_reap_progress_total 19463
telemt_me_writer_removed_unexpected_total 733
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1824
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 18397
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1362
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 155
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 17946
telemt_me_writer_teardown_success_total{mode="normal"} 20221
telemt_me_writer_teardown_noop_total 19463
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 39297
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 39535
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 39658
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 39684
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 39684
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 39684
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 39684
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 39684
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 39684
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 39684
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 39684
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 39684
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 39684
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 2.163128
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 39684
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 133
telemt_me_refill_failed_total 84
telemt_me_writer_restored_same_endpoint_total 642
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 20
telemt_me_writer_removed_unexpected_minus_restored_total 83
telemt_user_connections_total{user="hello"} 1947188
telemt_user_connections_current{user="hello"} 3402
telemt_user_octets_from_client{user="hello"} 35351899972 (32.92 GB)
telemt_user_octets_to_client{user="hello"} 871704738426 (811.84 GB)
telemt_user_msgs_from_client{user="hello"} 7339
telemt_user_msgs_to_client{user="hello"} 11522
telemt_user_unique_ips_current{user="hello"} 1326
telemt_user_unique_ips_recent_window{user="hello"} 672
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 54146.8 (15h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3839321
telemt_connections_bad_total 200188
telemt_connections_current 3623
telemt_connections_me_current 3623
telemt_handshake_timeouts_total 1660367
telemt_upstream_connect_attempt_total 21981
telemt_upstream_connect_success_total 21946
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 21949
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9858
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11802
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 286
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_reconnect_attempts_total 798
telemt_me_reconnect_success_total 395
telemt_me_reader_eof_total 394
telemt_me_idle_close_by_peer_total 394
telemt_me_route_drop_no_conn_total 746443
telemt_me_route_drop_channel_closed_total 5
telemt_me_route_drop_queue_full_total 12
telemt_me_route_drop_queue_full_profile_total{profile="high"} 12
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1739852
telemt_me_endpoint_quarantine_total 416
telemt_me_single_endpoint_outage_enter_total 1
telemt_me_single_endpoint_outage_exit_total 1
telemt_me_single_endpoint_outage_reconnect_attempt_total 1
telemt_me_single_endpoint_outage_reconnect_success_total 1
telemt_me_single_endpoint_quarantine_bypass_total 1
telemt_me_single_endpoint_shadow_rotate_total 425
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 12
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
telemt_desync_total 8588
telemt_desync_full_logged_total 3049
telemt_desync_suppressed_total 5539
telemt_desync_frames_bucket_total{bucket="1_2"} 1573
telemt_desync_frames_bucket_total{bucket="3_10"} 3428
telemt_desync_frames_bucket_total{bucket="gt_10"} 3587
telemt_pool_swap_total 59
telemt_pool_force_close_total 1460
telemt_me_writer_close_signal_drop_total 118
telemt_me_draining_writers_reap_progress_total 19637
telemt_me_writer_removed_unexpected_total 382
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1319
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 18721
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1411
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 49
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 18177
telemt_me_writer_teardown_success_total{mode="normal"} 20040
telemt_me_writer_teardown_noop_total 19637
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 39481
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 39628
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 39667
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 39677
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 39677
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 39677
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 39677
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 39677
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 39677
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 39677
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 39677
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 39677
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 39677
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 1.043418
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 39677
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 118
telemt_me_refill_failed_total 22
telemt_me_writer_restored_same_endpoint_total 346
telemt_me_writer_restored_fallback_total 2
telemt_me_writer_removed_unexpected_minus_restored_total 34
telemt_user_connections_total{user="hello"} 1733832
telemt_user_connections_current{user="hello"} 3623
telemt_user_octets_from_client{user="hello"} 30589650440 (28.49 GB)
telemt_user_octets_to_client{user="hello"} 840047741972 (782.36 GB)
telemt_user_unique_ips_current{user="hello"} 1515
telemt_user_unique_ips_recent_window{user="hello"} 541
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 52138.1 (14h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 799587
telemt_connections_bad_total 51456
telemt_connections_current 721
telemt_connections_me_current 721
telemt_handshake_timeouts_total 291970
telemt_upstream_connect_attempt_total 25043
telemt_upstream_connect_success_total 25041
telemt_upstream_connect_attempts_per_request{bucket="1"} 25041
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10342
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14628
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 71
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 1081
telemt_me_reconnect_success_total 414
telemt_me_reader_eof_total 409
telemt_me_idle_close_by_peer_total 409
telemt_me_route_drop_no_conn_total 172290
telemt_me_route_drop_channel_closed_total 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 394089
telemt_me_endpoint_quarantine_total 485
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 4
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 444
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
telemt_me_writers_active_current 46
telemt_desync_total 2729
telemt_desync_full_logged_total 1044
telemt_desync_suppressed_total 1685
telemt_desync_frames_bucket_total{bucket="1_2"} 432
telemt_desync_frames_bucket_total{bucket="3_10"} 989
telemt_desync_frames_bucket_total{bucket="gt_10"} 1308
telemt_pool_swap_total 57
telemt_pool_force_close_total 1267
telemt_pool_stale_pick_total 7
telemt_me_writer_close_signal_drop_total 85
telemt_me_draining_writers_reap_progress_total 22415
telemt_me_writer_removed_unexpected_total 389
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1634
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 21175
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1264
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 21148
telemt_me_writer_teardown_success_total{mode="normal"} 22809
telemt_me_writer_teardown_noop_total 22415
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 44797
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 45127
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 45192
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 45217
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 45224
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 45224
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 45224
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 45224
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 45224
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 45224
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 45224
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 45224
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 45224
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 2.582278
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 45224
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 85
telemt_me_refill_failed_total 35
telemt_me_writer_restored_same_endpoint_total 334
telemt_me_writer_restored_fallback_total 5
telemt_me_writer_removed_unexpected_minus_restored_total 50
telemt_user_connections_total{user="hello"} 393970
telemt_user_connections_current{user="hello"} 721
telemt_user_octets_from_client{user="hello"} 6384782359 (5.95 GB)
telemt_user_octets_to_client{user="hello"} 151959857401 (141.52 GB)
telemt_user_msgs_from_client{user="hello"} 804
telemt_user_msgs_to_client{user="hello"} 1943
telemt_user_unique_ips_current{user="hello"} 296
telemt_user_unique_ips_recent_window{user="hello"} 113
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 54156.6 (15h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2747828
telemt_connections_bad_total 256178
telemt_connections_current 4207
telemt_connections_me_current 4207
telemt_handshake_timeouts_total 71500
telemt_upstream_connect_attempt_total 22777
telemt_upstream_connect_success_total 22681
telemt_upstream_connect_fail_total 65
telemt_upstream_connect_attempts_per_request{bucket="1"} 22746
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11310
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11345
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 65
telemt_me_reconnect_attempts_total 933
telemt_me_reconnect_success_total 516
telemt_me_reader_eof_total 482
telemt_me_idle_close_by_peer_total 482
telemt_me_route_drop_no_conn_total 732294
telemt_me_route_drop_channel_closed_total 14
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2174809
telemt_me_endpoint_quarantine_total 422
telemt_me_single_endpoint_outage_enter_total 6
telemt_me_single_endpoint_outage_exit_total 6
telemt_me_single_endpoint_outage_reconnect_attempt_total 6
telemt_me_single_endpoint_outage_reconnect_success_total 6
telemt_me_single_endpoint_quarantine_bypass_total 6
telemt_me_single_endpoint_shadow_rotate_total 423
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
telemt_me_writers_active_current 44
telemt_desync_total 8689
telemt_desync_full_logged_total 2884
telemt_desync_suppressed_total 5805
telemt_desync_frames_bucket_total{bucket="1_2"} 2070
telemt_desync_frames_bucket_total{bucket="3_10"} 3247
telemt_desync_frames_bucket_total{bucket="gt_10"} 3372
telemt_pool_swap_total 60
telemt_pool_force_close_total 1479
telemt_pool_stale_pick_total 2
telemt_me_writer_close_signal_drop_total 156
telemt_me_draining_writers_reap_progress_total 20435
telemt_me_writer_removed_unexpected_total 474
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1564
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 19361
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1452
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 27
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 18956
telemt_me_writer_teardown_success_total{mode="normal"} 20925
telemt_me_writer_teardown_noop_total 20435
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 40884
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 41192
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 41253
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 41353
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 41360
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 41360
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 41360
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 41360
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 41360
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 41360
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 41360
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 41360
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 41360
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.493080
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 41360
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 156
telemt_me_refill_failed_total 21
telemt_me_writer_restored_same_endpoint_total 461
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 8
telemt_user_connections_total{user="hello"} 2168303
telemt_user_connections_current{user="hello"} 4207
telemt_user_octets_from_client{user="hello"} 45667208036 (42.53 GB)
telemt_user_octets_to_client{user="hello"} 1016302068232 (946.51 GB)
telemt_user_unique_ips_current{user="hello"} 1554
telemt_user_unique_ips_recent_window{user="hello"} 577
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 54153.2 (15h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2520586
telemt_connections_bad_total 197692
telemt_connections_current 3653
telemt_connections_me_current 3653
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 67387
telemt_upstream_connect_attempt_total 38912
telemt_upstream_connect_success_total 38674
telemt_upstream_connect_fail_total 195
telemt_upstream_connect_attempts_per_request{bucket="1"} 38869
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 24626
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12949
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 514
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 585
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 195
telemt_me_reconnect_attempts_total 3245
telemt_me_reconnect_success_total 668
telemt_me_reader_eof_total 585
telemt_me_idle_close_by_peer_total 585
telemt_me_seq_mismatch_total 28
telemt_me_route_drop_no_conn_total 735933
telemt_me_route_drop_channel_closed_total 52
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2026685
telemt_me_endpoint_quarantine_total 470
telemt_me_single_endpoint_outage_enter_total 14
telemt_me_single_endpoint_outage_exit_total 14
telemt_me_single_endpoint_outage_reconnect_attempt_total 14
telemt_me_single_endpoint_outage_reconnect_success_total 14
telemt_me_single_endpoint_quarantine_bypass_total 14
telemt_me_single_endpoint_shadow_rotate_total 421
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
telemt_me_writers_active_current 43
telemt_desync_total 7644
telemt_desync_full_logged_total 2614
telemt_desync_suppressed_total 5030
telemt_desync_frames_bucket_total{bucket="1_2"} 2005
telemt_desync_frames_bucket_total{bucket="3_10"} 2835
telemt_desync_frames_bucket_total{bucket="gt_10"} 2804
telemt_pool_swap_total 59
telemt_pool_force_close_total 1435
telemt_me_writer_close_signal_drop_total 133
telemt_me_draining_writers_reap_progress_total 19590
telemt_me_writer_removed_unexpected_total 597
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1837
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 18378
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1343
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 92
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 18155
telemt_me_writer_teardown_success_total{mode="normal"} 20215
telemt_me_writer_teardown_noop_total 19591
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 39276
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 39571
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 39709
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 39800
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 39806
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 39806
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 39806
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 39806
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 39806
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 39806
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 39806
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 39806
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 39806
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 4.154497
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 39806
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 133
telemt_me_refill_failed_total 146
telemt_me_writer_restored_same_endpoint_total 507
telemt_me_writer_restored_fallback_total 37
telemt_me_async_recovery_trigger_total 45
telemt_me_writer_removed_unexpected_minus_restored_total 53
telemt_user_connections_total{user="hello"} 2037554
telemt_user_connections_current{user="hello"} 3653
telemt_user_octets_from_client{user="hello"} 36672565917 (34.15 GB)
telemt_user_octets_to_client{user="hello"} 896194099352 (834.65 GB)
telemt_user_msgs_from_client{user="hello"} 75721
telemt_user_msgs_to_client{user="hello"} 209236
telemt_user_unique_ips_current{user="hello"} 1421
telemt_user_unique_ips_recent_window{user="hello"} 531
```