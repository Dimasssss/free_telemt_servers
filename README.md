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

# Server Metrics 2026-03-14 12:28:22 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 190501.7 (52h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 754949
telemt_connections_bad_total 35814
telemt_handshake_timeouts_total 14490
telemt_upstream_connect_attempt_total 48306
telemt_upstream_connect_success_total 48066
telemt_upstream_connect_fail_total 240
telemt_upstream_connect_attempts_per_request{bucket="1"} 48306
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 22017
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 25895
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 154
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 240
telemt_me_keepalive_failed_total 4
telemt_me_keepalive_timeout_total 6340
telemt_me_reconnect_attempts_total 43965
telemt_me_reconnect_success_total 38196
telemt_me_reader_eof_total 40837
telemt_me_idle_close_by_peer_total 40836
telemt_me_route_drop_no_conn_total 247967
telemt_me_route_drop_channel_closed_total 41
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 647412
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2768
telemt_desync_full_logged_total 924
telemt_desync_suppressed_total 1844
telemt_desync_frames_bucket_total{bucket="1_2"} 573
telemt_desync_frames_bucket_total{bucket="3_10"} 1038
telemt_desync_frames_bucket_total{bucket="gt_10"} 1157
telemt_pool_swap_total 173
telemt_me_writer_removed_unexpected_total 38785
telemt_me_refill_failed_total 173
telemt_me_writer_restored_same_endpoint_total 38176
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 589
telemt_user_connections_total{user="hello"} 647318
telemt_user_connections_current{user="hello"} 403
telemt_user_octets_from_client{user="hello"} 17933007962 (16.70 GB)
telemt_user_octets_to_client{user="hello"} 310022166876 (288.73 GB)
telemt_user_msgs_from_client{user="hello"} 2142
telemt_user_msgs_to_client{user="hello"} 2404
telemt_user_unique_ips_current{user="hello"} 108
telemt_user_unique_ips_recent_window{user="hello"} 39
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 190394.7 (52h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 373398
telemt_connections_bad_total 2863
telemt_handshake_timeouts_total 3352
telemt_upstream_connect_attempt_total 158183
telemt_upstream_connect_success_total 156783
telemt_upstream_connect_fail_total 1400
telemt_upstream_connect_attempts_per_request{bucket="1"} 158183
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 113871
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 40387
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2524
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1400
telemt_me_keepalive_timeout_total 5716
telemt_me_reconnect_attempts_total 196817
telemt_me_reconnect_success_total 42186
telemt_me_reader_eof_total 48112
telemt_me_idle_close_by_peer_total 48112
telemt_me_route_drop_no_conn_total 128929
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 247428
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
telemt_me_writer_removed_unexpected_total 47421
telemt_me_refill_failed_total 4824
telemt_me_writer_restored_same_endpoint_total 42168
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 5235
telemt_user_connections_total{user="hello"} 352321
telemt_user_connections_current{user="hello"} 146
telemt_user_octets_from_client{user="hello"} 3569814347 (3.32 GB)
telemt_user_octets_to_client{user="hello"} 113244677506 (105.47 GB)
telemt_user_msgs_from_client{user="hello"} 1713995
telemt_user_msgs_to_client{user="hello"} 9567945
telemt_user_unique_ips_current{user="hello"} 44
telemt_user_unique_ips_recent_window{user="hello"} 12
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 190358.3 (52h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 430403
telemt_connections_bad_total 3331
telemt_handshake_timeouts_total 36697
telemt_upstream_connect_attempt_total 50837
telemt_upstream_connect_success_total 50828
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 50837
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 23363
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 27386
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 72
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 4303
telemt_me_reconnect_attempts_total 42556
telemt_me_reconnect_success_total 41233
telemt_me_reader_eof_total 44297
telemt_me_idle_close_by_peer_total 44297
telemt_me_route_drop_no_conn_total 157861
telemt_me_route_drop_channel_closed_total 23
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 374935
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 147
telemt_desync_full_logged_total 67
telemt_desync_suppressed_total 80
telemt_desync_frames_bucket_total{bucket="1_2"} 15
telemt_desync_frames_bucket_total{bucket="3_10"} 53
telemt_desync_frames_bucket_total{bucket="gt_10"} 79
telemt_pool_swap_total 177
telemt_me_writer_removed_unexpected_total 41727
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 41212
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 494
telemt_user_connections_total{user="hello"} 374671
telemt_user_connections_current{user="hello"} 155
telemt_user_octets_from_client{user="hello"} 16214245346 (15.10 GB)
telemt_user_octets_to_client{user="hello"} 164925058083 (153.60 GB)
telemt_user_msgs_from_client{user="hello"} 166
telemt_user_msgs_to_client{user="hello"} 712
telemt_user_unique_ips_current{user="hello"} 58
telemt_user_unique_ips_recent_window{user="hello"} 17
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 190334.0 (52h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 548492
telemt_connections_bad_total 16781
telemt_handshake_timeouts_total 5334
telemt_upstream_connect_attempt_total 81262
telemt_upstream_connect_success_total 70544
telemt_upstream_connect_fail_total 10718
telemt_upstream_connect_attempts_per_request{bucket="1"} 81262
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 40971
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 29171
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 393
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10718
telemt_me_keepalive_timeout_total 5856
telemt_me_reconnect_attempts_total 159058
telemt_me_reconnect_success_total 42014
telemt_me_reader_eof_total 46999
telemt_me_idle_close_by_peer_total 46991
telemt_me_route_drop_no_conn_total 198273
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 470500
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 38
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2193
telemt_desync_full_logged_total 641
telemt_desync_suppressed_total 1552
telemt_desync_frames_bucket_total{bucket="1_2"} 508
telemt_desync_frames_bucket_total{bucket="3_10"} 832
telemt_desync_frames_bucket_total{bucket="gt_10"} 853
telemt_pool_swap_total 54
telemt_me_writer_removed_unexpected_total 46149
telemt_me_refill_failed_total 3649
telemt_me_writer_restored_same_endpoint_total 42004
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 4135
telemt_user_connections_total{user="hello"} 489361
telemt_user_connections_current{user="hello"} 222
telemt_user_octets_from_client{user="hello"} 10333360615 (9.62 GB)
telemt_user_octets_to_client{user="hello"} 201954409224 (188.08 GB)
telemt_user_msgs_from_client{user="hello"} 459818
telemt_user_msgs_to_client{user="hello"} 871707
telemt_user_unique_ips_current{user="hello"} 64
telemt_user_unique_ips_recent_window{user="hello"} 27
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 140505.4 (39h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 239305
telemt_connections_bad_total 38522
telemt_handshake_timeouts_total 2195
telemt_upstream_connect_attempt_total 49483
telemt_upstream_connect_success_total 48980
telemt_upstream_connect_fail_total 503
telemt_upstream_connect_attempts_per_request{bucket="1"} 49483
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 24393
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 24417
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 170
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 503
telemt_me_keepalive_timeout_total 3135
telemt_me_reconnect_attempts_total 55246
telemt_me_reconnect_success_total 37084
telemt_me_reader_eof_total 39673
telemt_me_idle_close_by_peer_total 39673
telemt_me_route_drop_no_conn_total 72799
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 187294
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 9
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 838
telemt_desync_full_logged_total 201
telemt_desync_suppressed_total 637
telemt_desync_frames_bucket_total{bucket="1_2"} 141
telemt_desync_frames_bucket_total{bucket="3_10"} 386
telemt_desync_frames_bucket_total{bucket="gt_10"} 311
telemt_pool_swap_total 102
telemt_me_writer_removed_unexpected_total 37999
telemt_me_refill_failed_total 563
telemt_me_writer_restored_same_endpoint_total 37066
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 42
telemt_me_writer_removed_unexpected_minus_restored_total 915
telemt_user_connections_total{user="hello"} 192050
telemt_user_connections_current{user="hello"} 106
telemt_user_octets_from_client{user="hello"} 2776188109 (2.59 GB)
telemt_user_octets_to_client{user="hello"} 88231020675 (82.17 GB)
telemt_user_msgs_from_client{user="hello"} 50955
telemt_user_msgs_to_client{user="hello"} 221508
telemt_user_unique_ips_current{user="hello"} 40
telemt_user_unique_ips_recent_window{user="hello"} 24
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 190290.1 (52h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1110907
telemt_connections_bad_total 37843
telemt_handshake_timeouts_total 27325
telemt_upstream_connect_attempt_total 39651
telemt_upstream_connect_success_total 39444
telemt_upstream_connect_fail_total 207
telemt_upstream_connect_attempts_per_request{bucket="1"} 39651
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18692
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20711
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 41
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 207
telemt_me_keepalive_timeout_total 5212
telemt_me_reconnect_attempts_total 34719
telemt_me_reconnect_success_total 30023
telemt_me_reader_eof_total 32194
telemt_me_idle_close_by_peer_total 32191
telemt_me_route_drop_no_conn_total 522864
telemt_me_route_drop_channel_closed_total 36
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1030305
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
telemt_pool_swap_total 178
telemt_me_writer_removed_unexpected_total 30551
telemt_me_refill_failed_total 141
telemt_me_writer_restored_same_endpoint_total 30016
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 528
telemt_user_connections_total{user="hello"} 1002904
telemt_user_connections_current{user="hello"} 461
telemt_user_octets_from_client{user="hello"} 21481359108 (20.01 GB)
telemt_user_octets_to_client{user="hello"} 505658523156 (470.93 GB)
telemt_user_unique_ips_current{user="hello"} 185
telemt_user_unique_ips_recent_window{user="hello"} 65
```