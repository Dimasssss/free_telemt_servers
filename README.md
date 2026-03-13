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

# Server Metrics 2026-03-13 01:40:19 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 65216.1 (18h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 265179
telemt_connections_bad_total 2773
telemt_handshake_timeouts_total 5615
telemt_upstream_connect_attempt_total 16510
telemt_upstream_connect_success_total 16439
telemt_upstream_connect_fail_total 71
telemt_upstream_connect_attempts_per_request{bucket="1"} 16510
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7271
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9122
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 46
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 71
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 1512
telemt_me_reconnect_attempts_total 16621
telemt_me_reconnect_success_total 13144
telemt_me_reader_eof_total 14031
telemt_me_idle_close_by_peer_total 14030
telemt_me_route_drop_no_conn_total 82390
telemt_me_route_drop_channel_closed_total 14
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 220012
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 728
telemt_desync_full_logged_total 274
telemt_desync_suppressed_total 454
telemt_desync_frames_bucket_total{bucket="1_2"} 129
telemt_desync_frames_bucket_total{bucket="3_10"} 271
telemt_desync_frames_bucket_total{bucket="gt_10"} 328
telemt_pool_swap_total 56
telemt_me_writer_removed_unexpected_total 13394
telemt_me_refill_failed_total 106
telemt_me_writer_restored_same_endpoint_total 13128
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 250
telemt_user_connections_total{user="hello"} 219780
telemt_user_connections_current{user="hello"} 199
telemt_user_octets_from_client{user="hello"} 3955398744 (3.68 GB)
telemt_user_octets_to_client{user="hello"} 110000950636 (102.45 GB)
telemt_user_unique_ips_current{user="hello"} 63
telemt_user_unique_ips_recent_window{user="hello"} 13
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 65109.0 (18h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 123232
telemt_connections_bad_total 733
telemt_handshake_timeouts_total 975
telemt_upstream_connect_attempt_total 36359
telemt_upstream_connect_success_total 35914
telemt_upstream_connect_fail_total 445
telemt_upstream_connect_attempts_per_request{bucket="1"} 36359
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 22473
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12940
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 501
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 445
telemt_me_keepalive_timeout_total 462
telemt_me_reconnect_attempts_total 60348
telemt_me_reconnect_success_total 16135
telemt_me_reader_eof_total 17941
telemt_me_idle_close_by_peer_total 17941
telemt_me_route_drop_no_conn_total 44000
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 100475
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 31
telemt_desync_full_logged_total 9
telemt_desync_suppressed_total 22
telemt_desync_frames_bucket_total{bucket="1_2"} 2
telemt_desync_frames_bucket_total{bucket="3_10"} 12
telemt_desync_frames_bucket_total{bucket="gt_10"} 17
telemt_pool_swap_total 16
telemt_me_writer_removed_unexpected_total 17633
telemt_me_refill_failed_total 1380
telemt_me_writer_restored_same_endpoint_total 16120
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 1498
telemt_user_connections_total{user="hello"} 116975
telemt_user_connections_current{user="hello"} 105
telemt_user_octets_from_client{user="hello"} 1251310272 (1.17 GB)
telemt_user_octets_to_client{user="hello"} 35346849827 (32.92 GB)
telemt_user_msgs_from_client{user="hello"} 257002
telemt_user_msgs_to_client{user="hello"} 2006834
telemt_user_unique_ips_current{user="hello"} 26
telemt_user_unique_ips_recent_window{user="hello"} 11
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 65072.6 (18h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 148589
telemt_connections_bad_total 1702
telemt_handshake_timeouts_total 2346
telemt_upstream_connect_attempt_total 17967
telemt_upstream_connect_success_total 17965
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 17967
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8350
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9594
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 19
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 368
telemt_me_reconnect_attempts_total 15802
telemt_me_reconnect_success_total 14646
telemt_me_reader_eof_total 15661
telemt_me_idle_close_by_peer_total 15661
telemt_me_route_drop_no_conn_total 56508
telemt_me_route_drop_channel_closed_total 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 138968
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 52
telemt_desync_full_logged_total 26
telemt_desync_suppressed_total 26
telemt_desync_frames_bucket_total{bucket="1_2"} 3
telemt_desync_frames_bucket_total{bucket="3_10"} 13
telemt_desync_frames_bucket_total{bucket="gt_10"} 36
telemt_pool_swap_total 57
telemt_me_writer_removed_unexpected_total 14810
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 14626
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 164
telemt_user_connections_total{user="hello"} 138932
telemt_user_connections_current{user="hello"} 52
telemt_user_octets_from_client{user="hello"} 2665101272 (2.48 GB)
telemt_user_octets_to_client{user="hello"} 63810896252 (59.43 GB)
telemt_user_unique_ips_current{user="hello"} 25
telemt_user_unique_ips_recent_window{user="hello"} 6
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 65048.3 (18h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 212269
telemt_connections_bad_total 13305
telemt_handshake_timeouts_total 1427
telemt_upstream_connect_attempt_total 30054
telemt_upstream_connect_success_total 20281
telemt_upstream_connect_fail_total 9773
telemt_upstream_connect_attempts_per_request{bucket="1"} 30054
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10356
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9763
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 154
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9773
telemt_me_keepalive_timeout_total 3217
telemt_me_reconnect_attempts_total 51035
telemt_me_reconnect_success_total 14136
telemt_me_reader_eof_total 15786
telemt_me_idle_close_by_peer_total 15779
telemt_me_route_drop_no_conn_total 76347
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 175963
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 499
telemt_desync_full_logged_total 143
telemt_desync_suppressed_total 356
telemt_desync_frames_bucket_total{bucket="1_2"} 124
telemt_desync_frames_bucket_total{bucket="3_10"} 186
telemt_desync_frames_bucket_total{bucket="gt_10"} 189
telemt_pool_swap_total 20
telemt_me_writer_removed_unexpected_total 15494
telemt_me_refill_failed_total 1149
telemt_me_writer_restored_same_endpoint_total 14126
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 1358
telemt_user_connections_total{user="hello"} 178715
telemt_user_connections_current{user="hello"} 111
telemt_user_octets_from_client{user="hello"} 3039485198 (2.83 GB)
telemt_user_octets_to_client{user="hello"} 73266646385 (68.23 GB)
telemt_user_msgs_from_client{user="hello"} 67768
telemt_user_msgs_to_client{user="hello"} 112762
telemt_user_unique_ips_current{user="hello"} 38
telemt_user_unique_ips_recent_window{user="hello"} 9
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 15220.0 (4h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 13517
telemt_connections_bad_total 2873
telemt_handshake_timeouts_total 24
telemt_upstream_connect_attempt_total 4715
telemt_upstream_connect_success_total 4674
telemt_upstream_connect_fail_total 40
telemt_upstream_connect_attempts_per_request{bucket="1"} 4714
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2069
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2586
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 19
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 40
telemt_me_keepalive_timeout_total 94
telemt_me_reconnect_attempts_total 3919
telemt_me_reconnect_success_total 3908
telemt_me_reader_eof_total 4174
telemt_me_idle_close_by_peer_total 4174
telemt_me_route_drop_no_conn_total 4188
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 10211
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 15
telemt_me_writer_removed_unexpected_total 3933
telemt_me_writer_restored_same_endpoint_total 3892
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 25
telemt_user_connections_total{user="hello"} 10211
telemt_user_connections_current{user="hello"} 39
telemt_user_octets_from_client{user="hello"} 47134848 (44.95 MB)
telemt_user_octets_to_client{user="hello"} 3128242988 (2.91 GB)
telemt_user_unique_ips_current{user="hello"} 26
telemt_user_unique_ips_recent_window{user="hello"} 7
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 65004.8 (18h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 356242
telemt_connections_bad_total 6577
telemt_handshake_timeouts_total 2611
telemt_upstream_connect_attempt_total 13804
telemt_upstream_connect_success_total 13728
telemt_upstream_connect_fail_total 76
telemt_upstream_connect_attempts_per_request{bucket="1"} 13804
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6424
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7284
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 20
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 76
telemt_me_keepalive_timeout_total 1343
telemt_me_reconnect_attempts_total 14087
telemt_me_reconnect_success_total 10469
telemt_me_reader_eof_total 11238
telemt_me_idle_close_by_peer_total 11236
telemt_me_route_drop_no_conn_total 159278
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 348497
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 301
telemt_desync_full_logged_total 118
telemt_desync_suppressed_total 183
telemt_desync_frames_bucket_total{bucket="1_2"} 75
telemt_desync_frames_bucket_total{bucket="3_10"} 112
telemt_desync_frames_bucket_total{bucket="gt_10"} 114
telemt_pool_swap_total 58
telemt_me_writer_removed_unexpected_total 10709
telemt_me_refill_failed_total 111
telemt_me_writer_restored_same_endpoint_total 10462
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 240
telemt_user_connections_total{user="hello"} 336798
telemt_user_connections_current{user="hello"} 226
telemt_user_octets_from_client{user="hello"} 5708180584 (5.32 GB)
telemt_user_octets_to_client{user="hello"} 183593574996 (170.98 GB)
telemt_user_unique_ips_current{user="hello"} 81
telemt_user_unique_ips_recent_window{user="hello"} 27
```