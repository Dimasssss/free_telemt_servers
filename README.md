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

# Server Metrics 2026-03-14 12:18:11 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 189891.0 (52h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 751515
telemt_connections_bad_total 35643
telemt_handshake_timeouts_total 14474
telemt_upstream_connect_attempt_total 48145
telemt_upstream_connect_success_total 47906
telemt_upstream_connect_fail_total 239
telemt_upstream_connect_attempts_per_request{bucket="1"} 48145
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21928
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 25824
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 154
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 239
telemt_me_keepalive_failed_total 4
telemt_me_keepalive_timeout_total 6337
telemt_me_reconnect_attempts_total 43851
telemt_me_reconnect_success_total 38084
telemt_me_reader_eof_total 40717
telemt_me_idle_close_by_peer_total 40716
telemt_me_route_drop_no_conn_total 247248
telemt_me_route_drop_channel_closed_total 41
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 644246
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2746
telemt_desync_full_logged_total 917
telemt_desync_suppressed_total 1829
telemt_desync_frames_bucket_total{bucket="1_2"} 565
telemt_desync_frames_bucket_total{bucket="3_10"} 1031
telemt_desync_frames_bucket_total{bucket="gt_10"} 1150
telemt_pool_swap_total 172
telemt_me_writer_removed_unexpected_total 38673
telemt_me_refill_failed_total 173
telemt_me_writer_restored_same_endpoint_total 38064
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 589
telemt_user_connections_total{user="hello"} 644152
telemt_user_connections_current{user="hello"} 418
telemt_user_octets_from_client{user="hello"} 17873241742 (16.65 GB)
telemt_user_octets_to_client{user="hello"} 309090377784 (287.86 GB)
telemt_user_msgs_from_client{user="hello"} 2142
telemt_user_msgs_to_client{user="hello"} 2404
telemt_user_unique_ips_current{user="hello"} 114
telemt_user_unique_ips_recent_window{user="hello"} 40
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 189783.6 (52h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 371980
telemt_connections_bad_total 2848
telemt_handshake_timeouts_total 3349
telemt_upstream_connect_attempt_total 157956
telemt_upstream_connect_success_total 156562
telemt_upstream_connect_fail_total 1394
telemt_upstream_connect_attempts_per_request{bucket="1"} 157956
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 113782
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 40257
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2522
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1394
telemt_me_keepalive_timeout_total 5713
telemt_me_reconnect_attempts_total 196639
telemt_me_reconnect_success_total 42009
telemt_me_reader_eof_total 47932
telemt_me_idle_close_by_peer_total 47932
telemt_me_route_drop_no_conn_total 128467
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 246355
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 47
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
telemt_pool_swap_total 38
telemt_me_writer_removed_unexpected_total 47241
telemt_me_refill_failed_total 4824
telemt_me_writer_restored_same_endpoint_total 41991
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 5232
telemt_user_connections_total{user="hello"} 351248
telemt_user_connections_current{user="hello"} 147
telemt_user_octets_from_client{user="hello"} 3562713959 (3.32 GB)
telemt_user_octets_to_client{user="hello"} 112975873974 (105.22 GB)
telemt_user_msgs_from_client{user="hello"} 1713995
telemt_user_msgs_to_client{user="hello"} 9567945
telemt_user_unique_ips_current{user="hello"} 39
telemt_user_unique_ips_recent_window{user="hello"} 11
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 189747.3 (52h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 429460
telemt_connections_bad_total 3320
telemt_handshake_timeouts_total 36673
telemt_upstream_connect_attempt_total 50644
telemt_upstream_connect_success_total 50635
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 50644
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 23273
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 27284
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 71
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 4299
telemt_me_reconnect_attempts_total 42408
telemt_me_reconnect_success_total 41085
telemt_me_reader_eof_total 44126
telemt_me_idle_close_by_peer_total 44126
telemt_me_route_drop_no_conn_total 157290
telemt_me_route_drop_channel_closed_total 23
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 374052
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 146
telemt_desync_full_logged_total 66
telemt_desync_suppressed_total 80
telemt_desync_frames_bucket_total{bucket="1_2"} 15
telemt_desync_frames_bucket_total{bucket="3_10"} 52
telemt_desync_frames_bucket_total{bucket="gt_10"} 79
telemt_pool_swap_total 176
telemt_me_writer_removed_unexpected_total 41578
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 41064
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 493
telemt_user_connections_total{user="hello"} 373811
telemt_user_connections_current{user="hello"} 145
telemt_user_octets_from_client{user="hello"} 16192877762 (15.08 GB)
telemt_user_octets_to_client{user="hello"} 163546884583 (152.31 GB)
telemt_user_msgs_from_client{user="hello"} 166
telemt_user_msgs_to_client{user="hello"} 712
telemt_user_unique_ips_current{user="hello"} 58
telemt_user_unique_ips_recent_window{user="hello"} 19
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 189722.7 (52h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 546076
telemt_connections_bad_total 16779
telemt_handshake_timeouts_total 5334
telemt_upstream_connect_attempt_total 81089
telemt_upstream_connect_success_total 70376
telemt_upstream_connect_fail_total 10713
telemt_upstream_connect_attempts_per_request{bucket="1"} 81089
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 40887
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 29088
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 392
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10713
telemt_me_keepalive_timeout_total 5852
telemt_me_reconnect_attempts_total 157560
telemt_me_reconnect_success_total 41893
telemt_me_reader_eof_total 46836
telemt_me_idle_close_by_peer_total 46828
telemt_me_route_drop_no_conn_total 197671
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 468271
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 37
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2170
telemt_desync_full_logged_total 635
telemt_desync_suppressed_total 1535
telemt_desync_frames_bucket_total{bucket="1_2"} 501
telemt_desync_frames_bucket_total{bucket="3_10"} 825
telemt_desync_frames_bucket_total{bucket="gt_10"} 844
telemt_pool_swap_total 54
telemt_me_writer_removed_unexpected_total 45985
telemt_me_refill_failed_total 3606
telemt_me_writer_restored_same_endpoint_total 41883
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 4092
telemt_user_connections_total{user="hello"} 487134
telemt_user_connections_current{user="hello"} 208
telemt_user_octets_from_client{user="hello"} 10302654579 (9.60 GB)
telemt_user_octets_to_client{user="hello"} 201024100208 (187.22 GB)
telemt_user_msgs_from_client{user="hello"} 459818
telemt_user_msgs_to_client{user="hello"} 871707
telemt_user_unique_ips_current{user="hello"} 68
telemt_user_unique_ips_recent_window{user="hello"} 28
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 139894.4 (38h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 238052
telemt_connections_bad_total 38392
telemt_handshake_timeouts_total 2195
telemt_upstream_connect_attempt_total 49254
telemt_upstream_connect_success_total 48756
telemt_upstream_connect_fail_total 498
telemt_upstream_connect_attempts_per_request{bucket="1"} 49254
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 24292
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 24295
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 169
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 498
telemt_me_keepalive_timeout_total 3132
telemt_me_reconnect_attempts_total 55056
telemt_me_reconnect_success_total 36894
telemt_me_reader_eof_total 39483
telemt_me_idle_close_by_peer_total 39483
telemt_me_route_drop_no_conn_total 72358
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 186196
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 9
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 812
telemt_desync_full_logged_total 197
telemt_desync_suppressed_total 615
telemt_desync_frames_bucket_total{bucket="1_2"} 134
telemt_desync_frames_bucket_total{bucket="3_10"} 382
telemt_desync_frames_bucket_total{bucket="gt_10"} 296
telemt_pool_swap_total 102
telemt_me_writer_removed_unexpected_total 37809
telemt_me_refill_failed_total 563
telemt_me_writer_restored_same_endpoint_total 36876
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 42
telemt_me_writer_removed_unexpected_minus_restored_total 915
telemt_user_connections_total{user="hello"} 190952
telemt_user_connections_current{user="hello"} 55
telemt_user_octets_from_client{user="hello"} 2770318657 (2.58 GB)
telemt_user_octets_to_client{user="hello"} 87948488107 (81.91 GB)
telemt_user_msgs_from_client{user="hello"} 50955
telemt_user_msgs_to_client{user="hello"} 221508
telemt_user_unique_ips_current{user="hello"} 33
telemt_user_unique_ips_recent_window{user="hello"} 9
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 189679.3 (52h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1107056
telemt_connections_bad_total 37793
telemt_handshake_timeouts_total 27273
telemt_upstream_connect_attempt_total 39513
telemt_upstream_connect_success_total 39306
telemt_upstream_connect_fail_total 207
telemt_upstream_connect_attempts_per_request{bucket="1"} 39513
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18618
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20647
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 41
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 207
telemt_me_keepalive_timeout_total 5206
telemt_me_reconnect_attempts_total 34625
telemt_me_reconnect_success_total 29931
telemt_me_reader_eof_total 32092
telemt_me_idle_close_by_peer_total 32089
telemt_me_route_drop_no_conn_total 520698
telemt_me_route_drop_channel_closed_total 36
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1026716
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
telemt_pool_swap_total 177
telemt_me_writer_removed_unexpected_total 30456
telemt_me_refill_failed_total 141
telemt_me_writer_restored_same_endpoint_total 29924
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 525
telemt_user_connections_total{user="hello"} 999306
telemt_user_connections_current{user="hello"} 414
telemt_user_octets_from_client{user="hello"} 21376239228 (19.91 GB)
telemt_user_octets_to_client{user="hello"} 502617429572 (468.10 GB)
telemt_user_unique_ips_current{user="hello"} 176
telemt_user_unique_ips_recent_window{user="hello"} 60
```