# Информация

Покупаю сервера у разных хостингов для запуска прокси для Telegram

Для прокси используется https://github.com/telemt/telemt
[Конфиг](https://github.com/Dimasssss/free_telemt_servers/blob/main/config.toml) используемый на всех серверах.

### [Итог по хостингам](Reviews.md)

---

## NKtelecom
- Локация: Netherlands - Amsterdam
- Тариф: AMS-CLOUD-60
- Краткое описание тарифа: 4 vCore, 4 Gb ram, 1 Gbit/s
- Цена в месяц: 4.99$
- Оплачен до: 19 апреля
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

# Server Metrics 2026-03-20 02:45:34 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.24

telemt_uptime_seconds 34079.1 (9h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 634246
telemt_connections_bad_total 40535
telemt_connections_current 828
telemt_connections_me_current 828
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 14072
telemt_upstream_connect_attempt_total 6992
telemt_upstream_connect_success_total 6905
telemt_upstream_connect_fail_total 87
telemt_upstream_connect_attempts_per_request{bucket="1"} 6992
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3922
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2955
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 28
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 87
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 24
telemt_me_reconnect_attempts_total 4135
telemt_me_reconnect_success_total 4096
telemt_me_reader_eof_total 4328
telemt_me_idle_close_by_peer_total 4327
telemt_me_route_drop_no_conn_total 178888
telemt_me_route_drop_channel_closed_total 58
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 502733
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2386
telemt_desync_full_logged_total 862
telemt_desync_suppressed_total 1524
telemt_desync_frames_bucket_total{bucket="1_2"} 490
telemt_desync_frames_bucket_total{bucket="3_10"} 854
telemt_desync_frames_bucket_total{bucket="gt_10"} 1042
telemt_pool_swap_total 37
telemt_me_writer_close_signal_drop_total 40
telemt_me_writer_removed_unexpected_total 4131
telemt_me_writer_restored_same_endpoint_total 4083
telemt_me_writer_restored_fallback_total 13
telemt_me_no_writer_failfast_total 20
telemt_me_async_recovery_trigger_total 447
telemt_me_writer_removed_unexpected_minus_restored_total 35
telemt_user_connections_total{user="hello"} 504167
telemt_user_connections_current{user="hello"} 828
telemt_user_octets_from_client{user="hello"} 30490050228 (28.40 GB)
telemt_user_octets_to_client{user="hello"} 175219018505 (163.19 GB)
telemt_user_msgs_from_client{user="hello"} 2449
telemt_user_msgs_to_client{user="hello"} 3730
telemt_user_unique_ips_current{user="hello"} 337
telemt_user_unique_ips_recent_window{user="hello"} 115
```

## psb.hosting

```
telemt 3.3.24

telemt_uptime_seconds 50533.7 (14h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3106270
telemt_connections_bad_total 148191
telemt_connections_current 1679
telemt_connections_me_current 1679
telemt_handshake_timeouts_total 68305
telemt_upstream_connect_attempt_total 9964
telemt_upstream_connect_success_total 9788
telemt_upstream_connect_fail_total 175
telemt_upstream_connect_attempts_per_request{bucket="1"} 9963
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5607
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4122
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 59
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 175
telemt_me_keepalive_timeout_total 46
telemt_me_reconnect_attempts_total 10271
telemt_me_reconnect_success_total 6024
telemt_me_reader_eof_total 6445
telemt_me_idle_close_by_peer_total 6445
telemt_me_route_drop_no_conn_total 1526248
telemt_me_route_drop_channel_closed_total 12
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2650304
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 11319
telemt_desync_full_logged_total 3738
telemt_desync_suppressed_total 7581
telemt_desync_frames_bucket_total{bucket="1_2"} 2159
telemt_desync_frames_bucket_total{bucket="3_10"} 4426
telemt_desync_frames_bucket_total{bucket="gt_10"} 4734
telemt_pool_swap_total 44
telemt_pool_stale_pick_total 2
telemt_me_writer_close_signal_drop_total 53
telemt_me_writer_removed_unexpected_total 6227
telemt_me_refill_failed_total 131
telemt_me_writer_restored_same_endpoint_total 5969
telemt_me_writer_restored_fallback_total 55
telemt_me_no_writer_failfast_total 13
telemt_me_async_recovery_trigger_total 631
telemt_me_writer_removed_unexpected_minus_restored_total 203
telemt_user_connections_total{user="hello"} 2650061
telemt_user_connections_current{user="hello"} 1679
telemt_user_octets_from_client{user="hello"} 40342524614 (37.57 GB)
telemt_user_octets_to_client{user="hello"} 984447615182 (916.84 GB)
telemt_user_msgs_from_client{user="hello"} 3634
telemt_user_msgs_to_client{user="hello"} 2851
telemt_user_unique_ips_current{user="hello"} 749
telemt_user_unique_ips_recent_window{user="hello"} 198
```

## koara.io

```
telemt 3.3.24

telemt_uptime_seconds 50511.8 (14h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3022823
telemt_connections_bad_total 478803
telemt_connections_current 1355
telemt_connections_me_current 1355
telemt_handshake_timeouts_total 47021
telemt_upstream_connect_attempt_total 8240
telemt_upstream_connect_success_total 8182
telemt_upstream_connect_fail_total 58
telemt_upstream_connect_attempts_per_request{bucket="1"} 8240
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4149
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4016
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 17
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 58
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 6581
telemt_me_reconnect_success_total 5645
telemt_me_reader_eof_total 5931
telemt_me_idle_close_by_peer_total 5930
telemt_me_route_drop_no_conn_total 1939292
telemt_me_route_drop_channel_closed_total 173
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2087308
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7856
telemt_desync_full_logged_total 2395
telemt_desync_suppressed_total 5461
telemt_desync_frames_bucket_total{bucket="1_2"} 1923
telemt_desync_frames_bucket_total{bucket="3_10"} 2979
telemt_desync_frames_bucket_total{bucket="gt_10"} 2954
telemt_pool_swap_total 50
telemt_me_writer_close_signal_drop_total 70
telemt_me_writer_removed_unexpected_total 5702
telemt_me_refill_failed_total 28
telemt_me_writer_restored_same_endpoint_total 5644
telemt_me_writer_restored_fallback_total 1
telemt_me_async_recovery_trigger_total 5604
telemt_me_writer_removed_unexpected_minus_restored_total 57
telemt_user_connections_total{user="hello"} 2082923
telemt_user_connections_current{user="hello"} 1355
telemt_user_octets_from_client{user="hello"} 30554538480 (28.46 GB)
telemt_user_octets_to_client{user="hello"} 802845137624 (747.71 GB)
telemt_user_unique_ips_current{user="hello"} 557
telemt_user_unique_ips_recent_window{user="hello"} 153
```

## landvps.ru

```
telemt 3.3.24

telemt_uptime_seconds 50499.5 (14h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2692234
telemt_connections_bad_total 194152
telemt_connections_current 1264
telemt_connections_me_current 1264
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_demotions_total 1790
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 31942
telemt_upstream_connect_attempt_total 56111
telemt_upstream_connect_success_total 51810
telemt_upstream_connect_fail_total 4301
telemt_upstream_connect_attempts_per_request{bucket="1"} 56111
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 43467
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7786
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 25
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 532
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4301
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 8880
telemt_me_reconnect_success_total 6026
telemt_me_reader_eof_total 6273
telemt_me_idle_close_by_peer_total 6272
telemt_me_route_drop_no_conn_total 1879713
telemt_me_route_drop_channel_closed_total 22
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2190877
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 17
telemt_me_endpoint_quarantine_total 2
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8463
telemt_desync_full_logged_total 2690
telemt_desync_suppressed_total 5773
telemt_desync_frames_bucket_total{bucket="1_2"} 2079
telemt_desync_frames_bucket_total{bucket="3_10"} 3081
telemt_desync_frames_bucket_total{bucket="gt_10"} 3303
telemt_pool_swap_total 37
telemt_me_writer_close_signal_drop_total 478
telemt_me_writer_removed_unexpected_total 6662
telemt_me_refill_failed_total 61
telemt_me_writer_restored_same_endpoint_total 6022
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 402
telemt_me_writer_removed_unexpected_minus_restored_total 636
telemt_user_connections_total{user="hello"} 2232953
telemt_user_connections_current{user="hello"} 1264
telemt_user_octets_from_client{user="hello"} 36182457397 (33.70 GB)
telemt_user_octets_to_client{user="hello"} 632793789997 (589.34 GB)
telemt_user_msgs_from_client{user="hello"} 240837
telemt_user_msgs_to_client{user="hello"} 1741640
telemt_user_unique_ips_current{user="hello"} 492
telemt_user_unique_ips_recent_window{user="hello"} 137
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 104222.8 (28h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6348920
telemt_connections_bad_total 1052980
telemt_connections_current 1384
telemt_connections_me_current 1384
telemt_relay_adaptive_promotions_total 29
telemt_relay_adaptive_demotions_total 4345
telemt_relay_adaptive_hard_promotions_total 27
telemt_handshake_timeouts_total 114738
telemt_upstream_connect_attempt_total 128197
telemt_upstream_connect_success_total 94909
telemt_upstream_connect_fail_total 33288
telemt_upstream_connect_attempts_per_request{bucket="1"} 128197
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 80662
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12811
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1436
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 33288
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 118
telemt_me_reconnect_attempts_total 79081
telemt_me_reconnect_success_total 13409
telemt_me_reader_eof_total 14437
telemt_me_idle_close_by_peer_total 14423
telemt_me_route_drop_no_conn_total 2816670
telemt_me_route_drop_channel_closed_total 18
telemt_me_route_drop_queue_full_total 10
telemt_me_route_drop_queue_full_profile_total{profile="high"} 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4509247
telemt_me_writer_pick_total{mode="p2c",result="full"} 8278
telemt_me_writer_pick_total{mode="p2c",result="closed"} 806
telemt_me_writer_pick_blocking_fallback_total 9050
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 19710
telemt_desync_full_logged_total 6254
telemt_desync_suppressed_total 13456
telemt_desync_frames_bucket_total{bucket="1_2"} 3476
telemt_desync_frames_bucket_total{bucket="3_10"} 8124
telemt_desync_frames_bucket_total{bucket="gt_10"} 8110
telemt_pool_swap_total 91
telemt_me_writer_removed_unexpected_total 13720
telemt_me_refill_failed_total 2047
telemt_me_writer_restored_same_endpoint_total 13384
telemt_me_writer_restored_fallback_total 25
telemt_me_no_writer_failfast_total 1489
telemt_me_async_recovery_trigger_total 7328
telemt_me_writer_removed_unexpected_minus_restored_total 311
telemt_user_connections_total{user="hello"} 4584465
telemt_user_connections_current{user="hello"} 1384
telemt_user_octets_from_client{user="hello"} 73124373880 (68.10 GB)
telemt_user_octets_to_client{user="hello"} 1767042531988 (1.61 TB)
telemt_user_msgs_from_client{user="hello"} 754082
telemt_user_msgs_to_client{user="hello"} 3090177
telemt_user_unique_ips_current{user="hello"} 585
telemt_user_unique_ips_recent_window{user="hello"} 173
```

## hostvds.com

```
telemt 3.3.24

telemt_uptime_seconds 50462.8 (14h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 872427
telemt_connections_bad_total 81122
telemt_connections_current 626
telemt_connections_me_current 626
telemt_relay_adaptive_promotions_total 29
telemt_relay_adaptive_hard_promotions_total 29
telemt_handshake_timeouts_total 13156
telemt_upstream_connect_attempt_total 13769
telemt_upstream_connect_success_total 13439
telemt_upstream_connect_fail_total 330
telemt_upstream_connect_attempts_per_request{bucket="1"} 13769
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5579
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7019
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 180
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 661
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 330
telemt_me_keepalive_failed_total 58
telemt_me_keepalive_timeout_total 546
telemt_me_reconnect_attempts_total 6736
telemt_me_reconnect_success_total 6627
telemt_me_reader_eof_total 7008
telemt_me_idle_close_by_peer_total 7005
telemt_me_route_drop_no_conn_total 472408
telemt_me_route_drop_channel_closed_total 144
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 585597
telemt_me_writer_pick_total{mode="p2c",result="success_fallback"} 881
telemt_me_writer_pick_total{mode="p2c",result="full"} 7065
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_writer_pick_blocking_fallback_total 8012
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1404
telemt_desync_full_logged_total 529
telemt_desync_suppressed_total 875
telemt_desync_frames_bucket_total{bucket="1_2"} 219
telemt_desync_frames_bucket_total{bucket="3_10"} 582
telemt_desync_frames_bucket_total{bucket="gt_10"} 603
telemt_pool_swap_total 41
telemt_pool_stale_pick_total 219
telemt_me_writer_close_signal_drop_total 151
telemt_me_writer_close_signal_channel_full_total 1
telemt_me_writer_removed_unexpected_total 6689
telemt_me_writer_restored_same_endpoint_total 6618
telemt_me_writer_restored_fallback_total 9
telemt_me_no_writer_failfast_total 1203
telemt_me_async_recovery_trigger_total 1464
telemt_me_writer_removed_unexpected_minus_restored_total 62
telemt_user_connections_total{user="hello"} 726886
telemt_user_connections_current{user="hello"} 626
telemt_user_octets_from_client{user="hello"} 7681111067 (7.15 GB)
telemt_user_octets_to_client{user="hello"} 146572993778 (136.51 GB)
telemt_user_msgs_from_client{user="hello"} 11096
telemt_user_msgs_to_client{user="hello"} 16837
telemt_user_unique_ips_current{user="hello"} 158
telemt_user_unique_ips_recent_window{user="hello"} 123
```

## 4vps.su

```
telemt 3.3.24

telemt_uptime_seconds 50464.2 (14h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2088637
telemt_connections_bad_total 123019
telemt_connections_current 1366
telemt_connections_me_current 1366
telemt_handshake_timeouts_total 38373
telemt_upstream_connect_attempt_total 9054
telemt_upstream_connect_success_total 8991
telemt_upstream_connect_fail_total 63
telemt_upstream_connect_attempts_per_request{bucket="1"} 9054
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4847
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4107
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 37
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 63
telemt_me_keepalive_timeout_total 8
telemt_me_reconnect_attempts_total 6507
telemt_me_reconnect_success_total 6462
telemt_me_reader_eof_total 6824
telemt_me_idle_close_by_peer_total 6824
telemt_me_route_drop_no_conn_total 758863
telemt_me_route_drop_channel_closed_total 5
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1783454
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 9365
telemt_desync_full_logged_total 3018
telemt_desync_suppressed_total 6347
telemt_desync_frames_bucket_total{bucket="1_2"} 1783
telemt_desync_frames_bucket_total{bucket="3_10"} 3279
telemt_desync_frames_bucket_total{bucket="gt_10"} 4303
telemt_pool_swap_total 50
telemt_me_writer_close_signal_drop_total 41
telemt_me_writer_removed_unexpected_total 6557
telemt_me_writer_restored_same_endpoint_total 6445
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 140
telemt_me_writer_removed_unexpected_minus_restored_total 95
telemt_user_connections_total{user="hello"} 1782562
telemt_user_connections_current{user="hello"} 1366
telemt_user_octets_from_client{user="hello"} 30340759456 (28.26 GB)
telemt_user_octets_to_client{user="hello"} 910990653512 (848.43 GB)
telemt_user_unique_ips_current{user="hello"} 544
telemt_user_unique_ips_recent_window{user="hello"} 127
```