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

# Server Metrics 2026-03-15 16:40:29 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.18

telemt_uptime_seconds 66361.1 (18h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 305444
telemt_connections_bad_total 2797
telemt_handshake_timeouts_total 9118
telemt_upstream_connect_attempt_total 16341
telemt_upstream_connect_success_total 16256
telemt_upstream_connect_fail_total 85
telemt_upstream_connect_attempts_per_request{bucket="1"} 16341
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7192
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9039
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 16
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 85
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 32
telemt_me_reconnect_attempts_total 16333
telemt_me_reconnect_success_total 12944
telemt_me_reader_eof_total 13791
telemt_me_idle_close_by_peer_total 13791
telemt_me_route_drop_no_conn_total 453774
telemt_me_route_drop_channel_closed_total 75
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 342496
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1771
telemt_desync_full_logged_total 709
telemt_desync_suppressed_total 1062
telemt_desync_frames_bucket_total{bucket="1_2"} 321
telemt_desync_frames_bucket_total{bucket="3_10"} 699
telemt_desync_frames_bucket_total{bucket="gt_10"} 751
telemt_pool_swap_total 57
telemt_me_writer_removed_unexpected_total 13186
telemt_me_refill_failed_total 104
telemt_me_writer_restored_same_endpoint_total 12910
telemt_me_writer_restored_fallback_total 34
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 242
telemt_user_connections_total{user="hello"} 281599
telemt_user_connections_current{user="hello"} 408
telemt_user_octets_from_client{user="hello"} 5928931188 (5.52 GB)
telemt_user_octets_to_client{user="hello"} 231317123860 (215.43 GB)
telemt_user_unique_ips_current{user="hello"} 120
telemt_user_unique_ips_recent_window{user="hello"} 40
```

## psb.hosting

```
telemt 3.3.18

telemt_uptime_seconds 66367.8 (18h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 119534
telemt_connections_bad_total 2820
telemt_handshake_timeouts_total 11205
telemt_upstream_connect_attempt_total 18291
telemt_upstream_connect_success_total 18291
telemt_upstream_connect_attempts_per_request{bucket="1"} 18291
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7880
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10183
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 228
telemt_me_keepalive_timeout_total 34
telemt_me_reconnect_attempts_total 17295
telemt_me_reconnect_success_total 14932
telemt_me_reader_eof_total 15950
telemt_me_idle_close_by_peer_total 15949
telemt_me_route_drop_no_conn_total 49262
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 101992
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3
telemt_desync_full_logged_total 3
telemt_desync_frames_bucket_total{bucket="1_2"} 1
telemt_desync_frames_bucket_total{bucket="3_10"} 2
telemt_pool_swap_total 56
telemt_me_writer_removed_unexpected_total 15187
telemt_me_refill_failed_total 71
telemt_me_writer_restored_same_endpoint_total 14916
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 255
telemt_user_connections_total{user="hello"} 101976
telemt_user_connections_current{user="hello"} 235
telemt_user_octets_from_client{user="hello"} 2033547196 (1.89 GB)
telemt_user_octets_to_client{user="hello"} 50677918960 (47.20 GB)
telemt_user_unique_ips_current{user="hello"} 53
telemt_user_unique_ips_recent_window{user="hello"} 29
```

## koara.io

```
telemt 3.3.18

telemt_uptime_seconds 66360.1 (18h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 125255
telemt_connections_bad_total 1665
telemt_handshake_timeouts_total 3098
telemt_upstream_connect_attempt_total 19774
telemt_upstream_connect_success_total 19766
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 19774
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8547
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11185
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 34
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 35
telemt_me_reconnect_attempts_total 23749
telemt_me_reconnect_success_total 16394
telemt_me_reader_eof_total 17582
telemt_me_idle_close_by_peer_total 17582
telemt_me_route_drop_no_conn_total 48669
telemt_me_route_drop_channel_closed_total 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 109337
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 12
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 59
telemt_desync_full_logged_total 23
telemt_desync_suppressed_total 36
telemt_desync_frames_bucket_total{bucket="1_2"} 5
telemt_desync_frames_bucket_total{bucket="3_10"} 29
telemt_desync_frames_bucket_total{bucket="gt_10"} 25
telemt_pool_swap_total 52
telemt_me_writer_removed_unexpected_total 16780
telemt_me_refill_failed_total 227
telemt_me_writer_restored_same_endpoint_total 16386
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 386
telemt_user_connections_total{user="hello"} 109232
telemt_user_connections_current{user="hello"} 203
telemt_user_octets_from_client{user="hello"} 10460762080 (9.74 GB)
telemt_user_octets_to_client{user="hello"} 62228367972 (57.95 GB)
telemt_user_unique_ips_current{user="hello"} 67
telemt_user_unique_ips_recent_window{user="hello"} 34
```

## landvps.ru

```
telemt 3.3.18

telemt_uptime_seconds 66359.9 (18h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 168476
telemt_connections_bad_total 916
telemt_handshake_timeouts_total 1043
telemt_upstream_connect_attempt_total 15919
telemt_upstream_connect_success_total 15908
telemt_upstream_connect_fail_total 11
telemt_upstream_connect_attempts_per_request{bucket="1"} 15919
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7650
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8196
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 61
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 11
telemt_me_keepalive_timeout_total 20
telemt_me_reconnect_attempts_total 12675
telemt_me_reconnect_success_total 12595
telemt_me_reader_eof_total 13400
telemt_me_idle_close_by_peer_total 13400
telemt_me_route_drop_no_conn_total 65734
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 154991
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 543
telemt_desync_full_logged_total 191
telemt_desync_suppressed_total 352
telemt_desync_frames_bucket_total{bucket="1_2"} 113
telemt_desync_frames_bucket_total{bucket="3_10"} 249
telemt_desync_frames_bucket_total{bucket="gt_10"} 181
telemt_pool_swap_total 59
telemt_me_writer_removed_unexpected_total 12749
telemt_me_writer_restored_same_endpoint_total 12584
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 154
telemt_user_connections_total{user="hello"} 154904
telemt_user_connections_current{user="hello"} 243
telemt_user_octets_from_client{user="hello"} 2901420272 (2.70 GB)
telemt_user_octets_to_client{user="hello"} 71066987136 (66.19 GB)
telemt_user_unique_ips_current{user="hello"} 69
telemt_user_unique_ips_recent_window{user="hello"} 30
```

## rdp-onedash.ru

```
telemt 3.3.18

telemt_uptime_seconds 41431.4 (11h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 102238
telemt_connections_bad_total 22857
telemt_handshake_timeouts_total 2293
telemt_upstream_connect_attempt_total 12775
telemt_upstream_connect_success_total 12703
telemt_upstream_connect_fail_total 72
telemt_upstream_connect_attempts_per_request{bucket="1"} 12775
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5814
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6824
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 65
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 72
telemt_me_keepalive_timeout_total 21
telemt_me_reconnect_attempts_total 104894
telemt_me_reconnect_success_total 10454
telemt_me_reader_eof_total 10953
telemt_me_idle_close_by_peer_total 10953
telemt_me_route_drop_no_conn_total 34981
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 74570
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 183
telemt_desync_full_logged_total 44
telemt_desync_suppressed_total 139
telemt_desync_frames_bucket_total{bucket="1_2"} 34
telemt_desync_frames_bucket_total{bucket="3_10"} 70
telemt_desync_frames_bucket_total{bucket="gt_10"} 79
telemt_pool_swap_total 27
telemt_me_writer_removed_unexpected_total 10506
telemt_me_refill_failed_total 3033
telemt_me_writer_restored_same_endpoint_total 10350
telemt_me_writer_restored_fallback_total 104
telemt_me_async_recovery_trigger_total 2255
telemt_me_writer_removed_unexpected_minus_restored_total 52
telemt_user_connections_total{user="hello"} 74705
telemt_user_connections_current{user="hello"} 153
telemt_user_octets_from_client{user="hello"} 1277332985 (1.19 GB)
telemt_user_octets_to_client{user="hello"} 30197707687 (28.12 GB)
telemt_user_msgs_from_client{user="hello"} 2259
telemt_user_msgs_to_client{user="hello"} 12105
telemt_user_unique_ips_current{user="hello"} 51
telemt_user_unique_ips_recent_window{user="hello"} 22
```

## hostvds.com

```
telemt 3.3.18

telemt_uptime_seconds 66360.6 (18h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 433534
telemt_connections_bad_total 57515
telemt_handshake_timeouts_total 3540
telemt_upstream_connect_attempt_total 14380
telemt_upstream_connect_success_total 14297
telemt_upstream_connect_fail_total 83
telemt_upstream_connect_attempts_per_request{bucket="1"} 14380
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7002
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7274
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 14
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 83
telemt_me_keepalive_timeout_total 61
telemt_me_reconnect_attempts_total 12254
telemt_me_reconnect_success_total 10953
telemt_me_reader_eof_total 11639
telemt_me_idle_close_by_peer_total 11639
telemt_me_route_drop_no_conn_total 254155
telemt_me_route_drop_channel_closed_total 61
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 384035
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 317
telemt_desync_full_logged_total 86
telemt_desync_suppressed_total 231
telemt_desync_frames_bucket_total{bucket="1_2"} 169
telemt_desync_frames_bucket_total{bucket="3_10"} 94
telemt_desync_frames_bucket_total{bucket="gt_10"} 54
telemt_pool_swap_total 56
telemt_me_writer_removed_unexpected_total 11109
telemt_me_refill_failed_total 38
telemt_me_writer_restored_same_endpoint_total 10926
telemt_me_writer_restored_fallback_total 27
telemt_me_async_recovery_trigger_total 40
telemt_me_writer_removed_unexpected_minus_restored_total 156
telemt_user_connections_total{user="hello"} 356773
telemt_user_connections_current{user="hello"} 651
telemt_user_octets_from_client{user="hello"} 9460164660 (8.81 GB)
telemt_user_octets_to_client{user="hello"} 189774143640 (176.74 GB)
telemt_user_unique_ips_current{user="hello"} 231
telemt_user_unique_ips_recent_window{user="hello"} 85
```