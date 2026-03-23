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

# Server Metrics 2026-03-23 04:34:25 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 113281.6 (31h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3859367
telemt_connections_bad_total 379266
telemt_connections_current 1281
telemt_connections_me_current 1281
telemt_handshake_timeouts_total 129100
telemt_upstream_connect_attempt_total 42202
telemt_upstream_connect_success_total 42201
telemt_upstream_connect_attempts_per_request{bucket="1"} 42201
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14641
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 27423
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 94
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 43
telemt_me_keepalive_failed_total 4
telemt_me_keepalive_timeout_total 451
telemt_me_reconnect_attempts_total 1463
telemt_me_reconnect_success_total 661
telemt_me_reader_eof_total 678
telemt_me_idle_close_by_peer_total 678
telemt_me_route_drop_no_conn_total 3039634
telemt_me_route_drop_channel_closed_total 1245
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3142850
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_endpoint_quarantine_total 803
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 885
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
telemt_me_writers_active_current 45
telemt_desync_total 13461
telemt_desync_full_logged_total 4299
telemt_desync_suppressed_total 9162
telemt_desync_frames_bucket_total{bucket="1_2"} 3545
telemt_desync_frames_bucket_total{bucket="3_10"} 4946
telemt_desync_frames_bucket_total{bucket="gt_10"} 4970
telemt_pool_swap_total 125
telemt_pool_force_close_total 3805
telemt_pool_stale_pick_total 29
telemt_me_writer_close_signal_drop_total 693
telemt_me_draining_writers_reap_progress_total 38655
telemt_me_writer_removed_unexpected_total 654
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2761
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 36178
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 11
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3743
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 62
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 34850
telemt_me_writer_teardown_success_total{mode="normal"} 38939
telemt_me_writer_teardown_noop_total 38667
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 63582
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 66068
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 68290
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 72384
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 75386
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 77088
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 77601
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 77606
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 77606
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 77606
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 77606
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 77606
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 77606
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 386.632179
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 77606
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 693
telemt_me_refill_failed_total 42
telemt_me_writer_restored_same_endpoint_total 594
telemt_me_writer_restored_fallback_total 1
telemt_me_writer_removed_unexpected_minus_restored_total 59
telemt_user_connections_total{user="hello"} 3131365
telemt_user_connections_current{user="hello"} 1281
telemt_user_octets_from_client{user="hello"} 43996016308 (40.97 GB)
telemt_user_octets_to_client{user="hello"} 854195837684 (795.53 GB)
telemt_user_unique_ips_current{user="hello"} 553
telemt_user_unique_ips_recent_window{user="hello"} 220
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 126647.5 (35h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4097848
telemt_connections_bad_total 381853
telemt_connections_current 841
telemt_connections_me_current 841
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 4
telemt_handshake_timeouts_total 103648
telemt_upstream_connect_attempt_total 79338
telemt_upstream_connect_success_total 78393
telemt_upstream_connect_fail_total 837
telemt_upstream_connect_attempts_per_request{bucket="1"} 79230
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 43482
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 34689
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 222
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 837
telemt_me_keepalive_timeout_total 7
telemt_me_reconnect_attempts_total 10697
telemt_me_reconnect_success_total 3834
telemt_me_reader_eof_total 3815
telemt_me_idle_close_by_peer_total 3815
telemt_me_route_drop_no_conn_total 3658406
telemt_me_route_drop_channel_closed_total 37
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3253307
telemt_me_endpoint_quarantine_total 1016
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_outage_enter_total 51
telemt_me_single_endpoint_outage_exit_total 51
telemt_me_single_endpoint_outage_reconnect_attempt_total 52
telemt_me_single_endpoint_outage_reconnect_success_total 50
telemt_me_single_endpoint_quarantine_bypass_total 52
telemt_me_single_endpoint_shadow_rotate_total 997
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
telemt_me_writers_active_current 92
telemt_desync_total 13362
telemt_desync_full_logged_total 7520
telemt_desync_suppressed_total 5842
telemt_desync_frames_bucket_total{bucket="1_2"} 3046
telemt_desync_frames_bucket_total{bucket="3_10"} 5247
telemt_desync_frames_bucket_total{bucket="gt_10"} 5069
telemt_pool_swap_total 119
telemt_pool_force_close_total 3292
telemt_pool_stale_pick_total 7
telemt_me_writer_close_signal_drop_total 258
telemt_me_draining_writers_reap_progress_total 52949
telemt_me_writer_removed_unexpected_total 3738
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6723
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 50004
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2834
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 458
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 49657
telemt_me_writer_teardown_success_total{mode="normal"} 56727
telemt_me_writer_teardown_noop_total 52950
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 107703
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 108955
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 109291
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 109599
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 109662
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 109675
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 109677
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 109677
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 109677
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 109677
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 109677
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 109677
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 109677
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 14.764899
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 109677
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 258
telemt_me_refill_failed_total 270
telemt_me_writer_restored_same_endpoint_total 3400
telemt_me_writer_restored_fallback_total 31
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 307
telemt_user_connections_total{user="hello"} 3267779
telemt_user_connections_current{user="hello"} 841
telemt_user_octets_from_client{user="hello"} 43965105991 (40.95 GB)
telemt_user_octets_to_client{user="hello"} 818953648769 (762.71 GB)
telemt_user_msgs_from_client{user="hello"} 52128
telemt_user_msgs_to_client{user="hello"} 188269
telemt_user_unique_ips_current{user="hello"} 488
telemt_user_unique_ips_recent_window{user="hello"} 175
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 201507.4 (55h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 16557813
telemt_connections_bad_total 1678849
telemt_connections_current 1570
telemt_connections_me_current 1570
telemt_relay_adaptive_promotions_total 19
telemt_relay_adaptive_hard_promotions_total 19
telemt_handshake_timeouts_total 403461
telemt_upstream_connect_attempt_total 90707
telemt_upstream_connect_success_total 90600
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 90617
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 44160
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 44702
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1731
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 3124
telemt_me_reconnect_success_total 1664
telemt_me_reader_eof_total 1619
telemt_me_idle_close_by_peer_total 1617
telemt_me_route_drop_no_conn_total 14087606
telemt_me_route_drop_channel_closed_total 145
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 13148774
telemt_me_endpoint_quarantine_total 1364
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 11
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 11
telemt_me_single_endpoint_shadow_rotate_total 1523
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 48
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
telemt_desync_total 54717
telemt_desync_full_logged_total 17456
telemt_desync_suppressed_total 37261
telemt_desync_frames_bucket_total{bucket="1_2"} 12213
telemt_desync_frames_bucket_total{bucket="3_10"} 21417
telemt_desync_frames_bucket_total{bucket="gt_10"} 21087
telemt_pool_swap_total 218
telemt_pool_force_close_total 7021
telemt_pool_stale_pick_total 19
telemt_me_writer_close_signal_drop_total 1088
telemt_me_draining_writers_reap_progress_total 69642
telemt_me_writer_removed_unexpected_total 1555
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5842
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 64638
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 45
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 8
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 6551
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 470
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 62621
telemt_me_writer_teardown_success_total{mode="normal"} 70480
telemt_me_writer_teardown_noop_total 69695
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 128895
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 132658
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 134451
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 136847
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 138514
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 139565
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 140136
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 140166
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 140167
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 140171
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 140173
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 140175
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 140175
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 318.327003
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 140175
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 1088
telemt_me_refill_failed_total 80
telemt_me_writer_restored_same_endpoint_total 1446
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 22
telemt_me_writer_removed_unexpected_minus_restored_total 101
telemt_user_connections_total{user="hello"} 13148734
telemt_user_connections_current{user="hello"} 1570
telemt_user_octets_from_client{user="hello"} 199150001369 (185.47 GB)
telemt_user_octets_to_client{user="hello"} 3561993704415 (3.24 TB)
telemt_user_msgs_from_client{user="hello"} 57811
telemt_user_msgs_to_client{user="hello"} 118217
telemt_user_unique_ips_current{user="hello"} 632
telemt_user_unique_ips_recent_window{user="hello"} 207
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 201508.8 (55h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 12089389
telemt_connections_bad_total 1280426
telemt_connections_current 917
telemt_connections_me_current 917
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 348774
telemt_upstream_connect_attempt_total 104994
telemt_upstream_connect_success_total 103628
telemt_upstream_connect_fail_total 891
telemt_upstream_connect_attempts_per_request{bucket="1"} 104519
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 55014
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 44614
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 194
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3806
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 891
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 226
telemt_me_reconnect_attempts_total 4597
telemt_me_reconnect_success_total 1973
telemt_me_reader_eof_total 1840
telemt_me_idle_close_by_peer_total 1840
telemt_me_route_drop_no_conn_total 4585647
telemt_me_route_drop_channel_closed_total 499
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8944306
telemt_me_endpoint_quarantine_total 1374
telemt_me_single_endpoint_outage_enter_total 29
telemt_me_single_endpoint_outage_exit_total 29
telemt_me_single_endpoint_outage_reconnect_attempt_total 35
telemt_me_single_endpoint_outage_reconnect_success_total 27
telemt_me_single_endpoint_quarantine_bypass_total 35
telemt_me_single_endpoint_shadow_rotate_total 1543
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 54
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
telemt_desync_total 39311
telemt_desync_full_logged_total 13240
telemt_desync_suppressed_total 26071
telemt_desync_frames_bucket_total{bucket="1_2"} 9742
telemt_desync_frames_bucket_total{bucket="3_10"} 15113
telemt_desync_frames_bucket_total{bucket="gt_10"} 14456
telemt_pool_swap_total 215
telemt_pool_force_close_total 6365
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 717
telemt_me_draining_writers_reap_progress_total 67724
telemt_me_writer_removed_unexpected_total 1867
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5925
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 63525
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 25
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5853
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 512
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 61359
telemt_me_writer_teardown_success_total{mode="normal"} 69450
telemt_me_writer_teardown_noop_total 67749
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 130428
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 133675
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 134824
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 136015
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 136774
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 137114
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 137189
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 137191
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 137197
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 137199
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 137199
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 137199
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 137199
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 104.598463
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 137199
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 717
telemt_me_refill_failed_total 141
telemt_me_writer_restored_same_endpoint_total 1689
telemt_me_writer_restored_fallback_total 20
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 216
telemt_me_writer_removed_unexpected_minus_restored_total 158
telemt_user_connections_total{user="hello"} 8881956
telemt_user_connections_current{user="hello"} 917
telemt_user_octets_from_client{user="hello"} 219117463608 (204.07 GB)
telemt_user_octets_to_client{user="hello"} 4007383100923 (3.64 TB)
telemt_user_msgs_from_client{user="hello"} 124042
telemt_user_msgs_to_client{user="hello"} 140191
telemt_user_unique_ips_current{user="hello"} 385
telemt_user_unique_ips_recent_window{user="hello"} 147
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 201472.7 (55h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11228366
telemt_connections_bad_total 1014252
telemt_connections_current 906
telemt_connections_me_current 906
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 350262
telemt_upstream_connect_attempt_total 89456
telemt_upstream_connect_success_total 87883
telemt_upstream_connect_fail_total 205
telemt_upstream_connect_attempts_per_request{bucket="1"} 88088
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 40286
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 43165
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2063
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2369
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 205
telemt_me_keepalive_failed_total 4
telemt_me_keepalive_timeout_total 1420
telemt_me_reconnect_attempts_total 5872
telemt_me_reconnect_success_total 2462
telemt_me_reader_eof_total 2209
telemt_me_idle_close_by_peer_total 2208
telemt_me_route_drop_no_conn_total 5362943
telemt_me_route_drop_channel_closed_total 384
telemt_me_route_drop_queue_full_total 9
telemt_me_route_drop_queue_full_profile_total{profile="high"} 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8458641
telemt_me_endpoint_quarantine_total 1422
telemt_me_single_endpoint_outage_enter_total 37
telemt_me_single_endpoint_outage_exit_total 37
telemt_me_single_endpoint_outage_reconnect_attempt_total 38
telemt_me_single_endpoint_outage_reconnect_success_total 32
telemt_me_single_endpoint_quarantine_bypass_total 38
telemt_me_single_endpoint_shadow_rotate_total 1503
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 71
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
telemt_desync_total 38525
telemt_desync_full_logged_total 12784
telemt_desync_suppressed_total 25741
telemt_desync_frames_bucket_total{bucket="1_2"} 9729
telemt_desync_frames_bucket_total{bucket="3_10"} 14756
telemt_desync_frames_bucket_total{bucket="gt_10"} 14040
telemt_pool_swap_total 211
telemt_pool_force_close_total 6252
telemt_pool_stale_pick_total 1619
telemt_me_writer_close_signal_drop_total 758
telemt_me_draining_writers_reap_progress_total 68292
telemt_me_writer_removed_unexpected_total 2355
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6690
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 63893
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 25
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 46
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5681
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 571
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 62040
telemt_me_writer_teardown_success_total{mode="normal"} 70583
telemt_me_writer_teardown_noop_total 68363
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 133096
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 135826
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 136791
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 137864
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 138465
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 138679
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 138807
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 138838
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 138846
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 138859
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 138892
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 138895
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 138946
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3174.939281
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 138946
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 758
telemt_me_refill_failed_total 181
telemt_me_writer_restored_same_endpoint_total 2144
telemt_me_writer_restored_fallback_total 17
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 68
telemt_me_writer_removed_unexpected_minus_restored_total 194
telemt_user_connections_total{user="hello"} 8450521
telemt_user_connections_current{user="hello"} 906
telemt_user_octets_from_client{user="hello"} 193582220659 (180.29 GB)
telemt_user_octets_to_client{user="hello"} 3509826111577 (3.19 TB)
telemt_user_msgs_from_client{user="hello"} 46587
telemt_user_msgs_to_client{user="hello"} 113900
telemt_user_unique_ips_current{user="hello"} 377
telemt_user_unique_ips_recent_window{user="hello"} 123
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 71752.7 (19h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11517303
telemt_connections_bad_total 675772
telemt_connections_current 1683
telemt_connections_me_current 1683
telemt_relay_adaptive_promotions_total 8
telemt_relay_adaptive_hard_promotions_total 8
telemt_handshake_timeouts_total 303651
telemt_upstream_connect_attempt_total 64713
telemt_upstream_connect_success_total 61296
telemt_upstream_connect_fail_total 2208
telemt_upstream_connect_attempts_per_request{bucket="1"} 63504
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 31560
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22185
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1517
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6034
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2208
telemt_me_keepalive_timeout_total 975
telemt_me_reconnect_attempts_total 8268
telemt_me_reconnect_success_total 1460
telemt_me_reader_eof_total 939
telemt_me_idle_close_by_peer_total 938
telemt_me_route_drop_no_conn_total 25340832
telemt_me_route_drop_channel_closed_total 59
telemt_me_route_drop_queue_full_total 27
telemt_me_route_drop_queue_full_profile_total{profile="high"} 27
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9544972
telemt_me_endpoint_quarantine_total 560
telemt_me_single_endpoint_outage_enter_total 102
telemt_me_single_endpoint_outage_exit_total 102
telemt_me_single_endpoint_outage_reconnect_attempt_total 200
telemt_me_single_endpoint_outage_reconnect_success_total 50
telemt_me_single_endpoint_quarantine_bypass_total 200
telemt_me_single_endpoint_shadow_rotate_total 576
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 40
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
telemt_desync_total 17026
telemt_desync_full_logged_total 4706
telemt_desync_suppressed_total 12320
telemt_desync_frames_bucket_total{bucket="1_2"} 3288
telemt_desync_frames_bucket_total{bucket="3_10"} 6953
telemt_desync_frames_bucket_total{bucket="gt_10"} 6785
telemt_pool_swap_total 74
telemt_pool_force_close_total 2314
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 515
telemt_me_draining_writers_reap_progress_total 23705
telemt_me_writer_removed_unexpected_total 1333
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3054
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 21935
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 9
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 10
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1992
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 322
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 21391
telemt_me_writer_teardown_success_total{mode="normal"} 24989
telemt_me_writer_teardown_noop_total 23724
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 44620
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 46522
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 47276
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 48168
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 48534
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 48657
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 48713
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 48713
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 48713
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 48713
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 48713
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 48713
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 48713
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 54.628860
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 48713
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 515
telemt_me_refill_failed_total 348
telemt_me_writer_restored_same_endpoint_total 943
telemt_me_writer_restored_fallback_total 18
telemt_me_no_writer_failfast_total 96
telemt_me_async_recovery_trigger_total 3153
telemt_me_writer_removed_unexpected_minus_restored_total 372
telemt_user_connections_total{user="hello"} 9571406
telemt_user_connections_current{user="hello"} 1683
telemt_user_octets_from_client{user="hello"} 89665147054 (83.51 GB)
telemt_user_octets_to_client{user="hello"} 684495529277 (637.49 GB)
telemt_user_msgs_from_client{user="hello"} 69581
telemt_user_msgs_to_client{user="hello"} 60103
telemt_user_unique_ips_current{user="hello"} 620
telemt_user_unique_ips_recent_window{user="hello"} 242
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 201479.2 (55h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11195049
telemt_connections_bad_total 987730
telemt_connections_current 1263
telemt_connections_me_current 1263
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 246639
telemt_upstream_connect_attempt_total 118343
telemt_upstream_connect_success_total 117113
telemt_upstream_connect_fail_total 1053
telemt_upstream_connect_attempts_per_request{bucket="1"} 118166
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 68827
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 46673
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 238
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1375
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1053
telemt_me_keepalive_timeout_total 23
telemt_me_reconnect_attempts_total 73461
telemt_me_reconnect_success_total 3231
telemt_me_reader_eof_total 2926
telemt_me_idle_close_by_peer_total 2923
telemt_me_route_drop_no_conn_total 5298247
telemt_me_route_drop_channel_closed_total 23
telemt_me_route_drop_queue_full_total 46
telemt_me_route_drop_queue_full_profile_total{profile="high"} 46
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8814087
telemt_me_endpoint_quarantine_total 1370
telemt_me_single_endpoint_outage_enter_total 44
telemt_me_single_endpoint_outage_exit_total 44
telemt_me_single_endpoint_outage_reconnect_attempt_total 46
telemt_me_single_endpoint_outage_reconnect_success_total 44
telemt_me_single_endpoint_quarantine_bypass_total 46
telemt_me_single_endpoint_shadow_rotate_total 1532
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 55
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
telemt_desync_total 46997
telemt_desync_full_logged_total 16151
telemt_desync_suppressed_total 30846
telemt_desync_frames_bucket_total{bucket="1_2"} 9537
telemt_desync_frames_bucket_total{bucket="3_10"} 18027
telemt_desync_frames_bucket_total{bucket="gt_10"} 19433
telemt_pool_swap_total 207
telemt_pool_force_close_total 5982
telemt_pool_stale_pick_total 69
telemt_me_writer_close_signal_drop_total 677
telemt_me_draining_writers_reap_progress_total 72330
telemt_me_writer_removed_unexpected_total 2944
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 7226
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 68094
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5233
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 749
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 66348
telemt_me_writer_teardown_success_total{mode="normal"} 75320
telemt_me_writer_teardown_noop_total 72331
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 145495
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 146915
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 147334
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 147607
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 147641
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 147644
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 147644
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 147647
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 147651
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 147651
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 147651
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 147651
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 147651
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 17.344764
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 147651
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 677
telemt_me_refill_failed_total 4320
telemt_me_writer_restored_same_endpoint_total 2721
telemt_me_writer_restored_fallback_total 54
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7369
telemt_me_writer_removed_unexpected_minus_restored_total 169
telemt_user_connections_total{user="hello"} 8816868
telemt_user_connections_current{user="hello"} 1263
telemt_user_octets_from_client{user="hello"} 198056650273 (184.45 GB)
telemt_user_octets_to_client{user="hello"} 3372563355812 (3.07 TB)
telemt_user_msgs_from_client{user="hello"} 160634
telemt_user_msgs_to_client{user="hello"} 619200
telemt_user_unique_ips_current{user="hello"} 499
telemt_user_unique_ips_recent_window{user="hello"} 185
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 138315.6 (38h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11947516
telemt_connections_bad_total 492313
telemt_connections_current 906
telemt_connections_me_current 906
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 4824425
telemt_upstream_connect_attempt_total 67266
telemt_upstream_connect_success_total 66787
telemt_upstream_connect_fail_total 466
telemt_upstream_connect_attempts_per_request{bucket="1"} 67253
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 35223
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 31325
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 239
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 466
telemt_me_reconnect_attempts_total 49242
telemt_me_reconnect_success_total 1941
telemt_me_reader_eof_total 1623
telemt_me_idle_close_by_peer_total 1622
telemt_me_route_drop_no_conn_total 4123482
telemt_me_route_drop_channel_closed_total 13
telemt_me_route_drop_queue_full_total 10
telemt_me_route_drop_queue_full_profile_total{profile="high"} 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5740867
telemt_me_endpoint_quarantine_total 955
telemt_me_single_endpoint_outage_enter_total 19
telemt_me_single_endpoint_outage_exit_total 19
telemt_me_single_endpoint_outage_reconnect_attempt_total 59
telemt_me_single_endpoint_outage_reconnect_success_total 19
telemt_me_single_endpoint_quarantine_bypass_total 59
telemt_me_single_endpoint_shadow_rotate_total 1068
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
telemt_me_writers_active_current 44
telemt_me_floor_cap_block_total 23
telemt_me_floor_swap_idle_failed_total 23
telemt_desync_total 32314
telemt_desync_full_logged_total 11038
telemt_desync_suppressed_total 21276
telemt_desync_frames_bucket_total{bucket="1_2"} 6479
telemt_desync_frames_bucket_total{bucket="3_10"} 12735
telemt_desync_frames_bucket_total{bucket="gt_10"} 13100
telemt_pool_swap_total 147
telemt_pool_force_close_total 4175
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 389
telemt_me_draining_writers_reap_progress_total 52215
telemt_me_writer_removed_unexpected_total 1663
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4143
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 49789
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3731
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 444
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 48040
telemt_me_writer_teardown_success_total{mode="normal"} 53932
telemt_me_writer_teardown_noop_total 52222
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 104851
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 105617
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 105927
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 106154
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 106154
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 106154
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 106154
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 106154
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 106154
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 106154
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 106154
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 106154
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 106154
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 8.774619
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 106154
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 389
telemt_me_refill_failed_total 2748
telemt_me_writer_restored_same_endpoint_total 1717
telemt_me_writer_restored_fallback_total 30
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4332
telemt_user_connections_total{user="hello"} 5732837
telemt_user_connections_current{user="hello"} 906
telemt_user_octets_from_client{user="hello"} 121218989988 (112.89 GB)
telemt_user_octets_to_client{user="hello"} 2235202676622 (2.03 TB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 386
telemt_user_unique_ips_recent_window{user="hello"} 155
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 119286.7 (33h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1636815
telemt_connections_bad_total 37197
telemt_connections_current 680
telemt_connections_me_current 680
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 34050
telemt_upstream_connect_attempt_total 56364
telemt_upstream_connect_success_total 56188
telemt_upstream_connect_fail_total 148
telemt_upstream_connect_attempts_per_request{bucket="1"} 56336
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26518
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 28846
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 824
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 148
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 2447
telemt_me_reconnect_success_total 991
telemt_me_reader_eof_total 985
telemt_me_idle_close_by_peer_total 985
telemt_me_route_drop_no_conn_total 545801
telemt_me_route_drop_channel_closed_total 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1454497
telemt_me_endpoint_quarantine_total 1013
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 10
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 10
telemt_me_single_endpoint_shadow_rotate_total 987
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 16
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
telemt_desync_total 10124
telemt_desync_full_logged_total 2855
telemt_desync_suppressed_total 7269
telemt_desync_frames_bucket_total{bucket="1_2"} 3212
telemt_desync_frames_bucket_total{bucket="3_10"} 3811
telemt_desync_frames_bucket_total{bucket="gt_10"} 3101
telemt_pool_swap_total 129
telemt_pool_force_close_total 3247
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 176
telemt_me_draining_writers_reap_progress_total 48043
telemt_me_writer_removed_unexpected_total 949
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3623
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 45412
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3159
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 88
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 44796
telemt_me_writer_teardown_success_total{mode="normal"} 49035
telemt_me_writer_teardown_noop_total 48047
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 96064
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 96815
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 97045
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 97082
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 97082
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 97082
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 97082
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 97082
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 97082
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 97082
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 97082
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 97082
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 97082
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 5.562729
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 97082
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 176
telemt_me_refill_failed_total 81
telemt_me_writer_restored_same_endpoint_total 848
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 79
telemt_user_connections_total{user="hello"} 1450148
telemt_user_connections_current{user="hello"} 680
telemt_user_octets_from_client{user="hello"} 27030529081 (25.17 GB)
telemt_user_octets_to_client{user="hello"} 603480788151 (562.04 GB)
telemt_user_msgs_from_client{user="hello"} 18894
telemt_user_msgs_to_client{user="hello"} 38815
telemt_user_unique_ips_current{user="hello"} 288
telemt_user_unique_ips_recent_window{user="hello"} 130
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 201483.9 (55h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 13486650
telemt_connections_bad_total 1629004
telemt_connections_current 1330
telemt_connections_me_current 1330
telemt_handshake_timeouts_total 394573
telemt_upstream_connect_attempt_total 81069
telemt_upstream_connect_success_total 80709
telemt_upstream_connect_fail_total 223
telemt_upstream_connect_attempts_per_request{bucket="1"} 80932
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 39921
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 40683
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 101
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 223
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 3170
telemt_me_reconnect_success_total 1603
telemt_me_reader_eof_total 1593
telemt_me_idle_close_by_peer_total 1593
telemt_me_route_drop_no_conn_total 4510713
telemt_me_route_drop_channel_closed_total 123
telemt_me_route_drop_queue_full_total 42
telemt_me_route_drop_queue_full_profile_total{profile="high"} 42
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 10166077
telemt_me_endpoint_quarantine_total 1482
telemt_me_kdf_drift_total 2
telemt_me_single_endpoint_outage_enter_total 13
telemt_me_single_endpoint_outage_exit_total 13
telemt_me_single_endpoint_outage_reconnect_attempt_total 14
telemt_me_single_endpoint_outage_reconnect_success_total 12
telemt_me_single_endpoint_quarantine_bypass_total 14
telemt_me_single_endpoint_shadow_rotate_total 1530
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 44
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
telemt_desync_total 42637
telemt_desync_full_logged_total 13925
telemt_desync_suppressed_total 28712
telemt_desync_frames_bucket_total{bucket="1_2"} 10381
telemt_desync_frames_bucket_total{bucket="3_10"} 15660
telemt_desync_frames_bucket_total{bucket="gt_10"} 16596
telemt_pool_swap_total 223
telemt_pool_force_close_total 5833
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 695
telemt_me_draining_writers_reap_progress_total 73388
telemt_me_writer_removed_unexpected_total 1524
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5664
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 69307
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5659
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 174
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 67555
telemt_me_writer_teardown_success_total{mode="normal"} 74971
telemt_me_writer_teardown_noop_total 73390
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 145732
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 147469
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 147852
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 148228
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 148348
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 148361
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 148361
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 148361
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 148361
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 148361
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 148361
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 148361
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 148361
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 19.927843
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 148361
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 695
telemt_me_refill_failed_total 84
telemt_me_writer_restored_same_endpoint_total 1412
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 44
telemt_me_writer_removed_unexpected_minus_restored_total 95
telemt_user_connections_total{user="hello"} 10132575
telemt_user_connections_current{user="hello"} 1330
telemt_user_octets_from_client{user="hello"} 196123191972 (182.65 GB)
telemt_user_octets_to_client{user="hello"} 4513773861332 (4.11 TB)
telemt_user_unique_ips_current{user="hello"} 483
telemt_user_unique_ips_recent_window{user="hello"} 159
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 201480.3 (55h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11805177
telemt_connections_bad_total 1383197
telemt_connections_current 966
telemt_connections_me_current 966
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 317489
telemt_upstream_connect_attempt_total 108897
telemt_upstream_connect_success_total 107961
telemt_upstream_connect_fail_total 728
telemt_upstream_connect_attempts_per_request{bucket="1"} 108689
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 58632
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 46345
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 913
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2071
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 728
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 10982
telemt_me_reconnect_success_total 2731
telemt_me_reader_eof_total 2532
telemt_me_idle_close_by_peer_total 2531
telemt_me_seq_mismatch_total 105
telemt_me_route_drop_no_conn_total 5678106
telemt_me_route_drop_channel_closed_total 354
telemt_me_route_drop_queue_full_total 19
telemt_me_route_drop_queue_full_profile_total{profile="high"} 19
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9084042
telemt_me_endpoint_quarantine_total 1657
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_outage_enter_total 56
telemt_me_single_endpoint_outage_exit_total 56
telemt_me_single_endpoint_outage_reconnect_attempt_total 56
telemt_me_single_endpoint_outage_reconnect_success_total 54
telemt_me_single_endpoint_quarantine_bypass_total 56
telemt_me_single_endpoint_shadow_rotate_total 1535
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 58
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
telemt_desync_total 42318
telemt_desync_full_logged_total 13622
telemt_desync_suppressed_total 28696
telemt_desync_frames_bucket_total{bucket="1_2"} 10999
telemt_desync_frames_bucket_total{bucket="3_10"} 15542
telemt_desync_frames_bucket_total{bucket="gt_10"} 15777
telemt_pool_swap_total 213
telemt_pool_force_close_total 5595
telemt_pool_stale_pick_total 390
telemt_me_writer_close_signal_drop_total 680
telemt_me_draining_writers_reap_progress_total 73708
telemt_me_writer_removed_unexpected_total 2567
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 7049
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 69325
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5124
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 471
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 68113
telemt_me_writer_teardown_success_total{mode="normal"} 76374
telemt_me_writer_teardown_noop_total 73713
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 147381
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 149179
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 149718
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 150037
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 150087
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 150087
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 150087
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 150087
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 150087
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 150087
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 150087
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 150087
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 150087
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 17.621376
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 150087
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 680
telemt_me_refill_failed_total 428
telemt_me_writer_restored_same_endpoint_total 2179
telemt_me_writer_restored_fallback_total 141
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 135
telemt_me_writer_removed_unexpected_minus_restored_total 247
telemt_user_connections_total{user="hello"} 9088547
telemt_user_connections_current{user="hello"} 966
telemt_user_octets_from_client{user="hello"} 158669932516 (147.77 GB)
telemt_user_octets_to_client{user="hello"} 3555907437226 (3.23 TB)
telemt_user_msgs_from_client{user="hello"} 103592
telemt_user_msgs_to_client{user="hello"} 254638
telemt_user_unique_ips_current{user="hello"} 400
telemt_user_unique_ips_recent_window{user="hello"} 144
```