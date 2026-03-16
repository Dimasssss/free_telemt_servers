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

# Server Metrics 2026-03-16 18:12:33 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.18

telemt_uptime_seconds 16477.2 (4h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 164086
telemt_connections_bad_total 742
telemt_handshake_timeouts_total 4152
telemt_upstream_connect_attempt_total 3512
telemt_upstream_connect_success_total 3499
telemt_upstream_connect_fail_total 13
telemt_upstream_connect_attempts_per_request{bucket="1"} 3512
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1668
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1826
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 13
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 3781
telemt_me_reconnect_success_total 2611
telemt_me_reader_eof_total 2716
telemt_me_idle_close_by_peer_total 2715
telemt_me_route_drop_no_conn_total 50516
telemt_me_route_drop_channel_closed_total 15
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 153791
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 14
telemt_me_endpoint_quarantine_total 5
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 772
telemt_desync_full_logged_total 180
telemt_desync_suppressed_total 592
telemt_desync_frames_bucket_total{bucket="1_2"} 289
telemt_desync_frames_bucket_total{bucket="3_10"} 274
telemt_desync_frames_bucket_total{bucket="gt_10"} 209
telemt_pool_swap_total 10
telemt_me_writer_removed_unexpected_total 2666
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 2609
telemt_me_writer_restored_fallback_total 2
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 55
telemt_user_connections_total{user="hello"} 153704
telemt_user_connections_current{user="hello"} 596
telemt_user_octets_from_client{user="hello"} 2933993732 (2.73 GB)
telemt_user_octets_to_client{user="hello"} 88561688700 (82.48 GB)
telemt_user_unique_ips_current{user="hello"} 199
telemt_user_unique_ips_recent_window{user="hello"} 58
```

## psb.hosting

```
telemt 3.3.18

telemt_uptime_seconds 11255.7 (3h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 78518
telemt_connections_bad_total 642
telemt_handshake_timeouts_total 3229
telemt_upstream_connect_attempt_total 2420
telemt_upstream_connect_success_total 2407
telemt_upstream_connect_fail_total 13
telemt_upstream_connect_attempts_per_request{bucket="1"} 2420
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 867
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1325
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 215
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 13
telemt_me_reconnect_attempts_total 5299
telemt_me_reconnect_success_total 1790
telemt_me_reader_eof_total 1936
telemt_me_idle_close_by_peer_total 1936
telemt_me_route_drop_no_conn_total 44923
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 71832
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 1
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 129
telemt_desync_full_logged_total 29
telemt_desync_suppressed_total 100
telemt_desync_frames_bucket_total{bucket="1_2"} 37
telemt_desync_frames_bucket_total{bucket="3_10"} 58
telemt_desync_frames_bucket_total{bucket="gt_10"} 34
telemt_pool_swap_total 4
telemt_me_writer_removed_unexpected_total 1932
telemt_me_refill_failed_total 109
telemt_me_writer_restored_same_endpoint_total 1785
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 343
telemt_me_writer_removed_unexpected_minus_restored_total 142
telemt_user_connections_total{user="hello"} 71773
telemt_user_connections_current{user="hello"} 398
telemt_user_octets_from_client{user="hello"} 829864764 (791.42 MB)
telemt_user_octets_to_client{user="hello"} 20986746400 (19.55 GB)
telemt_user_unique_ips_current{user="hello"} 122
telemt_user_unique_ips_recent_window{user="hello"} 47
```

## koara.io

```
telemt 3.3.18

telemt_uptime_seconds 16590.0 (4h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 67187
telemt_connections_bad_total 84
telemt_handshake_timeouts_total 885
telemt_upstream_connect_attempt_total 4893
telemt_upstream_connect_success_total 4842
telemt_upstream_connect_fail_total 51
telemt_upstream_connect_attempts_per_request{bucket="1"} 4893
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2545
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2269
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 28
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 51
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 41855
telemt_me_reconnect_success_total 2969
telemt_me_reader_eof_total 3331
telemt_me_idle_close_by_peer_total 3331
telemt_me_route_drop_no_conn_total 23802
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 62112
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 9
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 165
telemt_desync_full_logged_total 63
telemt_desync_suppressed_total 102
telemt_desync_frames_bucket_total{bucket="1_2"} 37
telemt_desync_frames_bucket_total{bucket="3_10"} 73
telemt_desync_frames_bucket_total{bucket="gt_10"} 55
telemt_pool_swap_total 4
telemt_me_writer_removed_unexpected_total 3306
telemt_me_refill_failed_total 1214
telemt_me_writer_restored_same_endpoint_total 2925
telemt_me_writer_restored_fallback_total 44
telemt_me_async_recovery_trigger_total 1272
telemt_me_writer_removed_unexpected_minus_restored_total 337
telemt_user_connections_total{user="hello"} 63046
telemt_user_connections_current{user="hello"} 233
telemt_user_octets_from_client{user="hello"} 836162918 (797.43 MB)
telemt_user_octets_to_client{user="hello"} 17933326134 (16.70 GB)
telemt_user_msgs_from_client{user="hello"} 4789
telemt_user_msgs_to_client{user="hello"} 14129
telemt_user_unique_ips_current{user="hello"} 80
telemt_user_unique_ips_recent_window{user="hello"} 33
```

## landvps.ru

```
telemt 3.3.18

telemt_uptime_seconds 16726.3 (4h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 130080
telemt_connections_bad_total 234
telemt_handshake_timeouts_total 1786
telemt_upstream_connect_attempt_total 3595
telemt_upstream_connect_success_total 3569
telemt_upstream_connect_fail_total 26
telemt_upstream_connect_attempts_per_request{bucket="1"} 3595
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1702
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1830
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 32
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 26
telemt_me_keepalive_timeout_total 15
telemt_me_reconnect_attempts_total 9005
telemt_me_reconnect_success_total 2647
telemt_me_reader_eof_total 2909
telemt_me_idle_close_by_peer_total 2908
telemt_me_route_drop_no_conn_total 47338
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 123504
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 13
telemt_me_endpoint_quarantine_total 1
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 668
telemt_desync_full_logged_total 189
telemt_desync_suppressed_total 479
telemt_desync_frames_bucket_total{bucket="1_2"} 114
telemt_desync_frames_bucket_total{bucket="3_10"} 277
telemt_desync_frames_bucket_total{bucket="gt_10"} 277
telemt_pool_swap_total 7
telemt_me_writer_removed_unexpected_total 2881
telemt_me_refill_failed_total 197
telemt_me_writer_restored_same_endpoint_total 2643
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 18
telemt_me_writer_removed_unexpected_minus_restored_total 234
telemt_user_connections_total{user="hello"} 123474
telemt_user_connections_current{user="hello"} 424
telemt_user_octets_from_client{user="hello"} 1770886252 (1.65 GB)
telemt_user_octets_to_client{user="hello"} 30875678612 (28.76 GB)
telemt_user_unique_ips_current{user="hello"} 129
telemt_user_unique_ips_recent_window{user="hello"} 50
```

## rdp-onedash.ru

```
telemt 3.3.18

telemt_uptime_seconds 14186.6 (3h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 73566
telemt_connections_bad_total 20528
telemt_handshake_timeouts_total 581
telemt_upstream_connect_attempt_total 3721
telemt_upstream_connect_success_total 3665
telemt_upstream_connect_fail_total 56
telemt_upstream_connect_attempts_per_request{bucket="1"} 3721
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1480
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2100
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 85
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 56
telemt_me_reconnect_attempts_total 4584
telemt_me_reconnect_success_total 2921
telemt_me_reader_eof_total 3025
telemt_me_idle_close_by_peer_total 3025
telemt_me_route_drop_no_conn_total 51721
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 68777
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 73
telemt_desync_full_logged_total 26
telemt_desync_suppressed_total 47
telemt_desync_frames_bucket_total{bucket="1_2"} 29
telemt_desync_frames_bucket_total{bucket="3_10"} 25
telemt_desync_frames_bucket_total{bucket="gt_10"} 19
telemt_pool_swap_total 6
telemt_me_writer_removed_unexpected_total 3074
telemt_me_refill_failed_total 51
telemt_me_writer_restored_same_endpoint_total 2921
telemt_me_async_recovery_trigger_total 22
telemt_me_writer_removed_unexpected_minus_restored_total 153
telemt_user_connections_total{user="hello"} 49820
telemt_user_connections_current{user="hello"} 190
telemt_user_octets_from_client{user="hello"} 2085381356 (1.94 GB)
telemt_user_octets_to_client{user="hello"} 33797050964 (31.48 GB)
telemt_user_unique_ips_current{user="hello"} 64
telemt_user_unique_ips_recent_window{user="hello"} 25
```

## hostvds.com

```
telemt 3.3.18

telemt_uptime_seconds 16298.2 (4h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 188170
telemt_connections_bad_total 2211
telemt_handshake_timeouts_total 3423
telemt_upstream_connect_attempt_total 3354
telemt_upstream_connect_success_total 3354
telemt_upstream_connect_attempts_per_request{bucket="1"} 3354
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1585
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1757
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 7503
telemt_me_reconnect_success_total 2474
telemt_me_reader_eof_total 2689
telemt_me_idle_close_by_peer_total 2688
telemt_me_route_drop_no_conn_total 86285
telemt_me_route_drop_channel_closed_total 27
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 174866
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_endpoint_quarantine_total 6
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 123
telemt_desync_full_logged_total 44
telemt_desync_suppressed_total 79
telemt_desync_frames_bucket_total{bucket="1_2"} 27
telemt_desync_frames_bucket_total{bucket="3_10"} 48
telemt_desync_frames_bucket_total{bucket="gt_10"} 48
telemt_pool_swap_total 7
telemt_me_writer_removed_unexpected_total 2652
telemt_me_refill_failed_total 156
telemt_me_writer_restored_same_endpoint_total 2468
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 208
telemt_me_writer_removed_unexpected_minus_restored_total 178
telemt_user_connections_total{user="hello"} 174529
telemt_user_connections_current{user="hello"} 751
telemt_user_octets_from_client{user="hello"} 3395909064 (3.16 GB)
telemt_user_octets_to_client{user="hello"} 65392219452 (60.90 GB)
telemt_user_unique_ips_current{user="hello"} 241
telemt_user_unique_ips_recent_window{user="hello"} 93
```