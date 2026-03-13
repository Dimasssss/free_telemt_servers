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

# Server Metrics 2026-03-13 09:31:17 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 93473.2 (25h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 366673
telemt_connections_bad_total 3189
telemt_handshake_timeouts_total 7845
telemt_upstream_connect_attempt_total 23583
telemt_upstream_connect_success_total 23474
telemt_upstream_connect_fail_total 109
telemt_upstream_connect_attempts_per_request{bucket="1"} 23583
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10581
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12845
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 48
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 109
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 1715
telemt_me_reconnect_attempts_total 22308
telemt_me_reconnect_success_total 18796
telemt_me_reader_eof_total 20082
telemt_me_idle_close_by_peer_total 20081
telemt_me_route_drop_no_conn_total 115339
telemt_me_route_drop_channel_closed_total 21
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 314355
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1011
telemt_desync_full_logged_total 374
telemt_desync_suppressed_total 637
telemt_desync_frames_bucket_total{bucket="1_2"} 211
telemt_desync_frames_bucket_total{bucket="3_10"} 367
telemt_desync_frames_bucket_total{bucket="gt_10"} 433
telemt_pool_swap_total 84
telemt_me_writer_removed_unexpected_total 19103
telemt_me_refill_failed_total 106
telemt_me_writer_restored_same_endpoint_total 18780
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 307
telemt_user_connections_total{user="hello"} 314048
telemt_user_connections_current{user="hello"} 347
telemt_user_octets_from_client{user="hello"} 5178619440 (4.82 GB)
telemt_user_octets_to_client{user="hello"} 140141514400 (130.52 GB)
telemt_user_unique_ips_current{user="hello"} 103
telemt_user_unique_ips_recent_window{user="hello"} 60
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 93365.7 (25h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 167675
telemt_connections_bad_total 1543
telemt_handshake_timeouts_total 1293
telemt_upstream_connect_attempt_total 46530
telemt_upstream_connect_success_total 45899
telemt_upstream_connect_fail_total 631
telemt_upstream_connect_attempts_per_request{bucket="1"} 46530
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26519
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18864
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 516
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 631
telemt_me_keepalive_timeout_total 714
telemt_me_reconnect_attempts_total 80121
telemt_me_reconnect_success_total 24743
telemt_me_reader_eof_total 27213
telemt_me_idle_close_by_peer_total 27213
telemt_me_route_drop_no_conn_total 64046
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 141307
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 19
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
telemt_me_writer_removed_unexpected_total 26679
telemt_me_refill_failed_total 1728
telemt_me_writer_restored_same_endpoint_total 24728
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 1936
telemt_user_connections_total{user="hello"} 157802
telemt_user_connections_current{user="hello"} 187
telemt_user_octets_from_client{user="hello"} 1652273792 (1.54 GB)
telemt_user_octets_to_client{user="hello"} 51044406767 (47.54 GB)
telemt_user_msgs_from_client{user="hello"} 257002
telemt_user_msgs_to_client{user="hello"} 2006834
telemt_user_unique_ips_current{user="hello"} 57
telemt_user_unique_ips_recent_window{user="hello"} 32
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 93329.1 (25h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 204420
telemt_connections_bad_total 2007
telemt_handshake_timeouts_total 4155
telemt_upstream_connect_attempt_total 25216
telemt_upstream_connect_success_total 25213
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 25216
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11583
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13605
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 23
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 641
telemt_me_reconnect_attempts_total 21701
telemt_me_reconnect_success_total 20512
telemt_me_reader_eof_total 22001
telemt_me_idle_close_by_peer_total 22001
telemt_me_route_drop_no_conn_total 77100
telemt_me_route_drop_channel_closed_total 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 190758
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
telemt_pool_swap_total 86
telemt_me_writer_removed_unexpected_total 20737
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 20492
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 225
telemt_user_connections_total{user="hello"} 190682
telemt_user_connections_current{user="hello"} 207
telemt_user_octets_from_client{user="hello"} 7847973820 (7.31 GB)
telemt_user_octets_to_client{user="hello"} 79491509980 (74.03 GB)
telemt_user_unique_ips_current{user="hello"} 68
telemt_user_unique_ips_recent_window{user="hello"} 39
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 93304.9 (25h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 290948
telemt_connections_bad_total 13664
telemt_handshake_timeouts_total 2142
telemt_upstream_connect_attempt_total 38296
telemt_upstream_connect_success_total 28290
telemt_upstream_connect_fail_total 10006
telemt_upstream_connect_attempts_per_request{bucket="1"} 38296
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14148
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13946
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 187
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10006
telemt_me_keepalive_timeout_total 3424
telemt_me_reconnect_attempts_total 77409
telemt_me_reconnect_success_total 20773
telemt_me_reader_eof_total 23182
telemt_me_idle_close_by_peer_total 23175
telemt_me_route_drop_no_conn_total 105056
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 248660
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 914
telemt_desync_full_logged_total 268
telemt_desync_suppressed_total 646
telemt_desync_frames_bucket_total{bucket="1_2"} 230
telemt_desync_frames_bucket_total{bucket="3_10"} 341
telemt_desync_frames_bucket_total{bucket="gt_10"} 343
telemt_pool_swap_total 26
telemt_me_writer_removed_unexpected_total 22804
telemt_me_refill_failed_total 1765
telemt_me_writer_restored_same_endpoint_total 20763
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 2031
telemt_user_connections_total{user="hello"} 251383
telemt_user_connections_current{user="hello"} 187
telemt_user_octets_from_client{user="hello"} 5556351150 (5.17 GB)
telemt_user_octets_to_client{user="hello"} 95031996817 (88.51 GB)
telemt_user_msgs_from_client{user="hello"} 67768
telemt_user_msgs_to_client{user="hello"} 112762
telemt_user_unique_ips_current{user="hello"} 66
telemt_user_unique_ips_recent_window{user="hello"} 27
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 43476.5 (12h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 56875
telemt_connections_bad_total 8754
telemt_handshake_timeouts_total 477
telemt_upstream_connect_attempt_total 15055
telemt_upstream_connect_success_total 14909
telemt_upstream_connect_fail_total 146
telemt_upstream_connect_attempts_per_request{bucket="1"} 15055
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6555
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8303
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 51
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 146
telemt_me_keepalive_timeout_total 358
telemt_me_reconnect_attempts_total 14941
telemt_me_reconnect_success_total 12716
telemt_me_reader_eof_total 13555
telemt_me_idle_close_by_peer_total 13555
telemt_me_route_drop_no_conn_total 17369
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 46072
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
telemt_pool_swap_total 35
telemt_me_writer_removed_unexpected_total 12898
telemt_me_refill_failed_total 68
telemt_me_writer_restored_same_endpoint_total 12698
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 182
telemt_user_connections_total{user="hello"} 46067
telemt_user_connections_current{user="hello"} 85
telemt_user_octets_from_client{user="hello"} 344506632 (328.55 MB)
telemt_user_octets_to_client{user="hello"} 12575379632 (11.71 GB)
telemt_user_unique_ips_current{user="hello"} 39
telemt_user_unique_ips_recent_window{user="hello"} 23
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 93261.5 (25h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 502580
telemt_connections_bad_total 13838
telemt_handshake_timeouts_total 5378
telemt_upstream_connect_attempt_total 19836
telemt_upstream_connect_success_total 19730
telemt_upstream_connect_fail_total 106
telemt_upstream_connect_attempts_per_request{bucket="1"} 19836
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9240
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10465
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 106
telemt_me_keepalive_timeout_total 1543
telemt_me_reconnect_attempts_total 18743
telemt_me_reconnect_success_total 15097
telemt_me_reader_eof_total 16192
telemt_me_idle_close_by_peer_total 16189
telemt_me_route_drop_no_conn_total 262310
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 492576
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 398
telemt_desync_full_logged_total 152
telemt_desync_suppressed_total 246
telemt_desync_frames_bucket_total{bucket="1_2"} 94
telemt_desync_frames_bucket_total{bucket="3_10"} 143
telemt_desync_frames_bucket_total{bucket="gt_10"} 161
telemt_pool_swap_total 87
telemt_me_writer_removed_unexpected_total 15405
telemt_me_refill_failed_total 111
telemt_me_writer_restored_same_endpoint_total 15090
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 308
telemt_user_connections_total{user="hello"} 465666
telemt_user_connections_current{user="hello"} 549
telemt_user_octets_from_client{user="hello"} 8482856264 (7.90 GB)
telemt_user_octets_to_client{user="hello"} 262721643040 (244.68 GB)
telemt_user_unique_ips_current{user="hello"} 163
telemt_user_unique_ips_recent_window{user="hello"} 73
```