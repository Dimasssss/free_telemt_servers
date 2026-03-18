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

# Server Metrics 2026-03-18 16:39:50 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 4468.7 (1h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 143801
telemt_connections_bad_total 11722
telemt_handshake_timeouts_total 4912
telemt_upstream_connect_attempt_total 578
telemt_upstream_connect_success_total 578
telemt_upstream_connect_attempts_per_request{bucket="1"} 578
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 280
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 276
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 22
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 336
telemt_me_reconnect_success_total 334
telemt_me_reader_eof_total 336
telemt_me_idle_close_by_peer_total 336
telemt_me_route_drop_no_conn_total 80195
telemt_me_route_drop_channel_closed_total 30
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 117540
telemt_me_writer_pick_total{mode="p2c",result="full"} 116
telemt_me_writer_pick_total{mode="p2c",result="closed"} 293
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 708
telemt_desync_full_logged_total 205
telemt_desync_suppressed_total 503
telemt_desync_frames_bucket_total{bucket="1_2"} 178
telemt_desync_frames_bucket_total{bucket="3_10"} 233
telemt_desync_frames_bucket_total{bucket="gt_10"} 297
telemt_pool_swap_total 4
telemt_me_writer_removed_unexpected_total 347
telemt_me_writer_restored_same_endpoint_total 323
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 75
telemt_me_writer_removed_unexpected_minus_restored_total 13
telemt_user_connections_total{user="hello"} 117490
telemt_user_connections_current{user="hello"} 1474
telemt_user_octets_from_client{user="hello"} 1627929060 (1.52 GB)
telemt_user_octets_to_client{user="hello"} 41546182656 (38.69 GB)
telemt_user_unique_ips_current{user="hello"} 500
telemt_user_unique_ips_recent_window{user="hello"} 203
```

## psb.hosting

```
telemt 3.3.22

