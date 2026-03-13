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

# Server Metrics 2026-03-13 19:40:16 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 130017.3 (36h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 551361
telemt_connections_bad_total 13574
telemt_handshake_timeouts_total 12466
telemt_upstream_connect_attempt_total 32920
telemt_upstream_connect_success_total 32753
telemt_upstream_connect_fail_total 167
telemt_upstream_connect_attempts_per_request{bucket="1"} 32920
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15082
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17529
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 142
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 167
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 5047
telemt_me_reconnect_attempts_total 30512
telemt_me_reconnect_success_total 25861
telemt_me_reader_eof_total 27613
telemt_me_idle_close_by_peer_total 27612
telemt_me_route_drop_no_conn_total 181993
telemt_me_route_drop_channel_closed_total 28
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 475894
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1535
telemt_desync_full_logged_total 523
telemt_desync_suppressed_total 1012
telemt_desync_frames_bucket_total{bucket="1_2"} 333
telemt_desync_frames_bucket_total{bucket="3_10"} 564
telemt_desync_frames_bucket_total{bucket="gt_10"} 638
telemt_pool_swap_total 116
telemt_me_writer_removed_unexpected_total 26297
telemt_me_refill_failed_total 140
telemt_me_writer_restored_same_endpoint_total 25845
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 436
telemt_user_connections_total{user="hello"} 475789
telemt_user_connections_current{user="hello"} 294
telemt_user_octets_from_client{user="hello"} 8783133082 (8.18 GB)
telemt_user_octets_to_client{user="hello"} 227330673052 (211.72 GB)
telemt_user_msgs_from_client{user="hello"} 2142
telemt_user_msgs_to_client{user="hello"} 2404
telemt_user_unique_ips_current{user="hello"} 82
telemt_user_unique_ips_recent_window{user="hello"} 25
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 129909.9 (36h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 276078
telemt_connections_bad_total 2098
telemt_handshake_timeouts_total 1875
telemt_upstream_connect_attempt_total 127084
telemt_upstream_connect_success_total 126143
telemt_upstream_connect_fail_total 941
telemt_upstream_connect_attempts_per_request{bucket="1"} 127084
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 95786
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 28129
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2228
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 941
telemt_me_keepalive_timeout_total 3604
telemt_me_reconnect_attempts_total 136523
telemt_me_reconnect_success_total 26304
telemt_me_reader_eof_total 30486
telemt_me_idle_close_by_peer_total 30486
telemt_me_route_drop_no_conn_total 83700
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 168492
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 33
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
telemt_me_writer_removed_unexpected_total 29993
telemt_me_refill_failed_total 3439
telemt_me_writer_restored_same_endpoint_total 26287
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 3689
telemt_user_connections_total{user="hello"} 261626
telemt_user_connections_current{user="hello"} 181
telemt_user_octets_from_client{user="hello"} 2698098748 (2.51 GB)
telemt_user_octets_to_client{user="hello"} 78673120894 (73.27 GB)
telemt_user_msgs_from_client{user="hello"} 1466215
telemt_user_msgs_to_client{user="hello"} 8160412
telemt_user_unique_ips_current{user="hello"} 42
telemt_user_unique_ips_recent_window{user="hello"} 18
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 129873.4 (36h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 323162
telemt_connections_bad_total 2635
telemt_handshake_timeouts_total 22189
telemt_upstream_connect_attempt_total 34499
telemt_upstream_connect_success_total 34494
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 34499
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15967
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18488
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 37
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 2788
telemt_me_reconnect_attempts_total 29193
telemt_me_reconnect_success_total 27955
telemt_me_reader_eof_total 29996
telemt_me_idle_close_by_peer_total 29996
telemt_me_route_drop_no_conn_total 115685
telemt_me_route_drop_channel_closed_total 18
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 287082
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
telemt_pool_swap_total 120
telemt_me_writer_removed_unexpected_total 28273
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 27935
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 318
telemt_user_connections_total{user="hello"} 286992
telemt_user_connections_current{user="hello"} 109
telemt_user_octets_from_client{user="hello"} 11750222312 (10.94 GB)
telemt_user_octets_to_client{user="hello"} 120338478872 (112.07 GB)
telemt_user_unique_ips_current{user="hello"} 48
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 129849.1 (36h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 428115
telemt_connections_bad_total 15200
telemt_handshake_timeouts_total 4138
telemt_upstream_connect_attempt_total 62408
telemt_upstream_connect_success_total 52115
telemt_upstream_connect_fail_total 10293
telemt_upstream_connect_attempts_per_request{bucket="1"} 62408
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 32684
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19127
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 295
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10293
telemt_me_keepalive_timeout_total 4722
telemt_me_reconnect_attempts_total 117211
telemt_me_reconnect_success_total 26589
telemt_me_reader_eof_total 30187
telemt_me_idle_close_by_peer_total 30180
telemt_me_route_drop_no_conn_total 148144
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 359376
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 28
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1449
telemt_desync_full_logged_total 432
telemt_desync_suppressed_total 1017
telemt_desync_frames_bucket_total{bucket="1_2"} 349
telemt_desync_frames_bucket_total{bucket="3_10"} 552
telemt_desync_frames_bucket_total{bucket="gt_10"} 548
telemt_pool_swap_total 32
telemt_me_writer_removed_unexpected_total 29757
telemt_me_refill_failed_total 2826
telemt_me_writer_restored_same_endpoint_total 26579
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 3168
telemt_user_connections_total{user="hello"} 378241
telemt_user_connections_current{user="hello"} 166
telemt_user_octets_from_client{user="hello"} 8564720487 (7.98 GB)
telemt_user_octets_to_client{user="hello"} 136065585884 (126.72 GB)
telemt_user_msgs_from_client{user="hello"} 459818
telemt_user_msgs_to_client{user="hello"} 871707
telemt_user_unique_ips_current{user="hello"} 48
telemt_user_unique_ips_recent_window{user="hello"} 25
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 80020.7 (22h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 135505
telemt_connections_bad_total 16902
telemt_handshake_timeouts_total 1424
telemt_upstream_connect_attempt_total 30664
telemt_upstream_connect_success_total 30373
telemt_upstream_connect_fail_total 291
telemt_upstream_connect_attempts_per_request{bucket="1"} 30664
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15682
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14590
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 101
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 291
telemt_me_keepalive_timeout_total 1249
telemt_me_reconnect_attempts_total 34878
telemt_me_reconnect_success_total 21487
telemt_me_reader_eof_total 23016
telemt_me_idle_close_by_peer_total 23016
telemt_me_route_drop_no_conn_total 42355
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 107879
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 594
telemt_desync_full_logged_total 136
telemt_desync_suppressed_total 458
telemt_desync_frames_bucket_total{bucket="1_2"} 83
telemt_desync_frames_bucket_total{bucket="3_10"} 297
telemt_desync_frames_bucket_total{bucket="gt_10"} 214
telemt_pool_swap_total 54
telemt_me_writer_removed_unexpected_total 22104
telemt_me_refill_failed_total 416
telemt_me_writer_restored_same_endpoint_total 21469
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 617
telemt_user_connections_total{user="hello"} 112773
telemt_user_connections_current{user="hello"} 107
telemt_user_octets_from_client{user="hello"} 1313445297 (1.22 GB)
telemt_user_octets_to_client{user="hello"} 45380152911 (42.26 GB)
telemt_user_msgs_from_client{user="hello"} 50955
telemt_user_msgs_to_client{user="hello"} 221508
telemt_user_unique_ips_current{user="hello"} 41
telemt_user_unique_ips_recent_window{user="hello"} 22
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 129805.5 (36h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 795479
telemt_connections_bad_total 24790
telemt_handshake_timeouts_total 24884
telemt_upstream_connect_attempt_total 26770
telemt_upstream_connect_success_total 26628
telemt_upstream_connect_fail_total 142
telemt_upstream_connect_attempts_per_request{bucket="1"} 26770
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12452
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14140
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 36
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 142
telemt_me_keepalive_timeout_total 3052
telemt_me_reconnect_attempts_total 24819
telemt_me_reconnect_success_total 20172
telemt_me_reader_eof_total 21649
telemt_me_idle_close_by_peer_total 21646
telemt_me_route_drop_no_conn_total 378043
telemt_me_route_drop_channel_closed_total 19
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 745803
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 691
telemt_desync_full_logged_total 225
telemt_desync_suppressed_total 466
telemt_desync_frames_bucket_total{bucket="1_2"} 247
telemt_desync_frames_bucket_total{bucket="3_10"} 226
telemt_desync_frames_bucket_total{bucket="gt_10"} 218
telemt_pool_swap_total 121
telemt_me_writer_removed_unexpected_total 20588
telemt_me_refill_failed_total 141
telemt_me_writer_restored_same_endpoint_total 20165
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 416
telemt_user_connections_total{user="hello"} 718671
telemt_user_connections_current{user="hello"} 419
telemt_user_octets_from_client{user="hello"} 12420618820 (11.57 GB)
telemt_user_octets_to_client{user="hello"} 352957481572 (328.72 GB)
telemt_user_unique_ips_current{user="hello"} 144
telemt_user_unique_ips_recent_window{user="hello"} 47
```