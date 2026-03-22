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

# Server Metrics 2026-03-22 05:44:57 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 31114.6 (8h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 546335
telemt_connections_bad_total 36166
telemt_connections_current 1345
telemt_connections_me_current 1345
telemt_handshake_timeouts_total 28568
telemt_upstream_connect_attempt_total 12792
telemt_upstream_connect_success_total 12791
telemt_upstream_connect_attempts_per_request{bucket="1"} 12791
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4483
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8277
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 20
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_me_reconnect_attempts_total 336
telemt_me_reconnect_success_total 203
telemt_me_reader_eof_total 199
telemt_me_idle_close_by_peer_total 199
telemt_me_route_drop_no_conn_total 118139
telemt_me_route_drop_channel_closed_total 35
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 452544
telemt_me_endpoint_quarantine_total 234
telemt_me_single_endpoint_shadow_rotate_total 258
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 6
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
telemt_desync_total 3975
telemt_desync_full_logged_total 1099
telemt_desync_suppressed_total 2876
telemt_desync_frames_bucket_total{bucket="1_2"} 1330
telemt_desync_frames_bucket_total{bucket="3_10"} 1509
telemt_desync_frames_bucket_total{bucket="gt_10"} 1136
telemt_pool_swap_total 34
telemt_pool_force_close_total 908
telemt_me_writer_close_signal_drop_total 82
telemt_me_draining_writers_reap_progress_total 11556
telemt_me_writer_removed_unexpected_total 196
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 801
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 10939
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 898
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 10
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 10648
telemt_me_writer_teardown_success_total{mode="normal"} 11740
telemt_me_writer_teardown_noop_total 11557
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 22406
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 22805
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 22988
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 23160
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 23262
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 23297
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 23297
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 23297
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 23297
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 23297
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 23297
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 23297
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 23297
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 11.512701
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 23297
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 82
telemt_me_refill_failed_total 7
telemt_me_writer_restored_same_endpoint_total 185
telemt_me_writer_removed_unexpected_minus_restored_total 11
telemt_user_connections_total{user="hello"} 451539
telemt_user_connections_current{user="hello"} 1345
telemt_user_octets_from_client{user="hello"} 6066267028 (5.65 GB)
telemt_user_octets_to_client{user="hello"} 161355425320 (150.27 GB)
telemt_user_unique_ips_current{user="hello"} 532
telemt_user_unique_ips_recent_window{user="hello"} 185
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 44481.5 (12h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1006072
telemt_connections_bad_total 81369
telemt_connections_current 760
telemt_connections_me_current 760
telemt_handshake_timeouts_total 34036
telemt_upstream_connect_attempt_total 23645
telemt_upstream_connect_success_total 23320
telemt_upstream_connect_fail_total 294
telemt_upstream_connect_attempts_per_request{bucket="1"} 23614
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11904
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11366
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 50
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 294
telemt_me_reconnect_attempts_total 1794
telemt_me_reconnect_success_total 641
telemt_me_reader_eof_total 565
telemt_me_idle_close_by_peer_total 565
telemt_me_route_drop_no_conn_total 381486
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 777463
telemt_me_endpoint_quarantine_total 417
telemt_me_single_endpoint_outage_enter_total 21
telemt_me_single_endpoint_outage_exit_total 21
telemt_me_single_endpoint_outage_reconnect_attempt_total 21
telemt_me_single_endpoint_outage_reconnect_success_total 21
telemt_me_single_endpoint_quarantine_bypass_total 21
telemt_me_single_endpoint_shadow_rotate_total 363
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
telemt_desync_total 3325
telemt_desync_full_logged_total 1924
telemt_desync_suppressed_total 1401
telemt_desync_frames_bucket_total{bucket="1_2"} 697
telemt_desync_frames_bucket_total{bucket="3_10"} 1273
telemt_desync_frames_bucket_total{bucket="gt_10"} 1355
telemt_pool_swap_total 48
telemt_pool_force_close_total 1259
telemt_me_writer_close_signal_drop_total 96
telemt_me_draining_writers_reap_progress_total 18365
telemt_me_writer_removed_unexpected_total 539
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1570
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 17347
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1237
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 22
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 17106
telemt_me_writer_teardown_success_total{mode="normal"} 18917
telemt_me_writer_teardown_noop_total 18365
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 36689
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 37042
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 37166
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 37268
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 37280
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 37282
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 37282
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 37282
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 37282
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 37282
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 37282
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 37282
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 37282
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 4.181270
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 37282
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 96
telemt_me_refill_failed_total 60
telemt_me_writer_restored_same_endpoint_total 480
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 46
telemt_user_connections_total{user="hello"} 779153
telemt_user_connections_current{user="hello"} 760
telemt_user_octets_from_client{user="hello"} 12338700619 (11.49 GB)
telemt_user_octets_to_client{user="hello"} 287829479338 (268.06 GB)
telemt_user_msgs_from_client{user="hello"} 6021
telemt_user_msgs_to_client{user="hello"} 9976
telemt_user_unique_ips_current{user="hello"} 493
telemt_user_unique_ips_recent_window{user="hello"} 278
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 119340.8 (33h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8343446
telemt_connections_bad_total 732185
telemt_connections_current 3173
telemt_connections_me_current 3173
telemt_handshake_timeouts_total 270766
telemt_upstream_connect_attempt_total 44443
telemt_upstream_connect_success_total 44365
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 44373
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20098
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 24077
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 184
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 1650
telemt_me_reconnect_success_total 865
telemt_me_reader_eof_total 873
telemt_me_idle_close_by_peer_total 873
telemt_me_route_drop_no_conn_total 4651849
telemt_me_route_drop_channel_closed_total 67
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6676777
telemt_me_endpoint_quarantine_total 759
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 898
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
telemt_me_writers_active_current 43
telemt_desync_total 28186
telemt_desync_full_logged_total 9397
telemt_desync_suppressed_total 18789
telemt_desync_frames_bucket_total{bucket="1_2"} 6097
telemt_desync_frames_bucket_total{bucket="3_10"} 11014
telemt_desync_frames_bucket_total{bucket="gt_10"} 11075
telemt_pool_swap_total 129
telemt_pool_force_close_total 4263
telemt_pool_stale_pick_total 17
telemt_me_writer_close_signal_drop_total 645
telemt_me_draining_writers_reap_progress_total 40604
telemt_me_writer_removed_unexpected_total 841
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3348
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 37601
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 40
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4016
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 247
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 36341
telemt_me_writer_teardown_success_total{mode="normal"} 40949
telemt_me_writer_teardown_noop_total 40648
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 74885
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 76877
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 77967
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 79579
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 80695
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 81292
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 81586
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 81597
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 81597
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 81597
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 81597
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 81597
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 81597
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 169.414003
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 81597
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 645
telemt_me_refill_failed_total 41
telemt_me_writer_restored_same_endpoint_total 772
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 8
telemt_me_writer_removed_unexpected_minus_restored_total 64
telemt_user_connections_total{user="hello"} 6668068
telemt_user_connections_current{user="hello"} 3173
telemt_user_octets_from_client{user="hello"} 113106827976 (105.34 GB)
telemt_user_octets_to_client{user="hello"} 2270586084452 (2.07 TB)
telemt_user_unique_ips_current{user="hello"} 1357
telemt_user_unique_ips_recent_window{user="hello"} 467
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 119341.9 (33h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6857301
telemt_connections_bad_total 607501
telemt_connections_current 2960
telemt_connections_me_current 2960
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 230116
telemt_upstream_connect_attempt_total 48366
telemt_upstream_connect_success_total 47965
telemt_upstream_connect_fail_total 204
telemt_upstream_connect_attempts_per_request{bucket="1"} 48169
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 23683
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23691
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 33
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 558
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 204
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 116
telemt_me_reconnect_attempts_total 2054
telemt_me_reconnect_success_total 930
telemt_me_reader_eof_total 908
telemt_me_idle_close_by_peer_total 908
telemt_me_route_drop_no_conn_total 2351804
telemt_me_route_drop_channel_closed_total 288
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5130764
telemt_me_endpoint_quarantine_total 756
telemt_me_single_endpoint_outage_enter_total 8
telemt_me_single_endpoint_outage_exit_total 8
telemt_me_single_endpoint_outage_reconnect_attempt_total 8
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 8
telemt_me_single_endpoint_shadow_rotate_total 920
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
telemt_me_writers_active_current 44
telemt_desync_total 23780
telemt_desync_full_logged_total 8159
telemt_desync_suppressed_total 15621
telemt_desync_frames_bucket_total{bucket="1_2"} 5702
telemt_desync_frames_bucket_total{bucket="3_10"} 9235
telemt_desync_frames_bucket_total{bucket="gt_10"} 8843
telemt_pool_swap_total 130
telemt_pool_force_close_total 3853
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 394
telemt_me_draining_writers_reap_progress_total 38973
telemt_me_writer_removed_unexpected_total 887
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3215
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 36588
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 6
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3635
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 218
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 35120
telemt_me_writer_teardown_success_total{mode="normal"} 39803
telemt_me_writer_teardown_noop_total 38979
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 75230
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 76912
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 77555
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 78158
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 78577
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 78762
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 78782
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 78782
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 78782
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 78782
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 78782
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 78782
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 78782
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 49.965774
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 78782
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 394
telemt_me_refill_failed_total 60
telemt_me_writer_restored_same_endpoint_total 811
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20
telemt_me_writer_removed_unexpected_minus_restored_total 66
telemt_user_connections_total{user="hello"} 5052208
telemt_user_connections_current{user="hello"} 2960
telemt_user_octets_from_client{user="hello"} 147174072385 (137.07 GB)
telemt_user_octets_to_client{user="hello"} 2419197893823 (2.20 TB)
telemt_user_msgs_from_client{user="hello"} 39229
telemt_user_msgs_to_client{user="hello"} 49019
telemt_user_unique_ips_current{user="hello"} 1291
telemt_user_unique_ips_recent_window{user="hello"} 358
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 119305.8 (33h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6695824
telemt_connections_bad_total 564310
telemt_connections_current 2646
telemt_connections_me_current 2646
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 223798
telemt_upstream_connect_attempt_total 54788
telemt_upstream_connect_success_total 54229
telemt_upstream_connect_fail_total 143
telemt_upstream_connect_attempts_per_request{bucket="1"} 54372
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 27049
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 25219
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 762
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1199
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 143
telemt_me_keepalive_timeout_total 73
telemt_me_reconnect_attempts_total 2464
telemt_me_reconnect_success_total 1073
telemt_me_reader_eof_total 1011
telemt_me_idle_close_by_peer_total 1011
telemt_me_route_drop_no_conn_total 2362941
telemt_me_route_drop_channel_closed_total 145
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4982930
telemt_me_endpoint_quarantine_total 851
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 11
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 11
telemt_me_single_endpoint_shadow_rotate_total 887
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 42
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
telemt_desync_total 23649
telemt_desync_full_logged_total 8035
telemt_desync_suppressed_total 15614
telemt_desync_frames_bucket_total{bucket="1_2"} 5746
telemt_desync_frames_bucket_total{bucket="3_10"} 9070
telemt_desync_frames_bucket_total{bucket="gt_10"} 8833
telemt_pool_swap_total 128
telemt_pool_force_close_total 3730
telemt_pool_stale_pick_total 1618
telemt_me_writer_close_signal_drop_total 417
telemt_me_draining_writers_reap_progress_total 39995
telemt_me_writer_removed_unexpected_total 1001
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3453
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 37559
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 12
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3488
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 242
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 36265
telemt_me_writer_teardown_success_total{mode="normal"} 41012
telemt_me_writer_teardown_noop_total 40007
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 78033
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 79558
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 80070
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 80644
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 80915
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 80975
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 81019
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 81019
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 81019
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 81019
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 81019
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 81019
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 81019
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 36.993417
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 81019
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 417
telemt_me_refill_failed_total 77
telemt_me_writer_restored_same_endpoint_total 938
telemt_me_writer_restored_fallback_total 6
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 42
telemt_me_writer_removed_unexpected_minus_restored_total 57
telemt_user_connections_total{user="hello"} 4977339
telemt_user_connections_current{user="hello"} 2646
telemt_user_octets_from_client{user="hello"} 137971185527 (128.50 GB)
telemt_user_octets_to_client{user="hello"} 2277838883103 (2.07 TB)
telemt_user_msgs_from_client{user="hello"} 44246
telemt_user_msgs_to_client{user="hello"} 113178
telemt_user_unique_ips_current{user="hello"} 1101
telemt_user_unique_ips_recent_window{user="hello"} 337
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 119345.7 (33h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 21413231
telemt_connections_bad_total 1814452
telemt_connections_current 4278
telemt_connections_me_current 4278
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 652702
telemt_upstream_connect_attempt_total 210640
telemt_upstream_connect_success_total 191966
telemt_upstream_connect_fail_total 16760
telemt_upstream_connect_attempts_per_request{bucket="1"} 208726
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 133165
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 46971
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1954
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9876
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 16760
telemt_me_keepalive_timeout_total 398
telemt_me_reconnect_attempts_total 65497
telemt_me_reconnect_success_total 2545
telemt_me_reader_eof_total 1590
telemt_me_idle_close_by_peer_total 1589
telemt_me_route_drop_no_conn_total 40469768
telemt_me_route_drop_channel_closed_total 130
telemt_me_route_drop_queue_full_total 13
telemt_me_route_drop_queue_full_profile_total{profile="high"} 13
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 17208576
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 5
telemt_me_endpoint_quarantine_total 929
telemt_me_single_endpoint_outage_enter_total 153
telemt_me_single_endpoint_outage_exit_total 153
telemt_me_single_endpoint_outage_reconnect_attempt_total 322
telemt_me_single_endpoint_outage_reconnect_success_total 80
telemt_me_single_endpoint_quarantine_bypass_total 322
telemt_me_single_endpoint_shadow_rotate_total 939
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 70
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
telemt_desync_total 33168
telemt_desync_full_logged_total 10017
telemt_desync_suppressed_total 23151
telemt_desync_frames_bucket_total{bucket="1_2"} 7241
telemt_desync_frames_bucket_total{bucket="3_10"} 14722
telemt_desync_frames_bucket_total{bucket="gt_10"} 11205
telemt_pool_swap_total 123
telemt_pool_force_close_total 3948
telemt_pool_stale_pick_total 29
telemt_me_writer_close_signal_drop_total 871
telemt_me_draining_writers_reap_progress_total 37554
telemt_me_writer_removed_unexpected_total 2368
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5084
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 34587
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 24
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3389
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 559
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 33606
telemt_me_writer_teardown_success_total{mode="normal"} 39671
telemt_me_writer_teardown_noop_total 37581
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 70085
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 72724
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 74076
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 75819
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 76806
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 77148
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 77233
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 77235
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 77238
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 77243
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 77243
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 77247
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 77252
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 219.148064
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 77252
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 871
telemt_me_refill_failed_total 3814
telemt_me_writer_restored_same_endpoint_total 1728
telemt_me_writer_restored_fallback_total 22
telemt_me_no_writer_failfast_total 666
telemt_me_async_recovery_trigger_total 14678
telemt_me_writer_removed_unexpected_minus_restored_total 618
telemt_user_connections_total{user="hello"} 17347944
telemt_user_connections_current{user="hello"} 4278
telemt_user_octets_from_client{user="hello"} 254794102933 (237.30 GB)
telemt_user_octets_to_client{user="hello"} 1340174093223 (1.22 TB)
telemt_user_msgs_from_client{user="hello"} 409002
telemt_user_msgs_to_client{user="hello"} 794272
telemt_user_unique_ips_current{user="hello"} 1685
telemt_user_unique_ips_recent_window{user="hello"} 775
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 119312.6 (33h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6465530
telemt_connections_bad_total 614735
telemt_connections_current 3090
telemt_connections_me_current 3090
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 136238
telemt_upstream_connect_attempt_total 63382
telemt_upstream_connect_success_total 62645
telemt_upstream_connect_fail_total 631
telemt_upstream_connect_attempts_per_request{bucket="1"} 63276
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 36087
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 26196
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 361
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 631
telemt_me_reconnect_attempts_total 69939
telemt_me_reconnect_success_total 1893
telemt_me_reader_eof_total 1667
telemt_me_idle_close_by_peer_total 1666
telemt_me_route_drop_no_conn_total 2486825
telemt_me_route_drop_channel_closed_total 12
telemt_me_route_drop_queue_full_total 39
telemt_me_route_drop_queue_full_profile_total{profile="high"} 39
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5033350
telemt_me_endpoint_quarantine_total 807
telemt_me_single_endpoint_outage_enter_total 24
telemt_me_single_endpoint_outage_exit_total 24
telemt_me_single_endpoint_outage_reconnect_attempt_total 25
telemt_me_single_endpoint_outage_reconnect_success_total 24
telemt_me_single_endpoint_quarantine_bypass_total 25
telemt_me_single_endpoint_shadow_rotate_total 909
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
telemt_me_writers_active_current 45
telemt_desync_total 25049
telemt_desync_full_logged_total 8777
telemt_desync_suppressed_total 16272
telemt_desync_frames_bucket_total{bucket="1_2"} 4956
telemt_desync_frames_bucket_total{bucket="3_10"} 9670
telemt_desync_frames_bucket_total{bucket="gt_10"} 10423
telemt_pool_swap_total 124
telemt_pool_force_close_total 3550
telemt_pool_stale_pick_total 54
telemt_me_writer_close_signal_drop_total 418
telemt_me_draining_writers_reap_progress_total 42102
telemt_me_writer_removed_unexpected_total 1702
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4247
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 39590
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3144
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 406
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 38552
telemt_me_writer_teardown_success_total{mode="normal"} 43837
telemt_me_writer_teardown_noop_total 42103
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 84533
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 85422
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 85714
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 85906
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 85937
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 85940
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 85940
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 85940
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 85940
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 85940
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 85940
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 85940
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 85940
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 9.586180
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 85940
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 418
telemt_me_refill_failed_total 4215
telemt_me_writer_restored_same_endpoint_total 1580
telemt_me_writer_restored_fallback_total 38
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7313
telemt_me_writer_removed_unexpected_minus_restored_total 84
telemt_user_connections_total{user="hello"} 5025342
telemt_user_connections_current{user="hello"} 3090
telemt_user_octets_from_client{user="hello"} 130061534712 (121.13 GB)
telemt_user_octets_to_client{user="hello"} 2091284100074 (1.90 TB)
telemt_user_msgs_from_client{user="hello"} 77823
telemt_user_msgs_to_client{user="hello"} 338392
telemt_user_unique_ips_current{user="hello"} 1302
telemt_user_unique_ips_recent_window{user="hello"} 396
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 56148.5 (15h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4499577
telemt_connections_bad_total 185357
telemt_connections_current 2257
telemt_connections_me_current 2257
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 1781053
telemt_upstream_connect_attempt_total 32234
telemt_upstream_connect_success_total 32018
telemt_upstream_connect_fail_total 209
telemt_upstream_connect_attempts_per_request{bucket="1"} 32227
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19426
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12508
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 84
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 209
telemt_me_reconnect_attempts_total 46101
telemt_me_reconnect_success_total 1036
telemt_me_reader_eof_total 727
telemt_me_idle_close_by_peer_total 727
telemt_me_route_drop_no_conn_total 1124771
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2227309
telemt_me_endpoint_quarantine_total 402
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 50
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 50
telemt_me_single_endpoint_shadow_rotate_total 437
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
telemt_me_writers_active_current 45
telemt_me_floor_cap_block_total 23
telemt_me_floor_swap_idle_failed_total 23
telemt_desync_total 11949
telemt_desync_full_logged_total 4106
telemt_desync_suppressed_total 7843
telemt_desync_frames_bucket_total{bucket="1_2"} 2299
telemt_desync_frames_bucket_total{bucket="3_10"} 4573
telemt_desync_frames_bucket_total{bucket="gt_10"} 5077
telemt_pool_swap_total 61
telemt_pool_force_close_total 1788
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 159
telemt_me_draining_writers_reap_progress_total 20831
telemt_me_writer_removed_unexpected_total 797
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1775
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 19883
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1578
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 210
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 19043
telemt_me_writer_teardown_success_total{mode="normal"} 21658
telemt_me_writer_teardown_noop_total 20833
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 41929
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 42228
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 42385
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 42491
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 42491
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 42491
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 42491
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 42491
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 42491
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 42491
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 42491
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 42491
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 42491
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.703358
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 42491
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 159
telemt_me_refill_failed_total 2618
telemt_me_writer_restored_same_endpoint_total 924
telemt_me_writer_restored_fallback_total 14
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4264
telemt_user_connections_total{user="hello"} 2229568
telemt_user_connections_current{user="hello"} 2257
telemt_user_octets_from_client{user="hello"} 59411905780 (55.33 GB)
telemt_user_octets_to_client{user="hello"} 982686773250 (915.20 GB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 1058
telemt_user_unique_ips_recent_window{user="hello"} 384
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 37119.6 (10h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 265646
telemt_connections_bad_total 1980
telemt_connections_current 513
telemt_connections_me_current 513
telemt_handshake_timeouts_total 6742
telemt_upstream_connect_attempt_total 17938
telemt_upstream_connect_success_total 17894
telemt_upstream_connect_fail_total 40
telemt_upstream_connect_attempts_per_request{bucket="1"} 17934
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7516
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10282
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 96
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 40
telemt_me_reconnect_attempts_total 424
telemt_me_reconnect_success_total 245
telemt_me_reader_eof_total 245
telemt_me_idle_close_by_peer_total 245
telemt_me_route_drop_no_conn_total 75044
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 237418
telemt_me_endpoint_quarantine_total 357
telemt_me_single_endpoint_outage_enter_total 1
telemt_me_single_endpoint_outage_exit_total 1
telemt_me_single_endpoint_outage_reconnect_attempt_total 1
telemt_me_single_endpoint_outage_reconnect_success_total 1
telemt_me_single_endpoint_quarantine_bypass_total 1
telemt_me_single_endpoint_shadow_rotate_total 323
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
telemt_me_writers_active_current 43
telemt_desync_total 1241
telemt_desync_full_logged_total 340
telemt_desync_suppressed_total 901
telemt_desync_frames_bucket_total{bucket="1_2"} 431
telemt_desync_frames_bucket_total{bucket="3_10"} 477
telemt_desync_frames_bucket_total{bucket="gt_10"} 333
telemt_pool_swap_total 41
telemt_pool_force_close_total 913
telemt_me_writer_close_signal_drop_total 35
telemt_me_draining_writers_reap_progress_total 16254
telemt_me_writer_removed_unexpected_total 234
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1043
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 15456
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 911
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 15341
telemt_me_writer_teardown_success_total{mode="normal"} 16499
telemt_me_writer_teardown_noop_total 16254
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 32489
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 32725
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 32743
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 32753
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 32753
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 32753
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 32753
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 32753
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 32753
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 32753
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 32753
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 32753
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 32753
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 1.270685
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 32753
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 35
telemt_me_refill_failed_total 10
telemt_me_writer_restored_same_endpoint_total 213
telemt_me_writer_restored_fallback_total 1
telemt_me_writer_removed_unexpected_minus_restored_total 20
telemt_user_connections_total{user="hello"} 237033
telemt_user_connections_current{user="hello"} 513
telemt_user_octets_from_client{user="hello"} 4000504728 (3.73 GB)
telemt_user_octets_to_client{user="hello"} 145663273764 (135.66 GB)
telemt_user_unique_ips_current{user="hello"} 210
telemt_user_unique_ips_recent_window{user="hello"} 85
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 119317.2 (33h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7831286
telemt_connections_bad_total 778340
telemt_connections_current 3202
telemt_connections_me_current 3202
telemt_handshake_timeouts_total 223081
telemt_upstream_connect_attempt_total 46994
telemt_upstream_connect_success_total 46823
telemt_upstream_connect_fail_total 134
telemt_upstream_connect_attempts_per_request{bucket="1"} 46957
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 23154
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23628
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 40
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 134
telemt_me_reconnect_attempts_total 1698
telemt_me_reconnect_success_total 914
telemt_me_reader_eof_total 908
telemt_me_idle_close_by_peer_total 908
telemt_me_route_drop_no_conn_total 2220758
telemt_me_route_drop_channel_closed_total 52
telemt_me_route_drop_queue_full_total 23
telemt_me_route_drop_queue_full_profile_total{profile="high"} 23
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5843937
telemt_me_endpoint_quarantine_total 850
telemt_me_single_endpoint_outage_enter_total 8
telemt_me_single_endpoint_outage_exit_total 8
telemt_me_single_endpoint_outage_reconnect_attempt_total 8
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 8
telemt_me_single_endpoint_shadow_rotate_total 916
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
telemt_me_writers_active_current 44
telemt_desync_total 22812
telemt_desync_full_logged_total 7523
telemt_desync_suppressed_total 15289
telemt_desync_frames_bucket_total{bucket="1_2"} 5706
telemt_desync_frames_bucket_total{bucket="3_10"} 8290
telemt_desync_frames_bucket_total{bucket="gt_10"} 8816
telemt_pool_swap_total 132
telemt_pool_force_close_total 3517
telemt_pool_stale_pick_total 3
telemt_me_writer_close_signal_drop_total 414
telemt_me_draining_writers_reap_progress_total 42424
telemt_me_writer_removed_unexpected_total 871
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3318
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 40004
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3429
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 88
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 38907
telemt_me_writer_teardown_success_total{mode="normal"} 43322
telemt_me_writer_teardown_noop_total 42426
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 84319
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 85268
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 85455
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 85660
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 85748
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 85748
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 85748
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 85748
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 85748
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 85748
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 85748
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 85748
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 85748
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 11.018748
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 85748
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 414
telemt_me_refill_failed_total 41
telemt_me_writer_restored_same_endpoint_total 818
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 45
telemt_user_connections_total{user="hello"} 5818430
telemt_user_connections_current{user="hello"} 3202
telemt_user_octets_from_client{user="hello"} 114752539232 (106.87 GB)
telemt_user_octets_to_client{user="hello"} 2724729990952 (2.48 TB)
telemt_user_unique_ips_current{user="hello"} 1269
telemt_user_unique_ips_recent_window{user="hello"} 384
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 119313.6 (33h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6813210
telemt_connections_bad_total 664596
telemt_connections_current 3102
telemt_connections_me_current 3102
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 183903
telemt_upstream_connect_attempt_total 62834
telemt_upstream_connect_success_total 62360
telemt_upstream_connect_fail_total 414
telemt_upstream_connect_attempts_per_request{bucket="1"} 62774
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 35988
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 25238
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 518
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 616
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 414
telemt_me_reconnect_attempts_total 5809
telemt_me_reconnect_success_total 1290
telemt_me_reader_eof_total 1156
telemt_me_idle_close_by_peer_total 1156
telemt_me_seq_mismatch_total 56
telemt_me_route_drop_no_conn_total 2277439
telemt_me_route_drop_channel_closed_total 191
telemt_me_route_drop_queue_full_total 13
telemt_me_route_drop_queue_full_profile_total{profile="high"} 13
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5212230
telemt_me_endpoint_quarantine_total 941
telemt_me_single_endpoint_outage_enter_total 30
telemt_me_single_endpoint_outage_exit_total 30
telemt_me_single_endpoint_outage_reconnect_attempt_total 30
telemt_me_single_endpoint_outage_reconnect_success_total 28
telemt_me_single_endpoint_quarantine_bypass_total 30
telemt_me_single_endpoint_shadow_rotate_total 915
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 35
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
telemt_desync_total 21768
telemt_desync_full_logged_total 7243
telemt_desync_suppressed_total 14525
telemt_desync_frames_bucket_total{bucket="1_2"} 5459
telemt_desync_frames_bucket_total{bucket="3_10"} 7962
telemt_desync_frames_bucket_total{bucket="gt_10"} 8347
telemt_pool_swap_total 130
telemt_pool_force_close_total 3463
telemt_pool_stale_pick_total 358
telemt_me_writer_close_signal_drop_total 416
telemt_me_draining_writers_reap_progress_total 40990
telemt_me_writer_removed_unexpected_total 1169
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3869
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 38348
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3240
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 223
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 37527
telemt_me_writer_teardown_success_total{mode="normal"} 42217
telemt_me_writer_teardown_noop_total 40994
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 81455
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 82571
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 82973
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 83173
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 83211
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 83211
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 83211
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 83211
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 83211
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 83211
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 83211
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 83211
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 83211
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 11.712716
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 83211
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 416
telemt_me_refill_failed_total 260
telemt_me_writer_restored_same_endpoint_total 1007
telemt_me_writer_restored_fallback_total 74
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 82
telemt_me_writer_removed_unexpected_minus_restored_total 88
telemt_user_connections_total{user="hello"} 5214786
telemt_user_connections_current{user="hello"} 3102
telemt_user_octets_from_client{user="hello"} 97603176653 (90.90 GB)
telemt_user_octets_to_client{user="hello"} 2261677524832 (2.06 TB)
telemt_user_msgs_from_client{user="hello"} 75721
telemt_user_msgs_to_client{user="hello"} 209236
telemt_user_unique_ips_current{user="hello"} 1247
telemt_user_unique_ips_recent_window{user="hello"} 367
```