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

# Server Metrics 2026-03-13 10:49:55 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 98196.9 (27h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 392192
telemt_connections_bad_total 3194
telemt_handshake_timeouts_total 8122
telemt_upstream_connect_attempt_total 24860
telemt_upstream_connect_success_total 24744
telemt_upstream_connect_fail_total 116
telemt_upstream_connect_attempts_per_request{bucket="1"} 24860
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11160
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13536
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 48
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 116
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 1789
telemt_me_reconnect_attempts_total 23315
telemt_me_reconnect_success_total 19793
telemt_me_reader_eof_total 21130
telemt_me_idle_close_by_peer_total 21129
telemt_me_route_drop_no_conn_total 122560
telemt_me_route_drop_channel_closed_total 21
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 338287
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1079
telemt_desync_full_logged_total 400
telemt_desync_suppressed_total 679
telemt_desync_frames_bucket_total{bucket="1_2"} 223
telemt_desync_frames_bucket_total{bucket="3_10"} 396
telemt_desync_frames_bucket_total{bucket="gt_10"} 460
telemt_pool_swap_total 88
telemt_me_writer_removed_unexpected_total 20110
telemt_me_refill_failed_total 106
telemt_me_writer_restored_same_endpoint_total 19777
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 317
telemt_user_connections_total{user="hello"} 337991
telemt_user_connections_current{user="hello"} 371
telemt_user_octets_from_client{user="hello"} 6004153424 (5.59 GB)
telemt_user_octets_to_client{user="hello"} 146213878668 (136.17 GB)
telemt_user_unique_ips_current{user="hello"} 106
telemt_user_unique_ips_recent_window{user="hello"} 43
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 98089.5 (27h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 179582
telemt_connections_bad_total 1565
telemt_handshake_timeouts_total 1378
telemt_upstream_connect_attempt_total 47715
telemt_upstream_connect_success_total 47048
telemt_upstream_connect_fail_total 667
telemt_upstream_connect_attempts_per_request{bucket="1"} 47715
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26999
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19532
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 517
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 667
telemt_me_keepalive_timeout_total 774
telemt_me_reconnect_attempts_total 87247
telemt_me_reconnect_success_total 25668
telemt_me_reader_eof_total 28346
telemt_me_idle_close_by_peer_total 28346
telemt_me_route_drop_no_conn_total 76600
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 152875
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 21
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
telemt_pool_swap_total 26
telemt_me_writer_removed_unexpected_total 27811
telemt_me_refill_failed_total 1921
telemt_me_writer_restored_same_endpoint_total 25652
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 2143
telemt_user_connections_total{user="hello"} 169154
telemt_user_connections_current{user="hello"} 176
telemt_user_octets_from_client{user="hello"} 1742545176 (1.62 GB)
telemt_user_octets_to_client{user="hello"} 56784793095 (52.88 GB)
telemt_user_msgs_from_client{user="hello"} 257002
telemt_user_msgs_to_client{user="hello"} 2006834
telemt_user_unique_ips_current{user="hello"} 61
telemt_user_unique_ips_recent_window{user="hello"} 25
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 98053.4 (27h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 218852
telemt_connections_bad_total 2050
telemt_handshake_timeouts_total 4517
telemt_upstream_connect_attempt_total 26474
telemt_upstream_connect_success_total 26471
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 26474
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12197
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14249
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 23
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 782
telemt_me_reconnect_attempts_total 22736
telemt_me_reconnect_success_total 21537
telemt_me_reader_eof_total 23090
telemt_me_idle_close_by_peer_total 23090
telemt_me_route_drop_no_conn_total 81772
telemt_me_route_drop_channel_closed_total 12
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 204236
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 63
telemt_desync_full_logged_total 31
telemt_desync_suppressed_total 32
telemt_desync_frames_bucket_total{bucket="1_2"} 3
telemt_desync_frames_bucket_total{bucket="3_10"} 21
telemt_desync_frames_bucket_total{bucket="gt_10"} 39
telemt_pool_swap_total 89
telemt_me_writer_removed_unexpected_total 21772
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 21517
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 235
telemt_user_connections_total{user="hello"} 204157
telemt_user_connections_current{user="hello"} 160
telemt_user_octets_from_client{user="hello"} 9216055952 (8.58 GB)
telemt_user_octets_to_client{user="hello"} 84648823384 (78.84 GB)
telemt_user_unique_ips_current{user="hello"} 62
telemt_user_unique_ips_recent_window{user="hello"} 24
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 98028.8 (27h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 307656
telemt_connections_bad_total 13676
telemt_handshake_timeouts_total 2268
telemt_upstream_connect_attempt_total 39078
telemt_upstream_connect_success_total 29043
telemt_upstream_connect_fail_total 10035
telemt_upstream_connect_attempts_per_request{bucket="1"} 39078
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14566
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14274
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 194
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10035
telemt_me_keepalive_timeout_total 3445
telemt_me_reconnect_attempts_total 84595
telemt_me_reconnect_success_total 21302
telemt_me_reader_eof_total 23926
telemt_me_idle_close_by_peer_total 23919
telemt_me_route_drop_no_conn_total 111402
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 264260
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 20
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 968
telemt_desync_full_logged_total 287
telemt_desync_suppressed_total 681
telemt_desync_frames_bucket_total{bucket="1_2"} 241
telemt_desync_frames_bucket_total{bucket="3_10"} 357
telemt_desync_frames_bucket_total{bucket="gt_10"} 370
telemt_pool_swap_total 26
telemt_me_writer_removed_unexpected_total 23548
telemt_me_refill_failed_total 1973
telemt_me_writer_restored_same_endpoint_total 21292
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 2246
telemt_user_connections_total{user="hello"} 266981
telemt_user_connections_current{user="hello"} 193
telemt_user_octets_from_client{user="hello"} 5697822790 (5.31 GB)
telemt_user_octets_to_client{user="hello"} 99428798649 (92.60 GB)
telemt_user_msgs_from_client{user="hello"} 67768
telemt_user_msgs_to_client{user="hello"} 112762
telemt_user_unique_ips_current{user="hello"} 64
telemt_user_unique_ips_recent_window{user="hello"} 32
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 48200.4 (13h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 66223
telemt_connections_bad_total 9630
telemt_handshake_timeouts_total 718
telemt_upstream_connect_attempt_total 16913
telemt_upstream_connect_success_total 16750
telemt_upstream_connect_fail_total 163
telemt_upstream_connect_attempts_per_request{bucket="1"} 16913
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7305
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9388
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 57
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 163
telemt_me_keepalive_timeout_total 437
telemt_me_reconnect_attempts_total 18834
telemt_me_reconnect_success_total 14332
telemt_me_reader_eof_total 15275
telemt_me_idle_close_by_peer_total 15275
telemt_me_route_drop_no_conn_total 20821
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 53850
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 79
telemt_desync_full_logged_total 14
telemt_desync_suppressed_total 65
telemt_desync_frames_bucket_total{bucket="1_2"} 7
telemt_desync_frames_bucket_total{bucket="3_10"} 34
telemt_desync_frames_bucket_total{bucket="gt_10"} 38
telemt_pool_swap_total 36
telemt_me_writer_removed_unexpected_total 14602
telemt_me_refill_failed_total 139
telemt_me_writer_restored_same_endpoint_total 14314
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 270
telemt_user_connections_total{user="hello"} 53846
telemt_user_connections_current{user="hello"} 85
telemt_user_octets_from_client{user="hello"} 488018948 (465.41 MB)
telemt_user_octets_to_client{user="hello"} 14435951872 (13.44 GB)
telemt_user_unique_ips_current{user="hello"} 36
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 97985.2 (27h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 542553
telemt_connections_bad_total 14514
telemt_handshake_timeouts_total 9528
telemt_upstream_connect_attempt_total 20886
telemt_upstream_connect_success_total 20777
telemt_upstream_connect_fail_total 109
telemt_upstream_connect_attempts_per_request{bucket="1"} 20886
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9740
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11012
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 109
telemt_me_keepalive_timeout_total 1614
telemt_me_reconnect_attempts_total 20527
telemt_me_reconnect_success_total 15910
telemt_me_reader_eof_total 17081
telemt_me_idle_close_by_peer_total 17078
telemt_me_route_drop_no_conn_total 275275
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 526389
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 438
telemt_desync_full_logged_total 166
telemt_desync_suppressed_total 272
telemt_desync_frames_bucket_total{bucket="1_2"} 106
telemt_desync_frames_bucket_total{bucket="3_10"} 164
telemt_desync_frames_bucket_total{bucket="gt_10"} 168
telemt_pool_swap_total 89
telemt_me_writer_removed_unexpected_total 16263
telemt_me_refill_failed_total 141
telemt_me_writer_restored_same_endpoint_total 15903
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 353
telemt_user_connections_total{user="hello"} 499468
telemt_user_connections_current{user="hello"} 484
telemt_user_octets_from_client{user="hello"} 9174053692 (8.54 GB)
telemt_user_octets_to_client{user="hello"} 276602599140 (257.61 GB)
telemt_user_unique_ips_current{user="hello"} 181
telemt_user_unique_ips_recent_window{user="hello"} 77
```