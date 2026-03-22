# Информация

Покупаю сервера у разных хостингов для запуска прокси для Telegram

Для прокси используется https://github.com/telemt/telemt
[Конфиг](https://github.com/Dimasssss/free_telemt_servers/blob/main/config.toml) используемый на всех серверах.

### **Принимаю донаты криптой для добавления и продления серверов:**
- TON (Можно отправлять TON и USDT в сети TON):
```
UQAyIvWts4-gC0b5ouoy_JNDfBEe337c7oOBqpGXFB8fJUzB
```
### **Спасибо:**
- Ivan Morozov - 20$

_Можете писать свой ник в коментарии к переводу_

### [Итог по хостингам](Reviews.md)

---

## NKtelecom
- Локация: Netherlands - Amsterdam
- Тариф: AMS-CLOUD-60
- Краткое описание тарифа: 4 vCore, 4 Gb ram, 1 Gbit/s
- Цена в месяц: 4.99$
- Оплачен до: 26 апреля
- Ссылка:
```bash
tg://proxy?server=s1.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## psb.hosting (2 сервера)
- Локация: Finland
- Тариф: FI-200
- Краткое описание тарифа: 2 vCore, 4 Gb ram, 1 Gbit/s
- Цена в месяц: 12$
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

## rdp-onedash.ru (2 сервера)
- Локация: Нидерланды
- Тариф: Mini
- Краткое описание тарифа: 2 vCore, 2 Gb ram, 1 Gbit/s
- Цена в месяц: 844 RUB
- Ссылка:
```bash
tg://proxy?server=s5.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## hostvds.com
- Локация: Франция, Париж
- Тариф: Highload-2
- Краткое описание тарифа: 2 vCore, 8 Gb ram, 10 Gbit/s
- Цена в месяц: €12.57
- Ссылка:
```bash
tg://proxy?server=s6.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## 4vps.su (2 сервера)
- Локация: Польша, Варшава
- Тариф: PL-cx21
- Краткое описание тарифа: 2 vCore, 4 Gb ram, 2 Gbit/s
- Цена в месяц: 770 RUB
- Оплачен до: 16 апреля
- Ссылка:
```bash
tg://proxy?server=s7.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

# Server Metrics 2026-03-22 12:59:07 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 57164.0 (15h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1742287
telemt_connections_bad_total 79627
telemt_connections_current 1614
telemt_connections_me_current 1614
telemt_handshake_timeouts_total 76694
telemt_upstream_connect_attempt_total 21557
telemt_upstream_connect_success_total 21556
telemt_upstream_connect_attempts_per_request{bucket="1"} 21556
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7447
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14045
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 51
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 13
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 893
telemt_me_reconnect_success_total 350
telemt_me_reader_eof_total 354
telemt_me_idle_close_by_peer_total 354
telemt_me_route_drop_no_conn_total 1182744
telemt_me_route_drop_channel_closed_total 541
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1476720
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_endpoint_quarantine_total 398
telemt_me_single_endpoint_outage_enter_total 3
telemt_me_single_endpoint_outage_exit_total 3
telemt_me_single_endpoint_outage_reconnect_attempt_total 3
telemt_me_single_endpoint_outage_reconnect_success_total 3
telemt_me_single_endpoint_quarantine_bypass_total 3
telemt_me_single_endpoint_shadow_rotate_total 453
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 44
telemt_desync_total 8539
telemt_desync_full_logged_total 2598
telemt_desync_suppressed_total 5941
telemt_desync_frames_bucket_total{bucket="1_2"} 2393
telemt_desync_frames_bucket_total{bucket="3_10"} 3217
telemt_desync_frames_bucket_total{bucket="gt_10"} 2929
telemt_pool_swap_total 63
telemt_pool_force_close_total 1884
telemt_pool_stale_pick_total 2
telemt_me_writer_close_signal_drop_total 300
telemt_me_draining_writers_reap_progress_total 19653
telemt_me_writer_removed_unexpected_total 345
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1395
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 18479
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1848
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 36
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 17769
telemt_me_writer_teardown_success_total{mode="normal"} 19874
telemt_me_writer_teardown_noop_total 19655
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 33681
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 34888
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 35919
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 37600
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 38810
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 39375
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 39526
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 39529
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 39529
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 39529
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 39529
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 39529
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 39529
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 143.734710
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 39529
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 300
telemt_me_refill_failed_total 29
telemt_me_writer_restored_same_endpoint_total 309
telemt_me_writer_removed_unexpected_minus_restored_total 36
telemt_user_connections_total{user="hello"} 1473888
telemt_user_connections_current{user="hello"} 1614
telemt_user_octets_from_client{user="hello"} 23356163840 (21.75 GB)
telemt_user_octets_to_client{user="hello"} 435689613620 (405.77 GB)
telemt_user_unique_ips_current{user="hello"} 633
telemt_user_unique_ips_recent_window{user="hello"} 240
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 70530.1 (19h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2806587
telemt_connections_bad_total 264383
telemt_connections_current 1464
telemt_connections_me_current 1464
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 4
telemt_handshake_timeouts_total 66798
telemt_upstream_connect_attempt_total 46050
telemt_upstream_connect_success_total 45510
telemt_upstream_connect_fail_total 478
telemt_upstream_connect_attempts_per_request{bucket="1"} 45988
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 27529
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17860
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 121
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 478
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 3522
telemt_me_reconnect_success_total 1587
telemt_me_reader_eof_total 1470
telemt_me_idle_close_by_peer_total 1470
telemt_me_route_drop_no_conn_total 2488555
telemt_me_route_drop_channel_closed_total 27
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2198042
telemt_me_endpoint_quarantine_total 595
telemt_me_single_endpoint_outage_enter_total 32
telemt_me_single_endpoint_outage_exit_total 32
telemt_me_single_endpoint_outage_reconnect_attempt_total 32
telemt_me_single_endpoint_outage_reconnect_success_total 32
telemt_me_single_endpoint_quarantine_bypass_total 32
telemt_me_single_endpoint_shadow_rotate_total 551
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 30
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 41
telemt_desync_total 8761
telemt_desync_full_logged_total 4911
telemt_desync_suppressed_total 3850
telemt_desync_frames_bucket_total{bucket="1_2"} 2062
telemt_desync_frames_bucket_total{bucket="3_10"} 3410
telemt_desync_frames_bucket_total{bucket="gt_10"} 3289
telemt_pool_swap_total 70
telemt_pool_force_close_total 2006
telemt_me_writer_close_signal_drop_total 169
telemt_me_draining_writers_reap_progress_total 28069
telemt_me_writer_removed_unexpected_total 1430
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3069
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 26430
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1766
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 240
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 26063
telemt_me_writer_teardown_success_total{mode="normal"} 29499
telemt_me_writer_teardown_noop_total 28069
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 56225
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 57062
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 57298
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 57537
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 57565
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 57568
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 57568
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 57568
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 57568
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 57568
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 57568
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 57568
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 57568
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 9.263362
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 57568
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 169
telemt_me_refill_failed_total 87
telemt_me_writer_restored_same_endpoint_total 1323
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 21
telemt_me_writer_removed_unexpected_minus_restored_total 83
telemt_user_connections_total{user="hello"} 2209698
telemt_user_connections_current{user="hello"} 1464
telemt_user_octets_from_client{user="hello"} 27185487323 (25.32 GB)
telemt_user_octets_to_client{user="hello"} 529842755998 (493.45 GB)
telemt_user_msgs_from_client{user="hello"} 42816
telemt_user_msgs_to_client{user="hello"} 172415
telemt_user_unique_ips_current{user="hello"} 908
telemt_user_unique_ips_recent_window{user="hello"} 719
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 145390.0 (40h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 13215993
telemt_connections_bad_total 1171646
telemt_connections_current 5115
telemt_connections_me_current 5115
telemt_handshake_timeouts_total 340662
telemt_upstream_connect_attempt_total 52921
telemt_upstream_connect_success_total 52841
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 52849
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 23928
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 28687
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 220
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 2407
telemt_me_reconnect_success_total 1267
telemt_me_reader_eof_total 1210
telemt_me_idle_close_by_peer_total 1209
telemt_me_route_drop_no_conn_total 10959845
telemt_me_route_drop_channel_closed_total 117
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 10563149
telemt_me_endpoint_quarantine_total 925
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 9
telemt_me_single_endpoint_outage_reconnect_success_total 9
telemt_me_single_endpoint_quarantine_bypass_total 9
telemt_me_single_endpoint_shadow_rotate_total 1082
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 39
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 51
telemt_desync_total 43548
telemt_desync_full_logged_total 13875
telemt_desync_suppressed_total 29673
telemt_desync_frames_bucket_total{bucket="1_2"} 9857
telemt_desync_frames_bucket_total{bucket="3_10"} 17003
telemt_desync_frames_bucket_total{bucket="gt_10"} 16688
telemt_pool_swap_total 156
telemt_pool_force_close_total 5333
telemt_pool_stale_pick_total 19
telemt_me_writer_close_signal_drop_total 844
telemt_me_draining_writers_reap_progress_total 48246
telemt_me_writer_removed_unexpected_total 1167
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4207
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 44551
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 40
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 8
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4904
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 429
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 42913
telemt_me_writer_teardown_success_total{mode="normal"} 48758
telemt_me_writer_teardown_noop_total 48294
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 88017
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 90874
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 92297
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 94276
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 95711
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 96541
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 97036
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 97052
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 97052
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 97052
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 97052
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 97052
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 97052
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 242.062547
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 97052
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 844
telemt_me_refill_failed_total 63
telemt_me_writer_restored_same_endpoint_total 1092
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 22
telemt_me_writer_removed_unexpected_minus_restored_total 68
telemt_user_connections_total{user="hello"} 10551313
telemt_user_connections_current{user="hello"} 5115
telemt_user_octets_from_client{user="hello"} 155556017704 (144.87 GB)
telemt_user_octets_to_client{user="hello"} 2905216493864 (2.64 TB)
telemt_user_unique_ips_current{user="hello"} 1981
telemt_user_unique_ips_recent_window{user="hello"} 757
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 145391.3 (40h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9941517
telemt_connections_bad_total 917330
telemt_connections_current 4717
telemt_connections_me_current 4717
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 299431
telemt_upstream_connect_attempt_total 79366
telemt_upstream_connect_success_total 78234
telemt_upstream_connect_fail_total 815
telemt_upstream_connect_attempts_per_request{bucket="1"} 79049
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 43099
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 31304
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 157
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3674
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 815
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 182
telemt_me_reconnect_attempts_total 3465
telemt_me_reconnect_success_total 1418
telemt_me_reader_eof_total 1303
telemt_me_idle_close_by_peer_total 1303
telemt_me_route_drop_no_conn_total 3976009
telemt_me_route_drop_channel_closed_total 415
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 7416278
telemt_me_endpoint_quarantine_total 907
telemt_me_single_endpoint_outage_enter_total 23
telemt_me_single_endpoint_outage_exit_total 23
telemt_me_single_endpoint_outage_reconnect_attempt_total 28
telemt_me_single_endpoint_outage_reconnect_success_total 21
telemt_me_single_endpoint_quarantine_bypass_total 28
telemt_me_single_endpoint_shadow_rotate_total 1105
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 40
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 43
telemt_desync_total 33508
telemt_desync_full_logged_total 11295
telemt_desync_suppressed_total 22213
telemt_desync_frames_bucket_total{bucket="1_2"} 8274
telemt_desync_frames_bucket_total{bucket="3_10"} 12884
telemt_desync_frames_bucket_total{bucket="gt_10"} 12350
telemt_pool_swap_total 155
telemt_pool_force_close_total 4760
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 589
telemt_me_draining_writers_reap_progress_total 46569
telemt_me_writer_removed_unexpected_total 1335
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4197
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 43575
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 12
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4355
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 405
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 41809
telemt_me_writer_teardown_success_total{mode="normal"} 47772
telemt_me_writer_teardown_noop_total 46581
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 88843
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 91458
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 92423
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 93387
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 94024
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 94302
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 94343
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 94345
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 94351
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 94353
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 94353
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 94353
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 94353
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 85.004424
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 94353
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 589
telemt_me_refill_failed_total 110
telemt_me_writer_restored_same_endpoint_total 1215
telemt_me_writer_restored_fallback_total 12
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 212
telemt_me_writer_removed_unexpected_minus_restored_total 108
telemt_user_connections_total{user="hello"} 7356388
telemt_user_connections_current{user="hello"} 4717
telemt_user_octets_from_client{user="hello"} 190042298573 (176.99 GB)
telemt_user_octets_to_client{user="hello"} 3339226613562 (3.04 TB)
telemt_user_msgs_from_client{user="hello"} 113340
telemt_user_msgs_to_client{user="hello"} 116189
telemt_user_unique_ips_current{user="hello"} 1901
telemt_user_unique_ips_recent_window{user="hello"} 681
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 145355.6 (40h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9364910
telemt_connections_bad_total 791810
telemt_connections_current 3996
telemt_connections_me_current 3996
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 297066
telemt_upstream_connect_attempt_total 64511
telemt_upstream_connect_success_total 63756
telemt_upstream_connect_fail_total 162
telemt_upstream_connect_attempts_per_request{bucket="1"} 63918
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 30718
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 29927
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1146
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1965
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 162
telemt_me_keepalive_timeout_total 306
telemt_me_reconnect_attempts_total 3892
telemt_me_reconnect_success_total 1692
telemt_me_reader_eof_total 1514
telemt_me_idle_close_by_peer_total 1513
telemt_me_route_drop_no_conn_total 4051222
telemt_me_route_drop_channel_closed_total 294
telemt_me_route_drop_queue_full_total 9
telemt_me_route_drop_queue_full_profile_total{profile="high"} 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 7058113
telemt_me_endpoint_quarantine_total 999
telemt_me_single_endpoint_outage_enter_total 26
telemt_me_single_endpoint_outage_exit_total 26
telemt_me_single_endpoint_outage_reconnect_attempt_total 27
telemt_me_single_endpoint_outage_reconnect_success_total 21
telemt_me_single_endpoint_quarantine_bypass_total 27
telemt_me_single_endpoint_shadow_rotate_total 1067
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 53
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 44
telemt_desync_total 33348
telemt_desync_full_logged_total 11051
telemt_desync_suppressed_total 22297
telemt_desync_frames_bucket_total{bucket="1_2"} 8479
telemt_desync_frames_bucket_total{bucket="3_10"} 12765
telemt_desync_frames_bucket_total{bucket="gt_10"} 12104
telemt_pool_swap_total 152
telemt_pool_force_close_total 4730
telemt_pool_stale_pick_total 1619
telemt_me_writer_close_signal_drop_total 614
telemt_me_draining_writers_reap_progress_total 47208
telemt_me_writer_removed_unexpected_total 1594
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4580
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 44144
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 21
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 46
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4239
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 491
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 42478
telemt_me_writer_teardown_success_total{mode="normal"} 48724
telemt_me_writer_teardown_noop_total 47275
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 91207
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 93463
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 94273
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 95173
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 95639
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 95804
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 95888
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 95903
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 95908
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 95920
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 95950
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 95950
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 95999
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3096.339264
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 95999
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 614
telemt_me_refill_failed_total 113
telemt_me_writer_restored_same_endpoint_total 1472
telemt_me_writer_restored_fallback_total 7
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 54
telemt_me_writer_removed_unexpected_minus_restored_total 115
telemt_user_connections_total{user="hello"} 7049581
telemt_user_connections_current{user="hello"} 3996
telemt_user_octets_from_client{user="hello"} 169698146601 (158.04 GB)
telemt_user_octets_to_client{user="hello"} 3013040774293 (2.74 TB)
telemt_user_msgs_from_client{user="hello"} 46485
telemt_user_msgs_to_client{user="hello"} 113805
telemt_user_unique_ips_current{user="hello"} 1572
telemt_user_unique_ips_recent_window{user="hello"} 619
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 15635.4 (4h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6584299
telemt_connections_bad_total 410070
telemt_connections_current 6602
telemt_connections_me_current 6602
telemt_relay_adaptive_promotions_total 7
telemt_relay_adaptive_hard_promotions_total 7
telemt_handshake_timeouts_total 104030
telemt_upstream_connect_attempt_total 24732
telemt_upstream_connect_success_total 23616
telemt_upstream_connect_fail_total 844
telemt_upstream_connect_attempts_per_request{bucket="1"} 24460
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13486
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5226
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 263
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4641
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 844
telemt_me_keepalive_timeout_total 550
telemt_me_reconnect_attempts_total 2394
telemt_me_reconnect_success_total 416
telemt_me_reader_eof_total 282
telemt_me_idle_close_by_peer_total 282
telemt_me_route_drop_no_conn_total 15811366
telemt_me_route_drop_channel_closed_total 23
telemt_me_route_drop_queue_full_total 25
telemt_me_route_drop_queue_full_profile_total{profile="high"} 25
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5493432
telemt_me_endpoint_quarantine_total 97
telemt_me_single_endpoint_outage_enter_total 23
telemt_me_single_endpoint_outage_exit_total 23
telemt_me_single_endpoint_outage_reconnect_attempt_total 40
telemt_me_single_endpoint_outage_reconnect_success_total 13
telemt_me_single_endpoint_quarantine_bypass_total 40
telemt_me_single_endpoint_shadow_rotate_total 127
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 10
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 85
telemt_desync_total 8221
telemt_desync_full_logged_total 2098
telemt_desync_suppressed_total 6123
telemt_desync_frames_bucket_total{bucket="1_2"} 1470
telemt_desync_frames_bucket_total{bucket="3_10"} 3307
telemt_desync_frames_bucket_total{bucket="gt_10"} 3444
telemt_pool_swap_total 14
telemt_pool_force_close_total 570
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 223
telemt_me_draining_writers_reap_progress_total 4039
telemt_me_writer_removed_unexpected_total 372
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 700
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 3668
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 424
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 146
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 3469
telemt_me_writer_teardown_success_total{mode="normal"} 4368
telemt_me_writer_teardown_noop_total 4042
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 6872
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 7568
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 7886
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 8217
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 8349
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 8409
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 8410
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 8410
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 8410
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 8410
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 8410
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 8410
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 8410
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 18.670319
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 8410
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 223
telemt_me_refill_failed_total 109
telemt_me_writer_restored_same_endpoint_total 295
telemt_me_writer_restored_fallback_total 3
telemt_me_async_recovery_trigger_total 204
telemt_me_writer_removed_unexpected_minus_restored_total 74
telemt_user_connections_total{user="hello"} 5506715
telemt_user_connections_current{user="hello"} 6602
telemt_user_octets_from_client{user="hello"} 30135849902 (28.07 GB)
telemt_user_octets_to_client{user="hello"} 162743718379 (151.57 GB)
telemt_user_msgs_from_client{user="hello"} 33078
telemt_user_msgs_to_client{user="hello"} 29827
telemt_user_unique_ips_current{user="hello"} 2485
telemt_user_unique_ips_recent_window{user="hello"} 1269
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 145362.2 (40h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9145676
telemt_connections_bad_total 763924
telemt_connections_current 4687
telemt_connections_me_current 4687
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 196545
telemt_upstream_connect_attempt_total 89020
telemt_upstream_connect_success_total 88144
telemt_upstream_connect_fail_total 754
telemt_upstream_connect_attempts_per_request{bucket="1"} 88898
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 54815
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 31869
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 208
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1252
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 754
telemt_me_keepalive_timeout_total 11
telemt_me_reconnect_attempts_total 71173
telemt_me_reconnect_success_total 2374
telemt_me_reader_eof_total 2117
telemt_me_idle_close_by_peer_total 2116
telemt_me_route_drop_no_conn_total 4403324
telemt_me_route_drop_channel_closed_total 19
telemt_me_route_drop_queue_full_total 45
telemt_me_route_drop_queue_full_profile_total{profile="high"} 45
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 7227835
telemt_me_endpoint_quarantine_total 973
telemt_me_single_endpoint_outage_enter_total 31
telemt_me_single_endpoint_outage_exit_total 31
telemt_me_single_endpoint_outage_reconnect_attempt_total 33
telemt_me_single_endpoint_outage_reconnect_success_total 31
telemt_me_single_endpoint_quarantine_bypass_total 33
telemt_me_single_endpoint_shadow_rotate_total 1088
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 42
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 45
telemt_desync_total 36972
telemt_desync_full_logged_total 12671
telemt_desync_suppressed_total 24301
telemt_desync_frames_bucket_total{bucket="1_2"} 7525
telemt_desync_frames_bucket_total{bucket="3_10"} 14240
telemt_desync_frames_bucket_total{bucket="gt_10"} 15207
telemt_pool_swap_total 149
telemt_pool_force_close_total 4395
telemt_pool_stale_pick_total 69
telemt_me_writer_close_signal_drop_total 532
telemt_me_draining_writers_reap_progress_total 49789
telemt_me_writer_removed_unexpected_total 2145
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5253
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 46697
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3798
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 597
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 45394
telemt_me_writer_teardown_success_total{mode="normal"} 51950
telemt_me_writer_teardown_noop_total 49790
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 99988
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 101108
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 101451
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 101696
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 101730
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 101733
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 101733
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 101736
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 101740
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 101740
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 101740
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 101740
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 101740
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 15.229249
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 101740
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 532
telemt_me_refill_failed_total 4247
telemt_me_writer_restored_same_endpoint_total 1993
telemt_me_writer_restored_fallback_total 41
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7333
telemt_me_writer_removed_unexpected_minus_restored_total 111
telemt_user_connections_total{user="hello"} 7229848
telemt_user_connections_current{user="hello"} 4687
telemt_user_octets_from_client{user="hello"} 168873287391 (157.28 GB)
telemt_user_octets_to_client{user="hello"} 2773819169005 (2.52 TB)
telemt_user_msgs_from_client{user="hello"} 146235
telemt_user_msgs_to_client{user="hello"} 572261
telemt_user_unique_ips_current{user="hello"} 1856
telemt_user_unique_ips_recent_window{user="hello"} 614
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 82198.0 (22h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8826163
telemt_connections_bad_total 313844
telemt_connections_current 4396
telemt_connections_me_current 4396
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 3705379
telemt_upstream_connect_attempt_total 41327
telemt_upstream_connect_success_total 41031
telemt_upstream_connect_fail_total 289
telemt_upstream_connect_attempts_per_request{bucket="1"} 41320
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 23595
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17324
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 112
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 289
telemt_me_reconnect_attempts_total 47893
telemt_me_reconnect_success_total 1423
telemt_me_reader_eof_total 1092
telemt_me_idle_close_by_peer_total 1092
telemt_me_route_drop_no_conn_total 3086292
telemt_me_route_drop_channel_closed_total 9
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4275974
telemt_me_endpoint_quarantine_total 549
telemt_me_single_endpoint_outage_enter_total 18
telemt_me_single_endpoint_outage_exit_total 18
telemt_me_single_endpoint_outage_reconnect_attempt_total 58
telemt_me_single_endpoint_outage_reconnect_success_total 18
telemt_me_single_endpoint_quarantine_bypass_total 58
telemt_me_single_endpoint_shadow_rotate_total 621
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 40
telemt_me_floor_cap_block_total 23
telemt_me_floor_swap_idle_failed_total 23
telemt_desync_total 23521
telemt_desync_full_logged_total 7884
telemt_desync_suppressed_total 15637
telemt_desync_frames_bucket_total{bucket="1_2"} 4786
telemt_desync_frames_bucket_total{bucket="3_10"} 9223
telemt_desync_frames_bucket_total{bucket="gt_10"} 9512
telemt_pool_swap_total 86
telemt_pool_force_close_total 2671
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 274
telemt_me_draining_writers_reap_progress_total 28788
telemt_me_writer_removed_unexpected_total 1157
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2615
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 27358
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2273
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 398
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 26117
telemt_me_writer_teardown_success_total{mode="normal"} 29973
telemt_me_writer_teardown_noop_total 28795
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 57829
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 58363
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 58592
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 58768
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 58768
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 58768
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 58768
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 58768
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 58768
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 58768
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 58768
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 58768
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 58768
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 6.261407
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 58768
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 274
telemt_me_refill_failed_total 2701
telemt_me_writer_restored_same_endpoint_total 1271
telemt_me_writer_restored_fallback_total 14
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4328
telemt_user_connections_total{user="hello"} 4271460
telemt_user_connections_current{user="hello"} 4396
telemt_user_octets_from_client{user="hello"} 95096191208 (88.57 GB)
telemt_user_octets_to_client{user="hello"} 1666203261910 (1.52 TB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 1684
telemt_user_unique_ips_recent_window{user="hello"} 654
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 63169.0 (17h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 719647
telemt_connections_bad_total 8494
telemt_connections_current 1037
telemt_connections_me_current 1037
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 13860
telemt_upstream_connect_attempt_total 32331
telemt_upstream_connect_success_total 32249
telemt_upstream_connect_fail_total 69
telemt_upstream_connect_attempts_per_request{bucket="1"} 32318
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14841
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17021
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 387
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 69
telemt_me_reconnect_attempts_total 1450
telemt_me_reconnect_success_total 620
telemt_me_reader_eof_total 600
telemt_me_idle_close_by_peer_total 600
telemt_me_route_drop_no_conn_total 241630
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 649837
telemt_me_endpoint_quarantine_total 572
telemt_me_single_endpoint_outage_enter_total 7
telemt_me_single_endpoint_outage_exit_total 7
telemt_me_single_endpoint_outage_reconnect_attempt_total 8
telemt_me_single_endpoint_outage_reconnect_success_total 6
telemt_me_single_endpoint_quarantine_bypass_total 8
telemt_me_single_endpoint_shadow_rotate_total 526
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 37
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 43
telemt_desync_total 3523
telemt_desync_full_logged_total 1043
telemt_desync_suppressed_total 2480
telemt_desync_frames_bucket_total{bucket="1_2"} 859
telemt_desync_frames_bucket_total{bucket="3_10"} 1404
telemt_desync_frames_bucket_total{bucket="gt_10"} 1260
telemt_pool_swap_total 67
telemt_pool_force_close_total 1624
telemt_me_writer_close_signal_drop_total 96
telemt_me_draining_writers_reap_progress_total 26459
telemt_me_writer_removed_unexpected_total 582
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2020
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 25041
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1547
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 77
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 24835
telemt_me_writer_teardown_success_total{mode="normal"} 27061
telemt_me_writer_teardown_noop_total 26461
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 52980
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 53392
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 53497
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 53522
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 53522
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 53522
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 53522
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 53522
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 53522
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 53522
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 53522
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 53522
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 53522
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 2.903211
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 53522
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 96
telemt_me_refill_failed_total 45
telemt_me_writer_restored_same_endpoint_total 537
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 36
telemt_user_connections_total{user="hello"} 651525
telemt_user_connections_current{user="hello"} 1037
telemt_user_octets_from_client{user="hello"} 12443953637 (11.59 GB)
telemt_user_octets_to_client{user="hello"} 312714073007 (291.24 GB)
telemt_user_msgs_from_client{user="hello"} 18894
telemt_user_msgs_to_client{user="hello"} 38815
telemt_user_unique_ips_current{user="hello"} 382
telemt_user_unique_ips_recent_window{user="hello"} 137
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 145366.5 (40h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11153795
telemt_connections_bad_total 1292095
telemt_connections_current 5823
telemt_connections_me_current 5823
telemt_handshake_timeouts_total 299777
telemt_upstream_connect_attempt_total 55084
telemt_upstream_connect_success_total 54871
telemt_upstream_connect_fail_total 165
telemt_upstream_connect_attempts_per_request{bucket="1"} 55036
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 27061
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 27763
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 46
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 165
telemt_me_reconnect_attempts_total 2154
telemt_me_reconnect_success_total 1147
telemt_me_reader_eof_total 1111
telemt_me_idle_close_by_peer_total 1111
telemt_me_route_drop_no_conn_total 3507317
telemt_me_route_drop_channel_closed_total 90
telemt_me_route_drop_queue_full_total 32
telemt_me_route_drop_queue_full_profile_total{profile="high"} 32
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8383739
telemt_me_endpoint_quarantine_total 1002
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 12
telemt_me_single_endpoint_outage_reconnect_success_total 10
telemt_me_single_endpoint_quarantine_bypass_total 12
telemt_me_single_endpoint_shadow_rotate_total 1092
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 40
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 43
telemt_desync_total 34198
telemt_desync_full_logged_total 11217
telemt_desync_suppressed_total 22981
telemt_desync_frames_bucket_total{bucket="1_2"} 8210
telemt_desync_frames_bucket_total{bucket="3_10"} 12642
telemt_desync_frames_bucket_total{bucket="gt_10"} 13346
telemt_pool_swap_total 161
telemt_pool_force_close_total 4414
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 550
telemt_me_draining_writers_reap_progress_total 49642
telemt_me_writer_removed_unexpected_total 1066
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4054
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 46690
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4264
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 150
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 45228
telemt_me_writer_teardown_success_total{mode="normal"} 50744
telemt_me_writer_teardown_noop_total 49644
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 98352
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 99733
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 100005
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 100282
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 100384
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 100388
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 100388
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 100388
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 100388
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 100388
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 100388
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 100388
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 100388
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 14.948741
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 100388
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 550
telemt_me_refill_failed_total 52
telemt_me_writer_restored_same_endpoint_total 1003
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 44
telemt_me_writer_removed_unexpected_minus_restored_total 52
telemt_user_connections_total{user="hello"} 8354656
telemt_user_connections_current{user="hello"} 5823
telemt_user_octets_from_client{user="hello"} 160383590112 (149.37 GB)
telemt_user_octets_to_client{user="hello"} 3777441349316 (3.44 TB)
telemt_user_unique_ips_current{user="hello"} 2105
telemt_user_unique_ips_recent_window{user="hello"} 758
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 145363.2 (40h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9665961
telemt_connections_bad_total 1086806
telemt_connections_current 4274
telemt_connections_me_current 4274
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 251262
telemt_upstream_connect_attempt_total 80402
telemt_upstream_connect_success_total 79817
telemt_upstream_connect_fail_total 507
telemt_upstream_connect_attempts_per_request{bucket="1"} 80324
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 44232
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 32680
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 909
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1996
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 507
telemt_me_reconnect_attempts_total 8499
telemt_me_reconnect_success_total 1870
telemt_me_reader_eof_total 1742
telemt_me_idle_close_by_peer_total 1742
telemt_me_seq_mismatch_total 70
telemt_me_route_drop_no_conn_total 4196641
telemt_me_route_drop_channel_closed_total 303
telemt_me_route_drop_queue_full_total 15
telemt_me_route_drop_queue_full_profile_total{profile="high"} 15
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 7435526
telemt_me_endpoint_quarantine_total 1114
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_outage_enter_total 36
telemt_me_single_endpoint_outage_exit_total 36
telemt_me_single_endpoint_outage_reconnect_attempt_total 36
telemt_me_single_endpoint_outage_reconnect_success_total 34
telemt_me_single_endpoint_quarantine_bypass_total 36
telemt_me_single_endpoint_shadow_rotate_total 1098
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 44
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 44
telemt_desync_total 33424
telemt_desync_full_logged_total 10938
telemt_desync_suppressed_total 22486
telemt_desync_frames_bucket_total{bucket="1_2"} 8269
telemt_desync_frames_bucket_total{bucket="3_10"} 12454
telemt_desync_frames_bucket_total{bucket="gt_10"} 12701
telemt_pool_swap_total 155
telemt_pool_force_close_total 4284
telemt_pool_stale_pick_total 358
telemt_me_writer_close_signal_drop_total 539
telemt_me_draining_writers_reap_progress_total 48757
telemt_me_writer_removed_unexpected_total 1766
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5024
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 45565
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3921
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 363
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 44473
telemt_me_writer_teardown_success_total{mode="normal"} 50589
telemt_me_writer_teardown_noop_total 48761
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 97093
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 98569
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 99041
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 99302
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 99350
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 99350
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 99350
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 99350
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 99350
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 99350
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 99350
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 99350
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 99350
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 14.798981
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 99350
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 539
telemt_me_refill_failed_total 340
telemt_me_writer_restored_same_endpoint_total 1514
telemt_me_writer_restored_fallback_total 94
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 128
telemt_me_writer_removed_unexpected_minus_restored_total 158
telemt_user_connections_total{user="hello"} 7442893
telemt_user_connections_current{user="hello"} 4274
telemt_user_octets_from_client{user="hello"} 132106393425 (123.03 GB)
telemt_user_octets_to_client{user="hello"} 2960874249675 (2.69 TB)
telemt_user_msgs_from_client{user="hello"} 100726
telemt_user_msgs_to_client{user="hello"} 247529
telemt_user_unique_ips_current{user="hello"} 1762
telemt_user_unique_ips_recent_window{user="hello"} 615
```