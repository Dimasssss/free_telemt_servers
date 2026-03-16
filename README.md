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

# Server Metrics 2026-03-16 18:22:46 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.18

telemt_uptime_seconds 17092.3 (4h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 169036
telemt_connections_bad_total 796
telemt_handshake_timeouts_total 4269
telemt_upstream_connect_attempt_total 3570
telemt_upstream_connect_success_total 3557
telemt_upstream_connect_fail_total 13
telemt_upstream_connect_attempts_per_request{bucket="1"} 3570
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1690
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1862
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 13
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 3839
telemt_me_reconnect_success_total 2669
telemt_me_reader_eof_total 2776
telemt_me_idle_close_by_peer_total 2775
telemt_me_route_drop_no_conn_total 52172
telemt_me_route_drop_channel_closed_total 15
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 158361
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 14
telemt_me_endpoint_quarantine_total 5
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 815
telemt_desync_full_logged_total 187
telemt_desync_suppressed_total 628
telemt_desync_frames_bucket_total{bucket="1_2"} 303
telemt_desync_frames_bucket_total{bucket="3_10"} 295
telemt_desync_frames_bucket_total{bucket="gt_10"} 217
telemt_pool_swap_total 10
telemt_me_writer_removed_unexpected_total 2726
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 2667
telemt_me_writer_restored_fallback_total 2
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 57
telemt_user_connections_total{user="hello"} 158275
telemt_user_connections_current{user="hello"} 599
telemt_user_octets_from_client{user="hello"} 2977168220 (2.77 GB)
telemt_user_octets_to_client{user="hello"} 91175453472 (84.91 GB)
telemt_user_unique_ips_current{user="hello"} 199
telemt_user_unique_ips_recent_window{user="hello"} 62
```

## psb.hosting

```
telemt 3.3.18

telemt_uptime_seconds 11871.5 (3h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 82183
telemt_connections_bad_total 643
telemt_handshake_timeouts_total 3234
telemt_upstream_connect_attempt_total 2562
telemt_upstream_connect_success_total 2549
telemt_upstream_connect_fail_total 13
telemt_upstream_connect_attempts_per_request{bucket="1"} 2562
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 922
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1398
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 229
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 13
telemt_me_reconnect_attempts_total 5398
telemt_me_reconnect_success_total 1888
telemt_me_reader_eof_total 2039
telemt_me_idle_close_by_peer_total 2039
telemt_me_route_drop_no_conn_total 46593
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 75360
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
telemt_pool_swap_total 5
telemt_me_writer_removed_unexpected_total 2030
telemt_me_refill_failed_total 109
telemt_me_writer_restored_same_endpoint_total 1883
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 343
telemt_me_writer_removed_unexpected_minus_restored_total 142
telemt_user_connections_total{user="hello"} 75301
telemt_user_connections_current{user="hello"} 394
telemt_user_octets_from_client{user="hello"} 857392628 (817.67 MB)
telemt_user_octets_to_client{user="hello"} 21769568376 (20.27 GB)
telemt_user_unique_ips_current{user="hello"} 124
telemt_user_unique_ips_recent_window{user="hello"} 41
```

## koara.io

```
telemt 3.3.18

telemt_uptime_seconds 17205.3 (4h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 69226
telemt_connections_bad_total 89
telemt_handshake_timeouts_total 900
telemt_upstream_connect_attempt_total 5028
telemt_upstream_connect_success_total 4975
telemt_upstream_connect_fail_total 52
telemt_upstream_connect_attempts_per_request{bucket="1"} 5027
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2602
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2344
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 29
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 52
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 41953
telemt_me_reconnect_success_total 3065
telemt_me_reader_eof_total 3429
telemt_me_idle_close_by_peer_total 3429
telemt_me_route_drop_no_conn_total 24547
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 64068
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
telemt_me_writer_removed_unexpected_total 3404
telemt_me_refill_failed_total 1214
telemt_me_writer_restored_same_endpoint_total 3021
telemt_me_writer_restored_fallback_total 44
telemt_me_async_recovery_trigger_total 1272
telemt_me_writer_removed_unexpected_minus_restored_total 339
telemt_user_connections_total{user="hello"} 65000
telemt_user_connections_current{user="hello"} 249
telemt_user_octets_from_client{user="hello"} 858302046 (818.54 MB)
telemt_user_octets_to_client{user="hello"} 19091477686 (17.78 GB)
telemt_user_msgs_from_client{user="hello"} 4789
telemt_user_msgs_to_client{user="hello"} 14129
telemt_user_unique_ips_current{user="hello"} 88
telemt_user_unique_ips_recent_window{user="hello"} 35
```

## landvps.ru

```
telemt 3.3.18

telemt_uptime_seconds 17341.6 (4h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 134403
telemt_connections_bad_total 235
telemt_handshake_timeouts_total 1807
telemt_upstream_connect_attempt_total 3724
telemt_upstream_connect_success_total 3698
telemt_upstream_connect_fail_total 26
telemt_upstream_connect_attempts_per_request{bucket="1"} 3724
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1775
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1886
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 32
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 26
telemt_me_keepalive_timeout_total 15
telemt_me_reconnect_attempts_total 9091
telemt_me_reconnect_success_total 2733
telemt_me_reader_eof_total 2999
telemt_me_idle_close_by_peer_total 2998
telemt_me_route_drop_no_conn_total 48984
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 127619
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 13
telemt_me_endpoint_quarantine_total 1
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 675
telemt_desync_full_logged_total 191
telemt_desync_suppressed_total 484
telemt_desync_frames_bucket_total{bucket="1_2"} 117
telemt_desync_frames_bucket_total{bucket="3_10"} 278
telemt_desync_frames_bucket_total{bucket="gt_10"} 280
telemt_pool_swap_total 8
telemt_me_writer_removed_unexpected_total 2968
telemt_me_refill_failed_total 197
telemt_me_writer_restored_same_endpoint_total 2729
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 18
telemt_me_writer_removed_unexpected_minus_restored_total 235
telemt_user_connections_total{user="hello"} 127585
telemt_user_connections_current{user="hello"} 365
telemt_user_octets_from_client{user="hello"} 1813236372 (1.69 GB)
telemt_user_octets_to_client{user="hello"} 32107062392 (29.90 GB)
telemt_user_unique_ips_current{user="hello"} 112
telemt_user_unique_ips_recent_window{user="hello"} 43
```

## rdp-onedash.ru

```
telemt 3.3.18

telemt_uptime_seconds 14802.1 (4h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 75279
telemt_connections_bad_total 20638
telemt_handshake_timeouts_total 591
telemt_upstream_connect_attempt_total 3931
telemt_upstream_connect_success_total 3871
telemt_upstream_connect_fail_total 60
telemt_upstream_connect_attempts_per_request{bucket="1"} 3931
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1561
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2225
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 85
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 60
telemt_me_reconnect_attempts_total 4746
telemt_me_reconnect_success_total 3082
telemt_me_reader_eof_total 3189
telemt_me_idle_close_by_peer_total 3189
telemt_me_route_drop_no_conn_total 52227
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 70315
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
telemt_me_writer_removed_unexpected_total 3238
telemt_me_refill_failed_total 51
telemt_me_writer_restored_same_endpoint_total 3082
telemt_me_async_recovery_trigger_total 22
telemt_me_writer_removed_unexpected_minus_restored_total 156
telemt_user_connections_total{user="hello"} 51358
telemt_user_connections_current{user="hello"} 154
telemt_user_octets_from_client{user="hello"} 2102661652 (1.96 GB)
telemt_user_octets_to_client{user="hello"} 34368468904 (32.01 GB)
telemt_user_unique_ips_current{user="hello"} 69
telemt_user_unique_ips_recent_window{user="hello"} 22
```

## hostvds.com

```
telemt 3.3.18

telemt_uptime_seconds 16911.0 (4h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 194431
telemt_connections_bad_total 2597
telemt_handshake_timeouts_total 3447
telemt_upstream_connect_attempt_total 3452
telemt_upstream_connect_success_total 3452
telemt_upstream_connect_attempts_per_request{bucket="1"} 3452
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1612
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1824
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 12
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 7592
telemt_me_reconnect_success_total 2563
telemt_me_reader_eof_total 2785
telemt_me_idle_close_by_peer_total 2784
telemt_me_route_drop_no_conn_total 91160
telemt_me_route_drop_channel_closed_total 30
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 180559
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_endpoint_quarantine_total 6
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 136
telemt_desync_full_logged_total 53
telemt_desync_suppressed_total 83
telemt_desync_frames_bucket_total{bucket="1_2"} 28
telemt_desync_frames_bucket_total{bucket="3_10"} 54
telemt_desync_frames_bucket_total{bucket="gt_10"} 54
telemt_pool_swap_total 8
telemt_me_writer_removed_unexpected_total 2741
telemt_me_refill_failed_total 156
telemt_me_writer_restored_same_endpoint_total 2557
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 208
telemt_me_writer_removed_unexpected_minus_restored_total 178
telemt_user_connections_total{user="hello"} 180160
telemt_user_connections_current{user="hello"} 756
telemt_user_octets_from_client{user="hello"} 3514787000 (3.27 GB)
telemt_user_octets_to_client{user="hello"} 66331889032 (61.78 GB)
telemt_user_unique_ips_current{user="hello"} 243
telemt_user_unique_ips_recent_window{user="hello"} 83
```