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

# Server Metrics 2026-03-22 19:44:30 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 81486.2 (22h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3029490
telemt_connections_bad_total 205273
telemt_connections_current 1169
telemt_connections_me_current 1169
telemt_handshake_timeouts_total 98053
telemt_upstream_connect_attempt_total 29866
telemt_upstream_connect_success_total 29865
telemt_upstream_connect_attempts_per_request{bucket="1"} 29865
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10349
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19411
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 76
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 29
telemt_me_keepalive_failed_total 4
telemt_me_keepalive_timeout_total 225
telemt_me_reconnect_attempts_total 1187
telemt_me_reconnect_success_total 501
telemt_me_reader_eof_total 506
telemt_me_idle_close_by_peer_total 506
telemt_me_route_drop_no_conn_total 2692832
telemt_me_route_drop_channel_closed_total 1073
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2564152
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_endpoint_quarantine_total 552
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 633
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 26
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
telemt_me_writers_active_current 50
telemt_desync_total 11004
telemt_desync_full_logged_total 3499
telemt_desync_suppressed_total 7505
telemt_desync_frames_bucket_total{bucket="1_2"} 2950
telemt_desync_frames_bucket_total{bucket="3_10"} 4086
telemt_desync_frames_bucket_total{bucket="gt_10"} 3968
telemt_pool_swap_total 90
telemt_pool_force_close_total 2788
telemt_pool_stale_pick_total 22
telemt_me_writer_close_signal_drop_total 582
telemt_me_draining_writers_reap_progress_total 27303
telemt_me_writer_removed_unexpected_total 490
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1990
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 25537
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 10
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2735
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 53
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 24515
telemt_me_writer_teardown_success_total{mode="normal"} 27527
telemt_me_writer_teardown_noop_total 27313
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 43266
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 45315
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 47279
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 50803
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 53247
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 54440
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 54836
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 54840
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 54840
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 54840
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 54840
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 54840
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 54840
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 302.738562
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 54840
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 582
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 443
telemt_me_writer_restored_fallback_total 1
telemt_me_writer_removed_unexpected_minus_restored_total 46
telemt_user_connections_total{user="hello"} 2556329
telemt_user_connections_current{user="hello"} 1169
telemt_user_octets_from_client{user="hello"} 37437627860 (34.87 GB)
telemt_user_octets_to_client{user="hello"} 671197405260 (625.10 GB)
telemt_user_unique_ips_current{user="hello"} 502
telemt_user_unique_ips_recent_window{user="hello"} 171
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 94853.9 (26h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3821836
telemt_connections_bad_total 340041
telemt_connections_current 1253
telemt_connections_me_current 1253
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 4
telemt_handshake_timeouts_total 97495
telemt_upstream_connect_attempt_total 57622
telemt_upstream_connect_success_total 56909
telemt_upstream_connect_fail_total 629
telemt_upstream_connect_attempts_per_request{bucket="1"} 57538
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 32066
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 24657
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 186
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 629
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 6563
telemt_me_reconnect_success_total 2467
telemt_me_reader_eof_total 2408
telemt_me_idle_close_by_peer_total 2408
telemt_me_route_drop_no_conn_total 3602042
telemt_me_route_drop_channel_closed_total 37
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3041863
telemt_me_endpoint_quarantine_total 729
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_outage_enter_total 39
telemt_me_single_endpoint_outage_exit_total 39
telemt_me_single_endpoint_outage_reconnect_attempt_total 39
telemt_me_single_endpoint_outage_reconnect_success_total 38
telemt_me_single_endpoint_quarantine_bypass_total 39
telemt_me_single_endpoint_shadow_rotate_total 730
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 37
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
telemt_me_writers_active_current 128
telemt_desync_total 12170
telemt_desync_full_logged_total 6801
telemt_desync_suppressed_total 5369
telemt_desync_frames_bucket_total{bucket="1_2"} 2789
telemt_desync_frames_bucket_total{bucket="3_10"} 4770
telemt_desync_frames_bucket_total{bucket="gt_10"} 4611
telemt_pool_swap_total 88
telemt_pool_force_close_total 2657
telemt_pool_stale_pick_total 6
telemt_me_writer_close_signal_drop_total 225
telemt_me_draining_writers_reap_progress_total 37725
telemt_me_writer_removed_unexpected_total 2358
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4508
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 35588
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2268
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 389
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 35068
telemt_me_writer_teardown_success_total{mode="normal"} 40096
telemt_me_writer_teardown_noop_total 37725
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 75972
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 77140
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 77435
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 77743
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 77806
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 77819
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 77821
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 77821
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 77821
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 77821
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 77821
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 77821
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 77821
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 13.974171
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 77821
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 225
telemt_me_refill_failed_total 164
telemt_me_writer_restored_same_endpoint_total 2154
telemt_me_writer_restored_fallback_total 25
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 179
telemt_user_connections_total{user="hello"} 3052664
telemt_user_connections_current{user="hello"} 1253
telemt_user_octets_from_client{user="hello"} 39615670787 (36.89 GB)
telemt_user_octets_to_client{user="hello"} 723900968710 (674.19 GB)
telemt_user_msgs_from_client{user="hello"} 42816
telemt_user_msgs_to_client{user="hello"} 172415
telemt_user_unique_ips_current{user="hello"} 710
telemt_user_unique_ips_recent_window{user="hello"} 184
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 169713.1 (47h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 15909151
telemt_connections_bad_total 1537953
telemt_connections_current 1903
telemt_connections_me_current 1903
telemt_relay_adaptive_promotions_total 19
telemt_relay_adaptive_hard_promotions_total 19
telemt_handshake_timeouts_total 392393
telemt_upstream_connect_attempt_total 75538
telemt_upstream_connect_success_total 75441
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 75458
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 37610
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 36138
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1686
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 2800
telemt_me_reconnect_success_total 1439
telemt_me_reader_eof_total 1381
telemt_me_idle_close_by_peer_total 1379
telemt_me_route_drop_no_conn_total 13963890
telemt_me_route_drop_channel_closed_total 143
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 12676642
telemt_me_endpoint_quarantine_total 1071
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 11
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 11
telemt_me_single_endpoint_shadow_rotate_total 1263
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 43
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
telemt_desync_total 52263
telemt_desync_full_logged_total 16447
telemt_desync_suppressed_total 35816
telemt_desync_frames_bucket_total{bucket="1_2"} 11648
telemt_desync_frames_bucket_total{bucket="3_10"} 20361
telemt_desync_frames_bucket_total{bucket="gt_10"} 20254
telemt_pool_swap_total 183
telemt_pool_force_close_total 6191
telemt_pool_stale_pick_total 19
telemt_me_writer_close_signal_drop_total 1005
telemt_me_draining_writers_reap_progress_total 55756
telemt_me_writer_removed_unexpected_total 1333
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4889
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 51477
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 43
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 8
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5723
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 468
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 49565
telemt_me_writer_teardown_success_total{mode="normal"} 56366
telemt_me_writer_teardown_noop_total 55807
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 101456
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 104917
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 106597
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 108880
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 110524
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 111568
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 112134
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 112164
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 112165
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 112169
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 112171
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 112173
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 112173
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 312.723933
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 112173
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 1005
telemt_me_refill_failed_total 75
telemt_me_writer_restored_same_endpoint_total 1241
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 22
telemt_me_writer_removed_unexpected_minus_restored_total 85
telemt_user_connections_total{user="hello"} 12677162
telemt_user_connections_current{user="hello"} 1903
telemt_user_octets_from_client{user="hello"} 185172073481 (172.45 GB)
telemt_user_octets_to_client{user="hello"} 3364562101847 (3.06 TB)
telemt_user_msgs_from_client{user="hello"} 57811
telemt_user_msgs_to_client{user="hello"} 118217
telemt_user_unique_ips_current{user="hello"} 745
telemt_user_unique_ips_recent_window{user="hello"} 255
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 169714.5 (47h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11500884
telemt_connections_bad_total 1146126
telemt_connections_current 1382
telemt_connections_me_current 1382
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 342345
telemt_upstream_connect_attempt_total 87993
telemt_upstream_connect_success_total 86763
telemt_upstream_connect_fail_total 845
telemt_upstream_connect_attempts_per_request{bucket="1"} 87608
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 46892
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 35989
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 174
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3708
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 845
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 187
telemt_me_reconnect_attempts_total 4137
telemt_me_reconnect_success_total 1718
telemt_me_reader_eof_total 1587
telemt_me_idle_close_by_peer_total 1587
telemt_me_route_drop_no_conn_total 4484248
telemt_me_route_drop_channel_closed_total 491
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8568866
telemt_me_endpoint_quarantine_total 1071
telemt_me_single_endpoint_outage_enter_total 27
telemt_me_single_endpoint_outage_exit_total 27
telemt_me_single_endpoint_outage_reconnect_attempt_total 32
telemt_me_single_endpoint_outage_reconnect_success_total 25
telemt_me_single_endpoint_quarantine_bypass_total 32
telemt_me_single_endpoint_shadow_rotate_total 1286
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 46
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
telemt_desync_total 37966
telemt_desync_full_logged_total 12791
telemt_desync_suppressed_total 25175
telemt_desync_frames_bucket_total{bucket="1_2"} 9360
telemt_desync_frames_bucket_total{bucket="3_10"} 14625
telemt_desync_frames_bucket_total{bucket="gt_10"} 13981
telemt_pool_swap_total 180
telemt_pool_force_close_total 5580
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 702
telemt_me_draining_writers_reap_progress_total 54152
telemt_me_writer_removed_unexpected_total 1625
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5008
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 50615
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 25
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5077
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 503
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 48572
telemt_me_writer_teardown_success_total{mode="normal"} 55623
telemt_me_writer_teardown_noop_total 54177
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 103160
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 106300
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 107435
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 108621
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 109376
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 109715
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 109790
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 109792
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 109798
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 109800
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 109800
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 109800
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 109800
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 103.649900
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 109800
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 702
telemt_me_refill_failed_total 131
telemt_me_writer_restored_same_endpoint_total 1469
telemt_me_writer_restored_fallback_total 16
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 216
telemt_me_writer_removed_unexpected_minus_restored_total 140
telemt_user_connections_total{user="hello"} 8507078
telemt_user_connections_current{user="hello"} 1382
telemt_user_octets_from_client{user="hello"} 213417895257 (198.76 GB)
telemt_user_octets_to_client{user="hello"} 3840693053698 (3.49 TB)
telemt_user_msgs_from_client{user="hello"} 113340
telemt_user_msgs_to_client{user="hello"} 116189
telemt_user_unique_ips_current{user="hello"} 515
telemt_user_unique_ips_recent_window{user="hello"} 164
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 169678.3 (47h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10795439
telemt_connections_bad_total 932664
telemt_connections_current 1083
telemt_connections_me_current 1083
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 343705
telemt_upstream_connect_attempt_total 73121
telemt_upstream_connect_success_total 72014
telemt_upstream_connect_fail_total 185
telemt_upstream_connect_attempts_per_request{bucket="1"} 72199
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 33821
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 34441
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1588
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2164
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 185
telemt_me_keepalive_timeout_total 1385
telemt_me_reconnect_attempts_total 4966
telemt_me_reconnect_success_total 2008
telemt_me_reader_eof_total 1754
telemt_me_idle_close_by_peer_total 1753
telemt_me_route_drop_no_conn_total 5254020
telemt_me_route_drop_channel_closed_total 374
telemt_me_route_drop_queue_full_total 9
telemt_me_route_drop_queue_full_profile_total{profile="high"} 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8162310
telemt_me_endpoint_quarantine_total 1157
telemt_me_single_endpoint_outage_enter_total 34
telemt_me_single_endpoint_outage_exit_total 34
telemt_me_single_endpoint_outage_reconnect_attempt_total 35
telemt_me_single_endpoint_outage_reconnect_success_total 29
telemt_me_single_endpoint_quarantine_bypass_total 35
telemt_me_single_endpoint_shadow_rotate_total 1246
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 61
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
telemt_desync_total 37434
telemt_desync_full_logged_total 12389
telemt_desync_suppressed_total 25045
telemt_desync_frames_bucket_total{bucket="1_2"} 9471
telemt_desync_frames_bucket_total{bucket="3_10"} 14316
telemt_desync_frames_bucket_total{bucket="gt_10"} 13647
telemt_pool_swap_total 178
telemt_pool_force_close_total 5526
telemt_pool_stale_pick_total 1619
telemt_me_writer_close_signal_drop_total 710
telemt_me_draining_writers_reap_progress_total 54282
telemt_me_writer_removed_unexpected_total 1895
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5452
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 50644
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 25
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 46
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4975
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 551
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 48756
telemt_me_writer_teardown_success_total{mode="normal"} 56096
telemt_me_writer_teardown_noop_total 54353
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 104741
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 107378
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 108319
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 109373
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 109968
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 110182
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 110310
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 110341
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 110349
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 110362
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 110395
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 110398
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 110449
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3173.783090
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 110449
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 710
telemt_me_refill_failed_total 157
telemt_me_writer_restored_same_endpoint_total 1728
telemt_me_writer_restored_fallback_total 13
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 68
telemt_me_writer_removed_unexpected_minus_restored_total 154
telemt_user_connections_total{user="hello"} 8154613
telemt_user_connections_current{user="hello"} 1083
telemt_user_octets_from_client{user="hello"} 189372952873 (176.37 GB)
telemt_user_octets_to_client{user="hello"} 3394254634829 (3.09 TB)
telemt_user_msgs_from_client{user="hello"} 46485
telemt_user_msgs_to_client{user="hello"} 113805
telemt_user_unique_ips_current{user="hello"} 463
telemt_user_unique_ips_recent_window{user="hello"} 136
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 39957.7 (11h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10775549
telemt_connections_bad_total 656932
telemt_connections_current 1965
telemt_connections_me_current 1965
telemt_relay_adaptive_promotions_total 8
telemt_relay_adaptive_hard_promotions_total 8
telemt_handshake_timeouts_total 231282
telemt_upstream_connect_attempt_total 44836
telemt_upstream_connect_success_total 42590
telemt_upstream_connect_fail_total 1545
telemt_upstream_connect_attempts_per_request{bucket="1"} 44135
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21750
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13420
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1460
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5960
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1545
telemt_me_keepalive_timeout_total 975
telemt_me_reconnect_attempts_total 6488
telemt_me_reconnect_success_total 892
telemt_me_reader_eof_total 554
telemt_me_idle_close_by_peer_total 554
telemt_me_route_drop_no_conn_total 25181676
telemt_me_route_drop_channel_closed_total 54
telemt_me_route_drop_queue_full_total 27
telemt_me_route_drop_queue_full_profile_total{profile="high"} 27
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8948189
telemt_me_endpoint_quarantine_total 248
telemt_me_single_endpoint_outage_enter_total 64
telemt_me_single_endpoint_outage_exit_total 64
telemt_me_single_endpoint_outage_reconnect_attempt_total 116
telemt_me_single_endpoint_outage_reconnect_success_total 35
telemt_me_single_endpoint_quarantine_bypass_total 116
telemt_me_single_endpoint_shadow_rotate_total 311
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
telemt_me_writers_active_current 53
telemt_desync_total 14522
telemt_desync_full_logged_total 3826
telemt_desync_suppressed_total 10696
telemt_desync_frames_bucket_total{bucket="1_2"} 2691
telemt_desync_frames_bucket_total{bucket="3_10"} 5900
telemt_desync_frames_bucket_total{bucket="gt_10"} 5931
telemt_pool_swap_total 40
telemt_pool_force_close_total 1475
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 430
telemt_me_draining_writers_reap_progress_total 11338
telemt_me_writer_removed_unexpected_total 798
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1711
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 10378
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 9
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 10
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1180
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 295
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 9863
telemt_me_writer_teardown_success_total{mode="normal"} 12089
telemt_me_writer_teardown_noop_total 11357
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 19993
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 21537
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 22141
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 22921
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 23272
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 23390
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 23446
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 23446
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 23446
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 23446
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 23446
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 23446
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 23446
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 49.840052
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 23446
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 430
telemt_me_refill_failed_total 310
telemt_me_writer_restored_same_endpoint_total 599
telemt_me_writer_restored_fallback_total 5
telemt_me_no_writer_failfast_total 96
telemt_me_async_recovery_trigger_total 3149
telemt_me_writer_removed_unexpected_minus_restored_total 194
telemt_user_connections_total{user="hello"} 8970350
telemt_user_connections_current{user="hello"} 1965
telemt_user_octets_from_client{user="hello"} 81949124667 (76.32 GB)
telemt_user_octets_to_client{user="hello"} 476348331679 (443.63 GB)
telemt_user_msgs_from_client{user="hello"} 58278
telemt_user_msgs_to_client{user="hello"} 46361
telemt_user_unique_ips_current{user="hello"} 730
telemt_user_unique_ips_recent_window{user="hello"} 274
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 169684.4 (47h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10669352
telemt_connections_bad_total 898552
telemt_connections_current 1617
telemt_connections_me_current 1617
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 234538
telemt_upstream_connect_attempt_total 102500
telemt_upstream_connect_success_total 101418
telemt_upstream_connect_fail_total 923
telemt_upstream_connect_attempts_per_request{bucket="1"} 102341
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 61790
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 38054
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 238
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1336
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 923
telemt_me_keepalive_timeout_total 23
telemt_me_reconnect_attempts_total 72369
telemt_me_reconnect_success_total 2811
telemt_me_reader_eof_total 2501
telemt_me_idle_close_by_peer_total 2499
telemt_me_route_drop_no_conn_total 5187703
telemt_me_route_drop_channel_closed_total 23
telemt_me_route_drop_queue_full_total 46
telemt_me_route_drop_queue_full_profile_total{profile="high"} 46
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8429027
telemt_me_endpoint_quarantine_total 1121
telemt_me_single_endpoint_outage_enter_total 39
telemt_me_single_endpoint_outage_exit_total 39
telemt_me_single_endpoint_outage_reconnect_attempt_total 41
telemt_me_single_endpoint_outage_reconnect_success_total 39
telemt_me_single_endpoint_quarantine_bypass_total 41
telemt_me_single_endpoint_shadow_rotate_total 1267
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
telemt_me_writers_active_current 49
telemt_desync_total 44862
telemt_desync_full_logged_total 15265
telemt_desync_suppressed_total 29597
telemt_desync_frames_bucket_total{bucket="1_2"} 9106
telemt_desync_frames_bucket_total{bucket="3_10"} 17183
telemt_desync_frames_bucket_total{bucket="gt_10"} 18573
telemt_pool_swap_total 173
telemt_pool_force_close_total 5167
telemt_pool_stale_pick_total 69
telemt_me_writer_close_signal_drop_total 634
telemt_me_draining_writers_reap_progress_total 58095
telemt_me_writer_removed_unexpected_total 2539
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6190
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 54470
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4442
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 725
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 52928
telemt_me_writer_teardown_success_total{mode="normal"} 60660
telemt_me_writer_teardown_noop_total 58096
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 116667
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 118024
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 118439
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 118712
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 118746
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 118749
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 118749
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 118752
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 118756
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 118756
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 118756
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 118756
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 118756
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 16.989664
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 118756
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 634
telemt_me_refill_failed_total 4285
telemt_me_writer_restored_same_endpoint_total 2360
telemt_me_writer_restored_fallback_total 48
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7367
telemt_me_writer_removed_unexpected_minus_restored_total 131
telemt_user_connections_total{user="hello"} 8432364
telemt_user_connections_current{user="hello"} 1617
telemt_user_octets_from_client{user="hello"} 191350869737 (178.21 GB)
telemt_user_octets_to_client{user="hello"} 3201890162104 (2.91 TB)
telemt_user_msgs_from_client{user="hello"} 160634
telemt_user_msgs_to_client{user="hello"} 619200
telemt_user_unique_ips_current{user="hello"} 629
telemt_user_unique_ips_recent_window{user="hello"} 192
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 106520.5 (29h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11247570
telemt_connections_bad_total 448251
telemt_connections_current 1234
telemt_connections_me_current 1234
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 4637491
telemt_upstream_connect_attempt_total 50598
telemt_upstream_connect_success_total 50220
telemt_upstream_connect_fail_total 369
telemt_upstream_connect_attempts_per_request{bucket="1"} 50589
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 27596
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22430
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 194
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 369
telemt_me_reconnect_attempts_total 48467
telemt_me_reconnect_success_total 1666
telemt_me_reader_eof_total 1322
telemt_me_idle_close_by_peer_total 1321
telemt_me_route_drop_no_conn_total 4028738
telemt_me_route_drop_channel_closed_total 12
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5412042
telemt_me_endpoint_quarantine_total 690
telemt_me_single_endpoint_outage_enter_total 19
telemt_me_single_endpoint_outage_exit_total 19
telemt_me_single_endpoint_outage_reconnect_attempt_total 59
telemt_me_single_endpoint_outage_reconnect_success_total 19
telemt_me_single_endpoint_quarantine_bypass_total 59
telemt_me_single_endpoint_shadow_rotate_total 805
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
telemt_me_writers_active_current 43
telemt_me_floor_cap_block_total 23
telemt_me_floor_swap_idle_failed_total 23
telemt_desync_total 30368
telemt_desync_full_logged_total 10268
telemt_desync_suppressed_total 20100
telemt_desync_frames_bucket_total{bucket="1_2"} 6067
telemt_desync_frames_bucket_total{bucket="3_10"} 11999
telemt_desync_frames_bucket_total{bucket="gt_10"} 12302
telemt_pool_swap_total 112
telemt_pool_force_close_total 3429
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 348
telemt_me_draining_writers_reap_progress_total 37056
telemt_me_writer_removed_unexpected_total 1382
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3299
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 35173
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2989
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 440
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 33627
telemt_me_writer_teardown_success_total{mode="normal"} 38472
telemt_me_writer_teardown_noop_total 37063
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 74285
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 75004
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 75308
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 75535
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 75535
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 75535
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 75535
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 75535
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 75535
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 75535
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 75535
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 75535
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 75535
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 8.466831
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 75535
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 348
telemt_me_refill_failed_total 2720
telemt_me_writer_restored_same_endpoint_total 1482
telemt_me_writer_restored_fallback_total 19
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4332
telemt_user_connections_total{user="hello"} 5404945
telemt_user_connections_current{user="hello"} 1234
telemt_user_octets_from_client{user="hello"} 116785985468 (108.77 GB)
telemt_user_octets_to_client{user="hello"} 2069484033286 (1.88 TB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 490
telemt_user_unique_ips_recent_window{user="hello"} 163
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 87491.3 (24h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1310425
telemt_connections_bad_total 29215
telemt_connections_current 1136
telemt_connections_me_current 1136
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 24733
telemt_upstream_connect_attempt_total 41581
telemt_upstream_connect_success_total 41455
telemt_upstream_connect_fail_total 99
telemt_upstream_connect_attempts_per_request{bucket="1"} 41554
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18698
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22056
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 701
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 99
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 1916
telemt_me_reconnect_success_total 803
telemt_me_reader_eof_total 779
telemt_me_idle_close_by_peer_total 779
telemt_me_route_drop_no_conn_total 457799
telemt_me_route_drop_channel_closed_total 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1162598
telemt_me_endpoint_quarantine_total 732
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 10
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 10
telemt_me_single_endpoint_shadow_rotate_total 720
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
telemt_desync_total 6897
telemt_desync_full_logged_total 2125
telemt_desync_suppressed_total 4772
telemt_desync_frames_bucket_total{bucket="1_2"} 1540
telemt_desync_frames_bucket_total{bucket="3_10"} 2726
telemt_desync_frames_bucket_total{bucket="gt_10"} 2631
telemt_pool_swap_total 94
telemt_pool_force_close_total 2408
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 141
telemt_me_draining_writers_reap_progress_total 34579
telemt_me_writer_removed_unexpected_total 752
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2729
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 32632
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2323
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 85
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 32171
telemt_me_writer_teardown_success_total{mode="normal"} 35361
telemt_me_writer_teardown_noop_total 34583
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 69170
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 69732
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 69907
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 69944
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 69944
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 69944
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 69944
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 69944
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 69944
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 69944
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 69944
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 69944
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 69944
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 4.290000
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 69944
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 141
telemt_me_refill_failed_total 61
telemt_me_writer_restored_same_endpoint_total 680
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 54
telemt_user_connections_total{user="hello"} 1158753
telemt_user_connections_current{user="hello"} 1136
telemt_user_octets_from_client{user="hello"} 22070708841 (20.55 GB)
telemt_user_octets_to_client{user="hello"} 490899874763 (457.19 GB)
telemt_user_msgs_from_client{user="hello"} 18894
telemt_user_msgs_to_client{user="hello"} 38815
telemt_user_unique_ips_current{user="hello"} 395
telemt_user_unique_ips_recent_window{user="hello"} 145
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 169689.3 (47h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 12984783
telemt_connections_bad_total 1514570
telemt_connections_current 1620
telemt_connections_me_current 1620
telemt_handshake_timeouts_total 372147
telemt_upstream_connect_attempt_total 63986
telemt_upstream_connect_success_total 63654
telemt_upstream_connect_fail_total 197
telemt_upstream_connect_attempts_per_request{bucket="1"} 63851
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 31476
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 32078
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 96
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 197
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 2518
telemt_me_reconnect_success_total 1311
telemt_me_reader_eof_total 1276
telemt_me_idle_close_by_peer_total 1276
telemt_me_route_drop_no_conn_total 4411152
telemt_me_route_drop_channel_closed_total 122
telemt_me_route_drop_queue_full_total 39
telemt_me_route_drop_queue_full_profile_total{profile="high"} 39
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9826656
telemt_me_endpoint_quarantine_total 1136
telemt_me_kdf_drift_total 2
telemt_me_single_endpoint_outage_enter_total 12
telemt_me_single_endpoint_outage_exit_total 12
telemt_me_single_endpoint_outage_reconnect_attempt_total 13
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 13
telemt_me_single_endpoint_shadow_rotate_total 1270
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
telemt_me_writers_active_current 43
telemt_desync_total 40625
telemt_desync_full_logged_total 13245
telemt_desync_suppressed_total 27380
telemt_desync_frames_bucket_total{bucket="1_2"} 9707
telemt_desync_frames_bucket_total{bucket="3_10"} 14993
telemt_desync_frames_bucket_total{bucket="gt_10"} 15925
telemt_pool_swap_total 188
telemt_pool_force_close_total 5175
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 650
telemt_me_draining_writers_reap_progress_total 57663
telemt_me_writer_removed_unexpected_total 1228
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4719
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 54210
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5001
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 174
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 52488
telemt_me_writer_teardown_success_total{mode="normal"} 58929
telemt_me_writer_teardown_noop_total 57665
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 114075
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 115723
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 116100
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 116461
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 116581
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 116594
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 116594
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 116594
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 116594
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 116594
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 116594
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 116594
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 116594
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 19.249695
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 116594
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 650
telemt_me_refill_failed_total 64
telemt_me_writer_restored_same_endpoint_total 1146
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 44
telemt_me_writer_removed_unexpected_minus_restored_total 68
telemt_user_connections_total{user="hello"} 9794371
telemt_user_connections_current{user="hello"} 1620
telemt_user_octets_from_client{user="hello"} 191695401780 (178.53 GB)
telemt_user_octets_to_client{user="hello"} 4326617049732 (3.94 TB)
telemt_user_unique_ips_current{user="hello"} 568
telemt_user_unique_ips_recent_window{user="hello"} 173
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 169686.0 (47h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11291515
telemt_connections_bad_total 1279718
telemt_connections_current 1305
telemt_connections_me_current 1305
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 296815
telemt_upstream_connect_attempt_total 90475
telemt_upstream_connect_success_total 89656
telemt_upstream_connect_fail_total 613
telemt_upstream_connect_attempts_per_request{bucket="1"} 90269
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 49034
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 37644
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 913
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2065
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 613
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 9740
telemt_me_reconnect_success_total 2339
telemt_me_reader_eof_total 2185
telemt_me_idle_close_by_peer_total 2184
telemt_me_seq_mismatch_total 78
telemt_me_route_drop_no_conn_total 5585233
telemt_me_route_drop_channel_closed_total 354
telemt_me_route_drop_queue_full_total 19
telemt_me_route_drop_queue_full_profile_total{profile="high"} 19
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8727323
telemt_me_endpoint_quarantine_total 1299
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_outage_enter_total 46
telemt_me_single_endpoint_outage_exit_total 46
telemt_me_single_endpoint_outage_reconnect_attempt_total 46
telemt_me_single_endpoint_outage_reconnect_success_total 44
telemt_me_single_endpoint_quarantine_bypass_total 46
telemt_me_single_endpoint_shadow_rotate_total 1269
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 53
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
telemt_desync_total 39823
telemt_desync_full_logged_total 12868
telemt_desync_suppressed_total 26955
telemt_desync_frames_bucket_total{bucket="1_2"} 9931
telemt_desync_frames_bucket_total{bucket="3_10"} 14817
telemt_desync_frames_bucket_total{bucket="gt_10"} 15075
telemt_pool_swap_total 178
telemt_pool_force_close_total 4970
telemt_pool_stale_pick_total 360
telemt_me_writer_close_signal_drop_total 635
telemt_me_draining_writers_reap_progress_total 57455
telemt_me_writer_removed_unexpected_total 2218
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6057
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 53690
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4499
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 471
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 52485
telemt_me_writer_teardown_success_total{mode="normal"} 59747
telemt_me_writer_teardown_noop_total 57460
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 114571
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 116302
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 116838
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 117157
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 117207
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 117207
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 117207
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 117207
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 117207
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 117207
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 117207
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 117207
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 117207
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 17.158433
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 117207
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 635
telemt_me_refill_failed_total 382
telemt_me_writer_restored_same_endpoint_total 1909
telemt_me_writer_restored_fallback_total 108
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 133
telemt_me_writer_removed_unexpected_minus_restored_total 201
telemt_user_connections_total{user="hello"} 8732914
telemt_user_connections_current{user="hello"} 1305
telemt_user_octets_from_client{user="hello"} 154457513365 (143.85 GB)
telemt_user_octets_to_client{user="hello"} 3370013053867 (3.07 TB)
telemt_user_msgs_from_client{user="hello"} 100726
telemt_user_msgs_to_client{user="hello"} 247529
telemt_user_unique_ips_current{user="hello"} 512
telemt_user_unique_ips_recent_window{user="hello"} 184
```