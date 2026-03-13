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

# Server Metrics 2026-03-13 23:09:02 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 142542.3 (39h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 582258
telemt_connections_bad_total 18662
telemt_handshake_timeouts_total 12830
telemt_upstream_connect_attempt_total 36248
telemt_upstream_connect_success_total 36065
telemt_upstream_connect_fail_total 183
telemt_upstream_connect_attempts_per_request{bucket="1"} 36248
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16512
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19405
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 148
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 183
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 5145
telemt_me_reconnect_attempts_total 33215
telemt_me_reconnect_success_total 28552
telemt_me_reader_eof_total 30505
telemt_me_idle_close_by_peer_total 30504
telemt_me_route_drop_no_conn_total 191770
telemt_me_route_drop_channel_closed_total 30
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 500139
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1616
telemt_desync_full_logged_total 549
telemt_desync_suppressed_total 1067
telemt_desync_frames_bucket_total{bucket="1_2"} 348
telemt_desync_frames_bucket_total{bucket="3_10"} 606
telemt_desync_frames_bucket_total{bucket="gt_10"} 662
telemt_pool_swap_total 128
telemt_me_writer_removed_unexpected_total 29018
telemt_me_refill_failed_total 140
telemt_me_writer_restored_same_endpoint_total 28536
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 466
telemt_user_connections_total{user="hello"} 500033
telemt_user_connections_current{user="hello"} 207
telemt_user_octets_from_client{user="hello"} 15313184038 (14.26 GB)
telemt_user_octets_to_client{user="hello"} 248503776064 (231.44 GB)
telemt_user_msgs_from_client{user="hello"} 2142
telemt_user_msgs_to_client{user="hello"} 2404
telemt_user_unique_ips_current{user="hello"} 59
telemt_user_unique_ips_recent_window{user="hello"} 15
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 142435.2 (39h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 297414
telemt_connections_bad_total 2157
telemt_handshake_timeouts_total 1921
telemt_upstream_connect_attempt_total 140341
telemt_upstream_connect_success_total 139295
telemt_upstream_connect_fail_total 1046
telemt_upstream_connect_attempts_per_request{bucket="1"} 140341
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 106077
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 30803
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2415
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1046
telemt_me_keepalive_timeout_total 3725
telemt_me_reconnect_attempts_total 149556
telemt_me_reconnect_success_total 28856
telemt_me_reader_eof_total 33404
telemt_me_idle_close_by_peer_total 33404
telemt_me_route_drop_no_conn_total 91068
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 178952
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 36
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
telemt_me_writer_removed_unexpected_total 32899
telemt_me_refill_failed_total 3766
telemt_me_writer_restored_same_endpoint_total 28839
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 4043
telemt_user_connections_total{user="hello"} 282064
telemt_user_connections_current{user="hello"} 116
telemt_user_octets_from_client{user="hello"} 2971683415 (2.77 GB)
telemt_user_octets_to_client{user="hello"} 88388279071 (82.32 GB)
telemt_user_msgs_from_client{user="hello"} 1686033
telemt_user_msgs_to_client{user="hello"} 9368110
telemt_user_unique_ips_current{user="hello"} 29
telemt_user_unique_ips_recent_window{user="hello"} 6
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 142399.0 (39h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 347540
telemt_connections_bad_total 2701
telemt_handshake_timeouts_total 30254
telemt_upstream_connect_attempt_total 37854
telemt_upstream_connect_success_total 37848
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 37854
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17398
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20404
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 44
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 2875
telemt_me_reconnect_attempts_total 31938
telemt_me_reconnect_success_total 30688
telemt_me_reader_eof_total 32947
telemt_me_idle_close_by_peer_total 32947
telemt_me_route_drop_no_conn_total 123190
telemt_me_route_drop_channel_closed_total 18
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 302450
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
telemt_pool_swap_total 132
telemt_me_writer_removed_unexpected_total 31037
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 30668
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 349
telemt_user_connections_total{user="hello"} 302352
telemt_user_connections_current{user="hello"} 99
telemt_user_octets_from_client{user="hello"} 12379606132 (11.53 GB)
telemt_user_octets_to_client{user="hello"} 125516763232 (116.90 GB)
telemt_user_unique_ips_current{user="hello"} 36
telemt_user_unique_ips_recent_window{user="hello"} 13
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 142374.3 (39h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 449960
telemt_connections_bad_total 15326
telemt_handshake_timeouts_total 4239
telemt_upstream_connect_attempt_total 65431
telemt_upstream_connect_success_total 55040
telemt_upstream_connect_fail_total 10391
telemt_upstream_connect_attempts_per_request{bucket="1"} 65431
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 34083
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20635
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 313
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10391
telemt_me_keepalive_timeout_total 5015
telemt_me_reconnect_attempts_total 131363
telemt_me_reconnect_success_total 28888
telemt_me_reader_eof_total 32919
telemt_me_idle_close_by_peer_total 32912
telemt_me_route_drop_no_conn_total 157481
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 380322
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 31
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1656
telemt_desync_full_logged_total 485
telemt_desync_suppressed_total 1171
telemt_desync_frames_bucket_total{bucket="1_2"} 387
telemt_desync_frames_bucket_total{bucket="3_10"} 630
telemt_desync_frames_bucket_total{bucket="gt_10"} 639
telemt_pool_swap_total 35
telemt_me_writer_removed_unexpected_total 32449
telemt_me_refill_failed_total 3196
telemt_me_writer_restored_same_endpoint_total 28878
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 3561
telemt_user_connections_total{user="hello"} 399164
telemt_user_connections_current{user="hello"} 134
telemt_user_octets_from_client{user="hello"} 9006443547 (8.39 GB)
telemt_user_octets_to_client{user="hello"} 152257186172 (141.80 GB)
telemt_user_msgs_from_client{user="hello"} 459818
telemt_user_msgs_to_client{user="hello"} 871707
telemt_user_unique_ips_current{user="hello"} 36
telemt_user_unique_ips_recent_window{user="hello"} 13
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 92545.9 (25h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 154818
telemt_connections_bad_total 22965
telemt_handshake_timeouts_total 1538
telemt_upstream_connect_attempt_total 34177
telemt_upstream_connect_success_total 33862
telemt_upstream_connect_fail_total 315
telemt_upstream_connect_attempts_per_request{bucket="1"} 34177
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17364
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16383
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 115
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 315
telemt_me_keepalive_timeout_total 1325
telemt_me_reconnect_attempts_total 37765
telemt_me_reconnect_success_total 24362
telemt_me_reader_eof_total 26082
telemt_me_idle_close_by_peer_total 26082
telemt_me_route_drop_no_conn_total 46971
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 120669
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
telemt_pool_swap_total 66
telemt_me_writer_removed_unexpected_total 25013
telemt_me_refill_failed_total 416
telemt_me_writer_restored_same_endpoint_total 24344
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 651
telemt_user_connections_total{user="hello"} 125545
telemt_user_connections_current{user="hello"} 87
telemt_user_octets_from_client{user="hello"} 1495826185 (1.39 GB)
telemt_user_octets_to_client{user="hello"} 59487324051 (55.40 GB)
telemt_user_msgs_from_client{user="hello"} 50955
telemt_user_msgs_to_client{user="hello"} 221508
telemt_user_unique_ips_current{user="hello"} 29
telemt_user_unique_ips_recent_window{user="hello"} 11
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 142330.5 (39h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 851829
telemt_connections_bad_total 27233
telemt_handshake_timeouts_total 25147
telemt_upstream_connect_attempt_total 29324
telemt_upstream_connect_success_total 29169
telemt_upstream_connect_fail_total 155
telemt_upstream_connect_attempts_per_request{bucket="1"} 29324
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13621
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15507
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 41
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 155
telemt_me_keepalive_timeout_total 3395
telemt_me_reconnect_attempts_total 26751
telemt_me_reconnect_success_total 22091
telemt_me_reader_eof_total 23685
telemt_me_idle_close_by_peer_total 23682
telemt_me_route_drop_no_conn_total 405911
telemt_me_route_drop_channel_closed_total 21
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 796205
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
telemt_pool_swap_total 133
telemt_me_writer_removed_unexpected_total 22527
telemt_me_refill_failed_total 141
telemt_me_writer_restored_same_endpoint_total 22084
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 436
telemt_user_connections_total{user="hello"} 769059
telemt_user_connections_current{user="hello"} 259
telemt_user_octets_from_client{user="hello"} 13242814992 (12.33 GB)
telemt_user_octets_to_client{user="hello"} 390920518472 (364.07 GB)
telemt_user_unique_ips_current{user="hello"} 97
telemt_user_unique_ips_recent_window{user="hello"} 26
```