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

# Server Metrics 2026-03-17 13:12:25 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 66429.4 (18h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 650070
telemt_connections_bad_total 5176
telemt_handshake_timeouts_total 20156
telemt_upstream_connect_attempt_total 16477
telemt_upstream_connect_success_total 16025
telemt_upstream_connect_fail_total 452
telemt_upstream_connect_attempts_per_request{bucket="1"} 16477
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8364
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7511
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 150
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 452
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 120
telemt_me_reconnect_attempts_total 14235
telemt_me_reconnect_success_total 10423
telemt_me_reader_eof_total 11097
telemt_me_idle_close_by_peer_total 11096
telemt_me_route_drop_no_conn_total 214938
telemt_me_route_drop_channel_closed_total 67
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 587586
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4352
telemt_desync_full_logged_total 1190
telemt_desync_suppressed_total 3162
telemt_desync_frames_bucket_total{bucket="1_2"} 1252
telemt_desync_frames_bucket_total{bucket="3_10"} 1797
telemt_desync_frames_bucket_total{bucket="gt_10"} 1303
telemt_pool_swap_total 57
telemt_me_writer_removed_unexpected_total 10693
telemt_me_refill_failed_total 114
telemt_me_writer_restored_same_endpoint_total 10401
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 270
telemt_user_connections_total{user="hello"} 589478
telemt_user_connections_current{user="hello"} 994
telemt_user_octets_from_client{user="hello"} 8485855103 (7.90 GB)
telemt_user_octets_to_client{user="hello"} 209258596235 (194.89 GB)
telemt_user_msgs_from_client{user="hello"} 17216
telemt_user_msgs_to_client{user="hello"} 23688
telemt_user_unique_ips_current{user="hello"} 336
telemt_user_unique_ips_recent_window{user="hello"} 149
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 66681.2 (18h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 389274
telemt_connections_bad_total 23443
telemt_handshake_timeouts_total 20405
telemt_upstream_connect_attempt_total 16796
telemt_upstream_connect_success_total 16526
telemt_upstream_connect_fail_total 270
telemt_upstream_connect_attempts_per_request{bucket="1"} 16796
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7101
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9075
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 350
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 270
telemt_me_keepalive_timeout_total 244
telemt_me_reconnect_attempts_total 26263
telemt_me_reconnect_success_total 13186
telemt_me_reader_eof_total 14177
telemt_me_idle_close_by_peer_total 14177
telemt_me_route_drop_no_conn_total 158695
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 325120
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1258
telemt_desync_full_logged_total 411
telemt_desync_suppressed_total 847
telemt_desync_frames_bucket_total{bucket="1_2"} 281
telemt_desync_frames_bucket_total{bucket="3_10"} 557
telemt_desync_frames_bucket_total{bucket="gt_10"} 420
telemt_pool_swap_total 39
telemt_me_writer_removed_unexpected_total 13756
telemt_me_refill_failed_total 405
telemt_me_writer_restored_same_endpoint_total 13170
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 1056
telemt_me_writer_removed_unexpected_minus_restored_total 570
telemt_user_connections_total{user="hello"} 325066
telemt_user_connections_current{user="hello"} 612
telemt_user_octets_from_client{user="hello"} 3601643876 (3.35 GB)
telemt_user_octets_to_client{user="hello"} 113986352372 (106.16 GB)
telemt_user_unique_ips_current{user="hello"} 174
telemt_user_unique_ips_recent_window{user="hello"} 98
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 66457.0 (18h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 213400
telemt_connections_bad_total 7755
telemt_handshake_timeouts_total 16597
telemt_upstream_connect_attempt_total 17472
telemt_upstream_connect_success_total 17383
telemt_upstream_connect_fail_total 89
telemt_upstream_connect_attempts_per_request{bucket="1"} 17472
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7731
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9577
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 70
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 89
telemt_me_keepalive_timeout_total 28
telemt_me_reconnect_attempts_total 15919
telemt_me_reconnect_success_total 14039
telemt_me_reader_eof_total 14963
telemt_me_idle_close_by_peer_total 14963
telemt_me_route_drop_no_conn_total 73536
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 177768
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 698
telemt_desync_full_logged_total 188
telemt_desync_suppressed_total 510
telemt_desync_frames_bucket_total{bucket="1_2"} 266
telemt_desync_frames_bucket_total{bucket="3_10"} 298
telemt_desync_frames_bucket_total{bucket="gt_10"} 134
telemt_pool_swap_total 55
telemt_me_writer_removed_unexpected_total 14294
telemt_me_refill_failed_total 56
telemt_me_writer_restored_same_endpoint_total 14028
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 255
telemt_user_connections_total{user="hello"} 177657
telemt_user_connections_current{user="hello"} 363
telemt_user_octets_from_client{user="hello"} 15228781852 (14.18 GB)
telemt_user_octets_to_client{user="hello"} 50102610496 (46.66 GB)
telemt_user_unique_ips_current{user="hello"} 127
telemt_user_unique_ips_recent_window{user="hello"} 53
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 66516.2 (18h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 488457
telemt_connections_bad_total 7890
telemt_handshake_timeouts_total 12618
telemt_upstream_connect_attempt_total 16003
telemt_upstream_connect_success_total 15859
telemt_upstream_connect_fail_total 144
telemt_upstream_connect_attempts_per_request{bucket="1"} 16003
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7885
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7858
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 107
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 144
telemt_me_keepalive_timeout_total 12
telemt_me_reconnect_attempts_total 15465
telemt_me_reconnect_success_total 11505
telemt_me_reader_eof_total 12288
telemt_me_idle_close_by_peer_total 12288
telemt_me_route_drop_no_conn_total 139429
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 412305
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1464
telemt_desync_full_logged_total 511
telemt_desync_suppressed_total 953
telemt_desync_frames_bucket_total{bucket="1_2"} 355
telemt_desync_frames_bucket_total{bucket="3_10"} 659
telemt_desync_frames_bucket_total{bucket="gt_10"} 450
telemt_pool_swap_total 51
telemt_me_writer_removed_unexpected_total 11832
telemt_me_refill_failed_total 119
telemt_me_writer_restored_same_endpoint_total 11496
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 327
telemt_user_connections_total{user="hello"} 413178
telemt_user_connections_current{user="hello"} 756
telemt_user_octets_from_client{user="hello"} 5274922026 (4.91 GB)
telemt_user_octets_to_client{user="hello"} 142163609207 (132.40 GB)
telemt_user_msgs_from_client{user="hello"} 4070
telemt_user_msgs_to_client{user="hello"} 5224
telemt_user_unique_ips_current{user="hello"} 212
telemt_user_unique_ips_recent_window{user="hello"} 118
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 66488.1 (18h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 245829
telemt_connections_bad_total 55992
telemt_handshake_timeouts_total 3211
telemt_upstream_connect_attempt_total 19280
telemt_upstream_connect_success_total 19033
telemt_upstream_connect_fail_total 247
telemt_upstream_connect_attempts_per_request{bucket="1"} 19280
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8486
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10303
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 244
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 247
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 31463
telemt_me_reconnect_success_total 15591
telemt_me_reader_eof_total 16724
telemt_me_idle_close_by_peer_total 16724
telemt_me_route_drop_no_conn_total 64788
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 177836
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1066
telemt_desync_full_logged_total 219
telemt_desync_suppressed_total 847
telemt_desync_frames_bucket_total{bucket="1_2"} 534
telemt_desync_frames_bucket_total{bucket="3_10"} 404
telemt_desync_frames_bucket_total{bucket="gt_10"} 128
telemt_pool_swap_total 36
telemt_me_writer_removed_unexpected_total 16292
telemt_me_refill_failed_total 493
telemt_me_writer_restored_same_endpoint_total 15583
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 143
telemt_me_writer_removed_unexpected_minus_restored_total 701
telemt_user_connections_total{user="hello"} 177840
telemt_user_connections_current{user="hello"} 265
telemt_user_octets_from_client{user="hello"} 2328635563 (2.17 GB)
telemt_user_octets_to_client{user="hello"} 69245249422 (64.49 GB)
telemt_user_msgs_from_client{user="hello"} 265
telemt_user_msgs_to_client{user="hello"} 707
telemt_user_unique_ips_current{user="hello"} 87
telemt_user_unique_ips_recent_window{user="hello"} 47
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 66649.6 (18h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 583117
telemt_connections_bad_total 53158
telemt_handshake_timeouts_total 5696
telemt_upstream_connect_attempt_total 13487
telemt_upstream_connect_success_total 13416
telemt_upstream_connect_fail_total 71
telemt_upstream_connect_attempts_per_request{bucket="1"} 13487
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6644
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6752
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 19
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 71
telemt_me_keepalive_timeout_total 37
telemt_me_reconnect_attempts_total 13991
telemt_me_reconnect_success_total 10088
telemt_me_reader_eof_total 10847
telemt_me_idle_close_by_peer_total 10847
telemt_me_route_drop_no_conn_total 386026
telemt_me_route_drop_channel_closed_total 30
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 581121
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 835
telemt_desync_full_logged_total 307
telemt_desync_suppressed_total 528
telemt_desync_frames_bucket_total{bucket="1_2"} 210
telemt_desync_frames_bucket_total{bucket="3_10"} 320
telemt_desync_frames_bucket_total{bucket="gt_10"} 305
telemt_pool_swap_total 60
telemt_me_writer_removed_unexpected_total 10363
telemt_me_refill_failed_total 120
telemt_me_writer_restored_same_endpoint_total 10074
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 275
telemt_user_connections_total{user="hello"} 493735
telemt_user_connections_current{user="hello"} 954
telemt_user_octets_from_client{user="hello"} 7236558384 (6.74 GB)
telemt_user_octets_to_client{user="hello"} 234907883688 (218.78 GB)
telemt_user_unique_ips_current{user="hello"} 294
telemt_user_unique_ips_recent_window{user="hello"} 135
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 14416.2 (4h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11195
telemt_connections_bad_total 58
telemt_handshake_timeouts_total 44
telemt_upstream_connect_attempt_total 8060
telemt_upstream_connect_success_total 7994
telemt_upstream_connect_fail_total 66
telemt_upstream_connect_attempts_per_request{bucket="1"} 8060
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4223
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3765
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 66
telemt_me_keepalive_timeout_total 12
telemt_me_reconnect_attempts_total 11269
telemt_me_reconnect_success_total 7121
telemt_me_reader_eof_total 7442
telemt_me_idle_close_by_peer_total 7442
telemt_me_seq_mismatch_total 9
telemt_me_route_drop_no_conn_total 3996
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 10801
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_endpoint_quarantine_total 11
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 5
telemt_me_writer_removed_unexpected_total 7321
telemt_me_refill_failed_total 128
telemt_me_writer_restored_same_endpoint_total 7107
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 880
telemt_me_writer_removed_unexpected_minus_restored_total 200
telemt_user_connections_total{user="hello"} 10904
telemt_user_connections_current{user="hello"} 94
telemt_user_octets_from_client{user="hello"} 308596969 (294.30 MB)
telemt_user_octets_to_client{user="hello"} 21330998510 (19.87 GB)
telemt_user_msgs_from_client{user="hello"} 350
telemt_user_msgs_to_client{user="hello"} 2305
telemt_user_unique_ips_current{user="hello"} 24
telemt_user_unique_ips_recent_window{user="hello"} 8
```