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

# Server Metrics 2026-03-13 18:13:41 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 124821.5 (34h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 527439
telemt_connections_bad_total 9528
telemt_handshake_timeouts_total 12143
telemt_upstream_connect_attempt_total 31343
telemt_upstream_connect_success_total 31188
telemt_upstream_connect_fail_total 155
telemt_upstream_connect_attempts_per_request{bucket="1"} 31343
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14172
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16920
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 96
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 155
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 3462
telemt_me_reconnect_attempts_total 29588
telemt_me_reconnect_success_total 24946
telemt_me_reader_eof_total 26637
telemt_me_idle_close_by_peer_total 26636
telemt_me_route_drop_no_conn_total 172392
telemt_me_route_drop_channel_closed_total 28
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 457687
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1468
telemt_desync_full_logged_total 508
telemt_desync_suppressed_total 960
telemt_desync_frames_bucket_total{bucket="1_2"} 322
telemt_desync_frames_bucket_total{bucket="3_10"} 539
telemt_desync_frames_bucket_total{bucket="gt_10"} 607
telemt_pool_swap_total 111
telemt_me_writer_removed_unexpected_total 25366
telemt_me_refill_failed_total 140
telemt_me_writer_restored_same_endpoint_total 24930
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 420
telemt_user_connections_total{user="hello"} 457257
telemt_user_connections_current{user="hello"} 313
telemt_user_octets_from_client{user="hello"} 8425307488 (7.85 GB)
telemt_user_octets_to_client{user="hello"} 216566863440 (201.69 GB)
telemt_user_unique_ips_current{user="hello"} 89
telemt_user_unique_ips_recent_window{user="hello"} 30
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 124714.9 (34h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 260590
telemt_connections_bad_total 1951
telemt_handshake_timeouts_total 1835
telemt_upstream_connect_attempt_total 113657
telemt_upstream_connect_success_total 112804
telemt_upstream_connect_fail_total 852
telemt_upstream_connect_attempts_per_request{bucket="1"} 113656
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 84525
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 26629
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1650
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 852
telemt_me_keepalive_timeout_total 1519
telemt_me_reconnect_attempts_total 128704
telemt_me_reconnect_success_total 26033
telemt_me_reader_eof_total 29995
telemt_me_idle_close_by_peer_total 29995
telemt_me_route_drop_no_conn_total 82896
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 166482
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 31
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 32
telemt_desync_full_logged_total 10
telemt_desync_suppressed_total 22
telemt_desync_frames_bucket_total{bucket="1_2"} 2
telemt_desync_frames_bucket_total{bucket="3_10"} 12
telemt_desync_frames_bucket_total{bucket="gt_10"} 18
telemt_pool_swap_total 26
telemt_me_writer_removed_unexpected_total 29465
telemt_me_refill_failed_total 3204
telemt_me_writer_restored_same_endpoint_total 26016
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 3432
telemt_user_connections_total{user="hello"} 246814
telemt_user_connections_current{user="hello"} 179
telemt_user_octets_from_client{user="hello"} 2570080282 (2.39 GB)
telemt_user_octets_to_client{user="hello"} 75992340870 (70.77 GB)
telemt_user_msgs_from_client{user="hello"} 1264973
telemt_user_msgs_to_client{user="hello"} 7371479
telemt_user_unique_ips_current{user="hello"} 36
telemt_user_unique_ips_recent_window{user="hello"} 26
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 124679.0 (34h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 307832
telemt_connections_bad_total 2553
telemt_handshake_timeouts_total 18435
telemt_upstream_connect_attempt_total 33245
telemt_upstream_connect_success_total 33241
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 33245
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15409
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17795
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 35
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 2688
telemt_me_reconnect_attempts_total 28198
telemt_me_reconnect_success_total 26968
telemt_me_reader_eof_total 28922
telemt_me_idle_close_by_peer_total 28922
telemt_me_route_drop_no_conn_total 110093
telemt_me_route_drop_channel_closed_total 17
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 275952
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 104
telemt_desync_full_logged_total 48
telemt_desync_suppressed_total 56
telemt_desync_frames_bucket_total{bucket="1_2"} 9
telemt_desync_frames_bucket_total{bucket="3_10"} 34
telemt_desync_frames_bucket_total{bucket="gt_10"} 61
telemt_pool_swap_total 114
telemt_me_writer_removed_unexpected_total 27271
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 26948
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 303
telemt_user_connections_total{user="hello"} 275865
telemt_user_connections_current{user="hello"} 162
telemt_user_octets_from_client{user="hello"} 10271981100 (9.57 GB)
telemt_user_octets_to_client{user="hello"} 113065453280 (105.30 GB)
telemt_user_unique_ips_current{user="hello"} 60
telemt_user_unique_ips_recent_window{user="hello"} 20
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 124654.1 (34h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 413814
telemt_connections_bad_total 15127
telemt_handshake_timeouts_total 3880
telemt_upstream_connect_attempt_total 60588
telemt_upstream_connect_success_total 50333
telemt_upstream_connect_fail_total 10255
telemt_upstream_connect_attempts_per_request{bucket="1"} 60588
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 31913
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18125
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 286
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10255
telemt_me_keepalive_timeout_total 4675
telemt_me_reconnect_attempts_total 114728
telemt_me_reconnect_success_total 25072
telemt_me_reader_eof_total 28599
telemt_me_idle_close_by_peer_total 28592
telemt_me_route_drop_no_conn_total 142769
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 345800
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 27
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1353
telemt_desync_full_logged_total 403
telemt_desync_suppressed_total 950
telemt_desync_frames_bucket_total{bucket="1_2"} 333
telemt_desync_frames_bucket_total{bucket="3_10"} 521
telemt_desync_frames_bucket_total{bucket="gt_10"} 499
telemt_pool_swap_total 31
telemt_me_writer_removed_unexpected_total 28190
telemt_me_refill_failed_total 2796
telemt_me_writer_restored_same_endpoint_total 25062
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 3118
telemt_user_connections_total{user="hello"} 364690
telemt_user_connections_current{user="hello"} 181
telemt_user_octets_from_client{user="hello"} 8388393339 (7.81 GB)
telemt_user_octets_to_client{user="hello"} 130055707992 (121.12 GB)
telemt_user_msgs_from_client{user="hello"} 459818
telemt_user_msgs_to_client{user="hello"} 871707
telemt_user_unique_ips_current{user="hello"} 50
telemt_user_unique_ips_recent_window{user="hello"} 24
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 74825.6 (20h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 123617
telemt_connections_bad_total 15507
telemt_handshake_timeouts_total 1402
telemt_upstream_connect_attempt_total 29357
telemt_upstream_connect_success_total 29081
telemt_upstream_connect_fail_total 276
telemt_upstream_connect_attempts_per_request{bucket="1"} 29357
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15026
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13962
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 93
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 276
telemt_me_keepalive_timeout_total 1187
telemt_me_reconnect_attempts_total 33804
telemt_me_reconnect_success_total 20415
telemt_me_reader_eof_total 21892
telemt_me_idle_close_by_peer_total 21892
telemt_me_route_drop_no_conn_total 38801
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 97822
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 482
telemt_desync_full_logged_total 101
telemt_desync_suppressed_total 381
telemt_desync_frames_bucket_total{bucket="1_2"} 66
telemt_desync_frames_bucket_total{bucket="3_10"} 256
telemt_desync_frames_bucket_total{bucket="gt_10"} 160
telemt_pool_swap_total 51
telemt_me_writer_removed_unexpected_total 21021
telemt_me_refill_failed_total 416
telemt_me_writer_restored_same_endpoint_total 20397
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 606
telemt_user_connections_total{user="hello"} 102719
telemt_user_connections_current{user="hello"} 156
telemt_user_octets_from_client{user="hello"} 1209257669 (1.13 GB)
telemt_user_octets_to_client{user="hello"} 34357109891 (32.00 GB)
telemt_user_msgs_from_client{user="hello"} 50955
telemt_user_msgs_to_client{user="hello"} 221508
telemt_user_unique_ips_current{user="hello"} 55
telemt_user_unique_ips_recent_window{user="hello"} 29
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 124611.1 (34h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 762029
telemt_connections_bad_total 24762
telemt_handshake_timeouts_total 24513
telemt_upstream_connect_attempt_total 25899
telemt_upstream_connect_success_total 25761
telemt_upstream_connect_fail_total 138
telemt_upstream_connect_attempts_per_request{bucket="1"} 25899
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12072
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13657
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 32
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 138
telemt_me_keepalive_timeout_total 2991
telemt_me_reconnect_attempts_total 24211
telemt_me_reconnect_success_total 19568
telemt_me_reader_eof_total 21002
telemt_me_idle_close_by_peer_total 20999
telemt_me_route_drop_no_conn_total 361854
telemt_me_route_drop_channel_closed_total 15
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 715002
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 681
telemt_desync_full_logged_total 221
telemt_desync_suppressed_total 460
telemt_desync_frames_bucket_total{bucket="1_2"} 241
telemt_desync_frames_bucket_total{bucket="3_10"} 223
telemt_desync_frames_bucket_total{bucket="gt_10"} 217
telemt_pool_swap_total 115
telemt_me_writer_removed_unexpected_total 19971
telemt_me_refill_failed_total 141
telemt_me_writer_restored_same_endpoint_total 19561
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 403
telemt_user_connections_total{user="hello"} 687889
telemt_user_connections_current{user="hello"} 486
telemt_user_octets_from_client{user="hello"} 12054554716 (11.23 GB)
telemt_user_octets_to_client{user="hello"} 341833958988 (318.36 GB)
telemt_user_unique_ips_current{user="hello"} 161
telemt_user_unique_ips_recent_window{user="hello"} 69
```