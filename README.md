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

# Server Metrics 2026-03-22 00:58:59 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 13957.0 (3h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 207068
telemt_connections_bad_total 14423
telemt_connections_current 634
telemt_connections_me_current 634
telemt_handshake_timeouts_total 11857
telemt_upstream_connect_attempt_total 5762
telemt_upstream_connect_success_total 5761
telemt_upstream_connect_attempts_per_request{bucket="1"} 5761
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2123
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3624
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_me_reconnect_attempts_total 201
telemt_me_reconnect_success_total 96
telemt_me_reader_eof_total 92
telemt_me_idle_close_by_peer_total 92
telemt_me_route_drop_no_conn_total 39555
telemt_me_route_drop_channel_closed_total 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 168877
telemt_me_endpoint_quarantine_total 105
telemt_me_single_endpoint_shadow_rotate_total 121
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 2
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
telemt_desync_total 1338
telemt_desync_full_logged_total 370
telemt_desync_suppressed_total 968
telemt_desync_frames_bucket_total{bucket="1_2"} 391
telemt_desync_frames_bucket_total{bucket="3_10"} 476
telemt_desync_frames_bucket_total{bucket="gt_10"} 471
telemt_pool_swap_total 15
telemt_pool_force_close_total 396
telemt_me_writer_close_signal_drop_total 28
telemt_me_draining_writers_reap_progress_total 5158
telemt_me_writer_removed_unexpected_total 94
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 378
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 4862
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 392
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 4762
telemt_me_writer_teardown_success_total{mode="normal"} 5240
telemt_me_writer_teardown_noop_total 5159
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 10069
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 10265
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 10328
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 10373
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 10397
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 10399
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 10399
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 10399
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 10399
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 10399
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 10399
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 10399
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 10399
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 2.817710
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 10399
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 28
telemt_me_refill_failed_total 6
telemt_me_writer_restored_same_endpoint_total 88
telemt_me_writer_removed_unexpected_minus_restored_total 6
telemt_user_connections_total{user="hello"} 168607
telemt_user_connections_current{user="hello"} 634
telemt_user_octets_from_client{user="hello"} 1881736932 (1.75 GB)
telemt_user_octets_to_client{user="hello"} 56538460988 (52.66 GB)
telemt_user_unique_ips_current{user="hello"} 316
telemt_user_unique_ips_recent_window{user="hello"} 60
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 27323.4 (7h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 714158
telemt_connections_bad_total 40837
telemt_connections_current 335
telemt_connections_me_current 335
telemt_handshake_timeouts_total 26953
telemt_upstream_connect_attempt_total 11980
telemt_upstream_connect_success_total 11776
telemt_upstream_connect_fail_total 184
telemt_upstream_connect_attempts_per_request{bucket="1"} 11960
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5266
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6472
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 38
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 184
telemt_me_reconnect_attempts_total 1075
telemt_me_reconnect_success_total 354
telemt_me_reader_eof_total 308
telemt_me_idle_close_by_peer_total 308
telemt_me_route_drop_no_conn_total 331983
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 576049
telemt_me_endpoint_quarantine_total 256
telemt_me_single_endpoint_outage_enter_total 16
telemt_me_single_endpoint_outage_exit_total 16
telemt_me_single_endpoint_outage_reconnect_attempt_total 16
telemt_me_single_endpoint_outage_reconnect_success_total 16
telemt_me_single_endpoint_quarantine_bypass_total 16
telemt_me_single_endpoint_shadow_rotate_total 224
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 16
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 35
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 41
telemt_desync_total 2507
telemt_desync_full_logged_total 1437
telemt_desync_suppressed_total 1070
telemt_desync_frames_bucket_total{bucket="1_2"} 539
telemt_desync_frames_bucket_total{bucket="3_10"} 938
telemt_desync_frames_bucket_total{bucket="gt_10"} 1030
telemt_pool_swap_total 30
telemt_pool_force_close_total 821
telemt_me_writer_close_signal_drop_total 59
telemt_me_draining_writers_reap_progress_total 10578
telemt_me_writer_removed_unexpected_total 290
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 910
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 9963
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 814
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 9757
telemt_me_writer_teardown_success_total{mode="normal"} 10873
telemt_me_writer_teardown_noop_total 10578
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 20977
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 21257
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 21345
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 21437
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 21449
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 21451
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 21451
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 21451
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 21451
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 21451
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 21451
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 21451
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 21451
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.457703
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 21451
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 59
telemt_me_refill_failed_total 38
telemt_me_writer_restored_same_endpoint_total 246
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 8
telemt_me_writer_removed_unexpected_minus_restored_total 35
telemt_user_connections_total{user="hello"} 575194
telemt_user_connections_current{user="hello"} 335
telemt_user_octets_from_client{user="hello"} 9726060048 (9.06 GB)
telemt_user_octets_to_client{user="hello"} 203183442964 (189.23 GB)
telemt_user_unique_ips_current{user="hello"} 247
telemt_user_unique_ips_recent_window{user="hello"} 101
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 102183.7 (28h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7556720
telemt_connections_bad_total 611987
telemt_connections_current 1423
telemt_connections_me_current 1423
telemt_handshake_timeouts_total 246257
telemt_upstream_connect_attempt_total 37331
telemt_upstream_connect_success_total 37259
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 37266
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16856
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20235
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 162
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 1529
telemt_me_reconnect_success_total 765
telemt_me_reader_eof_total 776
telemt_me_idle_close_by_peer_total 776
telemt_me_route_drop_no_conn_total 4512286
telemt_me_route_drop_channel_closed_total 66
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6145117
telemt_me_endpoint_quarantine_total 650
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 762
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
telemt_desync_total 26081
telemt_desync_full_logged_total 8619
telemt_desync_suppressed_total 17462
telemt_desync_frames_bucket_total{bucket="1_2"} 5607
telemt_desync_frames_bucket_total{bucket="3_10"} 10176
telemt_desync_frames_bucket_total{bucket="gt_10"} 10298
telemt_pool_swap_total 110
telemt_pool_force_close_total 3688
telemt_pool_stale_pick_total 17
telemt_me_writer_close_signal_drop_total 582
telemt_me_draining_writers_reap_progress_total 34055
telemt_me_writer_removed_unexpected_total 746
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2865
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 31495
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 40
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3449
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 239
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 30367
telemt_me_writer_teardown_success_total{mode="normal"} 34360
telemt_me_writer_teardown_noop_total 34099
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 62442
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 64234
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 65195
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 66642
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 67619
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 68158
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 68448
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 68459
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 68459
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 68459
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 68459
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 68459
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 68459
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 155.543824
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 68459
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 582
telemt_me_refill_failed_total 40
telemt_me_writer_restored_same_endpoint_total 682
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 8
telemt_me_writer_removed_unexpected_minus_restored_total 59
telemt_user_connections_total{user="hello"} 6137402
telemt_user_connections_current{user="hello"} 1423
telemt_user_octets_from_client{user="hello"} 105073700372 (97.86 GB)
telemt_user_octets_to_client{user="hello"} 2031944892808 (1.85 TB)
telemt_user_unique_ips_current{user="hello"} 747
telemt_user_unique_ips_recent_window{user="hello"} 170
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 102184.6 (28h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6219131
telemt_connections_bad_total 581364
telemt_connections_current 1542
telemt_connections_me_current 1542
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 206375
telemt_upstream_connect_attempt_total 41479
telemt_upstream_connect_success_total 41096
telemt_upstream_connect_fail_total 186
telemt_upstream_connect_attempts_per_request{bucket="1"} 41282
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20502
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20006
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 33
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 555
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 186
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 116
telemt_me_reconnect_attempts_total 1884
telemt_me_reconnect_success_total 833
telemt_me_reader_eof_total 801
telemt_me_idle_close_by_peer_total 801
telemt_me_route_drop_no_conn_total 2212504
telemt_me_route_drop_channel_closed_total 255
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4659625
telemt_me_endpoint_quarantine_total 628
telemt_me_single_endpoint_outage_enter_total 7
telemt_me_single_endpoint_outage_exit_total 7
telemt_me_single_endpoint_outage_reconnect_attempt_total 7
telemt_me_single_endpoint_outage_reconnect_success_total 7
telemt_me_single_endpoint_quarantine_bypass_total 7
telemt_me_single_endpoint_shadow_rotate_total 783
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 29
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
telemt_desync_total 22259
telemt_desync_full_logged_total 7551
telemt_desync_suppressed_total 14708
telemt_desync_frames_bucket_total{bucket="1_2"} 5361
telemt_desync_frames_bucket_total{bucket="3_10"} 8629
telemt_desync_frames_bucket_total{bucket="gt_10"} 8269
telemt_pool_swap_total 111
telemt_pool_force_close_total 3343
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 352
telemt_me_draining_writers_reap_progress_total 32733
telemt_me_writer_removed_unexpected_total 788
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2785
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 30671
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 6
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3130
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 213
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 29390
telemt_me_writer_teardown_success_total{mode="normal"} 33456
telemt_me_writer_teardown_noop_total 32739
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 62911
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 64433
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 65002
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 65579
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 65990
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 66175
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 66195
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 66195
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 66195
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 66195
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 66195
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 66195
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 66195
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 48.190885
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 66195
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 352
telemt_me_refill_failed_total 56
telemt_me_writer_restored_same_endpoint_total 725
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 20
telemt_me_writer_removed_unexpected_minus_restored_total 55
telemt_user_connections_total{user="hello"} 4592942
telemt_user_connections_current{user="hello"} 1542
telemt_user_octets_from_client{user="hello"} 138950223705 (129.41 GB)
telemt_user_octets_to_client{user="hello"} 2155999336083 (1.96 TB)
telemt_user_msgs_from_client{user="hello"} 39229
telemt_user_msgs_to_client{user="hello"} 49019
telemt_user_unique_ips_current{user="hello"} 753
telemt_user_unique_ips_recent_window{user="hello"} 133
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 102149.5 (28h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6120322
telemt_connections_bad_total 542214
telemt_connections_current 1310
telemt_connections_me_current 1310
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 196168
telemt_upstream_connect_attempt_total 47791
telemt_upstream_connect_success_total 47461
telemt_upstream_connect_fail_total 136
telemt_upstream_connect_attempts_per_request{bucket="1"} 47597
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 24619
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21391
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 395
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1056
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 136
telemt_me_keepalive_timeout_total 58
telemt_me_reconnect_attempts_total 1902
telemt_me_reconnect_success_total 861
telemt_me_reader_eof_total 801
telemt_me_idle_close_by_peer_total 801
telemt_me_route_drop_no_conn_total 2118294
telemt_me_route_drop_channel_closed_total 113
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4563200
telemt_me_endpoint_quarantine_total 704
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 9
telemt_me_single_endpoint_outage_reconnect_success_total 6
telemt_me_single_endpoint_quarantine_bypass_total 9
telemt_me_single_endpoint_shadow_rotate_total 766
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 36
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
telemt_desync_total 22102
telemt_desync_full_logged_total 7392
telemt_desync_suppressed_total 14710
telemt_desync_frames_bucket_total{bucket="1_2"} 5400
telemt_desync_frames_bucket_total{bucket="3_10"} 8470
telemt_desync_frames_bucket_total{bucket="gt_10"} 8232
telemt_pool_swap_total 110
telemt_pool_force_close_total 3221
telemt_pool_stale_pick_total 1618
telemt_me_writer_close_signal_drop_total 374
telemt_me_draining_writers_reap_progress_total 34083
telemt_me_writer_removed_unexpected_total 776
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2844
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 32026
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 11
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3006
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 215
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 30862
telemt_me_writer_teardown_success_total{mode="normal"} 34870
telemt_me_writer_teardown_noop_total 34094
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 66458
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 67817
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 68256
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 68714
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 68921
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 68946
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 68964
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 68964
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 68964
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 68964
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 68964
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 68964
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 68964
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 25.687948
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 68964
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 374
telemt_me_refill_failed_total 57
telemt_me_writer_restored_same_endpoint_total 746
telemt_me_writer_restored_fallback_total 5
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 42
telemt_me_writer_removed_unexpected_minus_restored_total 25
telemt_user_connections_total{user="hello"} 4563940
telemt_user_connections_current{user="hello"} 1310
telemt_user_octets_from_client{user="hello"} 132495918459 (123.40 GB)
telemt_user_octets_to_client{user="hello"} 2085447252739 (1.90 TB)
telemt_user_msgs_from_client{user="hello"} 44246
telemt_user_msgs_to_client{user="hello"} 113178
telemt_user_unique_ips_current{user="hello"} 658
telemt_user_unique_ips_recent_window{user="hello"} 115
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 102187.3 (28h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 20143318
telemt_connections_bad_total 1529814
telemt_connections_current 2052
telemt_connections_me_current 2052
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 587629
telemt_upstream_connect_attempt_total 190693
telemt_upstream_connect_success_total 173002
telemt_upstream_connect_fail_total 16050
telemt_upstream_connect_attempts_per_request{bucket="1"} 189052
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 122034
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 40857
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1221
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8890
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 16050
telemt_me_keepalive_timeout_total 398
telemt_me_reconnect_attempts_total 64468
telemt_me_reconnect_success_total 2206
telemt_me_reader_eof_total 1387
telemt_me_idle_close_by_peer_total 1386
telemt_me_route_drop_no_conn_total 39473008
telemt_me_route_drop_channel_closed_total 122
telemt_me_route_drop_queue_full_total 12
telemt_me_route_drop_queue_full_profile_total{profile="high"} 12
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 16353185
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 5
telemt_me_endpoint_quarantine_total 789
telemt_me_single_endpoint_outage_enter_total 125
telemt_me_single_endpoint_outage_exit_total 125
telemt_me_single_endpoint_outage_reconnect_attempt_total 261
telemt_me_single_endpoint_outage_reconnect_success_total 64
telemt_me_single_endpoint_quarantine_bypass_total 261
telemt_me_single_endpoint_shadow_rotate_total 798
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 58
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
telemt_desync_total 31629
telemt_desync_full_logged_total 9441
telemt_desync_suppressed_total 22188
telemt_desync_frames_bucket_total{bucket="1_2"} 6867
telemt_desync_frames_bucket_total{bucket="3_10"} 14034
telemt_desync_frames_bucket_total{bucket="gt_10"} 10728
telemt_pool_swap_total 105
telemt_pool_force_close_total 3464
telemt_pool_stale_pick_total 29
telemt_me_writer_close_signal_drop_total 772
telemt_me_draining_writers_reap_progress_total 31837
telemt_me_writer_removed_unexpected_total 2046
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4317
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 29302
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 23
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2942
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 522
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 28373
telemt_me_writer_teardown_success_total{mode="normal"} 33619
telemt_me_writer_teardown_noop_total 31863
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 58858
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 61233
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 62499
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 64118
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 65046
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 65381
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 65463
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 65465
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 65468
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 65473
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 65473
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 65477
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 65482
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 212.858135
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 65482
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 772
telemt_me_refill_failed_total 3792
telemt_me_writer_restored_same_endpoint_total 1530
telemt_me_writer_restored_fallback_total 21
telemt_me_no_writer_failfast_total 666
telemt_me_async_recovery_trigger_total 14678
telemt_me_writer_removed_unexpected_minus_restored_total 495
telemt_user_connections_total{user="hello"} 16480781
telemt_user_connections_current{user="hello"} 2052
telemt_user_octets_from_client{user="hello"} 198359923656 (184.74 GB)
telemt_user_octets_to_client{user="hello"} 1152936058846 (1.05 TB)
telemt_user_msgs_from_client{user="hello"} 367794
telemt_user_msgs_to_client{user="hello"} 650852
telemt_user_unique_ips_current{user="hello"} 967
telemt_user_unique_ips_recent_window{user="hello"} 184
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 102155.0 (28h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5899621
telemt_connections_bad_total 555313
telemt_connections_current 1450
telemt_connections_me_current 1450
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 122622
telemt_upstream_connect_attempt_total 56032
telemt_upstream_connect_success_total 55376
telemt_upstream_connect_fail_total 563
telemt_upstream_connect_attempts_per_request{bucket="1"} 55939
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 32717
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22316
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 342
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 563
telemt_me_reconnect_attempts_total 69426
telemt_me_reconnect_success_total 1736
telemt_me_reader_eof_total 1508
telemt_me_idle_close_by_peer_total 1507
telemt_me_route_drop_no_conn_total 2369682
telemt_me_route_drop_channel_closed_total 10
telemt_me_route_drop_queue_full_total 39
telemt_me_route_drop_queue_full_profile_total{profile="high"} 39
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4600906
telemt_me_endpoint_quarantine_total 689
telemt_me_single_endpoint_outage_enter_total 23
telemt_me_single_endpoint_outage_exit_total 23
telemt_me_single_endpoint_outage_reconnect_attempt_total 24
telemt_me_single_endpoint_outage_reconnect_success_total 23
telemt_me_single_endpoint_quarantine_bypass_total 24
telemt_me_single_endpoint_shadow_rotate_total 770
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
telemt_me_writers_active_current 43
telemt_desync_total 23131
telemt_desync_full_logged_total 8115
telemt_desync_suppressed_total 15016
telemt_desync_frames_bucket_total{bucket="1_2"} 4394
telemt_desync_frames_bucket_total{bucket="3_10"} 8958
telemt_desync_frames_bucket_total{bucket="gt_10"} 9779
telemt_pool_swap_total 105
telemt_pool_force_close_total 3066
telemt_pool_stale_pick_total 54
telemt_me_writer_close_signal_drop_total 384
telemt_me_draining_writers_reap_progress_total 35519
telemt_me_writer_removed_unexpected_total 1552
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3743
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 33353
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2665
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 401
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 32453
telemt_me_writer_teardown_success_total{mode="normal"} 37096
telemt_me_writer_teardown_noop_total 35520
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 71371
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 72188
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 72464
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 72584
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 72613
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 72616
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 72616
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 72616
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 72616
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 72616
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 72616
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 72616
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 72616
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 8.046365
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 72616
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 384
telemt_me_refill_failed_total 4196
telemt_me_writer_restored_same_endpoint_total 1458
telemt_me_writer_restored_fallback_total 32
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7305
telemt_me_writer_removed_unexpected_minus_restored_total 62
telemt_user_connections_total{user="hello"} 4593920
telemt_user_connections_current{user="hello"} 1450
telemt_user_octets_from_client{user="hello"} 122930441656 (114.49 GB)
telemt_user_octets_to_client{user="hello"} 1878920178490 (1.71 TB)
telemt_user_msgs_from_client{user="hello"} 77823
telemt_user_msgs_to_client{user="hello"} 338392
telemt_user_unique_ips_current{user="hello"} 733
telemt_user_unique_ips_recent_window{user="hello"} 117
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 38990.8 (10h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3788010
telemt_connections_bad_total 138196
telemt_connections_current 1045
telemt_connections_me_current 1045
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 1564331
telemt_upstream_connect_attempt_total 24337
telemt_upstream_connect_success_total 24178
telemt_upstream_connect_fail_total 152
telemt_upstream_connect_attempts_per_request{bucket="1"} 24330
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15813
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8297
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 68
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 152
telemt_me_reconnect_attempts_total 45719
telemt_me_reconnect_success_total 916
telemt_me_reader_eof_total 591
telemt_me_idle_close_by_peer_total 591
telemt_me_route_drop_no_conn_total 1006194
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1839368
telemt_me_endpoint_quarantine_total 290
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 50
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 50
telemt_me_single_endpoint_shadow_rotate_total 297
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 8
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
telemt_me_floor_cap_block_total 23
telemt_me_floor_swap_idle_failed_total 23
telemt_desync_total 10131
telemt_desync_full_logged_total 3485
telemt_desync_suppressed_total 6646
telemt_desync_frames_bucket_total{bucket="1_2"} 1802
telemt_desync_frames_bucket_total{bucket="3_10"} 3874
telemt_desync_frames_bucket_total{bucket="gt_10"} 4455
telemt_pool_swap_total 42
telemt_pool_force_close_total 1347
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 127
telemt_me_draining_writers_reap_progress_total 13665
telemt_me_writer_removed_unexpected_total 670
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1379
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 12977
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1141
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 206
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 12318
telemt_me_writer_teardown_success_total{mode="normal"} 14356
telemt_me_writer_teardown_noop_total 13667
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 27529
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 27803
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 27917
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 28023
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 28023
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 28023
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 28023
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 28023
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 28023
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 28023
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 28023
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 28023
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 28023
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.298852
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 28023
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 127
telemt_me_refill_failed_total 2603
telemt_me_writer_restored_same_endpoint_total 819
telemt_me_writer_restored_fallback_total 12
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4264
telemt_user_connections_total{user="hello"} 1843078
telemt_user_connections_current{user="hello"} 1045
telemt_user_octets_from_client{user="hello"} 53229150664 (49.57 GB)
telemt_user_octets_to_client{user="hello"} 790661930522 (736.36 GB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 533
telemt_user_unique_ips_recent_window{user="hello"} 132
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 19961.8 (5h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 172855
telemt_connections_bad_total 1430
telemt_connections_current 279
telemt_connections_me_current 279
telemt_handshake_timeouts_total 4781
telemt_upstream_connect_attempt_total 9413
telemt_upstream_connect_success_total 9389
telemt_upstream_connect_fail_total 22
telemt_upstream_connect_attempts_per_request{bucket="1"} 9411
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4018
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5300
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 71
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 22
telemt_me_reconnect_attempts_total 213
telemt_me_reconnect_success_total 129
telemt_me_reader_eof_total 130
telemt_me_idle_close_by_peer_total 130
telemt_me_route_drop_no_conn_total 48228
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 152022
telemt_me_endpoint_quarantine_total 202
telemt_me_single_endpoint_shadow_rotate_total 176
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 3
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
telemt_me_writers_active_current 42
telemt_desync_total 994
telemt_desync_full_logged_total 248
telemt_desync_suppressed_total 746
telemt_desync_frames_bucket_total{bucket="1_2"} 388
telemt_desync_frames_bucket_total{bucket="3_10"} 363
telemt_desync_frames_bucket_total{bucket="gt_10"} 243
telemt_pool_swap_total 22
telemt_pool_force_close_total 476
telemt_me_writer_close_signal_drop_total 20
telemt_me_draining_writers_reap_progress_total 8432
telemt_me_writer_removed_unexpected_total 127
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 568
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 7994
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 474
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 7956
telemt_me_writer_teardown_success_total{mode="normal"} 8562
telemt_me_writer_teardown_noop_total 8432
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 16842
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 16966
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 16984
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 16994
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 16994
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 16994
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 16994
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 16994
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 16994
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 16994
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 16994
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 16994
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 16994
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.836805
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 16994
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 20
telemt_me_refill_failed_total 5
telemt_me_writer_restored_same_endpoint_total 118
telemt_me_writer_removed_unexpected_minus_restored_total 9
telemt_user_connections_total{user="hello"} 151736
telemt_user_connections_current{user="hello"} 279
telemt_user_octets_from_client{user="hello"} 2832366272 (2.64 GB)
telemt_user_octets_to_client{user="hello"} 89566952584 (83.42 GB)
telemt_user_unique_ips_current{user="hello"} 143
telemt_user_unique_ips_recent_window{user="hello"} 27
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 102159.7 (28h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7131586
telemt_connections_bad_total 725072
telemt_connections_current 1701
telemt_connections_me_current 1701
telemt_handshake_timeouts_total 203530
telemt_upstream_connect_attempt_total 39467
telemt_upstream_connect_success_total 39315
telemt_upstream_connect_fail_total 115
telemt_upstream_connect_attempts_per_request{bucket="1"} 39430
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19507
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19767
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 40
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 115
telemt_me_reconnect_attempts_total 1523
telemt_me_reconnect_success_total 808
telemt_me_reader_eof_total 791
telemt_me_idle_close_by_peer_total 791
telemt_me_route_drop_no_conn_total 2107798
telemt_me_route_drop_channel_closed_total 52
telemt_me_route_drop_queue_full_total 23
telemt_me_route_drop_queue_full_profile_total{profile="high"} 23
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5373606
telemt_me_endpoint_quarantine_total 708
telemt_me_single_endpoint_outage_enter_total 8
telemt_me_single_endpoint_outage_exit_total 8
telemt_me_single_endpoint_outage_reconnect_attempt_total 8
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 8
telemt_me_single_endpoint_shadow_rotate_total 786
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 29
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
telemt_desync_total 20768
telemt_desync_full_logged_total 6943
telemt_desync_suppressed_total 13825
telemt_desync_frames_bucket_total{bucket="1_2"} 5047
telemt_desync_frames_bucket_total{bucket="3_10"} 7525
telemt_desync_frames_bucket_total{bucket="gt_10"} 8196
telemt_pool_swap_total 113
telemt_pool_force_close_total 3064
telemt_pool_stale_pick_total 3
telemt_me_writer_close_signal_drop_total 376
telemt_me_draining_writers_reap_progress_total 35562
telemt_me_writer_removed_unexpected_total 762
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2851
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 33492
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2976
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 88
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 32498
telemt_me_writer_teardown_success_total{mode="normal"} 36343
telemt_me_writer_teardown_noop_total 35564
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 70558
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 71441
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 71619
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 71819
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 71907
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 71907
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 71907
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 71907
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 71907
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 71907
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 71907
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 71907
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 71907
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 10.590289
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 71907
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 376
telemt_me_refill_failed_total 37
telemt_me_writer_restored_same_endpoint_total 719
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 35
telemt_user_connections_total{user="hello"} 5348715
telemt_user_connections_current{user="hello"} 1701
telemt_user_octets_from_client{user="hello"} 108261376604 (100.83 GB)
telemt_user_octets_to_client{user="hello"} 2506322332068 (2.28 TB)
telemt_user_unique_ips_current{user="hello"} 764
telemt_user_unique_ips_recent_window{user="hello"} 136
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 102156.1 (28h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6144246
telemt_connections_bad_total 604765
telemt_connections_current 1365
telemt_connections_me_current 1365
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 169139
telemt_upstream_connect_attempt_total 55325
telemt_upstream_connect_success_total 54909
telemt_upstream_connect_fail_total 357
telemt_upstream_connect_attempts_per_request{bucket="1"} 55266
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 32296
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21480
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 518
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 615
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 357
telemt_me_reconnect_attempts_total 5429
telemt_me_reconnect_success_total 1118
telemt_me_reader_eof_total 1000
telemt_me_idle_close_by_peer_total 1000
telemt_me_seq_mismatch_total 44
telemt_me_route_drop_no_conn_total 2161382
telemt_me_route_drop_channel_closed_total 189
telemt_me_route_drop_queue_full_total 11
telemt_me_route_drop_queue_full_profile_total{profile="high"} 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4742309
telemt_me_endpoint_quarantine_total 816
telemt_me_single_endpoint_outage_enter_total 27
telemt_me_single_endpoint_outage_exit_total 27
telemt_me_single_endpoint_outage_reconnect_attempt_total 27
telemt_me_single_endpoint_outage_reconnect_success_total 25
telemt_me_single_endpoint_quarantine_bypass_total 27
telemt_me_single_endpoint_shadow_rotate_total 780
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
telemt_me_writers_active_current 43
telemt_desync_total 19545
telemt_desync_full_logged_total 6572
telemt_desync_suppressed_total 12973
telemt_desync_frames_bucket_total{bucket="1_2"} 4893
telemt_desync_frames_bucket_total{bucket="3_10"} 7114
telemt_desync_frames_bucket_total{bucket="gt_10"} 7538
telemt_pool_swap_total 111
telemt_pool_force_close_total 3023
telemt_pool_stale_pick_total 358
telemt_me_writer_close_signal_drop_total 372
telemt_me_draining_writers_reap_progress_total 34184
telemt_me_writer_removed_unexpected_total 1012
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3342
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 31901
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2800
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 223
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 31161
telemt_me_writer_teardown_success_total{mode="normal"} 35243
telemt_me_writer_teardown_noop_total 34188
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 67806
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 68853
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 69198
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 69393
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 69431
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 69431
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 69431
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 69431
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 69431
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 69431
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 69431
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 69431
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 69431
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 10.971039
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 69431
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 372
telemt_me_refill_failed_total 249
telemt_me_writer_restored_same_endpoint_total 870
telemt_me_writer_restored_fallback_total 57
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 76
telemt_me_writer_removed_unexpected_minus_restored_total 85
telemt_user_connections_total{user="hello"} 4745483
telemt_user_connections_current{user="hello"} 1365
telemt_user_octets_from_client{user="hello"} 89544394253 (83.39 GB)
telemt_user_octets_to_client{user="hello"} 2033210889792 (1.85 TB)
telemt_user_msgs_from_client{user="hello"} 75721
telemt_user_msgs_to_client{user="hello"} 209236
telemt_user_unique_ips_current{user="hello"} 668
telemt_user_unique_ips_recent_window{user="hello"} 144
```