telemt_uptime_seconds 9297.6 (2h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 971810
telemt_connections_bad_total 60937
telemt_connections_current 3728
telemt_connections_me_current 3728
telemt_handshake_timeouts_total 15062
telemt_upstream_connect_attempt_total 1734
telemt_upstream_connect_success_total 1725
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 1734
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 955
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 758
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 12
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_reconnect_attempts_total 1220
telemt_me_reconnect_success_total 1210
telemt_me_reader_eof_total 1155
telemt_me_idle_close_by_peer_total 1154
telemt_me_route_drop_no_conn_total 986651
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 848239
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 14
telemt_me_endpoint_quarantine_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2367
telemt_desync_full_logged_total 738
telemt_desync_suppressed_total 1629
telemt_desync_frames_bucket_total{bucket="1_2"} 475
telemt_desync_frames_bucket_total{bucket="3_10"} 956
telemt_desync_frames_bucket_total{bucket="gt_10"} 936
telemt_pool_swap_total 6
telemt_me_writer_removed_unexpected_total 1142
telemt_me_writer_restored_same_endpoint_total 1208
telemt_me_writer_restored_fallback_total 2
telemt_me_async_recovery_trigger_total 2874
telemt_user_connections_total{user="hello"} 847403
telemt_user_connections_current{user="hello"} 3728
telemt_user_octets_from_client{user="hello"} 10378655520 (9.67 GB)
telemt_user_octets_to_client{user="hello"} 238699746056 (222.31 GB)
telemt_user_unique_ips_current{user="hello"} 1153
telemt_user_unique_ips_recent_window{user="hello"} 475
```

## koara.io

```
telemt 3.3.22

telemt_uptime_seconds 9225.8 (2h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 647547
telemt_connections_bad_total 44170
telemt_connections_current 3230
telemt_connections_me_current 3230
telemt_handshake_timeouts_total 14284
telemt_upstream_connect_attempt_total 1330
telemt_upstream_connect_success_total 1324
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 1330
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 694
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 619
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_keepalive_timeout_total 29
telemt_me_reconnect_attempts_total 818
telemt_me_reconnect_success_total 808
telemt_me_reader_eof_total 849
telemt_me_idle_close_by_peer_total 849
telemt_me_route_drop_no_conn_total 333024
telemt_me_route_drop_channel_closed_total 30
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 548573
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2231
telemt_desync_full_logged_total 638
telemt_desync_suppressed_total 1593
telemt_desync_frames_bucket_total{bucket="1_2"} 499
telemt_desync_frames_bucket_total{bucket="3_10"} 842
telemt_desync_frames_bucket_total{bucket="gt_10"} 890
telemt_pool_swap_total 9
telemt_me_writer_removed_unexpected_total 835
telemt_me_writer_restored_same_endpoint_total 791
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 652
telemt_me_writer_removed_unexpected_minus_restored_total 27
telemt_user_connections_total{user="hello"} 548307
telemt_user_connections_current{user="hello"} 3230
telemt_user_octets_from_client{user="hello"} 10138453220 (9.44 GB)
telemt_user_octets_to_client{user="hello"} 219276752604 (204.22 GB)
telemt_user_unique_ips_current{user="hello"} 975
telemt_user_unique_ips_recent_window{user="hello"} 428
```

## landvps.ru

```
telemt 3.3.22

telemt_uptime_seconds 9940.0 (2h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 911925
telemt_connections_bad_total 19354
telemt_connections_current 2648
telemt_connections_me_current 2648
telemt_handshake_timeouts_total 11915
telemt_upstream_connect_attempt_total 1577
telemt_upstream_connect_success_total 1565
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 1577
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 811
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 742
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 12
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_keepalive_timeout_total 6
telemt_me_reconnect_attempts_total 1045
telemt_me_reconnect_success_total 1035
telemt_me_reader_eof_total 1040
telemt_me_idle_close_by_peer_total 1039
telemt_me_route_drop_no_conn_total 1469464
telemt_me_route_drop_channel_closed_total 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 819909
telemt_me_writer_pick_total{mode="p2c",result="full"} 30
telemt_me_writer_pick_total{mode="p2c",result="closed"} 61
telemt_me_endpoint_quarantine_total 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3189
telemt_desync_full_logged_total 801
telemt_desync_suppressed_total 2388
telemt_desync_frames_bucket_total{bucket="1_2"} 728
telemt_desync_frames_bucket_total{bucket="3_10"} 1451
telemt_desync_frames_bucket_total{bucket="gt_10"} 1010
telemt_pool_swap_total 7
telemt_me_writer_removed_unexpected_total 1027
telemt_me_writer_restored_same_endpoint_total 1024
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 1000
telemt_user_connections_total{user="hello"} 819868
telemt_user_connections_current{user="hello"} 2648
telemt_user_octets_from_client{user="hello"} 7504701116 (6.99 GB)
telemt_user_octets_to_client{user="hello"} 151666297580 (141.25 GB)
telemt_user_unique_ips_current{user="hello"} 832
telemt_user_unique_ips_recent_window{user="hello"} 407
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 4454.7 (1h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 352886
telemt_connections_bad_total 71459
telemt_handshake_timeouts_total 3514
telemt_upstream_connect_attempt_total 814
telemt_upstream_connect_success_total 787
telemt_upstream_connect_fail_total 27
telemt_upstream_connect_attempts_per_request{bucket="1"} 814
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 452
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 330
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 27
telemt_me_keepalive_timeout_total 13
telemt_me_reconnect_attempts_total 1539
telemt_me_reconnect_success_total 540
telemt_me_reader_eof_total 550
telemt_me_idle_close_by_peer_total 550
telemt_me_route_drop_no_conn_total 142285
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 250492
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 870
telemt_desync_full_logged_total 296
telemt_desync_suppressed_total 574
telemt_desync_frames_bucket_total{bucket="1_2"} 139
telemt_desync_frames_bucket_total{bucket="3_10"} 279
telemt_desync_frames_bucket_total{bucket="gt_10"} 452
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 573
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 514
telemt_me_writer_restored_fallback_total 26
telemt_me_async_recovery_trigger_total 786
telemt_me_writer_removed_unexpected_minus_restored_total 33
telemt_user_connections_total{user="hello"} 250170
telemt_user_connections_current{user="hello"} 3095
telemt_user_octets_from_client{user="hello"} 3789653696 (3.53 GB)
telemt_user_octets_to_client{user="hello"} 96002442412 (89.41 GB)
telemt_user_unique_ips_current{user="hello"} 1028
telemt_user_unique_ips_recent_window{user="hello"} 424
```

## hostvds.com

```
telemt 3.3.22

telemt_uptime_seconds 9389.9 (2h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 176801
telemt_connections_bad_total 7403
telemt_connections_current 811
telemt_connections_me_current 811
telemt_relay_adaptive_promotions_total 18
telemt_relay_adaptive_hard_promotions_total 18
telemt_handshake_timeouts_total 1670
telemt_upstream_connect_attempt_total 5842
telemt_upstream_connect_success_total 5831
telemt_upstream_connect_fail_total 11
telemt_upstream_connect_attempts_per_request{bucket="1"} 5842
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3209
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2579
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 28
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 15
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 11
telemt_me_reconnect_attempts_total 330953
telemt_me_reconnect_success_total 1492
telemt_me_reader_eof_total 1446
telemt_me_idle_close_by_peer_total 1446
telemt_me_route_drop_no_conn_total 98038
telemt_me_route_drop_channel_closed_total 34
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 155679
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 9
telemt_me_endpoint_quarantine_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 343
telemt_desync_full_logged_total 121
telemt_desync_suppressed_total 222
telemt_desync_frames_bucket_total{bucket="1_2"} 57
telemt_desync_frames_bucket_total{bucket="3_10"} 138
telemt_desync_frames_bucket_total{bucket="gt_10"} 148
telemt_pool_swap_total 6
telemt_me_writer_removed_unexpected_total 1425
telemt_me_refill_failed_total 10448
telemt_me_writer_restored_same_endpoint_total 1481
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 40876
telemt_user_connections_total{user="hello"} 159405
telemt_user_connections_current{user="hello"} 811
telemt_user_octets_from_client{user="hello"} 2381833833 (2.22 GB)
telemt_user_octets_to_client{user="hello"} 34014049689 (31.68 GB)
telemt_user_msgs_from_client{user="hello"} 38712
telemt_user_msgs_to_client{user="hello"} 31668
telemt_user_unique_ips_current{user="hello"} 300
telemt_user_unique_ips_recent_window{user="hello"} 131
```

## 4vps.su

```
telemt 3.3.22

telemt_uptime_seconds 8459.2 (2h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 513774
telemt_connections_bad_total 18887
telemt_connections_current 2771
telemt_connections_me_current 2771
telemt_handshake_timeouts_total 9491
telemt_upstream_connect_attempt_total 1617
telemt_upstream_connect_success_total 1616
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 1617
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 880
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 727
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 10
telemt_me_reconnect_attempts_total 16654
telemt_me_reconnect_success_total 1143
telemt_me_reader_eof_total 1105
telemt_me_idle_close_by_peer_total 1105
telemt_me_route_drop_no_conn_total 346103
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="base"} 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 445009
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1375
telemt_desync_full_logged_total 499
telemt_desync_suppressed_total 876
telemt_desync_frames_bucket_total{bucket="1_2"} 291
telemt_desync_frames_bucket_total{bucket="3_10"} 484
telemt_desync_frames_bucket_total{bucket="gt_10"} 600
telemt_pool_swap_total 6
telemt_me_writer_removed_unexpected_total 1100
telemt_me_refill_failed_total 741
telemt_me_writer_restored_same_endpoint_total 1082
telemt_me_writer_restored_fallback_total 61
telemt_me_async_recovery_trigger_total 9552
telemt_user_connections_total{user="hello"} 444097
telemt_user_connections_current{user="hello"} 2771
telemt_user_octets_from_client{user="hello"} 7742052452 (7.21 GB)
telemt_user_octets_to_client{user="hello"} 197438349528 (183.88 GB)
telemt_user_unique_ips_current{user="hello"} 842
telemt_user_unique_ips_recent_window{user="hello"} 332
```