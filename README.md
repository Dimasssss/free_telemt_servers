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

# Server Metrics 2026-03-13 17:38:02 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 122683.1 (34h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 517724
telemt_connections_bad_total 7636
telemt_handshake_timeouts_total 11843
telemt_upstream_connect_attempt_total 30727
telemt_upstream_connect_success_total 30576
telemt_upstream_connect_fail_total 151
telemt_upstream_connect_attempts_per_request{bucket="1"} 30727
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13859
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16642
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 75
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 151
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 3426
telemt_me_reconnect_attempts_total 29063
telemt_me_reconnect_success_total 24424
telemt_me_reader_eof_total 26090
telemt_me_idle_close_by_peer_total 26089
telemt_me_route_drop_no_conn_total 168214
telemt_me_route_drop_channel_closed_total 28
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 450346
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1463
telemt_desync_full_logged_total 506
telemt_desync_suppressed_total 957
telemt_desync_frames_bucket_total{bucket="1_2"} 322
telemt_desync_frames_bucket_total{bucket="3_10"} 534
telemt_desync_frames_bucket_total{bucket="gt_10"} 607
telemt_pool_swap_total 110
telemt_me_writer_removed_unexpected_total 24838
telemt_me_refill_failed_total 140
telemt_me_writer_restored_same_endpoint_total 24408
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 414
telemt_user_connections_total{user="hello"} 449915
telemt_user_connections_current{user="hello"} 343
telemt_user_octets_from_client{user="hello"} 8302778600 (7.73 GB)
telemt_user_octets_to_client{user="hello"} 211977491588 (197.42 GB)
telemt_user_unique_ips_current{user="hello"} 104
telemt_user_unique_ips_recent_window{user="hello"} 35
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 122577.1 (34h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 254620
telemt_connections_bad_total 1948
telemt_handshake_timeouts_total 1813
telemt_upstream_connect_attempt_total 108423
telemt_upstream_connect_success_total 107579
telemt_upstream_connect_fail_total 838
telemt_upstream_connect_attempts_per_request{bucket="1"} 108417
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 79842
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 26192
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1545
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 838
telemt_me_keepalive_timeout_total 1513
telemt_me_reconnect_attempts_total 125216
telemt_me_reconnect_success_total 26033
telemt_me_reader_eof_total 29886
telemt_me_idle_close_by_peer_total 29886
telemt_me_route_drop_no_conn_total 82429
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 165848
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 30
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
telemt_me_writer_removed_unexpected_total 29356
telemt_me_refill_failed_total 3095
telemt_me_writer_restored_same_endpoint_total 26016
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 3323
telemt_user_connections_total{user="hello"} 241043
telemt_user_connections_current{user="hello"} 132
telemt_user_octets_from_client{user="hello"} 2513905809 (2.34 GB)
telemt_user_octets_to_client{user="hello"} 74095778543 (69.01 GB)
telemt_user_msgs_from_client{user="hello"} 1180008
telemt_user_msgs_to_client{user="hello"} 6835631
telemt_user_unique_ips_current{user="hello"} 32
telemt_user_unique_ips_recent_window{user="hello"} 28
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 122540.7 (34h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 300905
telemt_connections_bad_total 2493
telemt_handshake_timeouts_total 16892
telemt_upstream_connect_attempt_total 32730
telemt_upstream_connect_success_total 32726
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 32730
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15188
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17505
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 31
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 2605
telemt_me_reconnect_attempts_total 27769
telemt_me_reconnect_success_total 26539
telemt_me_reader_eof_total 28454
telemt_me_idle_close_by_peer_total 28454
telemt_me_route_drop_no_conn_total 107522
telemt_me_route_drop_channel_closed_total 17
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 270931
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
telemt_pool_swap_total 112
telemt_me_writer_removed_unexpected_total 26838
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 26519
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 299
telemt_user_connections_total{user="hello"} 270840
telemt_user_connections_current{user="hello"} 145
telemt_user_octets_from_client{user="hello"} 10160437940 (9.46 GB)
telemt_user_octets_to_client{user="hello"} 111862929580 (104.18 GB)
telemt_user_unique_ips_current{user="hello"} 58
telemt_user_unique_ips_recent_window{user="hello"} 26
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 122516.2 (34h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 407623
telemt_connections_bad_total 15106
telemt_handshake_timeouts_total 3866
telemt_upstream_connect_attempt_total 59996
telemt_upstream_connect_success_total 49749
telemt_upstream_connect_fail_total 10246
telemt_upstream_connect_attempts_per_request{bucket="1"} 59995
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 31692
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17769
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 279
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10246
telemt_me_keepalive_timeout_total 4654
telemt_me_reconnect_attempts_total 114233
telemt_me_reconnect_success_total 24579
telemt_me_reader_eof_total 28074
telemt_me_idle_close_by_peer_total 28067
telemt_me_route_drop_no_conn_total 140374
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 339810
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
telemt_pool_swap_total 29
telemt_me_writer_removed_unexpected_total 27689
telemt_me_refill_failed_total 2796
telemt_me_writer_restored_same_endpoint_total 24569
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 3110
telemt_user_connections_total{user="hello"} 358700
telemt_user_connections_current{user="hello"} 145
telemt_user_octets_from_client{user="hello"} 8351989287 (7.78 GB)
telemt_user_octets_to_client{user="hello"} 128851040208 (120.00 GB)
telemt_user_msgs_from_client{user="hello"} 459818
telemt_user_msgs_to_client{user="hello"} 871707
telemt_user_unique_ips_current{user="hello"} 46
telemt_user_unique_ips_recent_window{user="hello"} 27
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 72687.7 (20h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 118795
telemt_connections_bad_total 15092
telemt_handshake_timeouts_total 1392
telemt_upstream_connect_attempt_total 28762
telemt_upstream_connect_success_total 28499
telemt_upstream_connect_fail_total 263
telemt_upstream_connect_attempts_per_request{bucket="1"} 28762
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14757
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13654
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 88
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 263
telemt_me_keepalive_timeout_total 1163
telemt_me_reconnect_attempts_total 33351
telemt_me_reconnect_success_total 19964
telemt_me_reader_eof_total 21416
telemt_me_idle_close_by_peer_total 21416
telemt_me_route_drop_no_conn_total 36984
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 93564
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 425
telemt_desync_full_logged_total 86
telemt_desync_suppressed_total 339
telemt_desync_frames_bucket_total{bucket="1_2"} 53
telemt_desync_frames_bucket_total{bucket="3_10"} 233
telemt_desync_frames_bucket_total{bucket="gt_10"} 139
telemt_pool_swap_total 50
telemt_me_writer_removed_unexpected_total 20563
telemt_me_refill_failed_total 416
telemt_me_writer_restored_same_endpoint_total 19946
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 599
telemt_user_connections_total{user="hello"} 98462
telemt_user_connections_current{user="hello"} 125
telemt_user_octets_from_client{user="hello"} 1179119821 (1.10 GB)
telemt_user_octets_to_client{user="hello"} 31326942155 (29.18 GB)
telemt_user_msgs_from_client{user="hello"} 50955
telemt_user_msgs_to_client{user="hello"} 221508
telemt_user_unique_ips_current{user="hello"} 44
telemt_user_unique_ips_recent_window{user="hello"} 22
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 122473.2 (34h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 748029
telemt_connections_bad_total 24655
telemt_handshake_timeouts_total 24421
telemt_upstream_connect_attempt_total 25538
telemt_upstream_connect_success_total 25403
telemt_upstream_connect_fail_total 135
telemt_upstream_connect_attempts_per_request{bucket="1"} 25538
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11901
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13470
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 32
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 135
telemt_me_keepalive_timeout_total 2958
telemt_me_reconnect_attempts_total 23952
telemt_me_reconnect_success_total 19309
telemt_me_reader_eof_total 20723
telemt_me_idle_close_by_peer_total 20720
telemt_me_route_drop_no_conn_total 354040
telemt_me_route_drop_channel_closed_total 15
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 701666
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 680
telemt_desync_full_logged_total 220
telemt_desync_suppressed_total 460
telemt_desync_frames_bucket_total{bucket="1_2"} 241
telemt_desync_frames_bucket_total{bucket="3_10"} 223
telemt_desync_frames_bucket_total{bucket="gt_10"} 216
telemt_pool_swap_total 112
telemt_me_writer_removed_unexpected_total 19707
telemt_me_refill_failed_total 141
telemt_me_writer_restored_same_endpoint_total 19302
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 398
telemt_user_connections_total{user="hello"} 674549
telemt_user_connections_current{user="hello"} 438
telemt_user_octets_from_client{user="hello"} 11876812244 (11.06 GB)
telemt_user_octets_to_client{user="hello"} 338612348488 (315.36 GB)
telemt_user_unique_ips_current{user="hello"} 152
telemt_user_unique_ips_recent_window{user="hello"} 48
```