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

# Server Metrics 2026-03-13 10:36:25 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 97386.9 (27h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 387968
telemt_connections_bad_total 3193
telemt_handshake_timeouts_total 8099
telemt_upstream_connect_attempt_total 24603
telemt_upstream_connect_success_total 24488
telemt_upstream_connect_fail_total 115
telemt_upstream_connect_attempts_per_request{bucket="1"} 24603
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11028
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13412
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 48
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 115
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 1781
telemt_me_reconnect_attempts_total 23102
telemt_me_reconnect_success_total 19582
telemt_me_reader_eof_total 20915
telemt_me_idle_close_by_peer_total 20914
telemt_me_route_drop_no_conn_total 121302
telemt_me_route_drop_channel_closed_total 21
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 334440
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1074
telemt_desync_full_logged_total 397
telemt_desync_suppressed_total 677
telemt_desync_frames_bucket_total{bucket="1_2"} 218
telemt_desync_frames_bucket_total{bucket="3_10"} 396
telemt_desync_frames_bucket_total{bucket="gt_10"} 460
telemt_pool_swap_total 87
telemt_me_writer_removed_unexpected_total 19895
telemt_me_refill_failed_total 106
telemt_me_writer_restored_same_endpoint_total 19566
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 313
telemt_user_connections_total{user="hello"} 334144
telemt_user_connections_current{user="hello"} 350
telemt_user_octets_from_client{user="hello"} 5932662492 (5.53 GB)
telemt_user_octets_to_client{user="hello"} 144384485588 (134.47 GB)
telemt_user_unique_ips_current{user="hello"} 104
telemt_user_unique_ips_recent_window{user="hello"} 46
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 97279.8 (27h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 177845
telemt_connections_bad_total 1565
telemt_handshake_timeouts_total 1357
telemt_upstream_connect_attempt_total 47574
telemt_upstream_connect_success_total 46914
telemt_upstream_connect_fail_total 659
telemt_upstream_connect_attempts_per_request{bucket="1"} 47573
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26953
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19444
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 517
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 659
telemt_me_keepalive_timeout_total 760
telemt_me_reconnect_attempts_total 85804
telemt_me_reconnect_success_total 25569
telemt_me_reader_eof_total 28202
telemt_me_idle_close_by_peer_total 28202
telemt_me_route_drop_no_conn_total 75994
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 151194
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
telemt_me_writer_removed_unexpected_total 27668
telemt_me_refill_failed_total 1879
telemt_me_writer_restored_same_endpoint_total 25553
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 2099
telemt_user_connections_total{user="hello"} 167473
telemt_user_connections_current{user="hello"} 164
telemt_user_octets_from_client{user="hello"} 1733721432 (1.61 GB)
telemt_user_octets_to_client{user="hello"} 56388005863 (52.52 GB)
telemt_user_msgs_from_client{user="hello"} 257002
telemt_user_msgs_to_client{user="hello"} 2006834
telemt_user_unique_ips_current{user="hello"} 47
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 97243.6 (27h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 216357
telemt_connections_bad_total 2049
telemt_handshake_timeouts_total 4395
telemt_upstream_connect_attempt_total 26291
telemt_upstream_connect_success_total 26288
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 26291
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12112
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14151
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 23
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 768
telemt_me_reconnect_attempts_total 22585
telemt_me_reconnect_success_total 21387
telemt_me_reader_eof_total 22922
telemt_me_idle_close_by_peer_total 22922
telemt_me_route_drop_no_conn_total 80959
telemt_me_route_drop_channel_closed_total 12
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 201987
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
telemt_pool_swap_total 88
telemt_me_writer_removed_unexpected_total 21619
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 21367
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 232
telemt_user_connections_total{user="hello"} 201909
telemt_user_connections_current{user="hello"} 182
telemt_user_octets_from_client{user="hello"} 9198882464 (8.57 GB)
telemt_user_octets_to_client{user="hello"} 82612239236 (76.94 GB)
telemt_user_unique_ips_current{user="hello"} 72
telemt_user_unique_ips_recent_window{user="hello"} 22
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 97219.0 (27h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 305108
telemt_connections_bad_total 13675
telemt_handshake_timeouts_total 2246
telemt_upstream_connect_attempt_total 38971
telemt_upstream_connect_success_total 28943
telemt_upstream_connect_fail_total 10028
telemt_upstream_connect_attempts_per_request{bucket="1"} 38971
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14513
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14229
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 192
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10028
telemt_me_keepalive_timeout_total 3443
telemt_me_reconnect_attempts_total 83162
telemt_me_reconnect_success_total 21245
telemt_me_reader_eof_total 23826
telemt_me_idle_close_by_peer_total 23819
telemt_me_route_drop_no_conn_total 110285
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 261932
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 20
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 966
telemt_desync_full_logged_total 285
telemt_desync_suppressed_total 681
telemt_desync_frames_bucket_total{bucket="1_2"} 240
telemt_desync_frames_bucket_total{bucket="3_10"} 356
telemt_desync_frames_bucket_total{bucket="gt_10"} 370
telemt_pool_swap_total 26
telemt_me_writer_removed_unexpected_total 23448
telemt_me_refill_failed_total 1930
telemt_me_writer_restored_same_endpoint_total 21235
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 2203
telemt_user_connections_total{user="hello"} 264653
telemt_user_connections_current{user="hello"} 179
telemt_user_octets_from_client{user="hello"} 5672976258 (5.28 GB)
telemt_user_octets_to_client{user="hello"} 98910664761 (92.12 GB)
telemt_user_msgs_from_client{user="hello"} 67768
telemt_user_msgs_to_client{user="hello"} 112762
telemt_user_unique_ips_current{user="hello"} 71
telemt_user_unique_ips_recent_window{user="hello"} 31
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 47390.5 (13h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 64510
telemt_connections_bad_total 9475
telemt_handshake_timeouts_total 710
telemt_upstream_connect_attempt_total 16591
telemt_upstream_connect_success_total 16430
telemt_upstream_connect_fail_total 161
telemt_upstream_connect_attempts_per_request{bucket="1"} 16591
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7196
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9178
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 56
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 161
telemt_me_keepalive_timeout_total 422
telemt_me_reconnect_attempts_total 17279
telemt_me_reconnect_success_total 14056
telemt_me_reader_eof_total 14958
telemt_me_idle_close_by_peer_total 14958
telemt_me_route_drop_no_conn_total 20111
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 52403
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 76
telemt_desync_full_logged_total 13
telemt_desync_suppressed_total 63
telemt_desync_frames_bucket_total{bucket="1_2"} 7
telemt_desync_frames_bucket_total{bucket="3_10"} 32
telemt_desync_frames_bucket_total{bucket="gt_10"} 37
telemt_pool_swap_total 36
telemt_me_writer_removed_unexpected_total 14285
telemt_me_refill_failed_total 99
telemt_me_writer_restored_same_endpoint_total 14038
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 229
telemt_user_connections_total{user="hello"} 52398
telemt_user_connections_current{user="hello"} 88
telemt_user_octets_from_client{user="hello"} 480597872 (458.33 MB)
telemt_user_octets_to_client{user="hello"} 14004696664 (13.04 GB)
telemt_user_unique_ips_current{user="hello"} 36
telemt_user_unique_ips_recent_window{user="hello"} 17
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 97175.6 (26h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 535450
telemt_connections_bad_total 14509
telemt_handshake_timeouts_total 8824
telemt_upstream_connect_attempt_total 20725
telemt_upstream_connect_success_total 20618
telemt_upstream_connect_fail_total 107
telemt_upstream_connect_attempts_per_request{bucket="1"} 20725
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9665
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10928
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 107
telemt_me_keepalive_timeout_total 1591
telemt_me_reconnect_attempts_total 20411
telemt_me_reconnect_success_total 15794
telemt_me_reader_eof_total 16953
telemt_me_idle_close_by_peer_total 16950
telemt_me_route_drop_no_conn_total 273080
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 520281
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 2
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
telemt_pool_swap_total 88
telemt_me_writer_removed_unexpected_total 16146
telemt_me_refill_failed_total 141
telemt_me_writer_restored_same_endpoint_total 15787
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 352
telemt_user_connections_total{user="hello"} 493363
telemt_user_connections_current{user="hello"} 532
telemt_user_octets_from_client{user="hello"} 9133663104 (8.51 GB)
telemt_user_octets_to_client{user="hello"} 275193374116 (256.29 GB)
telemt_user_unique_ips_current{user="hello"} 177
telemt_user_unique_ips_recent_window{user="hello"} 54
```