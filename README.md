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

# Server Metrics 2026-03-14 00:05:07 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 145907.5 (40h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 587839
telemt_connections_bad_total 20100
telemt_handshake_timeouts_total 12841
telemt_upstream_connect_attempt_total 37138
telemt_upstream_connect_success_total 36952
telemt_upstream_connect_fail_total 186
telemt_upstream_connect_attempts_per_request{bucket="1"} 37138
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16888
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19916
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 148
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 186
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 5165
telemt_me_reconnect_attempts_total 33930
telemt_me_reconnect_success_total 29261
telemt_me_reader_eof_total 31264
telemt_me_idle_close_by_peer_total 31263
telemt_me_route_drop_no_conn_total 193184
telemt_me_route_drop_channel_closed_total 30
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 504105
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1628
telemt_desync_full_logged_total 556
telemt_desync_suppressed_total 1072
telemt_desync_frames_bucket_total{bucket="1_2"} 351
telemt_desync_frames_bucket_total{bucket="3_10"} 608
telemt_desync_frames_bucket_total{bucket="gt_10"} 669
telemt_pool_swap_total 132
telemt_me_writer_removed_unexpected_total 29733
telemt_me_refill_failed_total 140
telemt_me_writer_restored_same_endpoint_total 29245
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 472
telemt_user_connections_total{user="hello"} 504000
telemt_user_connections_current{user="hello"} 188
telemt_user_octets_from_client{user="hello"} 15424935046 (14.37 GB)
telemt_user_octets_to_client{user="hello"} 250111255780 (232.93 GB)
telemt_user_msgs_from_client{user="hello"} 2142
telemt_user_msgs_to_client{user="hello"} 2404
telemt_user_unique_ips_current{user="hello"} 56
telemt_user_unique_ips_recent_window{user="hello"} 11
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 145800.5 (40h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 301288
telemt_connections_bad_total 2180
telemt_handshake_timeouts_total 1930
telemt_upstream_connect_attempt_total 141717
telemt_upstream_connect_success_total 140649
telemt_upstream_connect_fail_total 1068
telemt_upstream_connect_attempts_per_request{bucket="1"} 141717
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 106513
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 31721
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2415
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1068
telemt_me_keepalive_timeout_total 3761
telemt_me_reconnect_attempts_total 154360
telemt_me_reconnect_success_total 30073
telemt_me_reader_eof_total 34745
telemt_me_idle_close_by_peer_total 34745
telemt_me_route_drop_no_conn_total 92721
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 182558
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
telemt_me_writer_removed_unexpected_total 34240
telemt_me_refill_failed_total 3878
telemt_me_writer_restored_same_endpoint_total 30056
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 4167
telemt_user_connections_total{user="hello"} 285670
telemt_user_connections_current{user="hello"} 109
telemt_user_octets_from_client{user="hello"} 2996691083 (2.79 GB)
telemt_user_octets_to_client{user="hello"} 89463807135 (83.32 GB)
telemt_user_msgs_from_client{user="hello"} 1686033
telemt_user_msgs_to_client{user="hello"} 9368110
telemt_user_unique_ips_current{user="hello"} 27
telemt_user_unique_ips_recent_window{user="hello"} 4
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 145764.7 (40h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 352426
telemt_connections_bad_total 2759
telemt_handshake_timeouts_total 32404
telemt_upstream_connect_attempt_total 38646
telemt_upstream_connect_success_total 38640
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 38646
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17707
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20878
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 51
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 2918
telemt_me_reconnect_attempts_total 32600
telemt_me_reconnect_success_total 31345
telemt_me_reader_eof_total 33659
telemt_me_idle_close_by_peer_total 33659
telemt_me_route_drop_no_conn_total 124671
telemt_me_route_drop_channel_closed_total 18
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 304928
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
telemt_me_writer_removed_unexpected_total 31713
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 31325
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 368
telemt_user_connections_total{user="hello"} 304830
telemt_user_connections_current{user="hello"} 73
telemt_user_octets_from_client{user="hello"} 12539292100 (11.68 GB)
telemt_user_octets_to_client{user="hello"} 126156205272 (117.49 GB)
telemt_user_unique_ips_current{user="hello"} 32
telemt_user_unique_ips_recent_window{user="hello"} 9
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 145739.7 (40h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 453723
telemt_connections_bad_total 15361
telemt_handshake_timeouts_total 4253
telemt_upstream_connect_attempt_total 66725
telemt_upstream_connect_success_total 56308
telemt_upstream_connect_fail_total 10416
telemt_upstream_connect_attempts_per_request{bucket="1"} 66724
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 34593
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21390
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 316
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10416
telemt_me_keepalive_timeout_total 5038
telemt_me_reconnect_attempts_total 133651
telemt_me_reconnect_success_total 30019
telemt_me_reader_eof_total 34102
telemt_me_idle_close_by_peer_total 34094
telemt_me_route_drop_no_conn_total 159397
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 383901
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 31
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1676
telemt_desync_full_logged_total 492
telemt_desync_suppressed_total 1184
telemt_desync_frames_bucket_total{bucket="1_2"} 394
telemt_desync_frames_bucket_total{bucket="3_10"} 638
telemt_desync_frames_bucket_total{bucket="gt_10"} 644
telemt_pool_swap_total 35
telemt_me_writer_removed_unexpected_total 33626
telemt_me_refill_failed_total 3232
telemt_me_writer_restored_same_endpoint_total 30009
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 3607
telemt_user_connections_total{user="hello"} 402743
telemt_user_connections_current{user="hello"} 117
telemt_user_octets_from_client{user="hello"} 9030554303 (8.41 GB)
telemt_user_octets_to_client{user="hello"} 153585619136 (143.04 GB)
telemt_user_msgs_from_client{user="hello"} 459818
telemt_user_msgs_to_client{user="hello"} 871707
telemt_user_unique_ips_current{user="hello"} 36
telemt_user_unique_ips_recent_window{user="hello"} 14
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 95911.2 (26h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 160214
telemt_connections_bad_total 23598
telemt_handshake_timeouts_total 1546
telemt_upstream_connect_attempt_total 35490
telemt_upstream_connect_success_total 35165
telemt_upstream_connect_fail_total 325
telemt_upstream_connect_attempts_per_request{bucket="1"} 35490
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17987
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17059
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 119
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 325
telemt_me_keepalive_timeout_total 1351
telemt_me_reconnect_attempts_total 38891
telemt_me_reconnect_success_total 25482
telemt_me_reader_eof_total 27254
telemt_me_idle_close_by_peer_total 27254
telemt_me_route_drop_no_conn_total 48345
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 125364
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
telemt_me_writer_removed_unexpected_total 26135
telemt_me_refill_failed_total 416
telemt_me_writer_restored_same_endpoint_total 25464
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 42
telemt_me_writer_removed_unexpected_minus_restored_total 653
telemt_user_connections_total{user="hello"} 130216
telemt_user_connections_current{user="hello"} 57
telemt_user_octets_from_client{user="hello"} 1638545025 (1.53 GB)
telemt_user_octets_to_client{user="hello"} 63082325975 (58.75 GB)
telemt_user_msgs_from_client{user="hello"} 50955
telemt_user_msgs_to_client{user="hello"} 221508
telemt_user_unique_ips_current{user="hello"} 22
telemt_user_unique_ips_recent_window{user="hello"} 11
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 145695.9 (40h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 863253
telemt_connections_bad_total 27361
telemt_handshake_timeouts_total 25234
telemt_upstream_connect_attempt_total 30065
telemt_upstream_connect_success_total 29903
telemt_upstream_connect_fail_total 162
telemt_upstream_connect_attempts_per_request{bucket="1"} 30065
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13949
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15913
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 41
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 162
telemt_me_keepalive_timeout_total 3404
telemt_me_reconnect_attempts_total 27355
telemt_me_reconnect_success_total 22691
telemt_me_reader_eof_total 24320
telemt_me_idle_close_by_peer_total 24317
telemt_me_route_drop_no_conn_total 411443
telemt_me_route_drop_channel_closed_total 21
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 806129
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 698
telemt_desync_full_logged_total 228
telemt_desync_suppressed_total 470
telemt_desync_frames_bucket_total{bucket="1_2"} 249
telemt_desync_frames_bucket_total{bucket="3_10"} 229
telemt_desync_frames_bucket_total{bucket="gt_10"} 220
telemt_pool_swap_total 135
telemt_me_writer_removed_unexpected_total 23134
telemt_me_refill_failed_total 141
telemt_me_writer_restored_same_endpoint_total 22684
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 443
telemt_user_connections_total{user="hello"} 778982
telemt_user_connections_current{user="hello"} 286
telemt_user_octets_from_client{user="hello"} 13768970280 (12.82 GB)
telemt_user_octets_to_client{user="hello"} 396965126848 (369.70 GB)
telemt_user_unique_ips_current{user="hello"} 113
telemt_user_unique_ips_recent_window{user="hello"} 35
```