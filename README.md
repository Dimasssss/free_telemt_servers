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

# Server Metrics 2026-03-12 11:21:26 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 13683.5 (3h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 72311
telemt_connections_bad_total 495
telemt_handshake_timeouts_total 2692
telemt_upstream_connect_attempt_total 3354
telemt_upstream_connect_success_total 3339
telemt_upstream_connect_fail_total 15
telemt_upstream_connect_attempts_per_request{bucket="1"} 3354
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1507
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1827
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 15
telemt_me_keepalive_timeout_total 142
telemt_me_reconnect_attempts_total 2617
telemt_me_reconnect_success_total 2601
telemt_me_reader_eof_total 2702
telemt_me_idle_close_by_peer_total 2701
telemt_me_route_drop_no_conn_total 19937
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 65401
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 269
telemt_desync_full_logged_total 103
telemt_desync_suppressed_total 166
telemt_desync_frames_bucket_total{bucket="1_2"} 60
telemt_desync_frames_bucket_total{bucket="3_10"} 97
telemt_desync_frames_bucket_total{bucket="gt_10"} 112
telemt_pool_swap_total 11
telemt_me_writer_removed_unexpected_total 2615
telemt_me_writer_restored_same_endpoint_total 2585
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 14
telemt_user_connections_total{user="hello"} 65418
telemt_user_connections_current{user="hello"} 390
telemt_user_octets_from_client{user="hello"} 948470780 (904.53 MB)
telemt_user_octets_to_client{user="hello"} 23014298232 (21.43 GB)
telemt_user_unique_ips_current{user="hello"} 100
telemt_user_unique_ips_recent_window{user="hello"} 43
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 13576.6 (3h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 29085
telemt_connections_bad_total 265
telemt_handshake_timeouts_total 259
telemt_upstream_connect_attempt_total 4688
telemt_upstream_connect_success_total 4590
telemt_upstream_connect_fail_total 98
telemt_upstream_connect_attempts_per_request{bucket="1"} 4688
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1776
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2808
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 98
telemt_me_keepalive_timeout_total 104
telemt_me_reconnect_attempts_total 11508
telemt_me_reconnect_success_total 3878
telemt_me_reader_eof_total 4159
telemt_me_idle_close_by_peer_total 4159
telemt_me_route_drop_no_conn_total 11837
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 27583
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 31
telemt_desync_full_logged_total 9
telemt_desync_suppressed_total 22
telemt_desync_frames_bucket_total{bucket="1_2"} 2
telemt_desync_frames_bucket_total{bucket="3_10"} 12
telemt_desync_frames_bucket_total{bucket="gt_10"} 17
telemt_pool_swap_total 2
telemt_me_writer_removed_unexpected_total 4130
telemt_me_refill_failed_total 238
telemt_me_writer_restored_same_endpoint_total 3863
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 252
telemt_user_connections_total{user="hello"} 27581
telemt_user_connections_current{user="hello"} 170
telemt_user_octets_from_client{user="hello"} 286441644 (273.17 MB)
telemt_user_octets_to_client{user="hello"} 6335767568 (5.90 GB)
telemt_user_unique_ips_current{user="hello"} 58
telemt_user_unique_ips_recent_window{user="hello"} 24
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 13540.2 (3h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 40414
telemt_connections_bad_total 104
telemt_handshake_timeouts_total 355
telemt_upstream_connect_attempt_total 3687
telemt_upstream_connect_success_total 3687
telemt_upstream_connect_attempts_per_request{bucket="1"} 3687
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1808
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1872
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_me_keepalive_timeout_total 63
telemt_me_reconnect_attempts_total 2996
telemt_me_reconnect_success_total 2978
telemt_me_reader_eof_total 3120
telemt_me_idle_close_by_peer_total 3120
telemt_me_route_drop_no_conn_total 13494
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 37880
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 10
telemt_desync_full_logged_total 6
telemt_desync_suppressed_total 4
telemt_desync_frames_bucket_total{bucket="3_10"} 6
telemt_desync_frames_bucket_total{bucket="gt_10"} 4
telemt_pool_swap_total 10
telemt_me_writer_removed_unexpected_total 2984
telemt_me_writer_restored_same_endpoint_total 2958
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 6
telemt_user_connections_total{user="hello"} 37865
telemt_user_connections_current{user="hello"} 175
telemt_user_octets_from_client{user="hello"} 499070612 (475.95 MB)
telemt_user_octets_to_client{user="hello"} 30307603764 (28.23 GB)
telemt_user_unique_ips_current{user="hello"} 67
telemt_user_unique_ips_recent_window{user="hello"} 28
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 13515.8 (3h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 49633
telemt_connections_bad_total 1038
telemt_handshake_timeouts_total 258
telemt_upstream_connect_attempt_total 3988
telemt_upstream_connect_success_total 3900
telemt_upstream_connect_fail_total 88
telemt_upstream_connect_attempts_per_request{bucket="1"} 3988
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1643
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2247
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 88
telemt_me_keepalive_timeout_total 167
telemt_me_reconnect_attempts_total 4397
telemt_me_reconnect_success_total 3204
telemt_me_reader_eof_total 3355
telemt_me_idle_close_by_peer_total 3355
telemt_me_route_drop_no_conn_total 15631
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 45057
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 168
telemt_desync_full_logged_total 58
telemt_desync_suppressed_total 110
telemt_desync_frames_bucket_total{bucket="1_2"} 65
telemt_desync_frames_bucket_total{bucket="3_10"} 57
telemt_desync_frames_bucket_total{bucket="gt_10"} 46
telemt_pool_swap_total 6
telemt_me_writer_removed_unexpected_total 3286
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 3196
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 121
telemt_me_writer_removed_unexpected_minus_restored_total 82
telemt_user_connections_total{user="hello"} 45056
telemt_user_connections_current{user="hello"} 204
telemt_user_octets_from_client{user="hello"} 958316864 (913.92 MB)
telemt_user_octets_to_client{user="hello"} 26590088580 (24.76 GB)
telemt_user_unique_ips_current{user="hello"} 66
telemt_user_unique_ips_recent_window{user="hello"} 32
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 13485.4 (3h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 25898
telemt_connections_bad_total 2580
telemt_handshake_timeouts_total 394
telemt_upstream_connect_attempt_total 4138
telemt_upstream_connect_success_total 3977
telemt_upstream_connect_fail_total 161
telemt_upstream_connect_attempts_per_request{bucket="1"} 4138
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1410
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2555
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 12
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 161
telemt_me_keepalive_timeout_total 90
telemt_me_reconnect_attempts_total 14649
telemt_me_reconnect_success_total 3286
telemt_me_reader_eof_total 3638
telemt_me_idle_close_by_peer_total 3638
telemt_me_seq_mismatch_total 6
telemt_me_route_drop_no_conn_total 7694
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 22197
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 336
telemt_desync_full_logged_total 101
telemt_desync_suppressed_total 235
telemt_desync_frames_bucket_total{bucket="1_2"} 8
telemt_desync_frames_bucket_total{bucket="3_10"} 281
telemt_desync_frames_bucket_total{bucket="gt_10"} 47
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 3661
telemt_me_refill_failed_total 356
telemt_me_writer_restored_same_endpoint_total 3270
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 18
telemt_me_writer_removed_unexpected_minus_restored_total 375
telemt_user_connections_total{user="hello"} 22194
telemt_user_connections_current{user="hello"} 91
telemt_user_octets_from_client{user="hello"} 140139476 (133.65 MB)
telemt_user_octets_to_client{user="hello"} 5747937028 (5.35 GB)
telemt_user_unique_ips_current{user="hello"} 36
telemt_user_unique_ips_recent_window{user="hello"} 12
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 13472.2 (3h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 71102
telemt_connections_bad_total 684
telemt_handshake_timeouts_total 736
telemt_upstream_connect_attempt_total 2627
telemt_upstream_connect_success_total 2613
telemt_upstream_connect_fail_total 14
telemt_upstream_connect_attempts_per_request{bucket="1"} 2627
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1259
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1352
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 14
telemt_me_keepalive_timeout_total 66
telemt_me_reconnect_attempts_total 1946
telemt_me_reconnect_success_total 1932
telemt_me_reader_eof_total 2027
telemt_me_idle_close_by_peer_total 2027
telemt_me_route_drop_no_conn_total 30547
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 67224
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 169
telemt_desync_full_logged_total 59
telemt_desync_suppressed_total 110
telemt_desync_frames_bucket_total{bucket="1_2"} 42
telemt_desync_frames_bucket_total{bucket="3_10"} 59
telemt_desync_frames_bucket_total{bucket="gt_10"} 68
telemt_pool_swap_total 13
telemt_me_writer_removed_unexpected_total 1953
telemt_me_writer_restored_same_endpoint_total 1925
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 21
telemt_user_connections_total{user="hello"} 67187
telemt_user_connections_current{user="hello"} 425
telemt_user_octets_from_client{user="hello"} 2059598512 (1.92 GB)
telemt_user_octets_to_client{user="hello"} 35397426804 (32.97 GB)
telemt_user_unique_ips_current{user="hello"} 128
telemt_user_unique_ips_recent_window{user="hello"} 59
```