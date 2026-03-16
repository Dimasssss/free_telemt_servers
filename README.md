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

# Server Metrics 2026-03-16 10:37:37 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.18

telemt_uptime_seconds 130987.0 (36h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 667885
telemt_connections_bad_total 26745
telemt_handshake_timeouts_total 22613
telemt_upstream_connect_attempt_total 30605
telemt_upstream_connect_success_total 30459
telemt_upstream_connect_fail_total 146
telemt_upstream_connect_attempts_per_request{bucket="1"} 30605
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13585
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16827
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 38
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 146
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 51
telemt_me_reconnect_attempts_total 35428
telemt_me_reconnect_success_total 23955
telemt_me_reader_eof_total 25787
telemt_me_idle_close_by_peer_total 25787
telemt_me_route_drop_no_conn_total 592004
telemt_me_route_drop_channel_closed_total 88
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 639927
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2952
telemt_desync_full_logged_total 1143
telemt_desync_suppressed_total 1809
telemt_desync_frames_bucket_total{bucket="1_2"} 651
telemt_desync_frames_bucket_total{bucket="3_10"} 1129
telemt_desync_frames_bucket_total{bucket="gt_10"} 1172
telemt_pool_swap_total 121
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 24571
telemt_me_refill_failed_total 354
telemt_me_writer_restored_same_endpoint_total 23920
telemt_me_writer_restored_fallback_total 35
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 616
telemt_user_connections_total{user="hello"} 576474
telemt_user_connections_current{user="hello"} 556
telemt_user_octets_from_client{user="hello"} 11060666712 (10.30 GB)
telemt_user_octets_to_client{user="hello"} 347617271888 (323.74 GB)
telemt_user_unique_ips_current{user="hello"} 178
telemt_user_unique_ips_recent_window{user="hello"} 85
```

## psb.hosting

```
telemt 3.3.18

telemt_uptime_seconds 130994.1 (36h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 271406
telemt_connections_bad_total 3798
telemt_handshake_timeouts_total 15704
telemt_upstream_connect_attempt_total 35027
telemt_upstream_connect_success_total 34952
telemt_upstream_connect_fail_total 75
telemt_upstream_connect_attempts_per_request{bucket="1"} 35027
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15081
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19153
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 718
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 75
telemt_me_keepalive_timeout_total 1307
telemt_me_reconnect_attempts_total 38360
telemt_me_reconnect_success_total 28032
telemt_me_reader_eof_total 30069
telemt_me_idle_close_by_peer_total 30068
telemt_me_route_drop_no_conn_total 128104
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 242579
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 206
telemt_desync_full_logged_total 67
telemt_desync_suppressed_total 139
telemt_desync_frames_bucket_total{bucket="1_2"} 41
telemt_desync_frames_bucket_total{bucket="3_10"} 76
telemt_desync_frames_bucket_total{bucket="gt_10"} 89
telemt_pool_swap_total 111
telemt_me_writer_removed_unexpected_total 28751
telemt_me_refill_failed_total 314
telemt_me_writer_restored_same_endpoint_total 28016
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 719
telemt_user_connections_total{user="hello"} 242110
telemt_user_connections_current{user="hello"} 391
telemt_user_octets_from_client{user="hello"} 5131765173 (4.78 GB)
telemt_user_octets_to_client{user="hello"} 128035302876 (119.24 GB)
telemt_user_msgs_from_client{user="hello"} 721
telemt_user_msgs_to_client{user="hello"} 1482
telemt_user_unique_ips_current{user="hello"} 105
telemt_user_unique_ips_recent_window{user="hello"} 61
```

## koara.io

```
telemt 3.3.18

telemt_uptime_seconds 130986.3 (36h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 275870
telemt_connections_bad_total 5777
telemt_handshake_timeouts_total 6735
telemt_upstream_connect_attempt_total 36483
telemt_upstream_connect_success_total 36475
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 36483
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15785
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20636
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 54
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 45
telemt_me_reconnect_attempts_total 37322
telemt_me_reconnect_success_total 29895
telemt_me_reader_eof_total 32127
telemt_me_idle_close_by_peer_total 32126
telemt_me_route_drop_no_conn_total 95477
telemt_me_route_drop_channel_closed_total 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 224242
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 12
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 113
telemt_desync_full_logged_total 44
telemt_desync_suppressed_total 69
telemt_desync_frames_bucket_total{bucket="1_2"} 15
telemt_desync_frames_bucket_total{bucket="3_10"} 47
telemt_desync_frames_bucket_total{bucket="gt_10"} 51
telemt_pool_swap_total 117
telemt_me_writer_removed_unexpected_total 30422
telemt_me_refill_failed_total 227
telemt_me_writer_restored_same_endpoint_total 29887
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 527
telemt_user_connections_total{user="hello"} 223919
telemt_user_connections_current{user="hello"} 274
telemt_user_octets_from_client{user="hello"} 17752420909 (16.53 GB)
telemt_user_octets_to_client{user="hello"} 123899695840 (115.39 GB)
telemt_user_msgs_from_client{user="hello"} 7
telemt_user_msgs_to_client{user="hello"} 46
telemt_user_unique_ips_current{user="hello"} 94
telemt_user_unique_ips_recent_window{user="hello"} 36
```

## landvps.ru

```
telemt 3.3.18

telemt_uptime_seconds 130985.7 (36h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 405564
telemt_connections_bad_total 1421
telemt_handshake_timeouts_total 3837
telemt_upstream_connect_attempt_total 30194
telemt_upstream_connect_success_total 30153
telemt_upstream_connect_fail_total 41
telemt_upstream_connect_attempts_per_request{bucket="1"} 30194
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14536
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15443
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 16
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 158
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 41
telemt_me_keepalive_timeout_total 23
telemt_me_reconnect_attempts_total 28627
telemt_me_reconnect_success_total 23635
telemt_me_reader_eof_total 25344
telemt_me_idle_close_by_peer_total 25343
telemt_me_route_drop_no_conn_total 140810
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 375747
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1371
telemt_desync_full_logged_total 460
telemt_desync_suppressed_total 911
telemt_desync_frames_bucket_total{bucket="1_2"} 281
telemt_desync_frames_bucket_total{bucket="3_10"} 581
telemt_desync_frames_bucket_total{bucket="gt_10"} 509
telemt_pool_swap_total 121
telemt_me_writer_removed_unexpected_total 24104
telemt_me_refill_failed_total 151
telemt_me_writer_restored_same_endpoint_total 23624
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 469
telemt_user_connections_total{user="hello"} 375616
telemt_user_connections_current{user="hello"} 489
telemt_user_octets_from_client{user="hello"} 6149700822 (5.73 GB)
telemt_user_octets_to_client{user="hello"} 147238433712 (137.13 GB)
telemt_user_msgs_from_client{user="hello"} 25
telemt_user_msgs_to_client{user="hello"} 50
telemt_user_unique_ips_current{user="hello"} 134
telemt_user_unique_ips_recent_window{user="hello"} 66
```

## rdp-onedash.ru

```
telemt 3.3.18

telemt_uptime_seconds 106057.0 (29h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 254458
telemt_connections_bad_total 42909
telemt_handshake_timeouts_total 4332
telemt_upstream_connect_attempt_total 30129
telemt_upstream_connect_success_total 29964
telemt_upstream_connect_fail_total 165
telemt_upstream_connect_attempts_per_request{bucket="1"} 30129
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13267
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16545
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 152
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 165
telemt_me_keepalive_timeout_total 24
telemt_me_reconnect_attempts_total 119042
telemt_me_reconnect_success_total 24534
telemt_me_reader_eof_total 26061
telemt_me_idle_close_by_peer_total 26061
telemt_me_route_drop_no_conn_total 78375
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 199815
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 668
telemt_desync_full_logged_total 157
telemt_desync_suppressed_total 511
telemt_desync_frames_bucket_total{bucket="1_2"} 97
telemt_desync_frames_bucket_total{bucket="3_10"} 269
telemt_desync_frames_bucket_total{bucket="gt_10"} 302
telemt_pool_swap_total 91
telemt_me_writer_removed_unexpected_total 24742
telemt_me_refill_failed_total 3033
telemt_me_writer_restored_same_endpoint_total 24430
telemt_me_writer_restored_fallback_total 104
telemt_me_async_recovery_trigger_total 2255
telemt_me_writer_removed_unexpected_minus_restored_total 208
telemt_user_connections_total{user="hello"} 199427
telemt_user_connections_current{user="hello"} 179
telemt_user_octets_from_client{user="hello"} 2561347301 (2.39 GB)
telemt_user_octets_to_client{user="hello"} 88937293467 (82.83 GB)
telemt_user_msgs_from_client{user="hello"} 2259
telemt_user_msgs_to_client{user="hello"} 12105
telemt_user_unique_ips_current{user="hello"} 66
telemt_user_unique_ips_recent_window{user="hello"} 36
```

## hostvds.com

```
telemt 3.3.18

telemt_uptime_seconds 130985.0 (36h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 905613
telemt_connections_bad_total 73144
telemt_handshake_timeouts_total 10588
telemt_upstream_connect_attempt_total 27501
telemt_upstream_connect_success_total 27355
telemt_upstream_connect_fail_total 146
telemt_upstream_connect_attempts_per_request{bucket="1"} 27501
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12977
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14334
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 19
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 146
telemt_me_keepalive_timeout_total 63
telemt_me_reconnect_attempts_total 23435
telemt_me_reconnect_success_total 20827
telemt_me_reader_eof_total 22243
telemt_me_idle_close_by_peer_total 22243
telemt_me_route_drop_no_conn_total 681322
telemt_me_route_drop_channel_closed_total 124
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 891142
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 452
telemt_desync_full_logged_total 133
telemt_desync_suppressed_total 319
telemt_desync_frames_bucket_total{bucket="1_2"} 174
telemt_desync_frames_bucket_total{bucket="3_10"} 144
telemt_desync_frames_bucket_total{bucket="gt_10"} 134
telemt_pool_swap_total 121
telemt_me_writer_removed_unexpected_total 21155
telemt_me_refill_failed_total 77
telemt_me_writer_restored_same_endpoint_total 20800
telemt_me_writer_restored_fallback_total 27
telemt_me_async_recovery_trigger_total 40
telemt_me_writer_removed_unexpected_minus_restored_total 328
telemt_user_connections_total{user="hello"} 749774
telemt_user_connections_current{user="hello"} 696
telemt_user_octets_from_client{user="hello"} 15940911064 (14.85 GB)
telemt_user_octets_to_client{user="hello"} 441952845380 (411.60 GB)
telemt_user_unique_ips_current{user="hello"} 258
telemt_user_unique_ips_recent_window{user="hello"} 118
```