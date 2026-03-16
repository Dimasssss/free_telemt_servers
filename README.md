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

# Server Metrics 2026-03-16 10:17:11 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.18

telemt_uptime_seconds 129761.7 (36h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 640307
telemt_connections_bad_total 11431
telemt_handshake_timeouts_total 22450
telemt_upstream_connect_attempt_total 30433
telemt_upstream_connect_success_total 30287
telemt_upstream_connect_fail_total 146
telemt_upstream_connect_attempts_per_request{bucket="1"} 30433
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13504
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16736
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 38
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 146
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 51
telemt_me_reconnect_attempts_total 33030
telemt_me_reconnect_success_total 23832
telemt_me_reader_eof_total 25591
telemt_me_idle_close_by_peer_total 25591
telemt_me_route_drop_no_conn_total 589478
telemt_me_route_drop_channel_closed_total 88
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 628188
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2940
telemt_desync_full_logged_total 1133
telemt_desync_suppressed_total 1807
telemt_desync_frames_bucket_total{bucket="1_2"} 647
telemt_desync_frames_bucket_total{bucket="3_10"} 1126
telemt_desync_frames_bucket_total{bucket="gt_10"} 1167
telemt_pool_swap_total 121
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 24375
telemt_me_refill_failed_total 283
telemt_me_writer_restored_same_endpoint_total 23797
telemt_me_writer_restored_fallback_total 35
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 543
telemt_user_connections_total{user="hello"} 564742
telemt_user_connections_current{user="hello"} 512
telemt_user_octets_from_client{user="hello"} 10963869752 (10.21 GB)
telemt_user_octets_to_client{user="hello"} 345315682752 (321.60 GB)
telemt_user_unique_ips_current{user="hello"} 166
telemt_user_unique_ips_recent_window{user="hello"} 66
```

## psb.hosting

```
telemt 3.3.18

telemt_uptime_seconds 129768.1 (36h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 265243
telemt_connections_bad_total 3795
telemt_handshake_timeouts_total 15670
telemt_upstream_connect_attempt_total 34698
telemt_upstream_connect_success_total 34623
telemt_upstream_connect_fail_total 75
telemt_upstream_connect_attempts_per_request{bucket="1"} 34698
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14952
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18964
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 707
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 75
telemt_me_keepalive_timeout_total 1307
telemt_me_reconnect_attempts_total 38074
telemt_me_reconnect_success_total 27751
telemt_me_reader_eof_total 29767
telemt_me_idle_close_by_peer_total 29766
telemt_me_route_drop_no_conn_total 125907
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 236618
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 199
telemt_desync_full_logged_total 66
telemt_desync_suppressed_total 133
telemt_desync_frames_bucket_total{bucket="1_2"} 40
telemt_desync_frames_bucket_total{bucket="3_10"} 71
telemt_desync_frames_bucket_total{bucket="gt_10"} 88
telemt_pool_swap_total 110
telemt_me_writer_removed_unexpected_total 28463
telemt_me_refill_failed_total 314
telemt_me_writer_restored_same_endpoint_total 27735
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 712
telemt_user_connections_total{user="hello"} 236151
telemt_user_connections_current{user="hello"} 372
telemt_user_octets_from_client{user="hello"} 5069164913 (4.72 GB)
telemt_user_octets_to_client{user="hello"} 126323412664 (117.65 GB)
telemt_user_msgs_from_client{user="hello"} 721
telemt_user_msgs_to_client{user="hello"} 1482
telemt_user_unique_ips_current{user="hello"} 96
telemt_user_unique_ips_recent_window{user="hello"} 46
```

## koara.io

```
telemt 3.3.18

telemt_uptime_seconds 129760.8 (36h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 271418
telemt_connections_bad_total 5767
telemt_handshake_timeouts_total 6399
telemt_upstream_connect_attempt_total 36162
telemt_upstream_connect_success_total 36154
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 36162
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15629
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20471
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 54
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 45
telemt_me_reconnect_attempts_total 37044
telemt_me_reconnect_success_total 29620
telemt_me_reader_eof_total 31832
telemt_me_idle_close_by_peer_total 31831
telemt_me_route_drop_no_conn_total 93696
telemt_me_route_drop_channel_closed_total 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 220327
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 12
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 104
telemt_desync_full_logged_total 40
telemt_desync_suppressed_total 64
telemt_desync_frames_bucket_total{bucket="1_2"} 15
telemt_desync_frames_bucket_total{bucket="3_10"} 45
telemt_desync_frames_bucket_total{bucket="gt_10"} 44
telemt_pool_swap_total 116
telemt_me_writer_removed_unexpected_total 30142
telemt_me_refill_failed_total 227
telemt_me_writer_restored_same_endpoint_total 29612
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 522
telemt_user_connections_total{user="hello"} 220015
telemt_user_connections_current{user="hello"} 249
telemt_user_octets_from_client{user="hello"} 17725129205 (16.51 GB)
telemt_user_octets_to_client{user="hello"} 120948175492 (112.64 GB)
telemt_user_msgs_from_client{user="hello"} 7
telemt_user_msgs_to_client{user="hello"} 46
telemt_user_unique_ips_current{user="hello"} 87
telemt_user_unique_ips_recent_window{user="hello"} 31
```

## landvps.ru

```
telemt 3.3.18

telemt_uptime_seconds 129760.4 (36h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 394925
telemt_connections_bad_total 1402
telemt_handshake_timeouts_total 3710
telemt_upstream_connect_attempt_total 29982
telemt_upstream_connect_success_total 29942
telemt_upstream_connect_fail_total 40
telemt_upstream_connect_attempts_per_request{bucket="1"} 29982
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14411
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15361
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 16
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 154
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 40
telemt_me_keepalive_timeout_total 23
telemt_me_reconnect_attempts_total 27626
telemt_me_reconnect_success_total 23469
telemt_me_reader_eof_total 25143
telemt_me_idle_close_by_peer_total 25142
telemt_me_route_drop_no_conn_total 137549
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 365651
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1303
telemt_desync_full_logged_total 450
telemt_desync_suppressed_total 853
telemt_desync_frames_bucket_total{bucket="1_2"} 261
telemt_desync_frames_bucket_total{bucket="3_10"} 555
telemt_desync_frames_bucket_total{bucket="gt_10"} 487
telemt_pool_swap_total 120
telemt_me_writer_removed_unexpected_total 23911
telemt_me_refill_failed_total 125
telemt_me_writer_restored_same_endpoint_total 23458
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 442
telemt_user_connections_total{user="hello"} 365521
telemt_user_connections_current{user="hello"} 402
telemt_user_octets_from_client{user="hello"} 6038123130 (5.62 GB)
telemt_user_octets_to_client{user="hello"} 144867460552 (134.92 GB)
telemt_user_msgs_from_client{user="hello"} 25
telemt_user_msgs_to_client{user="hello"} 50
telemt_user_unique_ips_current{user="hello"} 126
telemt_user_unique_ips_recent_window{user="hello"} 63
```

## rdp-onedash.ru

```
telemt 3.3.18

telemt_uptime_seconds 104831.6 (29h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 248146
telemt_connections_bad_total 40557
telemt_handshake_timeouts_total 4298
telemt_upstream_connect_attempt_total 29852
telemt_upstream_connect_success_total 29688
telemt_upstream_connect_fail_total 164
telemt_upstream_connect_attempts_per_request{bucket="1"} 29852
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13156
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16380
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 152
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 164
telemt_me_keepalive_timeout_total 24
telemt_me_reconnect_attempts_total 118812
telemt_me_reconnect_success_total 24304
telemt_me_reader_eof_total 25815
telemt_me_idle_close_by_peer_total 25815
telemt_me_route_drop_no_conn_total 76806
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 196300
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 660
telemt_desync_full_logged_total 154
telemt_desync_suppressed_total 506
telemt_desync_frames_bucket_total{bucket="1_2"} 97
telemt_desync_frames_bucket_total{bucket="3_10"} 266
telemt_desync_frames_bucket_total{bucket="gt_10"} 297
telemt_pool_swap_total 90
telemt_me_writer_removed_unexpected_total 24510
telemt_me_refill_failed_total 3033
telemt_me_writer_restored_same_endpoint_total 24200
telemt_me_writer_restored_fallback_total 104
telemt_me_async_recovery_trigger_total 2255
telemt_me_writer_removed_unexpected_minus_restored_total 206
telemt_user_connections_total{user="hello"} 195914
telemt_user_connections_current{user="hello"} 164
telemt_user_octets_from_client{user="hello"} 2542349341 (2.37 GB)
telemt_user_octets_to_client{user="hello"} 88486480459 (82.41 GB)
telemt_user_msgs_from_client{user="hello"} 2259
telemt_user_msgs_to_client{user="hello"} 12105
telemt_user_unique_ips_current{user="hello"} 60
telemt_user_unique_ips_recent_window{user="hello"} 33
```

## hostvds.com

```
telemt 3.3.18

telemt_uptime_seconds 129759.7 (36h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 890375
telemt_connections_bad_total 72892
telemt_handshake_timeouts_total 10383
telemt_upstream_connect_attempt_total 27253
telemt_upstream_connect_success_total 27111
telemt_upstream_connect_fail_total 142
telemt_upstream_connect_attempts_per_request{bucket="1"} 27253
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12874
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14195
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 19
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 23
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 142
telemt_me_keepalive_timeout_total 63
telemt_me_reconnect_attempts_total 23234
telemt_me_reconnect_success_total 20628
telemt_me_reader_eof_total 22044
telemt_me_idle_close_by_peer_total 22044
telemt_me_route_drop_no_conn_total 675893
telemt_me_route_drop_channel_closed_total 123
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 877485
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 417
telemt_desync_full_logged_total 119
telemt_desync_suppressed_total 298
telemt_desync_frames_bucket_total{bucket="1_2"} 174
telemt_desync_frames_bucket_total{bucket="3_10"} 124
telemt_desync_frames_bucket_total{bucket="gt_10"} 119
telemt_pool_swap_total 121
telemt_me_writer_removed_unexpected_total 20956
telemt_me_refill_failed_total 77
telemt_me_writer_restored_same_endpoint_total 20601
telemt_me_writer_restored_fallback_total 27
telemt_me_async_recovery_trigger_total 40
telemt_me_writer_removed_unexpected_minus_restored_total 328
telemt_user_connections_total{user="hello"} 736106
telemt_user_connections_current{user="hello"} 612
telemt_user_octets_from_client{user="hello"} 15585784976 (14.52 GB)
telemt_user_octets_to_client{user="hello"} 437976976588 (407.90 GB)
telemt_user_unique_ips_current{user="hello"} 236
telemt_user_unique_ips_recent_window{user="hello"} 91
```