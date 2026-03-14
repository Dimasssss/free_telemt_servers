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

# Server Metrics 2026-03-14 04:29:56 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 161796.3 (44h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 627504
telemt_connections_bad_total 31604
telemt_handshake_timeouts_total 12949
telemt_upstream_connect_attempt_total 41364
telemt_upstream_connect_success_total 41155
telemt_upstream_connect_fail_total 209
telemt_upstream_connect_attempts_per_request{bucket="1"} 41364
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18791
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22213
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 151
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 209
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 5551
telemt_me_reconnect_attempts_total 37396
telemt_me_reconnect_success_total 32712
telemt_me_reader_eof_total 34962
telemt_me_idle_close_by_peer_total 34961
telemt_me_route_drop_no_conn_total 203790
telemt_me_route_drop_channel_closed_total 30
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 531121
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1828
telemt_desync_full_logged_total 618
telemt_desync_suppressed_total 1210
telemt_desync_frames_bucket_total{bucket="1_2"} 390
telemt_desync_frames_bucket_total{bucket="3_10"} 675
telemt_desync_frames_bucket_total{bucket="gt_10"} 763
telemt_pool_swap_total 148
telemt_me_writer_removed_unexpected_total 33215
telemt_me_refill_failed_total 140
telemt_me_writer_restored_same_endpoint_total 32692
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 503
telemt_user_connections_total{user="hello"} 531010
telemt_user_connections_current{user="hello"} 262
telemt_user_octets_from_client{user="hello"} 15752405230 (14.67 GB)
telemt_user_octets_to_client{user="hello"} 257974021500 (240.26 GB)
telemt_user_msgs_from_client{user="hello"} 2142
telemt_user_msgs_to_client{user="hello"} 2404
telemt_user_unique_ips_current{user="hello"} 74
telemt_user_unique_ips_recent_window{user="hello"} 30
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 161689.2 (44h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 317304
telemt_connections_bad_total 2270
telemt_handshake_timeouts_total 2330
telemt_upstream_connect_attempt_total 147033
telemt_upstream_connect_success_total 145844
telemt_upstream_connect_fail_total 1189
telemt_upstream_connect_attempts_per_request{bucket="1"} 147033
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 108670
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 34757
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2417
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1189
telemt_me_keepalive_timeout_total 3869
telemt_me_reconnect_attempts_total 171287
telemt_me_reconnect_success_total 34479
telemt_me_reader_eof_total 39652
telemt_me_idle_close_by_peer_total 39652
telemt_me_route_drop_no_conn_total 100690
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 197377
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 41
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
telemt_pool_swap_total 31
telemt_me_writer_removed_unexpected_total 39083
telemt_me_refill_failed_total 4269
telemt_me_writer_restored_same_endpoint_total 34462
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 4604
telemt_user_connections_total{user="hello"} 300488
telemt_user_connections_current{user="hello"} 104
telemt_user_octets_from_client{user="hello"} 3136050627 (2.92 GB)
telemt_user_octets_to_client{user="hello"} 97066220223 (90.40 GB)
telemt_user_msgs_from_client{user="hello"} 1686033
telemt_user_msgs_to_client{user="hello"} 9368110
telemt_user_unique_ips_current{user="hello"} 38
telemt_user_unique_ips_recent_window{user="hello"} 13
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 161653.4 (44h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 369735
telemt_connections_bad_total 2932
telemt_handshake_timeouts_total 34808
telemt_upstream_connect_attempt_total 42862
telemt_upstream_connect_success_total 42853
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 42862
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19586
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23200
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 60
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 3393
telemt_me_reconnect_attempts_total 36036
telemt_me_reconnect_success_total 34755
telemt_me_reader_eof_total 37359
telemt_me_idle_close_by_peer_total 37359
telemt_me_route_drop_no_conn_total 132313
telemt_me_route_drop_channel_closed_total 18
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 319198
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
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
telemt_pool_swap_total 152
telemt_me_writer_removed_unexpected_total 35179
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 34734
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 424
telemt_user_connections_total{user="hello"} 318981
telemt_user_connections_current{user="hello"} 95
telemt_user_octets_from_client{user="hello"} 12702301296 (11.83 GB)
telemt_user_octets_to_client{user="hello"} 128144590624 (119.34 GB)
telemt_user_unique_ips_current{user="hello"} 34
telemt_user_unique_ips_recent_window{user="hello"} 13
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 161628.4 (44h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 471326
telemt_connections_bad_total 15556
telemt_handshake_timeouts_total 4410
telemt_upstream_connect_attempt_total 72608
telemt_upstream_connect_success_total 62089
telemt_upstream_connect_fail_total 10519
telemt_upstream_connect_attempts_per_request{bucket="1"} 72608
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 37017
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 24731
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 332
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10519
telemt_me_keepalive_timeout_total 5284
telemt_me_reconnect_attempts_total 141050
telemt_me_reconnect_success_total 35003
telemt_me_reader_eof_total 39396
telemt_me_idle_close_by_peer_total 39388
telemt_me_route_drop_no_conn_total 168820
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 400030
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 33
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1710
telemt_desync_full_logged_total 503
telemt_desync_suppressed_total 1207
telemt_desync_frames_bucket_total{bucket="1_2"} 401
telemt_desync_frames_bucket_total{bucket="3_10"} 647
telemt_desync_frames_bucket_total{bucket="gt_10"} 662
telemt_pool_swap_total 44
telemt_me_writer_removed_unexpected_total 38720
telemt_me_refill_failed_total 3307
telemt_me_writer_restored_same_endpoint_total 34993
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 3717
telemt_user_connections_total{user="hello"} 418880
telemt_user_connections_current{user="hello"} 128
telemt_user_octets_from_client{user="hello"} 9199770411 (8.57 GB)
telemt_user_octets_to_client{user="hello"} 163457145304 (152.23 GB)
telemt_user_msgs_from_client{user="hello"} 459818
telemt_user_msgs_to_client{user="hello"} 871707
telemt_user_unique_ips_current{user="hello"} 38
telemt_user_unique_ips_recent_window{user="hello"} 8
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 111800.0 (31h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 184138
telemt_connections_bad_total 26591
telemt_handshake_timeouts_total 1640
telemt_upstream_connect_attempt_total 40299
telemt_upstream_connect_success_total 39924
telemt_upstream_connect_fail_total 375
telemt_upstream_connect_attempts_per_request{bucket="1"} 40299
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20092
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19701
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 131
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 375
telemt_me_keepalive_timeout_total 2379
telemt_me_reconnect_attempts_total 42871
telemt_me_reconnect_success_total 29450
telemt_me_reader_eof_total 31519
telemt_me_idle_close_by_peer_total 31519
telemt_me_route_drop_no_conn_total 54610
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 145953
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 622
telemt_desync_full_logged_total 146
telemt_desync_suppressed_total 476
telemt_desync_frames_bucket_total{bucket="1_2"} 98
telemt_desync_frames_bucket_total{bucket="3_10"} 306
telemt_desync_frames_bucket_total{bucket="gt_10"} 218
telemt_pool_swap_total 84
telemt_me_writer_removed_unexpected_total 30134
telemt_me_refill_failed_total 416
telemt_me_writer_restored_same_endpoint_total 29432
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 42
telemt_me_writer_removed_unexpected_minus_restored_total 684
telemt_user_connections_total{user="hello"} 150706
telemt_user_connections_current{user="hello"} 37
telemt_user_octets_from_client{user="hello"} 2243828889 (2.09 GB)
telemt_user_octets_to_client{user="hello"} 68883464079 (64.15 GB)
telemt_user_msgs_from_client{user="hello"} 50955
telemt_user_msgs_to_client{user="hello"} 221508
telemt_user_unique_ips_current{user="hello"} 23
telemt_user_unique_ips_recent_window{user="hello"} 6
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 161584.5 (44h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 918888
telemt_connections_bad_total 28219
telemt_handshake_timeouts_total 25519
telemt_upstream_connect_attempt_total 33608
telemt_upstream_connect_success_total 33427
telemt_upstream_connect_fail_total 181
telemt_upstream_connect_attempts_per_request{bucket="1"} 33608
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15664
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17722
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 41
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 181
telemt_me_keepalive_timeout_total 4581
telemt_me_reconnect_attempts_total 30101
telemt_me_reconnect_success_total 25430
telemt_me_reader_eof_total 27296
telemt_me_idle_close_by_peer_total 27293
telemt_me_route_drop_no_conn_total 437210
telemt_me_route_drop_channel_closed_total 21
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 857966
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 760
telemt_desync_full_logged_total 250
telemt_desync_suppressed_total 510
telemt_desync_frames_bucket_total{bucket="1_2"} 256
telemt_desync_frames_bucket_total{bucket="3_10"} 248
telemt_desync_frames_bucket_total{bucket="gt_10"} 256
telemt_pool_swap_total 152
telemt_me_writer_removed_unexpected_total 25901
telemt_me_refill_failed_total 141
telemt_me_writer_restored_same_endpoint_total 25423
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 471
telemt_user_connections_total{user="hello"} 830630
telemt_user_connections_current{user="hello"} 314
telemt_user_octets_from_client{user="hello"} 14501797824 (13.51 GB)
telemt_user_octets_to_client{user="hello"} 420211664656 (391.35 GB)
telemt_user_unique_ips_current{user="hello"} 117
telemt_user_unique_ips_recent_window{user="hello"} 40
```