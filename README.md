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

# Server Metrics 2026-03-14 13:14:14 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 193253.5 (53h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 770290
telemt_connections_bad_total 37343
telemt_handshake_timeouts_total 14616
telemt_upstream_connect_attempt_total 48891
telemt_upstream_connect_success_total 48647
telemt_upstream_connect_fail_total 244
telemt_upstream_connect_attempts_per_request{bucket="1"} 48891
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 22282
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 26211
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 154
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 244
telemt_me_keepalive_failed_total 4
telemt_me_keepalive_timeout_total 6364
telemt_me_reconnect_attempts_total 44416
telemt_me_reconnect_success_total 38642
telemt_me_reader_eof_total 41311
telemt_me_idle_close_by_peer_total 41310
telemt_me_route_drop_no_conn_total 253457
telemt_me_route_drop_channel_closed_total 41
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 660619
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2893
telemt_desync_full_logged_total 965
telemt_desync_suppressed_total 1928
telemt_desync_frames_bucket_total{bucket="1_2"} 588
telemt_desync_frames_bucket_total{bucket="3_10"} 1099
telemt_desync_frames_bucket_total{bucket="gt_10"} 1206
telemt_pool_swap_total 176
telemt_me_writer_removed_unexpected_total 39237
telemt_me_refill_failed_total 173
telemt_me_writer_restored_same_endpoint_total 38622
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 595
telemt_user_connections_total{user="hello"} 660523
telemt_user_connections_current{user="hello"} 384
telemt_user_octets_from_client{user="hello"} 18212269846 (16.96 GB)
telemt_user_octets_to_client{user="hello"} 312994490856 (291.50 GB)
telemt_user_msgs_from_client{user="hello"} 2142
telemt_user_msgs_to_client{user="hello"} 2404
telemt_user_unique_ips_current{user="hello"} 116
telemt_user_unique_ips_recent_window{user="hello"} 47
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 193146.2 (53h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 379287
telemt_connections_bad_total 2881
telemt_handshake_timeouts_total 3389
telemt_upstream_connect_attempt_total 159081
telemt_upstream_connect_success_total 157664
telemt_upstream_connect_fail_total 1417
telemt_upstream_connect_attempts_per_request{bucket="1"} 159081
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 114247
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 40876
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2540
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1417
telemt_me_keepalive_timeout_total 5751
telemt_me_reconnect_attempts_total 199695
telemt_me_reconnect_success_total 42931
telemt_me_reader_eof_total 48937
telemt_me_idle_close_by_peer_total 48937
telemt_me_route_drop_no_conn_total 131096
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 252462
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 48
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 33
telemt_desync_full_logged_total 11
telemt_desync_suppressed_total 22
telemt_desync_frames_bucket_total{bucket="1_2"} 2
telemt_desync_frames_bucket_total{bucket="3_10"} 12
telemt_desync_frames_bucket_total{bucket="gt_10"} 19
telemt_pool_swap_total 38
telemt_me_writer_removed_unexpected_total 48249
telemt_me_refill_failed_total 4890
telemt_me_writer_restored_same_endpoint_total 42912
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 5318
telemt_user_connections_total{user="hello"} 357355
telemt_user_connections_current{user="hello"} 161
telemt_user_octets_from_client{user="hello"} 3655199315 (3.40 GB)
telemt_user_octets_to_client{user="hello"} 114351562750 (106.50 GB)
telemt_user_msgs_from_client{user="hello"} 1713995
telemt_user_msgs_to_client{user="hello"} 9567945
telemt_user_unique_ips_current{user="hello"} 46
telemt_user_unique_ips_recent_window{user="hello"} 18
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 193109.7 (53h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 436390
telemt_connections_bad_total 3355
telemt_handshake_timeouts_total 36834
telemt_upstream_connect_attempt_total 51956
telemt_upstream_connect_success_total 51947
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 51956
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 23938
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 27929
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 73
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 4388
telemt_me_reconnect_attempts_total 44689
telemt_me_reconnect_success_total 42211
telemt_me_reader_eof_total 45319
telemt_me_idle_close_by_peer_total 45319
telemt_me_route_drop_no_conn_total 160511
telemt_me_route_drop_channel_closed_total 23
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 380479
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 147
telemt_desync_full_logged_total 67
telemt_desync_suppressed_total 80
telemt_desync_frames_bucket_total{bucket="1_2"} 15
telemt_desync_frames_bucket_total{bucket="3_10"} 53
telemt_desync_frames_bucket_total{bucket="gt_10"} 79
telemt_pool_swap_total 177
telemt_me_writer_removed_unexpected_total 42748
telemt_me_refill_failed_total 69
telemt_me_writer_restored_same_endpoint_total 42190
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 537
telemt_user_connections_total{user="hello"} 380205
telemt_user_connections_current{user="hello"} 163
telemt_user_octets_from_client{user="hello"} 16309858278 (15.19 GB)
telemt_user_octets_to_client{user="hello"} 172960751643 (161.08 GB)
telemt_user_msgs_from_client{user="hello"} 166
telemt_user_msgs_to_client{user="hello"} 712
telemt_user_unique_ips_current{user="hello"} 60
telemt_user_unique_ips_recent_window{user="hello"} 21
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 193085.2 (53h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 557762
telemt_connections_bad_total 16791
telemt_handshake_timeouts_total 5394
telemt_upstream_connect_attempt_total 81854
telemt_upstream_connect_success_total 71106
telemt_upstream_connect_fail_total 10748
telemt_upstream_connect_attempts_per_request{bucket="1"} 81854
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 41272
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 29430
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 395
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10748
telemt_me_keepalive_timeout_total 5883
telemt_me_reconnect_attempts_total 163423
telemt_me_reconnect_success_total 42442
telemt_me_reader_eof_total 47556
telemt_me_idle_close_by_peer_total 47548
telemt_me_route_drop_no_conn_total 201527
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 479001
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 39
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2246
telemt_desync_full_logged_total 661
telemt_desync_suppressed_total 1585
telemt_desync_frames_bucket_total{bucket="1_2"} 524
telemt_desync_frames_bucket_total{bucket="3_10"} 850
telemt_desync_frames_bucket_total{bucket="gt_10"} 872
telemt_pool_swap_total 54
telemt_me_writer_removed_unexpected_total 46706
telemt_me_refill_failed_total 3772
telemt_me_writer_restored_same_endpoint_total 42432
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 4264
telemt_user_connections_total{user="hello"} 497859
telemt_user_connections_current{user="hello"} 246
telemt_user_octets_from_client{user="hello"} 10453273787 (9.74 GB)
telemt_user_octets_to_client{user="hello"} 207648055688 (193.39 GB)
telemt_user_msgs_from_client{user="hello"} 459818
telemt_user_msgs_to_client{user="hello"} 871707
telemt_user_unique_ips_current{user="hello"} 71
telemt_user_unique_ips_recent_window{user="hello"} 34
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 143256.8 (39h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 245201
telemt_connections_bad_total 39090
telemt_handshake_timeouts_total 2244
telemt_upstream_connect_attempt_total 50326
telemt_upstream_connect_success_total 49814
telemt_upstream_connect_fail_total 512
telemt_upstream_connect_attempts_per_request{bucket="1"} 50326
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 24805
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 24832
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 177
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 512
telemt_me_keepalive_timeout_total 3169
telemt_me_reconnect_attempts_total 59947
telemt_me_reconnect_success_total 37687
telemt_me_reader_eof_total 40418
telemt_me_idle_close_by_peer_total 40418
telemt_me_route_drop_no_conn_total 75210
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 192244
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 10
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 876
telemt_desync_full_logged_total 207
telemt_desync_suppressed_total 669
telemt_desync_frames_bucket_total{bucket="1_2"} 152
telemt_desync_frames_bucket_total{bucket="3_10"} 395
telemt_desync_frames_bucket_total{bucket="gt_10"} 329
telemt_pool_swap_total 103
telemt_me_writer_removed_unexpected_total 38734
telemt_me_refill_failed_total 691
telemt_me_writer_restored_same_endpoint_total 37669
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 42
telemt_me_writer_removed_unexpected_minus_restored_total 1047
telemt_user_connections_total{user="hello"} 197079
telemt_user_connections_current{user="hello"} 58
telemt_user_octets_from_client{user="hello"} 2818792655 (2.63 GB)
telemt_user_octets_to_client{user="hello"} 89675861904 (83.52 GB)
telemt_user_msgs_from_client{user="hello"} 51153
telemt_user_msgs_to_client{user="hello"} 221810
telemt_user_unique_ips_current{user="hello"} 27
telemt_user_unique_ips_recent_window{user="hello"} 42
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 193041.5 (53h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1131943
telemt_connections_bad_total 38210
telemt_handshake_timeouts_total 27495
telemt_upstream_connect_attempt_total 40275
telemt_upstream_connect_success_total 40064
telemt_upstream_connect_fail_total 211
telemt_upstream_connect_attempts_per_request{bucket="1"} 40275
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19002
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21021
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 41
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 211
telemt_me_keepalive_timeout_total 5272
telemt_me_reconnect_attempts_total 35205
telemt_me_reconnect_success_total 30504
telemt_me_reader_eof_total 32685
telemt_me_idle_close_by_peer_total 32682
telemt_me_route_drop_no_conn_total 533809
telemt_me_route_drop_channel_closed_total 39
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1049912
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 817
telemt_desync_full_logged_total 270
telemt_desync_suppressed_total 547
telemt_desync_frames_bucket_total{bucket="1_2"} 260
telemt_desync_frames_bucket_total{bucket="3_10"} 271
telemt_desync_frames_bucket_total{bucket="gt_10"} 286
telemt_pool_swap_total 179
telemt_me_writer_removed_unexpected_total 31036
telemt_me_refill_failed_total 141
telemt_me_writer_restored_same_endpoint_total 30497
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 532
telemt_user_connections_total{user="hello"} 1022531
telemt_user_connections_current{user="hello"} 494
telemt_user_octets_from_client{user="hello"} 21924593224 (20.42 GB)
telemt_user_octets_to_client{user="hello"} 517599584592 (482.05 GB)
telemt_user_unique_ips_current{user="hello"} 192
telemt_user_unique_ips_recent_window{user="hello"} 63
```