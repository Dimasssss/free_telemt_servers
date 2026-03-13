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

# Server Metrics 2026-03-14 00:00:02 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 145602.3 (40h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 587305
telemt_connections_bad_total 19999
telemt_handshake_timeouts_total 12838
telemt_upstream_connect_attempt_total 37050
telemt_upstream_connect_success_total 36865
telemt_upstream_connect_fail_total 185
telemt_upstream_connect_attempts_per_request{bucket="1"} 37050
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16844
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19873
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 148
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 185
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 5165
telemt_me_reconnect_attempts_total 33886
telemt_me_reconnect_success_total 29217
telemt_me_reader_eof_total 31220
telemt_me_idle_close_by_peer_total 31219
telemt_me_route_drop_no_conn_total 193124
telemt_me_route_drop_channel_closed_total 30
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 503677
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1625
telemt_desync_full_logged_total 555
telemt_desync_suppressed_total 1070
telemt_desync_frames_bucket_total{bucket="1_2"} 351
telemt_desync_frames_bucket_total{bucket="3_10"} 608
telemt_desync_frames_bucket_total{bucket="gt_10"} 666
telemt_pool_swap_total 131
telemt_me_writer_removed_unexpected_total 29689
telemt_me_refill_failed_total 140
telemt_me_writer_restored_same_endpoint_total 29201
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 472
telemt_user_connections_total{user="hello"} 503572
telemt_user_connections_current{user="hello"} 200
telemt_user_octets_from_client{user="hello"} 15413957510 (14.36 GB)
telemt_user_octets_to_client{user="hello"} 250038626516 (232.87 GB)
telemt_user_msgs_from_client{user="hello"} 2142
telemt_user_msgs_to_client{user="hello"} 2404
telemt_user_unique_ips_current{user="hello"} 55
telemt_user_unique_ips_recent_window{user="hello"} 14
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 145495.2 (40h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 300871
telemt_connections_bad_total 2180
telemt_handshake_timeouts_total 1930
telemt_upstream_connect_attempt_total 141639
telemt_upstream_connect_success_total 140571
telemt_upstream_connect_fail_total 1068
telemt_upstream_connect_attempts_per_request{bucket="1"} 141639
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 106498
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 31658
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2415
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1068
telemt_me_keepalive_timeout_total 3759
telemt_me_reconnect_attempts_total 154282
telemt_me_reconnect_success_total 29995
telemt_me_reader_eof_total 34667
telemt_me_idle_close_by_peer_total 34667
telemt_me_route_drop_no_conn_total 92610
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 182167
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 37
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
telemt_pool_swap_total 28
telemt_me_writer_removed_unexpected_total 34162
telemt_me_refill_failed_total 3878
telemt_me_writer_restored_same_endpoint_total 29978
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 4167
telemt_user_connections_total{user="hello"} 285279
telemt_user_connections_current{user="hello"} 84
telemt_user_octets_from_client{user="hello"} 2994936211 (2.79 GB)
telemt_user_octets_to_client{user="hello"} 89433145275 (83.29 GB)
telemt_user_msgs_from_client{user="hello"} 1686033
telemt_user_msgs_to_client{user="hello"} 9368110
telemt_user_unique_ips_current{user="hello"} 26
telemt_user_unique_ips_recent_window{user="hello"} 5
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 145459.0 (40h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 351969
telemt_connections_bad_total 2752
telemt_handshake_timeouts_total 32214
telemt_upstream_connect_attempt_total 38591
telemt_upstream_connect_success_total 38585
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 38591
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17693
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20837
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 51
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 2918
telemt_me_reconnect_attempts_total 32545
telemt_me_reconnect_success_total 31290
telemt_me_reader_eof_total 33604
telemt_me_idle_close_by_peer_total 33604
telemt_me_route_drop_no_conn_total 124575
telemt_me_route_drop_channel_closed_total 18
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 304691
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
telemt_pool_swap_total 135
telemt_me_writer_removed_unexpected_total 31658
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 31270
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 368
telemt_user_connections_total{user="hello"} 304593
telemt_user_connections_current{user="hello"} 70
telemt_user_octets_from_client{user="hello"} 12538505356 (11.68 GB)
telemt_user_octets_to_client{user="hello"} 126141568508 (117.48 GB)
telemt_user_unique_ips_current{user="hello"} 34
telemt_user_unique_ips_recent_window{user="hello"} 12
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 145434.5 (40h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 453196
telemt_connections_bad_total 15361
telemt_handshake_timeouts_total 4251
telemt_upstream_connect_attempt_total 66630
telemt_upstream_connect_success_total 56214
telemt_upstream_connect_fail_total 10416
telemt_upstream_connect_attempts_per_request{bucket="1"} 66630
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 34569
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21320
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 316
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10416
telemt_me_keepalive_timeout_total 5035
telemt_me_reconnect_attempts_total 133556
telemt_me_reconnect_success_total 29925
telemt_me_reader_eof_total 34006
telemt_me_idle_close_by_peer_total 33998
telemt_me_route_drop_no_conn_total 159223
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 383394
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 31
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1672
telemt_desync_full_logged_total 491
telemt_desync_suppressed_total 1181
telemt_desync_frames_bucket_total{bucket="1_2"} 391
telemt_desync_frames_bucket_total{bucket="3_10"} 638
telemt_desync_frames_bucket_total{bucket="gt_10"} 643
telemt_pool_swap_total 35
telemt_me_writer_removed_unexpected_total 33530
telemt_me_refill_failed_total 3232
telemt_me_writer_restored_same_endpoint_total 29915
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 3605
telemt_user_connections_total{user="hello"} 402236
telemt_user_connections_current{user="hello"} 112
telemt_user_octets_from_client{user="hello"} 9028046999 (8.41 GB)
telemt_user_octets_to_client{user="hello"} 153482824092 (142.94 GB)
telemt_user_msgs_from_client{user="hello"} 459818
telemt_user_msgs_to_client{user="hello"} 871707
telemt_user_unique_ips_current{user="hello"} 32
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 95606.1 (26h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 159649
telemt_connections_bad_total 23540
telemt_handshake_timeouts_total 1546
telemt_upstream_connect_attempt_total 35415
telemt_upstream_connect_success_total 35090
telemt_upstream_connect_fail_total 325
telemt_upstream_connect_attempts_per_request{bucket="1"} 35415
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17954
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17017
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 119
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 325
telemt_me_keepalive_timeout_total 1349
telemt_me_reconnect_attempts_total 38816
telemt_me_reconnect_success_total 25408
telemt_me_reader_eof_total 27180
telemt_me_idle_close_by_peer_total 27180
telemt_me_route_drop_no_conn_total 48216
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 124858
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 619
telemt_desync_full_logged_total 145
telemt_desync_suppressed_total 474
telemt_desync_frames_bucket_total{bucket="1_2"} 95
telemt_desync_frames_bucket_total{bucket="3_10"} 306
telemt_desync_frames_bucket_total{bucket="gt_10"} 218
telemt_pool_swap_total 68
telemt_me_writer_removed_unexpected_total 26061
telemt_me_refill_failed_total 416
telemt_me_writer_restored_same_endpoint_total 25390
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 42
telemt_me_writer_removed_unexpected_minus_restored_total 653
telemt_user_connections_total{user="hello"} 129711
telemt_user_connections_current{user="hello"} 50
telemt_user_octets_from_client{user="hello"} 1623962665 (1.51 GB)
telemt_user_octets_to_client{user="hello"} 62795236027 (58.48 GB)
telemt_user_msgs_from_client{user="hello"} 50955
telemt_user_msgs_to_client{user="hello"} 221508
telemt_user_unique_ips_current{user="hello"} 20
telemt_user_unique_ips_recent_window{user="hello"} 9
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 145390.5 (40h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 862057
telemt_connections_bad_total 27359
telemt_handshake_timeouts_total 25234
telemt_upstream_connect_attempt_total 30043
telemt_upstream_connect_success_total 29881
telemt_upstream_connect_fail_total 162
telemt_upstream_connect_attempts_per_request{bucket="1"} 30043
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13937
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15903
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 41
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 162
telemt_me_keepalive_timeout_total 3404
telemt_me_reconnect_attempts_total 27333
telemt_me_reconnect_success_total 22670
telemt_me_reader_eof_total 24297
telemt_me_idle_close_by_peer_total 24294
telemt_me_route_drop_no_conn_total 410884
telemt_me_route_drop_channel_closed_total 21
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 804961
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 697
telemt_desync_full_logged_total 227
telemt_desync_suppressed_total 470
telemt_desync_frames_bucket_total{bucket="1_2"} 249
telemt_desync_frames_bucket_total{bucket="3_10"} 229
telemt_desync_frames_bucket_total{bucket="gt_10"} 219
telemt_pool_swap_total 135
telemt_me_writer_removed_unexpected_total 23111
telemt_me_refill_failed_total 141
telemt_me_writer_restored_same_endpoint_total 22663
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 441
telemt_user_connections_total{user="hello"} 777814
telemt_user_connections_current{user="hello"} 231
telemt_user_octets_from_client{user="hello"} 13711853340 (12.77 GB)
telemt_user_octets_to_client{user="hello"} 396603471508 (369.37 GB)
telemt_user_unique_ips_current{user="hello"} 94
telemt_user_unique_ips_recent_window{user="hello"} 34
```