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

# Server Metrics 2026-03-22 01:19:19 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 15177.2 (4h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 221611
telemt_connections_bad_total 15646
telemt_connections_current 675
telemt_connections_me_current 675
telemt_handshake_timeouts_total 12790
telemt_upstream_connect_attempt_total 6303
telemt_upstream_connect_success_total 6302
telemt_upstream_connect_attempts_per_request{bucket="1"} 6302
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2307
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3981
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_me_reconnect_attempts_total 213
telemt_me_reconnect_success_total 104
telemt_me_reader_eof_total 100
telemt_me_idle_close_by_peer_total 100
telemt_me_route_drop_no_conn_total 41797
telemt_me_route_drop_channel_closed_total 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 180752
telemt_me_endpoint_quarantine_total 115
telemt_me_single_endpoint_shadow_rotate_total 129
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
telemt_me_writers_active_current 46
telemt_desync_total 1526
telemt_desync_full_logged_total 422
telemt_desync_suppressed_total 1104
telemt_desync_frames_bucket_total{bucket="1_2"} 465
telemt_desync_frames_bucket_total{bucket="3_10"} 551
telemt_desync_frames_bucket_total{bucket="gt_10"} 510
telemt_pool_swap_total 16
telemt_pool_force_close_total 418
telemt_me_writer_close_signal_drop_total 29
telemt_me_draining_writers_reap_progress_total 5637
telemt_me_writer_removed_unexpected_total 102
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 402
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 5325
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 414
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 5219
telemt_me_writer_teardown_success_total{mode="normal"} 5727
telemt_me_writer_teardown_noop_total 5638
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 11030
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 11229
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 11294
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 11339
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 11363
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 11365
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 11365
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 11365
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 11365
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 11365
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 11365
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 11365
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 11365
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 2.855830
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 11365
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 29
telemt_me_refill_failed_total 6
telemt_me_writer_restored_same_endpoint_total 96
telemt_me_writer_removed_unexpected_minus_restored_total 6
telemt_user_connections_total{user="hello"} 180461
telemt_user_connections_current{user="hello"} 675
telemt_user_octets_from_client{user="hello"} 1987361400 (1.85 GB)
telemt_user_octets_to_client{user="hello"} 60165274980 (56.03 GB)
telemt_user_unique_ips_current{user="hello"} 331
telemt_user_unique_ips_recent_window{user="hello"} 77
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 28543.2 (7h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 728862
telemt_connections_bad_total 42075
telemt_connections_current 628
telemt_connections_me_current 628
telemt_handshake_timeouts_total 27304
telemt_upstream_connect_attempt_total 12585
telemt_upstream_connect_success_total 12379
telemt_upstream_connect_fail_total 186
telemt_upstream_connect_attempts_per_request{bucket="1"} 12565
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5538
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6802
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 39
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 186
telemt_me_reconnect_attempts_total 1088
telemt_me_reconnect_success_total 367
telemt_me_reader_eof_total 319
telemt_me_idle_close_by_peer_total 319
telemt_me_route_drop_no_conn_total 333589
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 585211
telemt_me_endpoint_quarantine_total 263
telemt_me_single_endpoint_outage_enter_total 16
telemt_me_single_endpoint_outage_exit_total 16
telemt_me_single_endpoint_outage_reconnect_attempt_total 16
telemt_me_single_endpoint_outage_reconnect_success_total 16
telemt_me_single_endpoint_quarantine_bypass_total 16
telemt_me_single_endpoint_shadow_rotate_total 231
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
telemt_me_writers_active_current 46
telemt_desync_total 2557
telemt_desync_full_logged_total 1464
telemt_desync_suppressed_total 1093
telemt_desync_frames_bucket_total{bucket="1_2"} 548
telemt_desync_frames_bucket_total{bucket="3_10"} 959
telemt_desync_frames_bucket_total{bucket="gt_10"} 1050
telemt_pool_swap_total 31
telemt_pool_force_close_total 843
telemt_me_writer_close_signal_drop_total 61
telemt_me_draining_writers_reap_progress_total 11113
telemt_me_writer_removed_unexpected_total 301
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 940
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 10479
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 836
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 10270
telemt_me_writer_teardown_success_total{mode="normal"} 11419
telemt_me_writer_teardown_noop_total 11113
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 22057
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 22338
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 22426
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 22518
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 22530
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 22532
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 22532
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 22532
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 22532
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 22532
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 22532
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 22532
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 22532
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.470007
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 22532
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 61
telemt_me_refill_failed_total 38
telemt_me_writer_restored_same_endpoint_total 257
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 8
telemt_me_writer_removed_unexpected_minus_restored_total 35
telemt_user_connections_total{user="hello"} 584343
telemt_user_connections_current{user="hello"} 628
telemt_user_octets_from_client{user="hello"} 9811470072 (9.14 GB)
telemt_user_octets_to_client{user="hello"} 209038680044 (194.68 GB)
telemt_user_unique_ips_current{user="hello"} 421
telemt_user_unique_ips_recent_window{user="hello"} 105
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 103403.2 (28h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7593181
telemt_connections_bad_total 616770
telemt_connections_current 1793
telemt_connections_me_current 1793
telemt_handshake_timeouts_total 248091
telemt_upstream_connect_attempt_total 37896
telemt_upstream_connect_success_total 37823
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 37830
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17116
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20538
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 163
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 1543
telemt_me_reconnect_success_total 779
telemt_me_reader_eof_total 790
telemt_me_idle_close_by_peer_total 790
telemt_me_route_drop_no_conn_total 4517292
telemt_me_route_drop_channel_closed_total 66
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6168784
telemt_me_endpoint_quarantine_total 654
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 770
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 24
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
telemt_desync_total 26170
telemt_desync_full_logged_total 8643
telemt_desync_suppressed_total 17527
telemt_desync_frames_bucket_total{bucket="1_2"} 5633
telemt_desync_frames_bucket_total{bucket="3_10"} 10205
telemt_desync_frames_bucket_total{bucket="gt_10"} 10332
telemt_pool_swap_total 111
telemt_pool_force_close_total 3731
telemt_pool_stale_pick_total 17
telemt_me_writer_close_signal_drop_total 589
telemt_me_draining_writers_reap_progress_total 34570
telemt_me_writer_removed_unexpected_total 760
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2900
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 31973
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 40
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3492
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 239
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 30839
telemt_me_writer_teardown_success_total{mode="normal"} 34873
telemt_me_writer_teardown_noop_total 34614
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 63404
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 65221
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 66193
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 67659
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 68647
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 69186
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 69476
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 69487
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 69487
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 69487
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 69487
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 69487
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 69487
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 156.363890
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 69487
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 589
telemt_me_refill_failed_total 40
telemt_me_writer_restored_same_endpoint_total 696
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 8
telemt_me_writer_removed_unexpected_minus_restored_total 59
telemt_user_connections_total{user="hello"} 6161058
telemt_user_connections_current{user="hello"} 1793
telemt_user_octets_from_client{user="hello"} 105430808948 (98.19 GB)
telemt_user_octets_to_client{user="hello"} 2041406927992 (1.86 TB)
telemt_user_unique_ips_current{user="hello"} 906
telemt_user_unique_ips_recent_window{user="hello"} 162
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 103404.4 (28h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6250089
telemt_connections_bad_total 582981
telemt_connections_current 1421
telemt_connections_me_current 1421
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 207781
telemt_upstream_connect_attempt_total 41976
telemt_upstream_connect_success_total 41592
telemt_upstream_connect_fail_total 187
telemt_upstream_connect_attempts_per_request{bucket="1"} 41779
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20708
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20296
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 33
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 555
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 187
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 116
telemt_me_reconnect_attempts_total 1895
telemt_me_reconnect_success_total 842
telemt_me_reader_eof_total 811
telemt_me_idle_close_by_peer_total 811
telemt_me_route_drop_no_conn_total 2223769
telemt_me_route_drop_channel_closed_total 256
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4684534
telemt_me_endpoint_quarantine_total 637
telemt_me_single_endpoint_outage_enter_total 7
telemt_me_single_endpoint_outage_exit_total 7
telemt_me_single_endpoint_outage_reconnect_attempt_total 7
telemt_me_single_endpoint_outage_reconnect_success_total 7
telemt_me_single_endpoint_quarantine_bypass_total 7
telemt_me_single_endpoint_shadow_rotate_total 791
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
telemt_desync_total 22333
telemt_desync_full_logged_total 7584
telemt_desync_suppressed_total 14749
telemt_desync_frames_bucket_total{bucket="1_2"} 5379
telemt_desync_frames_bucket_total{bucket="3_10"} 8665
telemt_desync_frames_bucket_total{bucket="gt_10"} 8289
telemt_pool_swap_total 112
telemt_pool_force_close_total 3367
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 353
telemt_me_draining_writers_reap_progress_total 33175
telemt_me_writer_removed_unexpected_total 797
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2817
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 31091
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 6
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3154
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 213
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 29808
telemt_me_writer_teardown_success_total{mode="normal"} 33908
telemt_me_writer_teardown_noop_total 33181
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 63804
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 65327
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 65896
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 66473
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 66884
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 67069
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 67089
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 67089
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 67089
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 67089
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 67089
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 67089
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 67089
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 48.202753
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 67089
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 353
telemt_me_refill_failed_total 56
telemt_me_writer_restored_same_endpoint_total 734
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 20
telemt_me_writer_removed_unexpected_minus_restored_total 55
telemt_user_connections_total{user="hello"} 4615006
telemt_user_connections_current{user="hello"} 1421
telemt_user_octets_from_client{user="hello"} 139300652637 (129.73 GB)
telemt_user_octets_to_client{user="hello"} 2168191792907 (1.97 TB)
telemt_user_msgs_from_client{user="hello"} 39229
telemt_user_msgs_to_client{user="hello"} 49019
telemt_user_unique_ips_current{user="hello"} 711
telemt_user_unique_ips_recent_window{user="hello"} 145
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 103368.8 (28h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6148239
telemt_connections_bad_total 544704
telemt_connections_current 1425
telemt_connections_me_current 1425
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 196800
telemt_upstream_connect_attempt_total 48267
telemt_upstream_connect_success_total 47929
telemt_upstream_connect_fail_total 136
telemt_upstream_connect_attempts_per_request{bucket="1"} 48065
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 24815
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21648
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 408
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1058
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 136
telemt_me_keepalive_timeout_total 58
telemt_me_reconnect_attempts_total 1936
telemt_me_reconnect_success_total 864
telemt_me_reader_eof_total 806
telemt_me_idle_close_by_peer_total 806
telemt_me_route_drop_no_conn_total 2122579
telemt_me_route_drop_channel_closed_total 113
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4581436
telemt_me_endpoint_quarantine_total 714
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 9
telemt_me_single_endpoint_outage_reconnect_success_total 6
telemt_me_single_endpoint_quarantine_bypass_total 9
telemt_me_single_endpoint_shadow_rotate_total 772
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 38
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
telemt_desync_total 22132
telemt_desync_full_logged_total 7408
telemt_desync_suppressed_total 14724
telemt_desync_frames_bucket_total{bucket="1_2"} 5408
telemt_desync_frames_bucket_total{bucket="3_10"} 8477
telemt_desync_frames_bucket_total{bucket="gt_10"} 8247
telemt_pool_swap_total 111
telemt_pool_force_close_total 3246
telemt_pool_stale_pick_total 1618
telemt_me_writer_close_signal_drop_total 378
telemt_me_draining_writers_reap_progress_total 34527
telemt_me_writer_removed_unexpected_total 781
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2871
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 32448
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 11
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3031
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 215
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 31281
telemt_me_writer_teardown_success_total{mode="normal"} 35319
telemt_me_writer_teardown_noop_total 34538
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 67349
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 68710
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 69149
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 69607
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 69814
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 69839
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 69857
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 69857
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 69857
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 69857
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 69857
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 69857
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 69857
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 25.704321
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 69857
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 378
telemt_me_refill_failed_total 59
telemt_me_writer_restored_same_endpoint_total 748
telemt_me_writer_restored_fallback_total 5
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 42
telemt_me_writer_removed_unexpected_minus_restored_total 28
telemt_user_connections_total{user="hello"} 4582109
telemt_user_connections_current{user="hello"} 1425
telemt_user_octets_from_client{user="hello"} 132732904927 (123.62 GB)
telemt_user_octets_to_client{user="hello"} 2093586758099 (1.90 TB)
telemt_user_msgs_from_client{user="hello"} 44246
telemt_user_msgs_to_client{user="hello"} 113178
telemt_user_unique_ips_current{user="hello"} 697
telemt_user_unique_ips_recent_window{user="hello"} 129
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 103407.8 (28h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 20194577
telemt_connections_bad_total 1547453
telemt_connections_current 1956
telemt_connections_me_current 1956
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 591744
telemt_upstream_connect_attempt_total 191091
telemt_upstream_connect_success_total 173386
telemt_upstream_connect_fail_total 16052
telemt_upstream_connect_attempts_per_request{bucket="1"} 189438
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 122180
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 41095
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1221
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8890
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 16052
telemt_me_keepalive_timeout_total 398
telemt_me_reconnect_attempts_total 64566
telemt_me_reconnect_success_total 2215
telemt_me_reader_eof_total 1397
telemt_me_idle_close_by_peer_total 1396
telemt_me_route_drop_no_conn_total 39480761
telemt_me_route_drop_channel_closed_total 124
telemt_me_route_drop_queue_full_total 12
telemt_me_route_drop_queue_full_profile_total{profile="high"} 12
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 16381702
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 5
telemt_me_endpoint_quarantine_total 798
telemt_me_single_endpoint_outage_enter_total 125
telemt_me_single_endpoint_outage_exit_total 125
telemt_me_single_endpoint_outage_reconnect_attempt_total 261
telemt_me_single_endpoint_outage_reconnect_success_total 64
telemt_me_single_endpoint_quarantine_bypass_total 261
telemt_me_single_endpoint_shadow_rotate_total 803
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
telemt_me_writers_active_current 42
telemt_desync_total 31705
telemt_desync_full_logged_total 9474
telemt_desync_suppressed_total 22231
telemt_desync_frames_bucket_total{bucket="1_2"} 6878
telemt_desync_frames_bucket_total{bucket="3_10"} 14074
telemt_desync_frames_bucket_total{bucket="gt_10"} 10753
telemt_pool_swap_total 106
telemt_pool_force_close_total 3491
telemt_pool_stale_pick_total 29
telemt_me_writer_close_signal_drop_total 774
telemt_me_draining_writers_reap_progress_total 32185
telemt_me_writer_removed_unexpected_total 2056
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4343
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 29634
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 23
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2969
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 522
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 28694
telemt_me_writer_teardown_success_total{mode="normal"} 33977
telemt_me_writer_teardown_noop_total 32211
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 59521
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 61918
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 63187
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 64814
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 65752
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 66087
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 66169
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 66171
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 66174
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 66179
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 66179
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 66183
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 66188
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 213.420543
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 66188
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 774
telemt_me_refill_failed_total 3797
telemt_me_writer_restored_same_endpoint_total 1535
telemt_me_writer_restored_fallback_total 21
telemt_me_no_writer_failfast_total 666
telemt_me_async_recovery_trigger_total 14678
telemt_me_writer_removed_unexpected_minus_restored_total 500
telemt_user_connections_total{user="hello"} 16509242
telemt_user_connections_current{user="hello"} 1956
telemt_user_octets_from_client{user="hello"} 202104026256 (188.22 GB)
telemt_user_octets_to_client{user="hello"} 1161146643022 (1.06 TB)
telemt_user_msgs_from_client{user="hello"} 367794
telemt_user_msgs_to_client{user="hello"} 650852
telemt_user_unique_ips_current{user="hello"} 941
telemt_user_unique_ips_recent_window{user="hello"} 224
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 103375.2 (28h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5920370
telemt_connections_bad_total 556364
telemt_connections_current 1337
telemt_connections_me_current 1337
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 123336
telemt_upstream_connect_attempt_total 56562
telemt_upstream_connect_success_total 55901
telemt_upstream_connect_fail_total 567
telemt_upstream_connect_attempts_per_request{bucket="1"} 56468
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 32961
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22596
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 343
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 567
telemt_me_reconnect_attempts_total 69512
telemt_me_reconnect_success_total 1745
telemt_me_reader_eof_total 1517
telemt_me_idle_close_by_peer_total 1516
telemt_me_route_drop_no_conn_total 2373553
telemt_me_route_drop_channel_closed_total 10
telemt_me_route_drop_queue_full_total 39
telemt_me_route_drop_queue_full_profile_total{profile="high"} 39
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4618750
telemt_me_endpoint_quarantine_total 696
telemt_me_single_endpoint_outage_enter_total 23
telemt_me_single_endpoint_outage_exit_total 23
telemt_me_single_endpoint_outage_reconnect_attempt_total 24
telemt_me_single_endpoint_outage_reconnect_success_total 23
telemt_me_single_endpoint_quarantine_bypass_total 24
telemt_me_single_endpoint_shadow_rotate_total 778
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
telemt_me_writers_active_current 42
telemt_desync_total 23192
telemt_desync_full_logged_total 8139
telemt_desync_suppressed_total 15053
telemt_desync_frames_bucket_total{bucket="1_2"} 4402
telemt_desync_frames_bucket_total{bucket="3_10"} 8974
telemt_desync_frames_bucket_total{bucket="gt_10"} 9816
telemt_pool_swap_total 106
telemt_pool_force_close_total 3089
telemt_pool_stale_pick_total 54
telemt_me_writer_close_signal_drop_total 387
telemt_me_draining_writers_reap_progress_total 36009
telemt_me_writer_removed_unexpected_total 1561
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3771
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 33824
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2688
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 401
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 32920
telemt_me_writer_teardown_success_total{mode="normal"} 37595
telemt_me_writer_teardown_noop_total 36010
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 72354
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 73174
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 73453
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 73573
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 73602
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 73605
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 73605
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 73605
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 73605
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 73605
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 73605
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 73605
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 73605
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 8.082862
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 73605
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 387
telemt_me_refill_failed_total 4200
telemt_me_writer_restored_same_endpoint_total 1463
telemt_me_writer_restored_fallback_total 32
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7305
telemt_me_writer_removed_unexpected_minus_restored_total 66
telemt_user_connections_total{user="hello"} 4611760
telemt_user_connections_current{user="hello"} 1337
telemt_user_octets_from_client{user="hello"} 123078260456 (114.63 GB)
telemt_user_octets_to_client{user="hello"} 1885113807278 (1.71 TB)
telemt_user_msgs_from_client{user="hello"} 77823
telemt_user_msgs_to_client{user="hello"} 338392
telemt_user_unique_ips_current{user="hello"} 686
telemt_user_unique_ips_recent_window{user="hello"} 136
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 40210.9 (11h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3811387
telemt_connections_bad_total 138411
telemt_connections_current 1212
telemt_connections_me_current 1212
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 1570211
telemt_upstream_connect_attempt_total 24883
telemt_upstream_connect_success_total 24719
telemt_upstream_connect_fail_total 157
telemt_upstream_connect_attempts_per_request{bucket="1"} 24876
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16036
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8613
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 70
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 157
telemt_me_reconnect_attempts_total 45761
telemt_me_reconnect_success_total 925
telemt_me_reader_eof_total 602
telemt_me_idle_close_by_peer_total 602
telemt_me_route_drop_no_conn_total 1008956
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1855154
telemt_me_endpoint_quarantine_total 299
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 50
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 50
telemt_me_single_endpoint_shadow_rotate_total 305
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
telemt_me_writers_active_current 43
telemt_me_floor_cap_block_total 23
telemt_me_floor_swap_idle_failed_total 23
telemt_desync_total 10175
telemt_desync_full_logged_total 3508
telemt_desync_suppressed_total 6667
telemt_desync_frames_bucket_total{bucket="1_2"} 1816
telemt_desync_frames_bucket_total{bucket="3_10"} 3888
telemt_desync_frames_bucket_total{bucket="gt_10"} 4471
telemt_pool_swap_total 43
telemt_pool_force_close_total 1372
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 128
telemt_me_draining_writers_reap_progress_total 14160
telemt_me_writer_removed_unexpected_total 681
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1406
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 13456
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1166
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 206
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 12788
telemt_me_writer_teardown_success_total{mode="normal"} 14862
telemt_me_writer_teardown_noop_total 14162
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 28529
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 28803
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 28918
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 29024
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 29024
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 29024
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 29024
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 29024
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 29024
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 29024
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 29024
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 29024
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 29024
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.311705
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 29024
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 128
telemt_me_refill_failed_total 2605
telemt_me_writer_restored_same_endpoint_total 827
telemt_me_writer_restored_fallback_total 12
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4264
telemt_user_connections_total{user="hello"} 1858852
telemt_user_connections_current{user="hello"} 1212
telemt_user_octets_from_client{user="hello"} 53379275516 (49.71 GB)
telemt_user_octets_to_client{user="hello"} 795023759370 (740.42 GB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 643
telemt_user_unique_ips_recent_window{user="hello"} 145
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 21182.4 (5h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 177476
telemt_connections_bad_total 1541
telemt_connections_current 310
telemt_connections_me_current 310
telemt_handshake_timeouts_total 4899
telemt_upstream_connect_attempt_total 10073
telemt_upstream_connect_success_total 10049
telemt_upstream_connect_fail_total 22
telemt_upstream_connect_attempts_per_request{bucket="1"} 10071
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4278
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5698
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 73
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 22
telemt_me_reconnect_attempts_total 220
telemt_me_reconnect_success_total 134
telemt_me_reader_eof_total 136
telemt_me_idle_close_by_peer_total 136
telemt_me_route_drop_no_conn_total 49019
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 155946
telemt_me_endpoint_quarantine_total 211
telemt_me_single_endpoint_shadow_rotate_total 188
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 3
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
telemt_me_writers_active_current 44
telemt_desync_total 996
telemt_desync_full_logged_total 249
telemt_desync_suppressed_total 747
telemt_desync_frames_bucket_total{bucket="1_2"} 388
telemt_desync_frames_bucket_total{bucket="3_10"} 364
telemt_desync_frames_bucket_total{bucket="gt_10"} 244
telemt_pool_swap_total 23
telemt_pool_force_close_total 515
telemt_me_writer_close_signal_drop_total 20
telemt_me_draining_writers_reap_progress_total 9074
telemt_me_writer_removed_unexpected_total 132
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 607
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 8603
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 513
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 8559
telemt_me_writer_teardown_success_total{mode="normal"} 9210
telemt_me_writer_teardown_noop_total 9074
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 18113
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 18256
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 18274
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 18284
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 18284
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 18284
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 18284
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 18284
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 18284
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 18284
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 18284
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 18284
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 18284
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.887742
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 18284
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 20
telemt_me_refill_failed_total 5
telemt_me_writer_restored_same_endpoint_total 123
telemt_me_writer_removed_unexpected_minus_restored_total 9
telemt_user_connections_total{user="hello"} 155653
telemt_user_connections_current{user="hello"} 310
telemt_user_octets_from_client{user="hello"} 2879080740 (2.68 GB)
telemt_user_octets_to_client{user="hello"} 91417648080 (85.14 GB)
telemt_user_unique_ips_current{user="hello"} 142
telemt_user_unique_ips_recent_window{user="hello"} 43
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 103379.7 (28h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7171507
telemt_connections_bad_total 729411
telemt_connections_current 1749
telemt_connections_me_current 1749
telemt_handshake_timeouts_total 204568
telemt_upstream_connect_attempt_total 40049
telemt_upstream_connect_success_total 39896
telemt_upstream_connect_fail_total 116
telemt_upstream_connect_attempts_per_request{bucket="1"} 40012
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19777
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20078
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 40
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 116
telemt_me_reconnect_attempts_total 1532
telemt_me_reconnect_success_total 816
telemt_me_reader_eof_total 798
telemt_me_idle_close_by_peer_total 798
telemt_me_route_drop_no_conn_total 2110993
telemt_me_route_drop_channel_closed_total 52
telemt_me_route_drop_queue_full_total 23
telemt_me_route_drop_queue_full_profile_total{profile="high"} 23
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5394413
telemt_me_endpoint_quarantine_total 713
telemt_me_single_endpoint_outage_enter_total 8
telemt_me_single_endpoint_outage_exit_total 8
telemt_me_single_endpoint_outage_reconnect_attempt_total 8
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 8
telemt_me_single_endpoint_shadow_rotate_total 794
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
telemt_me_writers_active_current 45
telemt_desync_total 20984
telemt_desync_full_logged_total 6963
telemt_desync_suppressed_total 14021
telemt_desync_frames_bucket_total{bucket="1_2"} 5168
telemt_desync_frames_bucket_total{bucket="3_10"} 7599
telemt_desync_frames_bucket_total{bucket="gt_10"} 8217
telemt_pool_swap_total 114
telemt_pool_force_close_total 3087
telemt_pool_stale_pick_total 3
telemt_me_writer_close_signal_drop_total 377
telemt_me_draining_writers_reap_progress_total 36089
telemt_me_writer_removed_unexpected_total 769
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2876
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 34001
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2999
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 88
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 33002
telemt_me_writer_teardown_success_total{mode="normal"} 36877
telemt_me_writer_teardown_noop_total 36091
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 71618
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 72502
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 72680
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 72880
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 72968
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 72968
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 72968
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 72968
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 72968
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 72968
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 72968
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 72968
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 72968
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 10.596614
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 72968
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 377
telemt_me_refill_failed_total 37
telemt_me_writer_restored_same_endpoint_total 726
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 35
telemt_user_connections_total{user="hello"} 5369505
telemt_user_connections_current{user="hello"} 1749
telemt_user_octets_from_client{user="hello"} 108410152508 (100.96 GB)
telemt_user_octets_to_client{user="hello"} 2512424159108 (2.29 TB)
telemt_user_unique_ips_current{user="hello"} 768
telemt_user_unique_ips_recent_window{user="hello"} 140
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 103376.1 (28h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6178830
telemt_connections_bad_total 609878
telemt_connections_current 1431
telemt_connections_me_current 1431
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 169979
telemt_upstream_connect_attempt_total 55874
telemt_upstream_connect_success_total 55456
telemt_upstream_connect_fail_total 359
telemt_upstream_connect_attempts_per_request{bucket="1"} 55815
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 32580
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21743
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 518
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 615
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 359
telemt_me_reconnect_attempts_total 5442
telemt_me_reconnect_success_total 1131
telemt_me_reader_eof_total 1013
telemt_me_idle_close_by_peer_total 1013
telemt_me_seq_mismatch_total 45
telemt_me_route_drop_no_conn_total 2165067
telemt_me_route_drop_channel_closed_total 189
telemt_me_route_drop_queue_full_total 11
telemt_me_route_drop_queue_full_profile_total{profile="high"} 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4763361
telemt_me_endpoint_quarantine_total 825
telemt_me_single_endpoint_outage_enter_total 27
telemt_me_single_endpoint_outage_exit_total 27
telemt_me_single_endpoint_outage_reconnect_attempt_total 27
telemt_me_single_endpoint_outage_reconnect_success_total 25
telemt_me_single_endpoint_quarantine_bypass_total 27
telemt_me_single_endpoint_shadow_rotate_total 789
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
telemt_me_writers_active_current 44
telemt_desync_total 19716
telemt_desync_full_logged_total 6596
telemt_desync_suppressed_total 13120
telemt_desync_frames_bucket_total{bucket="1_2"} 4973
telemt_desync_frames_bucket_total{bucket="3_10"} 7175
telemt_desync_frames_bucket_total{bucket="gt_10"} 7568
telemt_pool_swap_total 112
telemt_pool_force_close_total 3044
telemt_pool_stale_pick_total 358
telemt_me_writer_close_signal_drop_total 373
telemt_me_draining_writers_reap_progress_total 34678
telemt_me_writer_removed_unexpected_total 1025
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3378
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 32373
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2821
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 223
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 31634
telemt_me_writer_teardown_success_total{mode="normal"} 35751
telemt_me_writer_teardown_noop_total 34682
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 68807
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 69855
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 70200
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 70395
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 70433
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 70433
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 70433
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 70433
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 70433
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 70433
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 70433
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 70433
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 70433
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 10.980073
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 70433
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 373
telemt_me_refill_failed_total 249
telemt_me_writer_restored_same_endpoint_total 882
telemt_me_writer_restored_fallback_total 58
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 76
telemt_me_writer_removed_unexpected_minus_restored_total 85
telemt_user_connections_total{user="hello"} 4766511
telemt_user_connections_current{user="hello"} 1431
telemt_user_octets_from_client{user="hello"} 89731770185 (83.57 GB)
telemt_user_octets_to_client{user="hello"} 2040242290020 (1.86 TB)
telemt_user_msgs_from_client{user="hello"} 75721
telemt_user_msgs_to_client{user="hello"} 209236
telemt_user_unique_ips_current{user="hello"} 684
telemt_user_unique_ips_recent_window{user="hello"} 137
```