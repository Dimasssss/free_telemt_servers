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

# Server Metrics 2026-03-16 07:08:16 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.18

telemt_uptime_seconds 118426.6 (32h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 538796
telemt_connections_bad_total 5702
telemt_handshake_timeouts_total 18963
telemt_upstream_connect_attempt_total 27882
telemt_upstream_connect_success_total 27751
telemt_upstream_connect_fail_total 131
telemt_upstream_connect_attempts_per_request{bucket="1"} 27882
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12321
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15383
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 38
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 131
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 51
telemt_me_reconnect_attempts_total 25326
telemt_me_reconnect_success_total 21892
telemt_me_reader_eof_total 23424
telemt_me_idle_close_by_peer_total 23424
telemt_me_route_drop_no_conn_total 519872
telemt_me_route_drop_channel_closed_total 83
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 537022
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2604
telemt_desync_full_logged_total 1037
telemt_desync_suppressed_total 1567
telemt_desync_frames_bucket_total{bucket="1_2"} 531
telemt_desync_frames_bucket_total{bucket="3_10"} 1007
telemt_desync_frames_bucket_total{bucket="gt_10"} 1066
telemt_pool_swap_total 115
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 22240
telemt_me_refill_failed_total 104
telemt_me_writer_restored_same_endpoint_total 21858
telemt_me_writer_restored_fallback_total 34
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 348
telemt_user_connections_total{user="hello"} 475850
telemt_user_connections_current{user="hello"} 519
telemt_user_octets_from_client{user="hello"} 9329969400 (8.69 GB)
telemt_user_octets_to_client{user="hello"} 314180758636 (292.60 GB)
telemt_user_unique_ips_current{user="hello"} 154
telemt_user_unique_ips_recent_window{user="hello"} 70
```

## psb.hosting

```
telemt 3.3.18

telemt_uptime_seconds 118434.2 (32h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 213472
telemt_connections_bad_total 3154
telemt_handshake_timeouts_total 15035
telemt_upstream_connect_attempt_total 31827
telemt_upstream_connect_success_total 31752
telemt_upstream_connect_fail_total 75
telemt_upstream_connect_attempts_per_request{bucket="1"} 31827
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13785
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17353
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 614
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 75
telemt_me_keepalive_timeout_total 1307
telemt_me_reconnect_attempts_total 32391
telemt_me_reconnect_success_total 25472
telemt_me_reader_eof_total 27290
telemt_me_idle_close_by_peer_total 27289
telemt_me_route_drop_no_conn_total 105820
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 187637
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 79
telemt_desync_full_logged_total 24
telemt_desync_suppressed_total 55
telemt_desync_frames_bucket_total{bucket="1_2"} 11
telemt_desync_frames_bucket_total{bucket="3_10"} 32
telemt_desync_frames_bucket_total{bucket="gt_10"} 36
telemt_pool_swap_total 105
telemt_me_writer_removed_unexpected_total 26032
telemt_me_refill_failed_total 208
telemt_me_writer_restored_same_endpoint_total 25456
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 560
telemt_user_connections_total{user="hello"} 187171
telemt_user_connections_current{user="hello"} 249
telemt_user_octets_from_client{user="hello"} 4339985969 (4.04 GB)
telemt_user_octets_to_client{user="hello"} 102549253028 (95.51 GB)
telemt_user_msgs_from_client{user="hello"} 721
telemt_user_msgs_to_client{user="hello"} 1482
telemt_user_unique_ips_current{user="hello"} 76
telemt_user_unique_ips_recent_window{user="hello"} 30
```

## koara.io

```
telemt 3.3.18

telemt_uptime_seconds 118426.4 (32h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 233290
telemt_connections_bad_total 5728
telemt_handshake_timeouts_total 4592
telemt_upstream_connect_attempt_total 33052
telemt_upstream_connect_success_total 33044
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 33052
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14340
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18650
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 54
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 39
telemt_me_reconnect_attempts_total 34518
telemt_me_reconnect_success_total 27119
telemt_me_reader_eof_total 29198
telemt_me_idle_close_by_peer_total 29197
telemt_me_route_drop_no_conn_total 81684
telemt_me_route_drop_channel_closed_total 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 185294
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 12
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 78
telemt_desync_full_logged_total 29
telemt_desync_suppressed_total 49
telemt_desync_frames_bucket_total{bucket="1_2"} 7
telemt_desync_frames_bucket_total{bucket="3_10"} 36
telemt_desync_frames_bucket_total{bucket="gt_10"} 35
telemt_pool_swap_total 109
telemt_me_writer_removed_unexpected_total 27612
telemt_me_refill_failed_total 227
telemt_me_writer_restored_same_endpoint_total 27111
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 493
telemt_user_connections_total{user="hello"} 185008
telemt_user_connections_current{user="hello"} 240
telemt_user_octets_from_client{user="hello"} 17275652737 (16.09 GB)
telemt_user_octets_to_client{user="hello"} 109739836084 (102.20 GB)
telemt_user_msgs_from_client{user="hello"} 7
telemt_user_msgs_to_client{user="hello"} 46
telemt_user_unique_ips_current{user="hello"} 77
telemt_user_unique_ips_recent_window{user="hello"} 23
```

## landvps.ru

```
telemt 3.3.18

telemt_uptime_seconds 118426.1 (32h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 313421
telemt_connections_bad_total 1330
telemt_handshake_timeouts_total 2856
telemt_upstream_connect_attempt_total 27487
telemt_upstream_connect_success_total 27458
telemt_upstream_connect_fail_total 29
telemt_upstream_connect_attempts_per_request{bucket="1"} 27487
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13144
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14166
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 13
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 135
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 29
telemt_me_keepalive_timeout_total 23
telemt_me_reconnect_attempts_total 21712
telemt_me_reconnect_success_total 21579
telemt_me_reader_eof_total 23049
telemt_me_idle_close_by_peer_total 23048
telemt_me_route_drop_no_conn_total 111865
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 288406
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1008
telemt_desync_full_logged_total 349
telemt_desync_suppressed_total 659
telemt_desync_frames_bucket_total{bucket="1_2"} 200
telemt_desync_frames_bucket_total{bucket="3_10"} 439
telemt_desync_frames_bucket_total{bucket="gt_10"} 369
telemt_pool_swap_total 116
telemt_me_writer_removed_unexpected_total 21855
telemt_me_writer_restored_same_endpoint_total 21568
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 276
telemt_user_connections_total{user="hello"} 288296
telemt_user_connections_current{user="hello"} 262
telemt_user_octets_from_client{user="hello"} 4713042702 (4.39 GB)
telemt_user_octets_to_client{user="hello"} 125317948308 (116.71 GB)
telemt_user_msgs_from_client{user="hello"} 25
telemt_user_msgs_to_client{user="hello"} 50
telemt_user_unique_ips_current{user="hello"} 86
telemt_user_unique_ips_recent_window{user="hello"} 45
```

## rdp-onedash.ru

```
telemt 3.3.18

telemt_uptime_seconds 93497.3 (25h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 209581
telemt_connections_bad_total 35517
telemt_handshake_timeouts_total 3607
telemt_upstream_connect_attempt_total 26646
telemt_upstream_connect_success_total 26500
telemt_upstream_connect_fail_total 146
telemt_upstream_connect_attempts_per_request{bucket="1"} 26646
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11748
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14612
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 140
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 146
telemt_me_keepalive_timeout_total 21
telemt_me_reconnect_attempts_total 116191
telemt_me_reconnect_success_total 21701
telemt_me_reader_eof_total 23060
telemt_me_idle_close_by_peer_total 23060
telemt_me_route_drop_no_conn_total 65657
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 165040
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 480
telemt_desync_full_logged_total 120
telemt_desync_suppressed_total 360
telemt_desync_frames_bucket_total{bucket="1_2"} 65
telemt_desync_frames_bucket_total{bucket="3_10"} 204
telemt_desync_frames_bucket_total{bucket="gt_10"} 211
telemt_pool_swap_total 81
telemt_me_writer_removed_unexpected_total 21877
telemt_me_refill_failed_total 3033
telemt_me_writer_restored_same_endpoint_total 21597
telemt_me_writer_restored_fallback_total 104
telemt_me_async_recovery_trigger_total 2255
telemt_me_writer_removed_unexpected_minus_restored_total 176
telemt_user_connections_total{user="hello"} 164671
telemt_user_connections_current{user="hello"} 140
telemt_user_octets_from_client{user="hello"} 2290846901 (2.13 GB)
telemt_user_octets_to_client{user="hello"} 71482987555 (66.57 GB)
telemt_user_msgs_from_client{user="hello"} 2259
telemt_user_msgs_to_client{user="hello"} 12105
telemt_user_unique_ips_current{user="hello"} 55
telemt_user_unique_ips_recent_window{user="hello"} 25
```

## hostvds.com

```
telemt 3.3.18

telemt_uptime_seconds 118425.2 (32h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 770790
telemt_connections_bad_total 66444
telemt_handshake_timeouts_total 5778
telemt_upstream_connect_attempt_total 24954
telemt_upstream_connect_success_total 24822
telemt_upstream_connect_fail_total 132
telemt_upstream_connect_attempts_per_request{bucket="1"} 24954
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11851
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12929
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 19
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 23
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 132
telemt_me_keepalive_timeout_total 62
telemt_me_reconnect_attempts_total 20273
telemt_me_reconnect_success_total 18929
telemt_me_reader_eof_total 20217
telemt_me_idle_close_by_peer_total 20217
telemt_me_route_drop_no_conn_total 630013
telemt_me_route_drop_channel_closed_total 101
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 775803
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 336
telemt_desync_full_logged_total 96
telemt_desync_suppressed_total 240
telemt_desync_frames_bucket_total{bucket="1_2"} 171
telemt_desync_frames_bucket_total{bucket="3_10"} 98
telemt_desync_frames_bucket_total{bucket="gt_10"} 67
telemt_pool_swap_total 112
telemt_me_writer_removed_unexpected_total 19193
telemt_me_refill_failed_total 38
telemt_me_writer_restored_same_endpoint_total 18902
telemt_me_writer_restored_fallback_total 27
telemt_me_async_recovery_trigger_total 40
telemt_me_writer_removed_unexpected_minus_restored_total 264
telemt_user_connections_total{user="hello"} 634449
telemt_user_connections_current{user="hello"} 464
telemt_user_octets_from_client{user="hello"} 14129712904 (13.16 GB)
telemt_user_octets_to_client{user="hello"} 382353154816 (356.09 GB)
telemt_user_unique_ips_current{user="hello"} 201
telemt_user_unique_ips_recent_window{user="hello"} 75
```