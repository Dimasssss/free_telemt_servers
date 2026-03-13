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

# Server Metrics 2026-03-13 21:52:39 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 137960.0 (38h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 573574
telemt_connections_bad_total 17009
telemt_handshake_timeouts_total 12800
telemt_upstream_connect_attempt_total 35024
telemt_upstream_connect_success_total 34847
telemt_upstream_connect_fail_total 177
telemt_upstream_connect_attempts_per_request{bucket="1"} 35024
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15974
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18726
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 147
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 177
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 5110
telemt_me_reconnect_attempts_total 32215
telemt_me_reconnect_success_total 27558
telemt_me_reader_eof_total 29430
telemt_me_idle_close_by_peer_total 29429
telemt_me_route_drop_no_conn_total 189147
telemt_me_route_drop_channel_closed_total 30
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 493403
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1585
telemt_desync_full_logged_total 537
telemt_desync_suppressed_total 1048
telemt_desync_frames_bucket_total{bucket="1_2"} 340
telemt_desync_frames_bucket_total{bucket="3_10"} 591
telemt_desync_frames_bucket_total{bucket="gt_10"} 654
telemt_pool_swap_total 123
telemt_me_writer_removed_unexpected_total 28012
telemt_me_refill_failed_total 140
telemt_me_writer_restored_same_endpoint_total 27542
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 454
telemt_user_connections_total{user="hello"} 493298
telemt_user_connections_current{user="hello"} 211
telemt_user_octets_from_client{user="hello"} 14852097958 (13.83 GB)
telemt_user_octets_to_client{user="hello"} 242490467848 (225.84 GB)
telemt_user_msgs_from_client{user="hello"} 2142
telemt_user_msgs_to_client{user="hello"} 2404
telemt_user_unique_ips_current{user="hello"} 63
telemt_user_unique_ips_recent_window{user="hello"} 14
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 137853.7 (38h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 292082
telemt_connections_bad_total 2138
telemt_handshake_timeouts_total 1918
telemt_upstream_connect_attempt_total 138692
telemt_upstream_connect_success_total 137678
telemt_upstream_connect_fail_total 1014
telemt_upstream_connect_attempts_per_request{bucket="1"} 138692
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 105470
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 29793
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2415
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1014
telemt_me_keepalive_timeout_total 3695
telemt_me_reconnect_attempts_total 144572
telemt_me_reconnect_success_total 27462
telemt_me_reader_eof_total 31866
telemt_me_idle_close_by_peer_total 31866
telemt_me_route_drop_no_conn_total 86883
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 173813
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 35
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
telemt_pool_swap_total 27
telemt_me_writer_removed_unexpected_total 31382
telemt_me_refill_failed_total 3654
telemt_me_writer_restored_same_endpoint_total 27445
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 3920
telemt_user_connections_total{user="hello"} 276926
telemt_user_connections_current{user="hello"} 150
telemt_user_octets_from_client{user="hello"} 2929079279 (2.73 GB)
telemt_user_octets_to_client{user="hello"} 84523274807 (78.72 GB)
telemt_user_msgs_from_client{user="hello"} 1686033
telemt_user_msgs_to_client{user="hello"} 9368110
telemt_user_unique_ips_current{user="hello"} 32
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 137817.8 (38h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 339771
telemt_connections_bad_total 2658
telemt_handshake_timeouts_total 27316
telemt_upstream_connect_attempt_total 36676
telemt_upstream_connect_success_total 36671
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 36676
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16907
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19722
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 40
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 2848
telemt_me_reconnect_attempts_total 30980
telemt_me_reconnect_success_total 29734
telemt_me_reader_eof_total 31892
telemt_me_idle_close_by_peer_total 31892
telemt_me_route_drop_no_conn_total 120985
telemt_me_route_drop_channel_closed_total 18
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 297847
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 112
telemt_desync_full_logged_total 52
telemt_desync_suppressed_total 60
telemt_desync_frames_bucket_total{bucket="1_2"} 12
telemt_desync_frames_bucket_total{bucket="3_10"} 38
telemt_desync_frames_bucket_total{bucket="gt_10"} 62
telemt_pool_swap_total 127
telemt_me_writer_removed_unexpected_total 30072
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 29714
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 338
telemt_user_connections_total{user="hello"} 297748
telemt_user_connections_current{user="hello"} 119
telemt_user_octets_from_client{user="hello"} 12334564060 (11.49 GB)
telemt_user_octets_to_client{user="hello"} 123626450944 (115.14 GB)
telemt_user_unique_ips_current{user="hello"} 35
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 137793.0 (38h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 444638
telemt_connections_bad_total 15269
telemt_handshake_timeouts_total 4233
telemt_upstream_connect_attempt_total 64113
telemt_upstream_connect_success_total 53748
telemt_upstream_connect_fail_total 10365
telemt_upstream_connect_attempts_per_request{bucket="1"} 64113
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 33527
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19908
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 304
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10365
telemt_me_keepalive_timeout_total 4769
telemt_me_reconnect_attempts_total 128933
telemt_me_reconnect_success_total 27842
telemt_me_reader_eof_total 31781
telemt_me_idle_close_by_peer_total 31774
telemt_me_route_drop_no_conn_total 154920
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 375209
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 31
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1589
telemt_desync_full_logged_total 470
telemt_desync_suppressed_total 1119
telemt_desync_frames_bucket_total{bucket="1_2"} 377
telemt_desync_frames_bucket_total{bucket="3_10"} 607
telemt_desync_frames_bucket_total{bucket="gt_10"} 605
telemt_pool_swap_total 32
telemt_me_writer_removed_unexpected_total 31352
telemt_me_refill_failed_total 3153
telemt_me_writer_restored_same_endpoint_total 27832
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 3510
telemt_user_connections_total{user="hello"} 394051
telemt_user_connections_current{user="hello"} 129
telemt_user_octets_from_client{user="hello"} 8923544763 (8.31 GB)
telemt_user_octets_to_client{user="hello"} 150275710076 (139.96 GB)
telemt_user_msgs_from_client{user="hello"} 459818
telemt_user_msgs_to_client{user="hello"} 871707
telemt_user_unique_ips_current{user="hello"} 46
telemt_user_unique_ips_recent_window{user="hello"} 13
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 87964.8 (24h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 149190
telemt_connections_bad_total 22028
telemt_handshake_timeouts_total 1536
telemt_upstream_connect_attempt_total 32806
telemt_upstream_connect_success_total 32496
telemt_upstream_connect_fail_total 310
telemt_upstream_connect_attempts_per_request{bucket="1"} 32806
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16689
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15696
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 111
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 310
telemt_me_keepalive_timeout_total 1300
telemt_me_reconnect_attempts_total 36614
telemt_me_reconnect_success_total 23217
telemt_me_reader_eof_total 24869
telemt_me_idle_close_by_peer_total 24869
telemt_me_route_drop_no_conn_total 45828
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 116056
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 611
telemt_desync_full_logged_total 143
telemt_desync_suppressed_total 468
telemt_desync_frames_bucket_total{bucket="1_2"} 92
telemt_desync_frames_bucket_total{bucket="3_10"} 302
telemt_desync_frames_bucket_total{bucket="gt_10"} 217
telemt_pool_swap_total 62
telemt_me_writer_removed_unexpected_total 23854
telemt_me_refill_failed_total 416
telemt_me_writer_restored_same_endpoint_total 23199
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 637
telemt_user_connections_total{user="hello"} 120950
telemt_user_connections_current{user="hello"} 60
telemt_user_octets_from_client{user="hello"} 1402936253 (1.31 GB)
telemt_user_octets_to_client{user="hello"} 57046457943 (53.13 GB)
telemt_user_msgs_from_client{user="hello"} 50955
telemt_user_msgs_to_client{user="hello"} 221508
telemt_user_unique_ips_current{user="hello"} 25
telemt_user_unique_ips_recent_window{user="hello"} 5
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 137749.1 (38h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 834378
telemt_connections_bad_total 27126
telemt_handshake_timeouts_total 25092
telemt_upstream_connect_attempt_total 28340
telemt_upstream_connect_success_total 28192
telemt_upstream_connect_fail_total 148
telemt_upstream_connect_attempts_per_request{bucket="1"} 28340
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13171
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14982
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 39
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 148
telemt_me_keepalive_timeout_total 3121
telemt_me_reconnect_attempts_total 26014
telemt_me_reconnect_success_total 21363
telemt_me_reader_eof_total 22907
telemt_me_idle_close_by_peer_total 22904
telemt_me_route_drop_no_conn_total 397638
telemt_me_route_drop_channel_closed_total 21
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 780778
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 693
telemt_desync_full_logged_total 226
telemt_desync_suppressed_total 467
telemt_desync_frames_bucket_total{bucket="1_2"} 249
telemt_desync_frames_bucket_total{bucket="3_10"} 226
telemt_desync_frames_bucket_total{bucket="gt_10"} 218
telemt_pool_swap_total 128
telemt_me_writer_removed_unexpected_total 21791
telemt_me_refill_failed_total 141
telemt_me_writer_restored_same_endpoint_total 21356
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 428
telemt_user_connections_total{user="hello"} 753637
telemt_user_connections_current{user="hello"} 325
telemt_user_octets_from_client{user="hello"} 13094587152 (12.20 GB)
telemt_user_octets_to_client{user="hello"} 375414230444 (349.63 GB)
telemt_user_unique_ips_current{user="hello"} 115
telemt_user_unique_ips_recent_window{user="hello"} 38
```