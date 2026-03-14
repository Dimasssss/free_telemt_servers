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

# Server Metrics 2026-03-14 11:17:07 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 186226.7 (51h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 731069
telemt_connections_bad_total 34240
telemt_handshake_timeouts_total 14234
telemt_upstream_connect_attempt_total 47368
telemt_upstream_connect_success_total 47133
telemt_upstream_connect_fail_total 235
telemt_upstream_connect_attempts_per_request{bucket="1"} 47368
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21524
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 25456
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 153
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 235
telemt_me_keepalive_failed_total 4
telemt_me_keepalive_timeout_total 6118
telemt_me_reconnect_attempts_total 43252
telemt_me_reconnect_success_total 37490
telemt_me_reader_eof_total 40087
telemt_me_idle_close_by_peer_total 40086
telemt_me_route_drop_no_conn_total 241670
telemt_me_route_drop_channel_closed_total 39
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 626831
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2571
telemt_desync_full_logged_total 855
telemt_desync_suppressed_total 1716
telemt_desync_frames_bucket_total{bucket="1_2"} 543
telemt_desync_frames_bucket_total{bucket="3_10"} 958
telemt_desync_frames_bucket_total{bucket="gt_10"} 1070
telemt_pool_swap_total 169
telemt_me_writer_removed_unexpected_total 38069
telemt_me_refill_failed_total 173
telemt_me_writer_restored_same_endpoint_total 37470
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 579
telemt_user_connections_total{user="hello"} 626721
telemt_user_connections_current{user="hello"} 410
telemt_user_octets_from_client{user="hello"} 17590577658 (16.38 GB)
telemt_user_octets_to_client{user="hello"} 301877717060 (281.15 GB)
telemt_user_msgs_from_client{user="hello"} 2142
telemt_user_msgs_to_client{user="hello"} 2404
telemt_user_unique_ips_current{user="hello"} 116
telemt_user_unique_ips_recent_window{user="hello"} 42
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 186119.8 (51h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 363866
telemt_connections_bad_total 2836
telemt_handshake_timeouts_total 3294
telemt_upstream_connect_attempt_total 155291
telemt_upstream_connect_success_total 153922
telemt_upstream_connect_fail_total 1369
telemt_upstream_connect_attempts_per_request{bucket="1"} 155291
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 112026
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 39424
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2471
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1369
telemt_me_keepalive_timeout_total 5531
telemt_me_reconnect_attempts_total 191972
telemt_me_reconnect_success_total 41345
telemt_me_reader_eof_total 47130
telemt_me_idle_close_by_peer_total 47130
telemt_me_route_drop_no_conn_total 125603
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 240390
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 46
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
telemt_pool_swap_total 37
telemt_me_writer_removed_unexpected_total 46448
telemt_me_refill_failed_total 4699
telemt_me_writer_restored_same_endpoint_total 41327
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 5103
telemt_user_connections_total{user="hello"} 343492
telemt_user_connections_current{user="hello"} 175
telemt_user_octets_from_client{user="hello"} 3510340383 (3.27 GB)
telemt_user_octets_to_client{user="hello"} 110393074563 (102.81 GB)
telemt_user_msgs_from_client{user="hello"} 1686033
telemt_user_msgs_to_client{user="hello"} 9368110
telemt_user_unique_ips_current{user="hello"} 46
telemt_user_unique_ips_recent_window{user="hello"} 22
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 186083.3 (51h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 420018
telemt_connections_bad_total 3283
telemt_handshake_timeouts_total 35913
telemt_upstream_connect_attempt_total 49632
telemt_upstream_connect_success_total 49623
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 49632
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 22760
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 26792
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 64
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 3929
telemt_me_reconnect_attempts_total 41619
telemt_me_reconnect_success_total 40305
telemt_me_reader_eof_total 43280
telemt_me_idle_close_by_peer_total 43280
telemt_me_route_drop_no_conn_total 152827
telemt_me_route_drop_channel_closed_total 23
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 365885
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 138
telemt_desync_full_logged_total 63
telemt_desync_suppressed_total 75
telemt_desync_frames_bucket_total{bucket="1_2"} 14
telemt_desync_frames_bucket_total{bucket="3_10"} 48
telemt_desync_frames_bucket_total{bucket="gt_10"} 76
telemt_pool_swap_total 173
telemt_me_writer_removed_unexpected_total 40786
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 40284
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 481
telemt_user_connections_total{user="hello"} 365608
telemt_user_connections_current{user="hello"} 154
telemt_user_octets_from_client{user="hello"} 14800365380 (13.78 GB)
telemt_user_octets_to_client{user="hello"} 161351088612 (150.27 GB)
telemt_user_unique_ips_current{user="hello"} 64
telemt_user_unique_ips_recent_window{user="hello"} 17
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 186058.8 (51h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 532181
telemt_connections_bad_total 16724
telemt_handshake_timeouts_total 5276
telemt_upstream_connect_attempt_total 79962
telemt_upstream_connect_success_total 69269
telemt_upstream_connect_fail_total 10693
telemt_upstream_connect_attempts_per_request{bucket="1"} 79962
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 40332
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 28560
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 368
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10693
telemt_me_keepalive_timeout_total 5711
telemt_me_reconnect_attempts_total 155606
telemt_me_reconnect_success_total 40968
telemt_me_reader_eof_total 45849
telemt_me_idle_close_by_peer_total 45841
telemt_me_route_drop_no_conn_total 193022
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 456169
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 37
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2038
telemt_desync_full_logged_total 608
telemt_desync_suppressed_total 1430
telemt_desync_frames_bucket_total{bucket="1_2"} 484
telemt_desync_frames_bucket_total{bucket="3_10"} 778
telemt_desync_frames_bucket_total{bucket="gt_10"} 776
telemt_pool_swap_total 53
telemt_me_writer_removed_unexpected_total 45016
telemt_me_refill_failed_total 3574
telemt_me_writer_restored_same_endpoint_total 40958
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 4048
telemt_user_connections_total{user="hello"} 475035
telemt_user_connections_current{user="hello"} 201
telemt_user_octets_from_client{user="hello"} 10100084411 (9.41 GB)
telemt_user_octets_to_client{user="hello"} 194692579876 (181.32 GB)
telemt_user_msgs_from_client{user="hello"} 459818
telemt_user_msgs_to_client{user="hello"} 871707
telemt_user_unique_ips_current{user="hello"} 69
telemt_user_unique_ips_recent_window{user="hello"} 24
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 136230.3 (37h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 229563
telemt_connections_bad_total 36125
telemt_handshake_timeouts_total 2137
telemt_upstream_connect_attempt_total 47851
telemt_upstream_connect_success_total 47375
telemt_upstream_connect_fail_total 476
telemt_upstream_connect_attempts_per_request{bucket="1"} 47851
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 23627
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23590
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 158
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 476
telemt_me_keepalive_timeout_total 2916
telemt_me_reconnect_attempts_total 51578
telemt_me_reconnect_success_total 35694
telemt_me_reader_eof_total 38196
telemt_me_idle_close_by_peer_total 38196
telemt_me_route_drop_no_conn_total 69535
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 180272
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 773
telemt_desync_full_logged_total 191
telemt_desync_suppressed_total 582
telemt_desync_frames_bucket_total{bucket="1_2"} 128
telemt_desync_frames_bucket_total{bucket="3_10"} 368
telemt_desync_frames_bucket_total{bucket="gt_10"} 277
telemt_pool_swap_total 102
telemt_me_writer_removed_unexpected_total 36522
telemt_me_refill_failed_total 492
telemt_me_writer_restored_same_endpoint_total 35676
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 42
telemt_me_writer_removed_unexpected_minus_restored_total 828
telemt_user_connections_total{user="hello"} 185028
telemt_user_connections_current{user="hello"} 96
telemt_user_octets_from_client{user="hello"} 2717969241 (2.53 GB)
telemt_user_octets_to_client{user="hello"} 85347266683 (79.49 GB)
telemt_user_msgs_from_client{user="hello"} 50955
telemt_user_msgs_to_client{user="hello"} 221508
telemt_user_unique_ips_current{user="hello"} 46
telemt_user_unique_ips_recent_window{user="hello"} 18
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 186015.6 (51h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1082334
telemt_connections_bad_total 37432
telemt_handshake_timeouts_total 27056
telemt_upstream_connect_attempt_total 38871
telemt_upstream_connect_success_total 38667
telemt_upstream_connect_fail_total 204
telemt_upstream_connect_attempts_per_request{bucket="1"} 38871
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18318
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20308
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 41
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 204
telemt_me_keepalive_timeout_total 4937
telemt_me_reconnect_attempts_total 34161
telemt_me_reconnect_success_total 29470
telemt_me_reader_eof_total 31600
telemt_me_idle_close_by_peer_total 31597
telemt_me_route_drop_no_conn_total 507306
telemt_me_route_drop_channel_closed_total 27
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1003610
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 809
telemt_desync_full_logged_total 268
telemt_desync_suppressed_total 541
telemt_desync_frames_bucket_total{bucket="1_2"} 260
telemt_desync_frames_bucket_total{bucket="3_10"} 269
telemt_desync_frames_bucket_total{bucket="gt_10"} 280
telemt_pool_swap_total 173
telemt_me_writer_removed_unexpected_total 29989
telemt_me_refill_failed_total 141
telemt_me_writer_restored_same_endpoint_total 29463
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 519
telemt_user_connections_total{user="hello"} 976195
telemt_user_connections_current{user="hello"} 532
telemt_user_octets_from_client{user="hello"} 19661139428 (18.31 GB)
telemt_user_octets_to_client{user="hello"} 490025543424 (456.37 GB)
telemt_user_unique_ips_current{user="hello"} 199
telemt_user_unique_ips_recent_window{user="hello"} 63
```