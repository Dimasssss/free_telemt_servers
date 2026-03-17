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

# Server Metrics 2026-03-17 11:30:29 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 60312.7 (16h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 539403
telemt_connections_bad_total 4623
telemt_handshake_timeouts_total 16019
telemt_upstream_connect_attempt_total 14843
telemt_upstream_connect_success_total 14402
telemt_upstream_connect_fail_total 441
telemt_upstream_connect_attempts_per_request{bucket="1"} 14843
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7611
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6641
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 150
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 441
telemt_me_keepalive_timeout_total 110
telemt_me_reconnect_attempts_total 10655
telemt_me_reconnect_success_total 9120
telemt_me_reader_eof_total 9694
telemt_me_idle_close_by_peer_total 9693
telemt_me_route_drop_no_conn_total 176222
telemt_me_route_drop_channel_closed_total 49
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 486993
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3863
telemt_desync_full_logged_total 1015
telemt_desync_suppressed_total 2848
telemt_desync_frames_bucket_total{bucket="1_2"} 1121
telemt_desync_frames_bucket_total{bucket="3_10"} 1608
telemt_desync_frames_bucket_total{bucket="gt_10"} 1134
telemt_pool_swap_total 56
telemt_me_writer_removed_unexpected_total 9303
telemt_me_refill_failed_total 43
telemt_me_writer_restored_same_endpoint_total 9098
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 183
telemt_user_connections_total{user="hello"} 488928
telemt_user_connections_current{user="hello"} 1044
telemt_user_octets_from_client{user="hello"} 6711118255 (6.25 GB)
telemt_user_octets_to_client{user="hello"} 179446192407 (167.12 GB)
telemt_user_msgs_from_client{user="hello"} 17216
telemt_user_msgs_to_client{user="hello"} 23688
telemt_user_unique_ips_current{user="hello"} 350
telemt_user_unique_ips_recent_window{user="hello"} 146
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 60564.7 (16h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 301017
telemt_connections_bad_total 11544
telemt_handshake_timeouts_total 17470
telemt_upstream_connect_attempt_total 15331
telemt_upstream_connect_success_total 15113
telemt_upstream_connect_fail_total 218
telemt_upstream_connect_attempts_per_request{bucket="1"} 15331
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6527
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8378
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 208
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 218
telemt_me_keepalive_timeout_total 13
telemt_me_reconnect_attempts_total 24427
telemt_me_reconnect_success_total 12093
telemt_me_reader_eof_total 13064
telemt_me_idle_close_by_peer_total 13064
telemt_me_route_drop_no_conn_total 112116
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 257187
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 772
telemt_desync_full_logged_total 278
telemt_desync_suppressed_total 494
telemt_desync_frames_bucket_total{bucket="1_2"} 218
telemt_desync_frames_bucket_total{bucket="3_10"} 333
telemt_desync_frames_bucket_total{bucket="gt_10"} 221
telemt_pool_swap_total 38
telemt_me_writer_removed_unexpected_total 12610
telemt_me_refill_failed_total 384
telemt_me_writer_restored_same_endpoint_total 12077
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 1056
telemt_me_writer_removed_unexpected_minus_restored_total 517
telemt_user_connections_total{user="hello"} 257175
telemt_user_connections_current{user="hello"} 533
telemt_user_octets_from_client{user="hello"} 3027465684 (2.82 GB)
telemt_user_octets_to_client{user="hello"} 93400533852 (86.99 GB)
telemt_user_unique_ips_current{user="hello"} 182
telemt_user_unique_ips_recent_window{user="hello"} 78
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 60340.4 (16h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 177635
telemt_connections_bad_total 7714
telemt_handshake_timeouts_total 14364
telemt_upstream_connect_attempt_total 15807
telemt_upstream_connect_success_total 15725
telemt_upstream_connect_fail_total 82
telemt_upstream_connect_attempts_per_request{bucket="1"} 15807
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6946
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8710
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 67
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 82
telemt_me_keepalive_timeout_total 23
telemt_me_reconnect_attempts_total 14568
telemt_me_reconnect_success_total 12697
telemt_me_reader_eof_total 13573
telemt_me_idle_close_by_peer_total 13573
telemt_me_route_drop_no_conn_total 53002
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 145243
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 531
telemt_desync_full_logged_total 139
telemt_desync_suppressed_total 392
telemt_desync_frames_bucket_total{bucket="1_2"} 230
telemt_desync_frames_bucket_total{bucket="3_10"} 225
telemt_desync_frames_bucket_total{bucket="gt_10"} 76
telemt_pool_swap_total 52
telemt_me_writer_removed_unexpected_total 12931
telemt_me_refill_failed_total 56
telemt_me_writer_restored_same_endpoint_total 12686
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 234
telemt_user_connections_total{user="hello"} 145147
telemt_user_connections_current{user="hello"} 363
telemt_user_octets_from_client{user="hello"} 13693451488 (12.75 GB)
telemt_user_octets_to_client{user="hello"} 42026259944 (39.14 GB)
telemt_user_unique_ips_current{user="hello"} 129
telemt_user_unique_ips_recent_window{user="hello"} 67
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 60399.5 (16h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 401088
telemt_connections_bad_total 6722
telemt_handshake_timeouts_total 12038
telemt_upstream_connect_attempt_total 13772
telemt_upstream_connect_success_total 13643
telemt_upstream_connect_fail_total 129
telemt_upstream_connect_attempts_per_request{bucket="1"} 13772
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6415
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7141
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 79
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 129
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 11654
telemt_me_reconnect_success_total 10548
telemt_me_reader_eof_total 11205
telemt_me_idle_close_by_peer_total 11205
telemt_me_route_drop_no_conn_total 112748
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 332768
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 969
telemt_desync_full_logged_total 351
telemt_desync_suppressed_total 618
telemt_desync_frames_bucket_total{bucket="1_2"} 234
telemt_desync_frames_bucket_total{bucket="3_10"} 415
telemt_desync_frames_bucket_total{bucket="gt_10"} 320
telemt_pool_swap_total 49
telemt_me_writer_removed_unexpected_total 10756
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 10540
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 208
telemt_user_connections_total{user="hello"} 332703
telemt_user_connections_current{user="hello"} 771
telemt_user_octets_from_client{user="hello"} 4389337034 (4.09 GB)
telemt_user_octets_to_client{user="hello"} 121834251201 (113.47 GB)
telemt_user_msgs_from_client{user="hello"} 65
telemt_user_msgs_to_client{user="hello"} 189
telemt_user_unique_ips_current{user="hello"} 203
telemt_user_unique_ips_recent_window{user="hello"} 123
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 60371.4 (16h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 210930
telemt_connections_bad_total 51972
telemt_handshake_timeouts_total 3027
telemt_upstream_connect_attempt_total 17823
telemt_upstream_connect_success_total 17588
telemt_upstream_connect_fail_total 235
telemt_upstream_connect_attempts_per_request{bucket="1"} 17823
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7897
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9479
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 212
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 235
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 28097
telemt_me_reconnect_success_total 14444
telemt_me_reader_eof_total 15469
telemt_me_idle_close_by_peer_total 15469
telemt_me_route_drop_no_conn_total 55555
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 149101
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 889
telemt_desync_full_logged_total 172
telemt_desync_suppressed_total 717
telemt_desync_frames_bucket_total{bucket="1_2"} 473
telemt_desync_frames_bucket_total{bucket="3_10"} 320
telemt_desync_frames_bucket_total{bucket="gt_10"} 96
telemt_pool_swap_total 34
telemt_me_writer_removed_unexpected_total 15048
telemt_me_refill_failed_total 424
telemt_me_writer_restored_same_endpoint_total 14436
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 143
telemt_me_writer_removed_unexpected_minus_restored_total 604
telemt_user_connections_total{user="hello"} 149116
telemt_user_connections_current{user="hello"} 307
telemt_user_octets_from_client{user="hello"} 2092820951 (1.95 GB)
telemt_user_octets_to_client{user="hello"} 63666997962 (59.29 GB)
telemt_user_msgs_from_client{user="hello"} 265
telemt_user_msgs_to_client{user="hello"} 707
telemt_user_unique_ips_current{user="hello"} 104
telemt_user_unique_ips_recent_window{user="hello"} 64
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 60532.7 (16h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 496171
telemt_connections_bad_total 51655
telemt_handshake_timeouts_total 4706
telemt_upstream_connect_attempt_total 12287
telemt_upstream_connect_success_total 12221
telemt_upstream_connect_fail_total 66
telemt_upstream_connect_attempts_per_request{bucket="1"} 12287
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6040
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6161
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 19
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 66
telemt_me_keepalive_timeout_total 31
telemt_me_reconnect_attempts_total 13080
telemt_me_reconnect_success_total 9187
telemt_me_reader_eof_total 9909
telemt_me_idle_close_by_peer_total 9909
telemt_me_route_drop_no_conn_total 333654
telemt_me_route_drop_channel_closed_total 18
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 490557
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 733
telemt_desync_full_logged_total 273
telemt_desync_suppressed_total 460
telemt_desync_frames_bucket_total{bucket="1_2"} 195
telemt_desync_frames_bucket_total{bucket="3_10"} 287
telemt_desync_frames_bucket_total{bucket="gt_10"} 251
telemt_pool_swap_total 56
telemt_me_writer_removed_unexpected_total 9451
telemt_me_refill_failed_total 120
telemt_me_writer_restored_same_endpoint_total 9173
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 264
telemt_user_connections_total{user="hello"} 412249
telemt_user_connections_current{user="hello"} 1045
telemt_user_octets_from_client{user="hello"} 6067528272 (5.65 GB)
telemt_user_octets_to_client{user="hello"} 208384633860 (194.07 GB)
telemt_user_unique_ips_current{user="hello"} 346
telemt_user_unique_ips_recent_window{user="hello"} 179
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 8299.5 (2h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6045
telemt_connections_bad_total 35
telemt_handshake_timeouts_total 34
telemt_upstream_connect_attempt_total 4622
telemt_upstream_connect_success_total 4578
telemt_upstream_connect_fail_total 44
telemt_upstream_connect_attempts_per_request{bucket="1"} 4622
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2437
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2141
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 44
telemt_me_keepalive_timeout_total 12
telemt_me_reconnect_attempts_total 5745
telemt_me_reconnect_success_total 3980
telemt_me_reader_eof_total 4133
telemt_me_idle_close_by_peer_total 4133
telemt_me_seq_mismatch_total 5
telemt_me_route_drop_no_conn_total 2357
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5736
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 3
telemt_me_writer_removed_unexpected_total 4075
telemt_me_refill_failed_total 54
telemt_me_writer_restored_same_endpoint_total 3971
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 880
telemt_me_writer_removed_unexpected_minus_restored_total 95
telemt_user_connections_total{user="hello"} 5842
telemt_user_connections_current{user="hello"} 97
telemt_user_octets_from_client{user="hello"} 146358537 (139.58 MB)
telemt_user_octets_to_client{user="hello"} 18973911186 (17.67 GB)
telemt_user_msgs_from_client{user="hello"} 350
telemt_user_msgs_to_client{user="hello"} 2305
telemt_user_unique_ips_current{user="hello"} 22
telemt_user_unique_ips_recent_window{user="hello"} 9
```