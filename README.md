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

# Server Metrics 2026-03-22 11:32:18 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 51955.9 (14h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1462920
telemt_connections_bad_total 72825
telemt_connections_current 1896
telemt_connections_me_current 1896
telemt_handshake_timeouts_total 66873
telemt_upstream_connect_attempt_total 19980
telemt_upstream_connect_success_total 19979
telemt_upstream_connect_attempts_per_request{bucket="1"} 19979
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6878
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13039
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 50
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 12
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 679
telemt_me_reconnect_success_total 331
telemt_me_reader_eof_total 326
telemt_me_idle_close_by_peer_total 326
telemt_me_route_drop_no_conn_total 879374
telemt_me_route_drop_channel_closed_total 443
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1230788
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_endpoint_quarantine_total 370
telemt_me_single_endpoint_outage_enter_total 2
telemt_me_single_endpoint_outage_exit_total 2
telemt_me_single_endpoint_outage_reconnect_attempt_total 2
telemt_me_single_endpoint_outage_reconnect_success_total 2
telemt_me_single_endpoint_quarantine_bypass_total 2
telemt_me_single_endpoint_shadow_rotate_total 417
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 14
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
telemt_me_writers_active_current 48
telemt_desync_total 7752
telemt_desync_full_logged_total 2315
telemt_desync_suppressed_total 5437
telemt_desync_frames_bucket_total{bucket="1_2"} 2227
telemt_desync_frames_bucket_total{bucket="3_10"} 2912
telemt_desync_frames_bucket_total{bucket="gt_10"} 2613
telemt_pool_swap_total 57
telemt_pool_force_close_total 1669
telemt_pool_stale_pick_total 2
telemt_me_writer_close_signal_drop_total 252
telemt_me_draining_writers_reap_progress_total 18188
telemt_me_writer_removed_unexpected_total 321
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1279
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 17139
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1634
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 35
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 16519
telemt_me_writer_teardown_success_total{mode="normal"} 18418
telemt_me_writer_teardown_noop_total 18190
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 31789
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 32835
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 33696
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 35055
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 36028
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 36496
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 36606
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 36608
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 36608
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 36608
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 36608
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 36608
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 36608
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 115.551907
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 36608
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 252
telemt_me_refill_failed_total 18
telemt_me_writer_restored_same_endpoint_total 296
telemt_me_writer_removed_unexpected_minus_restored_total 25
telemt_user_connections_total{user="hello"} 1228295
telemt_user_connections_current{user="hello"} 1896
telemt_user_octets_from_client{user="hello"} 19785264988 (18.43 GB)
telemt_user_octets_to_client{user="hello"} 380040560852 (353.94 GB)
telemt_user_unique_ips_current{user="hello"} 700
telemt_user_unique_ips_recent_window{user="hello"} 401
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 65322.4 (18h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2404627
telemt_connections_bad_total 197976
telemt_connections_current 2449
telemt_connections_me_current 2449
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 4
telemt_handshake_timeouts_total 55299
telemt_upstream_connect_attempt_total 43754
telemt_upstream_connect_success_total 43241
telemt_upstream_connect_fail_total 453
telemt_upstream_connect_attempts_per_request{bucket="1"} 43694
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26557
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16572
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 112
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 453
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 3367
telemt_me_reconnect_success_total 1499
telemt_me_reader_eof_total 1382
telemt_me_idle_close_by_peer_total 1382
telemt_me_route_drop_no_conn_total 2058482
telemt_me_route_drop_channel_closed_total 20
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1897588
telemt_me_endpoint_quarantine_total 556
telemt_me_single_endpoint_outage_enter_total 30
telemt_me_single_endpoint_outage_exit_total 30
telemt_me_single_endpoint_outage_reconnect_attempt_total 30
telemt_me_single_endpoint_outage_reconnect_success_total 30
telemt_me_single_endpoint_quarantine_bypass_total 30
telemt_me_single_endpoint_shadow_rotate_total 514
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
telemt_me_writers_active_current 86
telemt_desync_total 7567
telemt_desync_full_logged_total 4273
telemt_desync_suppressed_total 3294
telemt_desync_frames_bucket_total{bucket="1_2"} 1739
telemt_desync_frames_bucket_total{bucket="3_10"} 2968
telemt_desync_frames_bucket_total{bucket="gt_10"} 2860
telemt_pool_swap_total 65
telemt_pool_force_close_total 1814
telemt_me_writer_close_signal_drop_total 152
telemt_me_draining_writers_reap_progress_total 26022
telemt_me_writer_removed_unexpected_total 1345
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2883
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 24481
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1626
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 188
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 24208
telemt_me_writer_teardown_success_total{mode="normal"} 27364
telemt_me_writer_teardown_noop_total 26022
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 52244
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 52929
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 53149
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 53366
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 53384
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 53386
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 53386
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 53386
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 53386
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 53386
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 53386
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 53386
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 53386
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 7.940108
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 53386
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 152
telemt_me_refill_failed_total 84
telemt_me_writer_restored_same_endpoint_total 1246
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 21
telemt_me_writer_removed_unexpected_minus_restored_total 77
telemt_user_connections_total{user="hello"} 1909489
telemt_user_connections_current{user="hello"} 2449
telemt_user_octets_from_client{user="hello"} 24182362703 (22.52 GB)
telemt_user_octets_to_client{user="hello"} 479511767574 (446.58 GB)
telemt_user_msgs_from_client{user="hello"} 42816
telemt_user_msgs_to_client{user="hello"} 172415
telemt_user_unique_ips_current{user="hello"} 1429
telemt_user_unique_ips_recent_window{user="hello"} 663
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 140182.0 (38h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 12271084
telemt_connections_bad_total 1070245
telemt_connections_current 4884
telemt_connections_me_current 4884
telemt_handshake_timeouts_total 322043
telemt_upstream_connect_attempt_total 50954
telemt_upstream_connect_success_total 50874
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 50882
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 23022
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 27638
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 208
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 2194
telemt_me_reconnect_success_total 1122
telemt_me_reader_eof_total 1103
telemt_me_idle_close_by_peer_total 1102
telemt_me_route_drop_no_conn_total 9771612
telemt_me_route_drop_channel_closed_total 106
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9789603
telemt_me_endpoint_quarantine_total 888
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 9
telemt_me_single_endpoint_outage_reconnect_success_total 9
telemt_me_single_endpoint_quarantine_bypass_total 9
telemt_me_single_endpoint_shadow_rotate_total 1044
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 38
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
telemt_desync_total 40029
telemt_desync_full_logged_total 12879
telemt_desync_suppressed_total 27150
telemt_desync_frames_bucket_total{bucket="1_2"} 9021
telemt_desync_frames_bucket_total{bucket="3_10"} 15619
telemt_desync_frames_bucket_total{bucket="gt_10"} 15389
telemt_pool_swap_total 151
telemt_pool_force_close_total 5094
telemt_pool_stale_pick_total 19
telemt_me_writer_close_signal_drop_total 798
telemt_me_draining_writers_reap_progress_total 46474
telemt_me_writer_removed_unexpected_total 1062
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3993
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 42942
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 40
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4753
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 341
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 41380
telemt_me_writer_teardown_success_total{mode="normal"} 46935
telemt_me_writer_teardown_noop_total 46518
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 85062
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 87694
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 89035
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 90946
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 92301
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 93043
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 93441
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 93453
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 93453
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 93453
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 93453
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 93453
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 93453
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 214.057760
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 93453
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 798
telemt_me_refill_failed_total 58
telemt_me_writer_restored_same_endpoint_total 976
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 10
telemt_me_writer_removed_unexpected_minus_restored_total 79
telemt_user_connections_total{user="hello"} 9778625
telemt_user_connections_current{user="hello"} 4884
telemt_user_octets_from_client{user="hello"} 145832299512 (135.82 GB)
telemt_user_octets_to_client{user="hello"} 2774015173956 (2.52 TB)
telemt_user_unique_ips_current{user="hello"} 1895
telemt_user_unique_ips_recent_window{user="hello"} 804
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 140183.6 (38h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9249813
telemt_connections_bad_total 828763
telemt_connections_current 4905
telemt_connections_me_current 4905
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 281977
telemt_upstream_connect_attempt_total 57553
telemt_upstream_connect_success_total 56973
telemt_upstream_connect_fail_total 266
telemt_upstream_connect_attempts_per_request{bucket="1"} 57239
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 27667
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 28004
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 131
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1171
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 266
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 182
telemt_me_reconnect_attempts_total 3223
telemt_me_reconnect_success_total 1307
telemt_me_reader_eof_total 1198
telemt_me_idle_close_by_peer_total 1198
telemt_me_route_drop_no_conn_total 3750874
telemt_me_route_drop_channel_closed_total 383
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6901799
telemt_me_endpoint_quarantine_total 884
telemt_me_single_endpoint_outage_enter_total 21
telemt_me_single_endpoint_outage_exit_total 21
telemt_me_single_endpoint_outage_reconnect_attempt_total 26
telemt_me_single_endpoint_outage_reconnect_success_total 19
telemt_me_single_endpoint_quarantine_bypass_total 26
telemt_me_single_endpoint_shadow_rotate_total 1070
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
telemt_me_writers_active_current 43
telemt_desync_total 31242
telemt_desync_full_logged_total 10563
telemt_desync_suppressed_total 20679
telemt_desync_frames_bucket_total{bucket="1_2"} 7672
telemt_desync_frames_bucket_total{bucket="3_10"} 12031
telemt_desync_frames_bucket_total{bucket="gt_10"} 11539
telemt_pool_swap_total 150
telemt_pool_force_close_total 4602
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 531
telemt_me_draining_writers_reap_progress_total 45016
telemt_me_writer_removed_unexpected_total 1231
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3967
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 42177
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 8
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4240
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 362
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 40415
telemt_me_writer_teardown_success_total{mode="normal"} 46143
telemt_me_writer_teardown_noop_total 45024
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 86124
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 88509
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 89396
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 90285
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 90888
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 91140
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 91167
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 91167
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 91167
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 91167
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 91167
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 91167
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 91167
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 70.071772
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 91167
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 531
telemt_me_refill_failed_total 104
telemt_me_writer_restored_same_endpoint_total 1121
telemt_me_writer_restored_fallback_total 12
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 212
telemt_me_writer_removed_unexpected_minus_restored_total 98
telemt_user_connections_total{user="hello"} 6823223
telemt_user_connections_current{user="hello"} 4905
telemt_user_octets_from_client{user="hello"} 178691441939 (166.42 GB)
telemt_user_octets_to_client{user="hello"} 3139814431982 (2.86 TB)
telemt_user_msgs_from_client{user="hello"} 42822
telemt_user_msgs_to_client{user="hello"} 51589
telemt_user_unique_ips_current{user="hello"} 1909
telemt_user_unique_ips_recent_window{user="hello"} 660
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 140147.5 (38h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8774664
telemt_connections_bad_total 732513
telemt_connections_current 4081
telemt_connections_me_current 4081
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 279731
telemt_upstream_connect_attempt_total 61782
telemt_upstream_connect_success_total 61067
telemt_upstream_connect_fail_total 147
telemt_upstream_connect_attempts_per_request{bucket="1"} 61214
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 29810
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 28833
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1025
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1399
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 147
telemt_me_keepalive_timeout_total 238
telemt_me_reconnect_attempts_total 3730
telemt_me_reconnect_success_total 1544
telemt_me_reader_eof_total 1432
telemt_me_idle_close_by_peer_total 1432
telemt_me_route_drop_no_conn_total 3716195
telemt_me_route_drop_channel_closed_total 251
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6597719
telemt_me_endpoint_quarantine_total 961
telemt_me_single_endpoint_outage_enter_total 19
telemt_me_single_endpoint_outage_exit_total 19
telemt_me_single_endpoint_outage_reconnect_attempt_total 19
telemt_me_single_endpoint_outage_reconnect_success_total 15
telemt_me_single_endpoint_quarantine_bypass_total 19
telemt_me_single_endpoint_shadow_rotate_total 1025
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 52
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
telemt_desync_total 30539
telemt_desync_full_logged_total 10347
telemt_desync_suppressed_total 20192
telemt_desync_frames_bucket_total{bucket="1_2"} 7486
telemt_desync_frames_bucket_total{bucket="3_10"} 11772
telemt_desync_frames_bucket_total{bucket="gt_10"} 11281
telemt_pool_swap_total 147
telemt_pool_force_close_total 4522
telemt_pool_stale_pick_total 1619
telemt_me_writer_close_signal_drop_total 536
telemt_me_draining_writers_reap_progress_total 45727
telemt_me_writer_removed_unexpected_total 1459
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4345
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 42779
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 17
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4087
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 435
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 41205
telemt_me_writer_teardown_success_total{mode="normal"} 47124
telemt_me_writer_teardown_noop_total 45744
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 88609
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 90696
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 91460
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 92277
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 92672
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 92805
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 92864
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 92866
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 92868
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 92868
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 92868
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 92868
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 92868
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 56.992199
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 92868
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 536
telemt_me_refill_failed_total 113
telemt_me_writer_restored_same_endpoint_total 1363
telemt_me_writer_restored_fallback_total 7
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 50
telemt_me_writer_removed_unexpected_minus_restored_total 89
telemt_user_connections_total{user="hello"} 6588903
telemt_user_connections_current{user="hello"} 4081
telemt_user_octets_from_client{user="hello"} 162205533255 (151.07 GB)
telemt_user_octets_to_client{user="hello"} 2857689296411 (2.60 TB)
telemt_user_msgs_from_client{user="hello"} 44246
telemt_user_msgs_to_client{user="hello"} 113178
telemt_user_unique_ips_current{user="hello"} 1612
telemt_user_unique_ips_recent_window{user="hello"} 674
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 10427.6 (2h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4436192
telemt_connections_bad_total 280866
telemt_connections_current 6491
telemt_connections_me_current 6491
telemt_relay_adaptive_promotions_total 7
telemt_relay_adaptive_hard_promotions_total 7
telemt_handshake_timeouts_total 68157
telemt_upstream_connect_attempt_total 23097
telemt_upstream_connect_success_total 22061
telemt_upstream_connect_fail_total 831
telemt_upstream_connect_attempts_per_request{bucket="1"} 22892
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12805
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4380
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 262
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4614
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 831
telemt_me_keepalive_timeout_total 419
telemt_me_reconnect_attempts_total 2229
telemt_me_reconnect_success_total 332
telemt_me_reader_eof_total 203
telemt_me_idle_close_by_peer_total 203
telemt_me_route_drop_no_conn_total 10121963
telemt_me_route_drop_channel_closed_total 20
telemt_me_route_drop_queue_full_total 11
telemt_me_route_drop_queue_full_profile_total{profile="high"} 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3701449
telemt_me_endpoint_quarantine_total 77
telemt_me_single_endpoint_outage_enter_total 22
telemt_me_single_endpoint_outage_exit_total 22
telemt_me_single_endpoint_outage_reconnect_attempt_total 39
telemt_me_single_endpoint_outage_reconnect_success_total 12
telemt_me_single_endpoint_quarantine_bypass_total 39
telemt_me_single_endpoint_shadow_rotate_total 88
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
telemt_me_writers_active_current 47
telemt_desync_total 5355
telemt_desync_full_logged_total 1414
telemt_desync_suppressed_total 3941
telemt_desync_frames_bucket_total{bucket="1_2"} 990
telemt_desync_frames_bucket_total{bucket="3_10"} 2157
telemt_desync_frames_bucket_total{bucket="gt_10"} 2208
telemt_pool_swap_total 9
telemt_pool_force_close_total 399
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 166
telemt_me_draining_writers_reap_progress_total 2735
telemt_me_writer_removed_unexpected_total 292
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 521
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 2469
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 269
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 130
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 2336
telemt_me_writer_teardown_success_total{mode="normal"} 2990
telemt_me_writer_teardown_noop_total 2738
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 4620
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 5150
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 5383
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 5618
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 5700
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 5727
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 5728
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 5728
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 5728
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 5728
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 5728
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 5728
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 5728
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 11.986548
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 5728
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 166
telemt_me_refill_failed_total 105
telemt_me_writer_restored_same_endpoint_total 220
telemt_me_writer_restored_fallback_total 3
telemt_me_async_recovery_trigger_total 204
telemt_me_writer_removed_unexpected_minus_restored_total 69
telemt_user_connections_total{user="hello"} 3716797
telemt_user_connections_current{user="hello"} 6491
telemt_user_octets_from_client{user="hello"} 20113749442 (18.73 GB)
telemt_user_octets_to_client{user="hello"} 108771669755 (101.30 GB)
telemt_user_msgs_from_client{user="hello"} 33078
telemt_user_msgs_to_client{user="hello"} 29827
telemt_user_unique_ips_current{user="hello"} 2428
telemt_user_unique_ips_recent_window{user="hello"} 1389
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 140154.1 (38h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8512537
telemt_connections_bad_total 737166
telemt_connections_current 4876
telemt_connections_me_current 4876
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 177485
telemt_upstream_connect_attempt_total 87033
telemt_upstream_connect_success_total 86170
telemt_upstream_connect_fail_total 742
telemt_upstream_connect_attempts_per_request{bucket="1"} 86912
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 53886
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 30833
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 208
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1243
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 742
telemt_me_keepalive_timeout_total 11
telemt_me_reconnect_attempts_total 70707
telemt_me_reconnect_success_total 2206
telemt_me_reader_eof_total 1937
telemt_me_idle_close_by_peer_total 1936
telemt_me_route_drop_no_conn_total 3815359
telemt_me_route_drop_channel_closed_total 18
telemt_me_route_drop_queue_full_total 45
telemt_me_route_drop_queue_full_profile_total{profile="high"} 45
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6722077
telemt_me_endpoint_quarantine_total 942
telemt_me_single_endpoint_outage_enter_total 30
telemt_me_single_endpoint_outage_exit_total 30
telemt_me_single_endpoint_outage_reconnect_attempt_total 32
telemt_me_single_endpoint_outage_reconnect_success_total 30
telemt_me_single_endpoint_quarantine_bypass_total 32
telemt_me_single_endpoint_shadow_rotate_total 1051
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
telemt_me_writers_active_current 44
telemt_desync_total 34347
telemt_desync_full_logged_total 11820
telemt_desync_suppressed_total 22527
telemt_desync_frames_bucket_total{bucket="1_2"} 7046
telemt_desync_frames_bucket_total{bucket="3_10"} 13183
telemt_desync_frames_bucket_total{bucket="gt_10"} 14118
telemt_pool_swap_total 145
telemt_pool_force_close_total 4223
telemt_pool_stale_pick_total 69
telemt_me_writer_close_signal_drop_total 510
telemt_me_draining_writers_reap_progress_total 48117
telemt_me_writer_removed_unexpected_total 1966
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4961
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 45147
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3681
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 542
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 43894
telemt_me_writer_teardown_success_total{mode="normal"} 50108
telemt_me_writer_teardown_noop_total 48118
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 96542
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 97613
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 97942
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 98185
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 98216
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 98219
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 98219
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 98222
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 98226
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 98226
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 98226
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 98226
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 98226
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 14.821361
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 98226
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 510
telemt_me_refill_failed_total 4235
telemt_me_writer_restored_same_endpoint_total 1831
telemt_me_writer_restored_fallback_total 41
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7333
telemt_me_writer_removed_unexpected_minus_restored_total 94
telemt_user_connections_total{user="hello"} 6725093
telemt_user_connections_current{user="hello"} 4876
telemt_user_octets_from_client{user="hello"} 160431735035 (149.41 GB)
telemt_user_octets_to_client{user="hello"} 2637771685633 (2.40 TB)
telemt_user_msgs_from_client{user="hello"} 146235
telemt_user_msgs_to_client{user="hello"} 572261
telemt_user_unique_ips_current{user="hello"} 1940
telemt_user_unique_ips_recent_window{user="hello"} 667
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 76990.1 (21h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7758301
telemt_connections_bad_total 283871
telemt_connections_current 4431
telemt_connections_me_current 4431
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 3219358
telemt_upstream_connect_attempt_total 39519
telemt_upstream_connect_success_total 39233
telemt_upstream_connect_fail_total 279
telemt_upstream_connect_attempts_per_request{bucket="1"} 39512
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 22795
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16331
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 107
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 279
telemt_me_reconnect_attempts_total 47788
telemt_me_reconnect_success_total 1343
telemt_me_reader_eof_total 1011
telemt_me_idle_close_by_peer_total 1011
telemt_me_route_drop_no_conn_total 2490068
telemt_me_route_drop_channel_closed_total 9
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3809001
telemt_me_endpoint_quarantine_total 524
telemt_me_single_endpoint_outage_enter_total 17
telemt_me_single_endpoint_outage_exit_total 17
telemt_me_single_endpoint_outage_reconnect_attempt_total 57
telemt_me_single_endpoint_outage_reconnect_success_total 17
telemt_me_single_endpoint_quarantine_bypass_total 57
telemt_me_single_endpoint_shadow_rotate_total 585
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 20
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
telemt_me_floor_cap_block_total 23
telemt_me_floor_swap_idle_failed_total 23
telemt_desync_total 20789
telemt_desync_full_logged_total 6956
telemt_desync_suppressed_total 13833
telemt_desync_frames_bucket_total{bucket="1_2"} 4231
telemt_desync_frames_bucket_total{bucket="3_10"} 8053
telemt_desync_frames_bucket_total{bucket="gt_10"} 8505
telemt_pool_swap_total 81
telemt_pool_force_close_total 2487
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 248
telemt_me_draining_writers_reap_progress_total 27221
telemt_me_writer_removed_unexpected_total 1078
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2425
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 25900
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2126
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 361
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 24734
telemt_me_writer_teardown_success_total{mode="normal"} 28325
telemt_me_writer_teardown_noop_total 27228
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 54701
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 55191
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 55402
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 55553
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 55553
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 55553
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 55553
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 55553
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 55553
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 55553
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 55553
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 55553
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 55553
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 5.433517
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 55553
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 248
telemt_me_refill_failed_total 2700
telemt_me_writer_restored_same_endpoint_total 1195
telemt_me_writer_restored_fallback_total 14
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4328
telemt_user_connections_total{user="hello"} 3807154
telemt_user_connections_current{user="hello"} 4431
telemt_user_octets_from_client{user="hello"} 88498350636 (82.42 GB)
telemt_user_octets_to_client{user="hello"} 1529219278390 (1.39 TB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 1683
telemt_user_unique_ips_recent_window{user="hello"} 653
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 57960.7 (16h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 618844
telemt_connections_bad_total 5731
telemt_connections_current 964
telemt_connections_me_current 964
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 11965
telemt_upstream_connect_attempt_total 30144
telemt_upstream_connect_success_total 30075
telemt_upstream_connect_fail_total 61
telemt_upstream_connect_attempts_per_request{bucket="1"} 30136
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13943
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15803
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 329
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 61
telemt_me_reconnect_attempts_total 1330
telemt_me_reconnect_success_total 567
telemt_me_reader_eof_total 551
telemt_me_idle_close_by_peer_total 551
telemt_me_route_drop_no_conn_total 205303
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 559282
telemt_me_endpoint_quarantine_total 530
telemt_me_single_endpoint_outage_enter_total 7
telemt_me_single_endpoint_outage_exit_total 7
telemt_me_single_endpoint_outage_reconnect_attempt_total 8
telemt_me_single_endpoint_outage_reconnect_success_total 6
telemt_me_single_endpoint_quarantine_bypass_total 8
telemt_me_single_endpoint_shadow_rotate_total 491
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
telemt_me_writers_active_current 45
telemt_desync_total 3069
telemt_desync_full_logged_total 881
telemt_desync_suppressed_total 2188
telemt_desync_frames_bucket_total{bucket="1_2"} 802
telemt_desync_frames_bucket_total{bucket="3_10"} 1207
telemt_desync_frames_bucket_total{bucket="gt_10"} 1060
telemt_pool_swap_total 61
telemt_pool_force_close_total 1490
telemt_me_writer_close_signal_drop_total 79
telemt_me_draining_writers_reap_progress_total 24565
telemt_me_writer_removed_unexpected_total 534
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1845
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 23272
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1414
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 76
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 23075
telemt_me_writer_teardown_success_total{mode="normal"} 25117
telemt_me_writer_teardown_noop_total 24565
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 49192
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 49558
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 49657
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 49682
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 49682
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 49682
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 49682
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 49682
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 49682
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 49682
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 49682
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 49682
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 49682
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 2.687693
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 49682
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 79
telemt_me_refill_failed_total 42
telemt_me_writer_restored_same_endpoint_total 497
telemt_me_writer_restored_fallback_total 2
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 35
telemt_user_connections_total{user="hello"} 561169
telemt_user_connections_current{user="hello"} 964
telemt_user_octets_from_client{user="hello"} 10682414981 (9.95 GB)
telemt_user_octets_to_client{user="hello"} 262880871283 (244.83 GB)
telemt_user_msgs_from_client{user="hello"} 18894
telemt_user_msgs_to_client{user="hello"} 38815
telemt_user_unique_ips_current{user="hello"} 367
telemt_user_unique_ips_recent_window{user="hello"} 154
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 140158.6 (38h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10317015
telemt_connections_bad_total 1205009
telemt_connections_current 5995
telemt_connections_me_current 5995
telemt_handshake_timeouts_total 273073
telemt_upstream_connect_attempt_total 53506
telemt_upstream_connect_success_total 53301
telemt_upstream_connect_fail_total 158
telemt_upstream_connect_attempts_per_request{bucket="1"} 53459
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26313
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 26945
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 42
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 158
telemt_me_reconnect_attempts_total 2053
telemt_me_reconnect_success_total 1100
telemt_me_reader_eof_total 1065
telemt_me_idle_close_by_peer_total 1065
telemt_me_route_drop_no_conn_total 3008745
telemt_me_route_drop_channel_closed_total 81
telemt_me_route_drop_queue_full_total 29
telemt_me_route_drop_queue_full_profile_total{profile="high"} 29
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 7707219
telemt_me_endpoint_quarantine_total 977
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 12
telemt_me_single_endpoint_outage_reconnect_success_total 10
telemt_me_single_endpoint_quarantine_bypass_total 12
telemt_me_single_endpoint_shadow_rotate_total 1054
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
telemt_me_writers_active_current 44
telemt_desync_total 31465
telemt_desync_full_logged_total 10346
telemt_desync_suppressed_total 21119
telemt_desync_frames_bucket_total{bucket="1_2"} 7617
telemt_desync_frames_bucket_total{bucket="3_10"} 11550
telemt_desync_frames_bucket_total{bucket="gt_10"} 12298
telemt_pool_swap_total 155
telemt_pool_force_close_total 4216
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 517
telemt_me_draining_writers_reap_progress_total 48263
telemt_me_writer_removed_unexpected_total 1023
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3906
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 45413
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4087
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 129
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 44047
telemt_me_writer_teardown_success_total{mode="normal"} 49319
telemt_me_writer_teardown_noop_total 48265
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 95749
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 97004
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 97235
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 97484
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 97581
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 97584
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 97584
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 97584
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 97584
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 97584
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 97584
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 97584
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 97584
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 13.668409
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 97584
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 517
telemt_me_refill_failed_total 49
telemt_me_writer_restored_same_endpoint_total 960
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 52
telemt_user_connections_total{user="hello"} 7678785
telemt_user_connections_current{user="hello"} 5995
telemt_user_octets_from_client{user="hello"} 149019521048 (138.79 GB)
telemt_user_octets_to_client{user="hello"} 3558490417248 (3.24 TB)
telemt_user_unique_ips_current{user="hello"} 2142
telemt_user_unique_ips_recent_window{user="hello"} 727
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 140154.9 (38h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9031989
telemt_connections_bad_total 1022336
telemt_connections_current 4815
telemt_connections_me_current 4815
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 229740
telemt_upstream_connect_attempt_total 78031
telemt_upstream_connect_success_total 77472
telemt_upstream_connect_fail_total 488
telemt_upstream_connect_attempts_per_request{bucket="1"} 77960
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 43180
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 31413
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 909
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1970
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 488
telemt_me_reconnect_attempts_total 6647
telemt_me_reconnect_success_total 1581
telemt_me_reader_eof_total 1402
telemt_me_idle_close_by_peer_total 1402
telemt_me_seq_mismatch_total 67
telemt_me_route_drop_no_conn_total 3490147
telemt_me_route_drop_channel_closed_total 278
telemt_me_route_drop_queue_full_total 15
telemt_me_route_drop_queue_full_profile_total{profile="high"} 15
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6920772
telemt_me_endpoint_quarantine_total 1088
telemt_me_single_endpoint_outage_enter_total 35
telemt_me_single_endpoint_outage_exit_total 35
telemt_me_single_endpoint_outage_reconnect_attempt_total 35
telemt_me_single_endpoint_outage_reconnect_success_total 33
telemt_me_single_endpoint_quarantine_bypass_total 35
telemt_me_single_endpoint_shadow_rotate_total 1061
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 41
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
telemt_me_writers_active_current 48
telemt_desync_total 30746
telemt_desync_full_logged_total 10106
telemt_desync_suppressed_total 20640
telemt_desync_frames_bucket_total{bucket="1_2"} 7600
telemt_desync_frames_bucket_total{bucket="3_10"} 11415
telemt_desync_frames_bucket_total{bucket="gt_10"} 11731
telemt_pool_swap_total 152
telemt_pool_force_close_total 4151
telemt_pool_stale_pick_total 358
telemt_me_writer_close_signal_drop_total 515
telemt_me_draining_writers_reap_progress_total 46918
telemt_me_writer_removed_unexpected_total 1421
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4568
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 43835
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3840
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 311
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 42767
telemt_me_writer_teardown_success_total{mode="normal"} 48403
telemt_me_writer_teardown_noop_total 46922
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 93186
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 94569
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 95030
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 95287
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 95325
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 95325
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 95325
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 95325
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 95325
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 95325
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 95325
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 95325
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 95325
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 13.929956
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 95325
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 515
telemt_me_refill_failed_total 291
telemt_me_writer_restored_same_endpoint_total 1231
telemt_me_writer_restored_fallback_total 91
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 128
telemt_me_writer_removed_unexpected_minus_restored_total 99
telemt_user_connections_total{user="hello"} 6928530
telemt_user_connections_current{user="hello"} 4815
telemt_user_octets_from_client{user="hello"} 123992726673 (115.48 GB)
telemt_user_octets_to_client{user="hello"} 2846739814239 (2.59 TB)
telemt_user_msgs_from_client{user="hello"} 100726
telemt_user_msgs_to_client{user="hello"} 247529
telemt_user_unique_ips_current{user="hello"} 1863
telemt_user_unique_ips_recent_window{user="hello"} 659
```