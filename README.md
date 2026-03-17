# Информация

Покупаю сервера у разных хостингов для запуска прокси для Telegram

Для прокси используется https://github.com/telemt/telemt  
[Конфиг](https://github.com/Dimasssss/free_telemt_servers/blob/main/config.toml) используемый на всех серверах.

### [Итог по хостингам](Reviews.md)

---

## NKtelecom
- Локация: Netherlands - Amsterdam
- Тариф: AMS-CLOUD-40
- Краткое описание тарифа: 2 vCore, 2 Gb ram, 1 Gbit/s
- Цена в месяц: 4.99$
- Оплачен до: 26 марта
- Ссылка:
```bash
tg://proxy?server=s1.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## psb.hosting
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

## rdp-onedash.ru
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

## 4vps.su
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

# Server Metrics 2026-03-17 08:11:26 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 48363.9 (13h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 336326
telemt_connections_bad_total 3567
telemt_handshake_timeouts_total 9930
telemt_upstream_connect_attempt_total 9988
telemt_upstream_connect_success_total 9934
telemt_upstream_connect_fail_total 54
telemt_upstream_connect_attempts_per_request{bucket="1"} 9988
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4558
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5370
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 54
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 7564
telemt_me_reconnect_success_total 7534
telemt_me_reader_eof_total 8004
telemt_me_idle_close_by_peer_total 8004
telemt_me_route_drop_no_conn_total 103286
telemt_me_route_drop_channel_closed_total 24
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 304085
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2373
telemt_desync_full_logged_total 670
telemt_desync_suppressed_total 1703
telemt_desync_frames_bucket_total{bucket="1_2"} 562
telemt_desync_frames_bucket_total{bucket="3_10"} 1141
telemt_desync_frames_bucket_total{bucket="gt_10"} 670
telemt_pool_swap_total 48
telemt_me_writer_removed_unexpected_total 7613
telemt_me_writer_restored_same_endpoint_total 7513
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 79
telemt_user_connections_total{user="hello"} 303829
telemt_user_connections_current{user="hello"} 904
telemt_user_octets_from_client{user="hello"} 4231635748 (3.94 GB)
telemt_user_octets_to_client{user="hello"} 128229449812 (119.42 GB)
telemt_user_unique_ips_current{user="hello"} 302
telemt_user_unique_ips_recent_window{user="hello"} 147
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 48615.8 (13h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 188103
telemt_connections_bad_total 2351
telemt_handshake_timeouts_total 11963
telemt_upstream_connect_attempt_total 13196
telemt_upstream_connect_success_total 13026
telemt_upstream_connect_fail_total 170
telemt_upstream_connect_attempts_per_request{bucket="1"} 13196
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5560
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7364
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 102
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 170
telemt_me_reconnect_attempts_total 12910
telemt_me_reconnect_success_total 10637
telemt_me_reader_eof_total 11261
telemt_me_idle_close_by_peer_total 11261
telemt_me_route_drop_no_conn_total 68301
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 164226
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 424
telemt_desync_full_logged_total 154
telemt_desync_suppressed_total 270
telemt_desync_frames_bucket_total{bucket="1_2"} 127
telemt_desync_frames_bucket_total{bucket="3_10"} 182
telemt_desync_frames_bucket_total{bucket="gt_10"} 115
telemt_pool_swap_total 36
telemt_me_writer_removed_unexpected_total 10810
telemt_me_refill_failed_total 70
telemt_me_writer_restored_same_endpoint_total 10621
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 1056
telemt_me_writer_removed_unexpected_minus_restored_total 173
telemt_user_connections_total{user="hello"} 164244
telemt_user_connections_current{user="hello"} 519
telemt_user_octets_from_client{user="hello"} 2001011816 (1.86 GB)
telemt_user_octets_to_client{user="hello"} 65077278804 (60.61 GB)
telemt_user_unique_ips_current{user="hello"} 153
telemt_user_unique_ips_recent_window{user="hello"} 71
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 48391.6 (13h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 116193
telemt_connections_bad_total 7265
telemt_handshake_timeouts_total 5554
telemt_upstream_connect_attempt_total 12648
telemt_upstream_connect_success_total 12584
telemt_upstream_connect_fail_total 64
telemt_upstream_connect_attempts_per_request{bucket="1"} 12648
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5564
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6958
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 61
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 64
telemt_me_keepalive_timeout_total 17
telemt_me_reconnect_attempts_total 10219
telemt_me_reconnect_success_total 10157
telemt_me_reader_eof_total 10866
telemt_me_idle_close_by_peer_total 10866
telemt_me_route_drop_no_conn_total 36199
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 94520
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 202
telemt_desync_full_logged_total 52
telemt_desync_suppressed_total 150
telemt_desync_frames_bucket_total{bucket="1_2"} 66
telemt_desync_frames_bucket_total{bucket="3_10"} 75
telemt_desync_frames_bucket_total{bucket="gt_10"} 61
telemt_pool_swap_total 46
telemt_me_writer_removed_unexpected_total 10287
telemt_me_writer_restored_same_endpoint_total 10146
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 130
telemt_user_connections_total{user="hello"} 94465
telemt_user_connections_current{user="hello"} 269
telemt_user_octets_from_client{user="hello"} 6529255132 (6.08 GB)
telemt_user_octets_to_client{user="hello"} 30231387240 (28.16 GB)
telemt_user_unique_ips_current{user="hello"} 94
telemt_user_unique_ips_recent_window{user="hello"} 37
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 48450.7 (13h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 239113
telemt_connections_bad_total 6151
telemt_handshake_timeouts_total 10187
telemt_upstream_connect_attempt_total 11115
telemt_upstream_connect_success_total 11020
telemt_upstream_connect_fail_total 95
telemt_upstream_connect_attempts_per_request{bucket="1"} 11115
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5206
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5745
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 61
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 95
telemt_me_keepalive_timeout_total 5
telemt_me_reconnect_attempts_total 9622
telemt_me_reconnect_success_total 8557
telemt_me_reader_eof_total 9112
telemt_me_idle_close_by_peer_total 9112
telemt_me_route_drop_no_conn_total 66764
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 191838
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 401
telemt_desync_full_logged_total 143
telemt_desync_suppressed_total 258
telemt_desync_frames_bucket_total{bucket="1_2"} 102
telemt_desync_frames_bucket_total{bucket="3_10"} 166
telemt_desync_frames_bucket_total{bucket="gt_10"} 133
telemt_pool_swap_total 42
telemt_me_writer_removed_unexpected_total 8714
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 8549
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 157
telemt_user_connections_total{user="hello"} 191843
telemt_user_connections_current{user="hello"} 642
telemt_user_octets_from_client{user="hello"} 2047204398 (1.91 GB)
telemt_user_octets_to_client{user="hello"} 86385511849 (80.45 GB)
telemt_user_msgs_from_client{user="hello"} 65
telemt_user_msgs_to_client{user="hello"} 189
telemt_user_unique_ips_current{user="hello"} 188
telemt_user_unique_ips_recent_window{user="hello"} 87
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 48422.5 (13h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 141839
telemt_connections_bad_total 39053
telemt_handshake_timeouts_total 2592
telemt_upstream_connect_attempt_total 14906
telemt_upstream_connect_success_total 14710
telemt_upstream_connect_fail_total 196
telemt_upstream_connect_attempts_per_request{bucket="1"} 14906
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6566
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7952
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 192
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 196
telemt_me_reconnect_attempts_total 16704
telemt_me_reconnect_success_total 12192
telemt_me_reader_eof_total 12878
telemt_me_idle_close_by_peer_total 12878
telemt_me_route_drop_no_conn_total 37441
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 95714
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 224
telemt_desync_full_logged_total 57
telemt_desync_suppressed_total 167
telemt_desync_frames_bucket_total{bucket="1_2"} 100
telemt_desync_frames_bucket_total{bucket="3_10"} 79
telemt_desync_frames_bucket_total{bucket="gt_10"} 45
telemt_pool_swap_total 32
telemt_me_writer_removed_unexpected_total 12481
telemt_me_refill_failed_total 139
telemt_me_writer_restored_same_endpoint_total 12184
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 143
telemt_me_writer_removed_unexpected_minus_restored_total 289
telemt_user_connections_total{user="hello"} 95752
telemt_user_connections_current{user="hello"} 211
telemt_user_octets_from_client{user="hello"} 983081735 (937.54 MB)
telemt_user_octets_to_client{user="hello"} 45175933058 (42.07 GB)
telemt_user_msgs_from_client{user="hello"} 265
telemt_user_msgs_to_client{user="hello"} 707
telemt_user_unique_ips_current{user="hello"} 75
telemt_user_unique_ips_recent_window{user="hello"} 36
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 48583.9 (13h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 339093
telemt_connections_bad_total 43397
telemt_handshake_timeouts_total 3183
telemt_upstream_connect_attempt_total 10016
telemt_upstream_connect_success_total 9963
telemt_upstream_connect_fail_total 53
telemt_upstream_connect_attempts_per_request{bucket="1"} 10016
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4852
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5096
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 14
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 53
telemt_me_keepalive_timeout_total 16
telemt_me_reconnect_attempts_total 11436
telemt_me_reconnect_success_total 7561
telemt_me_reader_eof_total 8169
telemt_me_idle_close_by_peer_total 8169
telemt_me_route_drop_no_conn_total 248420
telemt_me_route_drop_channel_closed_total 5
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 357413
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 417
telemt_desync_full_logged_total 171
telemt_desync_suppressed_total 246
telemt_desync_frames_bucket_total{bucket="1_2"} 134
telemt_desync_frames_bucket_total{bucket="3_10"} 155
telemt_desync_frames_bucket_total{bucket="gt_10"} 128
telemt_pool_swap_total 46
telemt_me_writer_removed_unexpected_total 7790
telemt_me_refill_failed_total 120
telemt_me_writer_restored_same_endpoint_total 7547
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 229
telemt_user_connections_total{user="hello"} 279335
telemt_user_connections_current{user="hello"} 802
telemt_user_octets_from_client{user="hello"} 3973373908 (3.70 GB)
telemt_user_octets_to_client{user="hello"} 168437046864 (156.87 GB)
telemt_user_unique_ips_current{user="hello"} 269
telemt_user_unique_ips_recent_window{user="hello"} 98
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 36590.0 (10h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2441
telemt_connections_bad_total 195
telemt_handshake_timeouts_total 4
telemt_upstream_connect_attempt_total 18071
telemt_upstream_connect_success_total 18070
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 18071
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10205
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7857
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 16266
telemt_me_reconnect_success_total 16174
telemt_me_reader_eof_total 17700
telemt_me_idle_close_by_peer_total 17700
telemt_me_route_drop_no_conn_total 448
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2215
telemt_me_writer_pick_total{mode="p2c",result="full"} 3
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 37
telemt_me_writer_removed_unexpected_total 16316
telemt_me_writer_restored_same_endpoint_total 16174
telemt_me_async_recovery_trigger_total 18
telemt_me_writer_removed_unexpected_minus_restored_total 142
telemt_user_connections_total{user="hello"} 2215
telemt_user_connections_current{user="hello"} 39
telemt_user_octets_from_client{user="hello"} 232467504 (221.70 MB)
telemt_user_octets_to_client{user="hello"} 17278255864 (16.09 GB)
telemt_user_unique_ips_current{user="hello"} 12
telemt_user_unique_ips_recent_window{user="hello"} 5
```