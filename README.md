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

# Server Metrics 2026-03-14 08:34:21 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 176460.9 (49h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 679479
telemt_connections_bad_total 32509
telemt_handshake_timeouts_total 13270
telemt_upstream_connect_attempt_total 44809
telemt_upstream_connect_success_total 44581
telemt_upstream_connect_fail_total 228
telemt_upstream_connect_attempts_per_request{bucket="1"} 44809
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20417
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 24012
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 152
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 228
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 5748
telemt_me_reconnect_attempts_total 40106
telemt_me_reconnect_success_total 35410
telemt_me_reader_eof_total 37858
telemt_me_idle_close_by_peer_total 37857
telemt_me_route_drop_no_conn_total 224713
telemt_me_route_drop_channel_closed_total 32
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 580060
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2235
telemt_desync_full_logged_total 758
telemt_desync_suppressed_total 1477
telemt_desync_frames_bucket_total{bucket="1_2"} 483
telemt_desync_frames_bucket_total{bucket="3_10"} 819
telemt_desync_frames_bucket_total{bucket="gt_10"} 933
telemt_pool_swap_total 162
telemt_me_writer_removed_unexpected_total 35936
telemt_me_refill_failed_total 140
telemt_me_writer_restored_same_endpoint_total 35390
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 526
telemt_user_connections_total{user="hello"} 579943
telemt_user_connections_current{user="hello"} 388
telemt_user_octets_from_client{user="hello"} 16950972906 (15.79 GB)
telemt_user_octets_to_client{user="hello"} 278610826612 (259.48 GB)
telemt_user_msgs_from_client{user="hello"} 2142
telemt_user_msgs_to_client{user="hello"} 2404
telemt_user_unique_ips_current{user="hello"} 114
telemt_user_unique_ips_recent_window{user="hello"} 47
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 176353.9 (48h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 342184
telemt_connections_bad_total 2783
telemt_handshake_timeouts_total 3016
telemt_upstream_connect_attempt_total 152167
telemt_upstream_connect_success_total 150861
telemt_upstream_connect_fail_total 1306
telemt_upstream_connect_attempts_per_request{bucket="1"} 152167
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 110660
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 37763
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2437
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1306
telemt_me_keepalive_timeout_total 5319
telemt_me_reconnect_attempts_total 179389
telemt_me_reconnect_success_total 38783
telemt_me_reader_eof_total 44229
telemt_me_idle_close_by_peer_total 44229
telemt_me_route_drop_no_conn_total 115043
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 219702
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 43
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
telemt_pool_swap_total 36
telemt_me_writer_removed_unexpected_total 43555
telemt_me_refill_failed_total 4387
telemt_me_writer_restored_same_endpoint_total 38766
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 4772
telemt_user_connections_total{user="hello"} 322808
telemt_user_connections_current{user="hello"} 104
telemt_user_octets_from_client{user="hello"} 3326378299 (3.10 GB)
telemt_user_octets_to_client{user="hello"} 104671057379 (97.48 GB)
telemt_user_msgs_from_client{user="hello"} 1686033
telemt_user_msgs_to_client{user="hello"} 9368110
telemt_user_unique_ips_current{user="hello"} 39
telemt_user_unique_ips_recent_window{user="hello"} 22
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 176317.6 (48h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 399797
telemt_connections_bad_total 3197
telemt_handshake_timeouts_total 35516
telemt_upstream_connect_attempt_total 46581
telemt_upstream_connect_success_total 46572
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 46581
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21301
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 25203
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 61
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 3511
telemt_me_reconnect_attempts_total 39055
telemt_me_reconnect_success_total 37763
telemt_me_reader_eof_total 40587
telemt_me_idle_close_by_peer_total 40587
telemt_me_route_drop_no_conn_total 144437
telemt_me_route_drop_channel_closed_total 22
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 346999
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 123
telemt_desync_full_logged_total 55
telemt_desync_suppressed_total 68
telemt_desync_frames_bucket_total{bucket="1_2"} 13
telemt_desync_frames_bucket_total{bucket="3_10"} 41
telemt_desync_frames_bucket_total{bucket="gt_10"} 69
telemt_pool_swap_total 166
telemt_me_writer_removed_unexpected_total 38220
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 37742
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 457
telemt_user_connections_total{user="hello"} 346760
telemt_user_connections_current{user="hello"} 151
telemt_user_octets_from_client{user="hello"} 13660290836 (12.72 GB)
telemt_user_octets_to_client{user="hello"} 144836520820 (134.89 GB)
telemt_user_unique_ips_current{user="hello"} 67
telemt_user_unique_ips_recent_window{user="hello"} 30
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 176293.1 (48h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 502042
telemt_connections_bad_total 16283
telemt_handshake_timeouts_total 4583
telemt_upstream_connect_attempt_total 76987
telemt_upstream_connect_success_total 66361
telemt_upstream_connect_fail_total 10626
telemt_upstream_connect_attempts_per_request{bucket="1"} 76987
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 38969
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 27038
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 345
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10626
telemt_me_keepalive_timeout_total 5482
telemt_me_reconnect_attempts_total 148404
telemt_me_reconnect_success_total 38564
telemt_me_reader_eof_total 43227
telemt_me_idle_close_by_peer_total 43219
telemt_me_route_drop_no_conn_total 181784
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 428683
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 34
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1872
telemt_desync_full_logged_total 555
telemt_desync_suppressed_total 1317
telemt_desync_frames_bucket_total{bucket="1_2"} 442
telemt_desync_frames_bucket_total{bucket="3_10"} 722
telemt_desync_frames_bucket_total{bucket="gt_10"} 708
telemt_pool_swap_total 50
telemt_me_writer_removed_unexpected_total 42436
telemt_me_refill_failed_total 3425
telemt_me_writer_restored_same_endpoint_total 38554
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 3872
telemt_user_connections_total{user="hello"} 447565
telemt_user_connections_current{user="hello"} 188
telemt_user_octets_from_client{user="hello"} 9670232531 (9.01 GB)
telemt_user_octets_to_client{user="hello"} 185294032020 (172.57 GB)
telemt_user_msgs_from_client{user="hello"} 459818
telemt_user_msgs_to_client{user="hello"} 871707
telemt_user_unique_ips_current{user="hello"} 57
telemt_user_unique_ips_recent_window{user="hello"} 21
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 126464.6 (35h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 207725
telemt_connections_bad_total 31633
telemt_handshake_timeouts_total 1769
telemt_upstream_connect_attempt_total 44571
telemt_upstream_connect_success_total 44141
telemt_upstream_connect_fail_total 430
telemt_upstream_connect_attempts_per_request{bucket="1"} 44571
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 22082
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21915
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 144
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 430
telemt_me_keepalive_timeout_total 2566
telemt_me_reconnect_attempts_total 47676
telemt_me_reconnect_success_total 32959
telemt_me_reader_eof_total 35266
telemt_me_idle_close_by_peer_total 35266
telemt_me_route_drop_no_conn_total 62348
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 163761
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 709
telemt_desync_full_logged_total 172
telemt_desync_suppressed_total 537
telemt_desync_frames_bucket_total{bucket="1_2"} 118
telemt_desync_frames_bucket_total{bucket="3_10"} 338
telemt_desync_frames_bucket_total{bucket="gt_10"} 253
telemt_pool_swap_total 96
telemt_me_writer_removed_unexpected_total 33719
telemt_me_refill_failed_total 456
telemt_me_writer_restored_same_endpoint_total 32941
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 42
telemt_me_writer_removed_unexpected_minus_restored_total 760
telemt_user_connections_total{user="hello"} 168523
telemt_user_connections_current{user="hello"} 94
telemt_user_octets_from_client{user="hello"} 2472351253 (2.30 GB)
telemt_user_octets_to_client{user="hello"} 80713821755 (75.17 GB)
telemt_user_msgs_from_client{user="hello"} 50955
telemt_user_msgs_to_client{user="hello"} 221508
telemt_user_unique_ips_current{user="hello"} 37
telemt_user_unique_ips_recent_window{user="hello"} 24
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 176249.3 (48h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1014280
telemt_connections_bad_total 36334
telemt_handshake_timeouts_total 26349
telemt_upstream_connect_attempt_total 36698
telemt_upstream_connect_success_total 36503
telemt_upstream_connect_fail_total 195
telemt_upstream_connect_attempts_per_request{bucket="1"} 36698
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17185
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19277
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 41
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 195
telemt_me_keepalive_timeout_total 4759
telemt_me_reconnect_attempts_total 32481
telemt_me_reconnect_success_total 27798
telemt_me_reader_eof_total 29808
telemt_me_idle_close_by_peer_total 29805
telemt_me_route_drop_no_conn_total 476734
telemt_me_route_drop_channel_closed_total 25
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 940098
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 787
telemt_desync_full_logged_total 257
telemt_desync_suppressed_total 530
telemt_desync_frames_bucket_total{bucket="1_2"} 260
telemt_desync_frames_bucket_total{bucket="3_10"} 262
telemt_desync_frames_bucket_total{bucket="gt_10"} 265
telemt_pool_swap_total 166
telemt_me_writer_removed_unexpected_total 28294
telemt_me_refill_failed_total 141
telemt_me_writer_restored_same_endpoint_total 27791
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 496
telemt_user_connections_total{user="hello"} 912730
telemt_user_connections_current{user="hello"} 434
telemt_user_octets_from_client{user="hello"} 15472852976 (14.41 GB)
telemt_user_octets_to_client{user="hello"} 454981616712 (423.73 GB)
telemt_user_unique_ips_current{user="hello"} 187
telemt_user_unique_ips_recent_window{user="hello"} 72
```