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

# Server Metrics 2026-03-17 10:34:05 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 56923.2 (15h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 476829
telemt_connections_bad_total 3922
telemt_handshake_timeouts_total 13326
telemt_upstream_connect_attempt_total 14288
telemt_upstream_connect_success_total 13853
telemt_upstream_connect_fail_total 435
telemt_upstream_connect_attempts_per_request{bucket="1"} 14288
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7372
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6331
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 150
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 435
telemt_me_keepalive_timeout_total 104
telemt_me_reconnect_attempts_total 10236
telemt_me_reconnect_success_total 8705
telemt_me_reader_eof_total 9255
telemt_me_idle_close_by_peer_total 9254
telemt_me_route_drop_no_conn_total 150517
telemt_me_route_drop_channel_closed_total 42
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 431866
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3457
telemt_desync_full_logged_total 918
telemt_desync_suppressed_total 2539
telemt_desync_frames_bucket_total{bucket="1_2"} 935
telemt_desync_frames_bucket_total{bucket="3_10"} 1482
telemt_desync_frames_bucket_total{bucket="gt_10"} 1040
telemt_pool_swap_total 53
telemt_me_writer_removed_unexpected_total 8885
telemt_me_refill_failed_total 43
telemt_me_writer_restored_same_endpoint_total 8683
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 180
telemt_user_connections_total{user="hello"} 433825
telemt_user_connections_current{user="hello"} 1003
telemt_user_octets_from_client{user="hello"} 6254311167 (5.82 GB)
telemt_user_octets_to_client{user="hello"} 167225089627 (155.74 GB)
telemt_user_msgs_from_client{user="hello"} 17216
telemt_user_msgs_to_client{user="hello"} 23688
telemt_user_unique_ips_current{user="hello"} 350
telemt_user_unique_ips_recent_window{user="hello"} 148
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 57174.4 (15h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 260054
telemt_connections_bad_total 5249
telemt_handshake_timeouts_total 15507
telemt_upstream_connect_attempt_total 14745
telemt_upstream_connect_success_total 14539
telemt_upstream_connect_fail_total 206
telemt_upstream_connect_attempts_per_request{bucket="1"} 14745
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6275
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8095
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 169
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 206
telemt_me_keepalive_timeout_total 6
telemt_me_reconnect_attempts_total 20413
telemt_me_reconnect_success_total 11699
telemt_me_reader_eof_total 12546
telemt_me_idle_close_by_peer_total 12546
telemt_me_route_drop_no_conn_total 94225
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 226806
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 602
telemt_desync_full_logged_total 230
telemt_desync_suppressed_total 372
telemt_desync_frames_bucket_total{bucket="1_2"} 175
telemt_desync_frames_bucket_total{bucket="3_10"} 262
telemt_desync_frames_bucket_total{bucket="gt_10"} 165
telemt_pool_swap_total 37
telemt_me_writer_removed_unexpected_total 12095
telemt_me_refill_failed_total 271
telemt_me_writer_restored_same_endpoint_total 11683
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 1056
telemt_me_writer_removed_unexpected_minus_restored_total 396
telemt_user_connections_total{user="hello"} 226806
telemt_user_connections_current{user="hello"} 487
telemt_user_octets_from_client{user="hello"} 2752155008 (2.56 GB)
telemt_user_octets_to_client{user="hello"} 84423855804 (78.63 GB)
telemt_user_unique_ips_current{user="hello"} 161
telemt_user_unique_ips_recent_window{user="hello"} 68
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 56950.2 (15h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 158406
telemt_connections_bad_total 7609
telemt_handshake_timeouts_total 11911
telemt_upstream_connect_attempt_total 15227
telemt_upstream_connect_success_total 15147
telemt_upstream_connect_fail_total 80
telemt_upstream_connect_attempts_per_request{bucket="1"} 15227
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6697
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8382
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 66
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 80
telemt_me_keepalive_timeout_total 17
telemt_me_reconnect_attempts_total 14130
telemt_me_reconnect_success_total 12262
telemt_me_reader_eof_total 13112
telemt_me_idle_close_by_peer_total 13112
telemt_me_route_drop_no_conn_total 47393
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 129100
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 463
telemt_desync_full_logged_total 118
telemt_desync_suppressed_total 345
telemt_desync_frames_bucket_total{bucket="1_2"} 193
telemt_desync_frames_bucket_total{bucket="3_10"} 195
telemt_desync_frames_bucket_total{bucket="gt_10"} 75
telemt_pool_swap_total 49
telemt_me_writer_removed_unexpected_total 12488
telemt_me_refill_failed_total 56
telemt_me_writer_restored_same_endpoint_total 12251
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 226
telemt_user_connections_total{user="hello"} 129012
telemt_user_connections_current{user="hello"} 341
telemt_user_octets_from_client{user="hello"} 9752865644 (9.08 GB)
telemt_user_octets_to_client{user="hello"} 39005684136 (36.33 GB)
telemt_user_unique_ips_current{user="hello"} 107
telemt_user_unique_ips_recent_window{user="hello"} 39
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 57009.5 (15h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 354454
telemt_connections_bad_total 6221
telemt_handshake_timeouts_total 11603
telemt_upstream_connect_attempt_total 12986
telemt_upstream_connect_success_total 12867
telemt_upstream_connect_fail_total 119
telemt_upstream_connect_attempts_per_request{bucket="1"} 12986
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6094
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6689
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 76
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 119
telemt_me_keepalive_timeout_total 6
telemt_me_reconnect_attempts_total 11039
telemt_me_reconnect_success_total 9944
telemt_me_reader_eof_total 10574
telemt_me_idle_close_by_peer_total 10574
telemt_me_route_drop_no_conn_total 99310
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 290432
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 701
telemt_desync_full_logged_total 272
telemt_desync_suppressed_total 429
telemt_desync_frames_bucket_total{bucket="1_2"} 165
telemt_desync_frames_bucket_total{bucket="3_10"} 314
telemt_desync_frames_bucket_total{bucket="gt_10"} 222
telemt_pool_swap_total 48
telemt_me_writer_removed_unexpected_total 10133
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 9936
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 189
telemt_user_connections_total{user="hello"} 290387
telemt_user_connections_current{user="hello"} 698
telemt_user_octets_from_client{user="hello"} 3661490546 (3.41 GB)
telemt_user_octets_to_client{user="hello"} 111644738625 (103.98 GB)
telemt_user_msgs_from_client{user="hello"} 65
telemt_user_msgs_to_client{user="hello"} 189
telemt_user_unique_ips_current{user="hello"} 205
telemt_user_unique_ips_recent_window{user="hello"} 91
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 56981.5 (15h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 193018
telemt_connections_bad_total 51292
telemt_handshake_timeouts_total 2887
telemt_upstream_connect_attempt_total 17337
telemt_upstream_connect_success_total 17111
telemt_upstream_connect_fail_total 226
telemt_upstream_connect_attempts_per_request{bucket="1"} 17337
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7633
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9269
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 209
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 226
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 23653
telemt_me_reconnect_success_total 14129
telemt_me_reader_eof_total 15026
telemt_me_idle_close_by_peer_total 15026
telemt_me_route_drop_no_conn_total 50169
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 132857
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 579
telemt_desync_full_logged_total 128
telemt_desync_suppressed_total 451
telemt_desync_frames_bucket_total{bucket="1_2"} 291
telemt_desync_frames_bucket_total{bucket="3_10"} 209
telemt_desync_frames_bucket_total{bucket="gt_10"} 79
telemt_pool_swap_total 34
telemt_me_writer_removed_unexpected_total 14604
telemt_me_refill_failed_total 295
telemt_me_writer_restored_same_endpoint_total 14121
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 143
telemt_me_writer_removed_unexpected_minus_restored_total 475
telemt_user_connections_total{user="hello"} 132885
telemt_user_connections_current{user="hello"} 304
telemt_user_octets_from_client{user="hello"} 1939217135 (1.81 GB)
telemt_user_octets_to_client{user="hello"} 59410548054 (55.33 GB)
telemt_user_msgs_from_client{user="hello"} 265
telemt_user_msgs_to_client{user="hello"} 707
telemt_user_unique_ips_current{user="hello"} 104
telemt_user_unique_ips_recent_window{user="hello"} 41
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 57142.9 (15h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 449709
telemt_connections_bad_total 50930
telemt_handshake_timeouts_total 4457
telemt_upstream_connect_attempt_total 11559
telemt_upstream_connect_success_total 11495
telemt_upstream_connect_fail_total 64
telemt_upstream_connect_attempts_per_request{bucket="1"} 11559
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5653
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5822
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 19
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 64
telemt_me_keepalive_timeout_total 21
telemt_me_reconnect_attempts_total 12532
telemt_me_reconnect_success_total 8647
telemt_me_reader_eof_total 9338
telemt_me_idle_close_by_peer_total 9338
telemt_me_route_drop_no_conn_total 289210
telemt_me_route_drop_channel_closed_total 12
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 448899
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 672
telemt_desync_full_logged_total 257
telemt_desync_suppressed_total 415
telemt_desync_frames_bucket_total{bucket="1_2"} 183
telemt_desync_frames_bucket_total{bucket="3_10"} 256
telemt_desync_frames_bucket_total{bucket="gt_10"} 233
telemt_pool_swap_total 54
telemt_me_writer_removed_unexpected_total 8899
telemt_me_refill_failed_total 120
telemt_me_writer_restored_same_endpoint_total 8633
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 252
telemt_user_connections_total{user="hello"} 370769
telemt_user_connections_current{user="hello"} 942
telemt_user_octets_from_client{user="hello"} 5313023040 (4.95 GB)
telemt_user_octets_to_client{user="hello"} 197095377228 (183.56 GB)
telemt_user_unique_ips_current{user="hello"} 304
telemt_user_unique_ips_recent_window{user="hello"} 108
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 4909.6 (1h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4116
telemt_connections_bad_total 31
telemt_handshake_timeouts_total 32
telemt_upstream_connect_attempt_total 2157
telemt_upstream_connect_success_total 2128
telemt_upstream_connect_fail_total 29
telemt_upstream_connect_attempts_per_request{bucket="1"} 2157
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1172
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 956
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 29
telemt_me_reconnect_attempts_total 1746
telemt_me_reconnect_success_total 1716
telemt_me_reader_eof_total 1799
telemt_me_idle_close_by_peer_total 1799
telemt_me_seq_mismatch_total 3
telemt_me_route_drop_no_conn_total 1532
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3825
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_endpoint_quarantine_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 3
telemt_me_writer_removed_unexpected_total 1738
telemt_me_writer_restored_same_endpoint_total 1710
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 880
telemt_me_writer_removed_unexpected_minus_restored_total 22
telemt_user_connections_total{user="hello"} 3931
telemt_user_connections_current{user="hello"} 87
telemt_user_octets_from_client{user="hello"} 72329285 (68.98 MB)
telemt_user_octets_to_client{user="hello"} 17228870982 (16.05 GB)
telemt_user_msgs_from_client{user="hello"} 350
telemt_user_msgs_to_client{user="hello"} 2305
telemt_user_unique_ips_current{user="hello"} 21
telemt_user_unique_ips_recent_window{user="hello"} 10
```