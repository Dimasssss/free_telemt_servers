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

# Server Metrics 2026-03-15 14:53:19 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.18

telemt_uptime_seconds 59930.8 (16h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 271353
telemt_connections_bad_total 2600
telemt_handshake_timeouts_total 7618
telemt_upstream_connect_attempt_total 15059
telemt_upstream_connect_success_total 14981
telemt_upstream_connect_fail_total 78
telemt_upstream_connect_attempts_per_request{bucket="1"} 15059
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6632
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8329
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 12
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 78
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 32
telemt_me_reconnect_attempts_total 15361
telemt_me_reconnect_success_total 11980
telemt_me_reader_eof_total 12771
telemt_me_idle_close_by_peer_total 12771
telemt_me_route_drop_no_conn_total 442323
telemt_me_route_drop_channel_closed_total 72
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 311328
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1723
telemt_desync_full_logged_total 687
telemt_desync_suppressed_total 1036
telemt_desync_frames_bucket_total{bucket="1_2"} 308
telemt_desync_frames_bucket_total{bucket="3_10"} 676
telemt_desync_frames_bucket_total{bucket="gt_10"} 739
telemt_pool_swap_total 51
telemt_me_writer_removed_unexpected_total 12207
telemt_me_refill_failed_total 104
telemt_me_writer_restored_same_endpoint_total 11949
telemt_me_writer_restored_fallback_total 31
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 227
telemt_user_connections_total{user="hello"} 250435
telemt_user_connections_current{user="hello"} 377
telemt_user_octets_from_client{user="hello"} 5521208960 (5.14 GB)
telemt_user_octets_to_client{user="hello"} 214716777692 (199.97 GB)
telemt_user_unique_ips_current{user="hello"} 119
telemt_user_unique_ips_recent_window{user="hello"} 35
```

## psb.hosting

```
telemt 3.3.18

telemt_uptime_seconds 59937.8 (16h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 100813
telemt_connections_bad_total 2795
telemt_handshake_timeouts_total 9618
telemt_upstream_connect_attempt_total 16577
telemt_upstream_connect_success_total 16576
telemt_upstream_connect_attempts_per_request{bucket="1"} 16576
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7123
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9298
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 155
telemt_me_keepalive_timeout_total 34
telemt_me_reconnect_attempts_total 15891
telemt_me_reconnect_success_total 13535
telemt_me_reader_eof_total 14476
telemt_me_idle_close_by_peer_total 14476
telemt_me_route_drop_no_conn_total 42570
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 85324
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1
telemt_desync_full_logged_total 1
telemt_desync_frames_bucket_total{bucket="3_10"} 1
telemt_pool_swap_total 52
telemt_me_writer_removed_unexpected_total 13766
telemt_me_refill_failed_total 71
telemt_me_writer_restored_same_endpoint_total 13519
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 231
telemt_user_connections_total{user="hello"} 85315
telemt_user_connections_current{user="hello"} 193
telemt_user_octets_from_client{user="hello"} 1659607884 (1.55 GB)
telemt_user_octets_to_client{user="hello"} 40645660020 (37.85 GB)
telemt_user_unique_ips_current{user="hello"} 51
telemt_user_unique_ips_recent_window{user="hello"} 17
```

## koara.io

```
telemt 3.3.18

telemt_uptime_seconds 59930.0 (16h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 110144
telemt_connections_bad_total 1654
telemt_handshake_timeouts_total 2806
telemt_upstream_connect_attempt_total 17673
telemt_upstream_connect_success_total 17665
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 17673
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7630
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10001
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 34
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 35
telemt_me_reconnect_attempts_total 21962
telemt_me_reconnect_success_total 14620
telemt_me_reader_eof_total 15709
telemt_me_idle_close_by_peer_total 15709
telemt_me_route_drop_no_conn_total 41827
telemt_me_route_drop_channel_closed_total 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 95024
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 12
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 56
telemt_desync_full_logged_total 22
telemt_desync_suppressed_total 34
telemt_desync_frames_bucket_total{bucket="1_2"} 4
telemt_desync_frames_bucket_total{bucket="3_10"} 28
telemt_desync_frames_bucket_total{bucket="gt_10"} 24
telemt_pool_swap_total 49
telemt_me_writer_removed_unexpected_total 14982
telemt_me_refill_failed_total 227
telemt_me_writer_restored_same_endpoint_total 14612
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 362
telemt_user_connections_total{user="hello"} 94925
telemt_user_connections_current{user="hello"} 178
telemt_user_octets_from_client{user="hello"} 10257246632 (9.55 GB)
telemt_user_octets_to_client{user="hello"} 55198200252 (51.41 GB)
telemt_user_unique_ips_current{user="hello"} 66
telemt_user_unique_ips_recent_window{user="hello"} 22
```

## landvps.ru

```
telemt 3.3.18

telemt_uptime_seconds 59929.8 (16h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 145782
telemt_connections_bad_total 799
telemt_handshake_timeouts_total 924
telemt_upstream_connect_attempt_total 14423
telemt_upstream_connect_success_total 14419
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 14423
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6939
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7425
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 55
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_keepalive_timeout_total 20
telemt_me_reconnect_attempts_total 11486
telemt_me_reconnect_success_total 11416
telemt_me_reader_eof_total 12149
telemt_me_idle_close_by_peer_total 12149
telemt_me_route_drop_no_conn_total 56570
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 133458
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 466
telemt_desync_full_logged_total 149
telemt_desync_suppressed_total 317
telemt_desync_frames_bucket_total{bucket="1_2"} 96
telemt_desync_frames_bucket_total{bucket="3_10"} 214
telemt_desync_frames_bucket_total{bucket="gt_10"} 156
telemt_pool_swap_total 54
telemt_me_writer_removed_unexpected_total 11548
telemt_me_writer_restored_same_endpoint_total 11405
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 132
telemt_user_connections_total{user="hello"} 133372
telemt_user_connections_current{user="hello"} 261
telemt_user_octets_from_client{user="hello"} 2484186952 (2.31 GB)
telemt_user_octets_to_client{user="hello"} 64897618500 (60.44 GB)
telemt_user_unique_ips_current{user="hello"} 70
telemt_user_unique_ips_recent_window{user="hello"} 30
```

## rdp-onedash.ru

```
telemt 3.3.18

telemt_uptime_seconds 35001.2 (9h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 84342
telemt_connections_bad_total 21577
telemt_handshake_timeouts_total 1431
telemt_upstream_connect_attempt_total 10998
telemt_upstream_connect_success_total 10931
telemt_upstream_connect_fail_total 67
telemt_upstream_connect_attempts_per_request{bucket="1"} 10998
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4972
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5913
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 46
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 67
telemt_me_keepalive_timeout_total 21
telemt_me_reconnect_attempts_total 103434
telemt_me_reconnect_success_total 9003
telemt_me_reader_eof_total 9405
telemt_me_idle_close_by_peer_total 9405
telemt_me_route_drop_no_conn_total 28977
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 59411
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 156
telemt_desync_full_logged_total 35
telemt_desync_suppressed_total 121
telemt_desync_frames_bucket_total{bucket="1_2"} 22
telemt_desync_frames_bucket_total{bucket="3_10"} 65
telemt_desync_frames_bucket_total{bucket="gt_10"} 69
telemt_pool_swap_total 22
telemt_me_writer_removed_unexpected_total 9025
telemt_me_refill_failed_total 3033
telemt_me_writer_restored_same_endpoint_total 8899
telemt_me_writer_restored_fallback_total 104
telemt_me_async_recovery_trigger_total 2255
telemt_me_writer_removed_unexpected_minus_restored_total 22
telemt_user_connections_total{user="hello"} 59547
telemt_user_connections_current{user="hello"} 124
telemt_user_octets_from_client{user="hello"} 859789993 (819.96 MB)
telemt_user_octets_to_client{user="hello"} 23856748379 (22.22 GB)
telemt_user_msgs_from_client{user="hello"} 2259
telemt_user_msgs_to_client{user="hello"} 12105
telemt_user_unique_ips_current{user="hello"} 43
telemt_user_unique_ips_recent_window{user="hello"} 23
```

## hostvds.com

```
telemt 3.3.18

telemt_uptime_seconds 59929.1 (16h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 364421
telemt_connections_bad_total 49027
telemt_handshake_timeouts_total 3042
telemt_upstream_connect_attempt_total 12837
telemt_upstream_connect_success_total 12760
telemt_upstream_connect_fail_total 77
telemt_upstream_connect_attempts_per_request{bucket="1"} 12837
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6346
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6410
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 77
telemt_me_keepalive_timeout_total 60
telemt_me_reconnect_attempts_total 11028
telemt_me_reconnect_success_total 9740
telemt_me_reader_eof_total 10380
telemt_me_idle_close_by_peer_total 10380
telemt_me_route_drop_no_conn_total 170269
telemt_me_route_drop_channel_closed_total 41
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 301555
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 301
telemt_desync_full_logged_total 79
telemt_desync_suppressed_total 222
telemt_desync_frames_bucket_total{bucket="1_2"} 167
telemt_desync_frames_bucket_total{bucket="3_10"} 87
telemt_desync_frames_bucket_total{bucket="gt_10"} 47
telemt_pool_swap_total 54
telemt_me_writer_removed_unexpected_total 9873
telemt_me_refill_failed_total 38
telemt_me_writer_restored_same_endpoint_total 9713
telemt_me_writer_restored_fallback_total 27
telemt_me_async_recovery_trigger_total 40
telemt_me_writer_removed_unexpected_minus_restored_total 133
telemt_user_connections_total{user="hello"} 299353
telemt_user_connections_current{user="hello"} 645
telemt_user_octets_from_client{user="hello"} 7568235452 (7.05 GB)
telemt_user_octets_to_client{user="hello"} 152334352040 (141.87 GB)
telemt_user_unique_ips_current{user="hello"} 233
telemt_user_unique_ips_recent_window{user="hello"} 78
```