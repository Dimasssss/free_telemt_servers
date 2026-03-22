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

# Server Metrics 2026-03-22 01:34:35 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 16093.3 (4h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 233235
telemt_connections_bad_total 16597
telemt_connections_current 745
telemt_connections_me_current 745
telemt_handshake_timeouts_total 13500
telemt_upstream_connect_attempt_total 6672
telemt_upstream_connect_success_total 6671
telemt_upstream_connect_attempts_per_request{bucket="1"} 6671
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2440
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4217
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_me_reconnect_attempts_total 218
telemt_me_reconnect_success_total 110
telemt_me_reader_eof_total 107
telemt_me_idle_close_by_peer_total 107
telemt_me_route_drop_no_conn_total 43633
telemt_me_route_drop_channel_closed_total 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 190331
telemt_me_endpoint_quarantine_total 122
telemt_me_single_endpoint_shadow_rotate_total 136
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 2
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
telemt_me_writers_active_current 44
telemt_desync_total 1641
telemt_desync_full_logged_total 454
telemt_desync_suppressed_total 1187
telemt_desync_frames_bucket_total{bucket="1_2"} 514
telemt_desync_frames_bucket_total{bucket="3_10"} 597
telemt_desync_frames_bucket_total{bucket="gt_10"} 530
telemt_pool_swap_total 17
telemt_pool_force_close_total 444
telemt_me_writer_close_signal_drop_total 30
telemt_me_draining_writers_reap_progress_total 5977
telemt_me_writer_removed_unexpected_total 108
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 425
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 5649
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 439
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 5533
telemt_me_writer_teardown_success_total{mode="normal"} 6074
telemt_me_writer_teardown_noop_total 5978
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 11712
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 11914
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 11980
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 12026
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 12050
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 12052
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 12052
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 12052
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 12052
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 12052
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 12052
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 12052
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 12052
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 2.904192
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 12052
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 30
telemt_me_refill_failed_total 6
telemt_me_writer_restored_same_endpoint_total 100
telemt_me_writer_removed_unexpected_minus_restored_total 8
telemt_user_connections_total{user="hello"} 190029
telemt_user_connections_current{user="hello"} 745
telemt_user_octets_from_client{user="hello"} 2067385552 (1.93 GB)
telemt_user_octets_to_client{user="hello"} 64839685524 (60.39 GB)
telemt_user_unique_ips_current{user="hello"} 343
telemt_user_unique_ips_recent_window{user="hello"} 88
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 29459.6 (8h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 739245
telemt_connections_bad_total 42597
telemt_connections_current 918
telemt_connections_me_current 918
telemt_handshake_timeouts_total 27656
telemt_upstream_connect_attempt_total 13285
telemt_upstream_connect_success_total 13070
telemt_upstream_connect_fail_total 195
telemt_upstream_connect_attempts_per_request{bucket="1"} 13265
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5806
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7222
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 42
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 195
telemt_me_reconnect_attempts_total 1134
telemt_me_reconnect_success_total 413
telemt_me_reader_eof_total 365
telemt_me_idle_close_by_peer_total 365
telemt_me_route_drop_no_conn_total 335031
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 592221
telemt_me_endpoint_quarantine_total 265
telemt_me_single_endpoint_outage_enter_total 16
telemt_me_single_endpoint_outage_exit_total 16
telemt_me_single_endpoint_outage_reconnect_attempt_total 16
telemt_me_single_endpoint_outage_reconnect_success_total 16
telemt_me_single_endpoint_quarantine_bypass_total 16
telemt_me_single_endpoint_shadow_rotate_total 239
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 16
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
telemt_me_writers_active_current 91
telemt_desync_total 2595
telemt_desync_full_logged_total 1486
telemt_desync_suppressed_total 1109
telemt_desync_frames_bucket_total{bucket="1_2"} 553
telemt_desync_frames_bucket_total{bucket="3_10"} 982
telemt_desync_frames_bucket_total{bucket="gt_10"} 1060
telemt_pool_swap_total 31
telemt_pool_force_close_total 843
telemt_me_writer_close_signal_drop_total 61
telemt_me_draining_writers_reap_progress_total 11706
telemt_me_writer_removed_unexpected_total 347
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1006
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 11052
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 836
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 10863
telemt_me_writer_teardown_success_total{mode="normal"} 12058
telemt_me_writer_teardown_noop_total 11706
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 23289
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 23570
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 23658
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 23750
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 23762
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 23764
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 23764
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 23764
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 23764
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 23764
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 23764
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 23764
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 23764
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.481299
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 23764
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 61
telemt_me_refill_failed_total 38
telemt_me_writer_restored_same_endpoint_total 303
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 8
telemt_me_writer_removed_unexpected_minus_restored_total 35
telemt_user_connections_total{user="hello"} 591354
telemt_user_connections_current{user="hello"} 918
telemt_user_octets_from_client{user="hello"} 9865539512 (9.19 GB)
telemt_user_octets_to_client{user="hello"} 212419678500 (197.83 GB)
telemt_user_unique_ips_current{user="hello"} 565
telemt_user_unique_ips_recent_window{user="hello"} 114
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 104319.4 (28h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7619661
telemt_connections_bad_total 618707
telemt_connections_current 1557
telemt_connections_me_current 1557
telemt_handshake_timeouts_total 249165
telemt_upstream_connect_attempt_total 38327
telemt_upstream_connect_success_total 38254
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 38261
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17327
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20757
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 164
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 1550
telemt_me_reconnect_success_total 786
telemt_me_reader_eof_total 797
telemt_me_idle_close_by_peer_total 797
telemt_me_route_drop_no_conn_total 4520598
telemt_me_route_drop_channel_closed_total 66
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6184973
telemt_me_endpoint_quarantine_total 664
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 778
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 24
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
telemt_me_writers_active_current 44
telemt_desync_total 26203
telemt_desync_full_logged_total 8658
telemt_desync_suppressed_total 17545
telemt_desync_frames_bucket_total{bucket="1_2"} 5639
telemt_desync_frames_bucket_total{bucket="3_10"} 10219
telemt_desync_frames_bucket_total{bucket="gt_10"} 10345
telemt_pool_swap_total 112
telemt_pool_force_close_total 3760
telemt_pool_stale_pick_total 17
telemt_me_writer_close_signal_drop_total 593
telemt_me_draining_writers_reap_progress_total 34957
telemt_me_writer_removed_unexpected_total 766
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2924
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 32343
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 40
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3521
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 239
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 31197
telemt_me_writer_teardown_success_total{mode="normal"} 35267
telemt_me_writer_teardown_noop_total 35001
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 64131
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 65966
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 66954
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 68436
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 69428
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 69967
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 70257
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 70268
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 70268
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 70268
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 70268
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 70268
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 70268
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 156.943472
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 70268
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 593
telemt_me_refill_failed_total 40
telemt_me_writer_restored_same_endpoint_total 702
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 8
telemt_me_writer_removed_unexpected_minus_restored_total 59
telemt_user_connections_total{user="hello"} 6177221
telemt_user_connections_current{user="hello"} 1557
telemt_user_octets_from_client{user="hello"} 105531904072 (98.28 GB)
telemt_user_octets_to_client{user="hello"} 2046882038632 (1.86 TB)
telemt_user_unique_ips_current{user="hello"} 835
telemt_user_unique_ips_recent_window{user="hello"} 143
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 104320.9 (28h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6273337
telemt_connections_bad_total 583724
telemt_connections_current 1417
telemt_connections_me_current 1417
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 208487
telemt_upstream_connect_attempt_total 42385
telemt_upstream_connect_success_total 42000
telemt_upstream_connect_fail_total 188
telemt_upstream_connect_attempts_per_request{bucket="1"} 42188
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20910
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20502
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 33
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 555
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 188
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 116
telemt_me_reconnect_attempts_total 1904
telemt_me_reconnect_success_total 851
telemt_me_reader_eof_total 821
telemt_me_idle_close_by_peer_total 821
telemt_me_route_drop_no_conn_total 2234061
telemt_me_route_drop_channel_closed_total 257
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4701800
telemt_me_endpoint_quarantine_total 644
telemt_me_single_endpoint_outage_enter_total 7
telemt_me_single_endpoint_outage_exit_total 7
telemt_me_single_endpoint_outage_reconnect_attempt_total 7
telemt_me_single_endpoint_outage_reconnect_success_total 7
telemt_me_single_endpoint_quarantine_bypass_total 7
telemt_me_single_endpoint_shadow_rotate_total 799
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 29
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
telemt_desync_total 22358
telemt_desync_full_logged_total 7597
telemt_desync_suppressed_total 14761
telemt_desync_frames_bucket_total{bucket="1_2"} 5381
telemt_desync_frames_bucket_total{bucket="3_10"} 8675
telemt_desync_frames_bucket_total{bucket="gt_10"} 8302
telemt_pool_swap_total 113
telemt_pool_force_close_total 3393
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 355
telemt_me_draining_writers_reap_progress_total 33526
telemt_me_writer_removed_unexpected_total 806
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2842
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 31427
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 6
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3180
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 213
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 30133
telemt_me_writer_teardown_success_total{mode="normal"} 34269
telemt_me_writer_teardown_noop_total 33532
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 64515
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 66039
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 66608
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 67185
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 67596
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 67781
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 67801
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 67801
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 67801
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 67801
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 67801
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 67801
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 67801
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 48.218804
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 67801
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 355
telemt_me_refill_failed_total 56
telemt_me_writer_restored_same_endpoint_total 743
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 20
telemt_me_writer_removed_unexpected_minus_restored_total 55
telemt_user_connections_total{user="hello"} 4628654
telemt_user_connections_current{user="hello"} 1417
telemt_user_octets_from_client{user="hello"} 139458314713 (129.88 GB)
telemt_user_octets_to_client{user="hello"} 2176049470207 (1.98 TB)
telemt_user_msgs_from_client{user="hello"} 39229
telemt_user_msgs_to_client{user="hello"} 49019
telemt_user_unique_ips_current{user="hello"} 723
telemt_user_unique_ips_recent_window{user="hello"} 110
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 104284.9 (28h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6169840
telemt_connections_bad_total 545032
telemt_connections_current 1278
telemt_connections_me_current 1278
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 197549
telemt_upstream_connect_attempt_total 48647
telemt_upstream_connect_success_total 48301
telemt_upstream_connect_fail_total 136
telemt_upstream_connect_attempts_per_request{bucket="1"} 48437
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 24961
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21870
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 412
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1058
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 136
telemt_me_keepalive_timeout_total 58
telemt_me_reconnect_attempts_total 1945
telemt_me_reconnect_success_total 872
telemt_me_reader_eof_total 816
telemt_me_idle_close_by_peer_total 816
telemt_me_route_drop_no_conn_total 2130752
telemt_me_route_drop_channel_closed_total 117
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4598380
telemt_me_endpoint_quarantine_total 723
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 9
telemt_me_single_endpoint_outage_reconnect_success_total 6
telemt_me_single_endpoint_quarantine_bypass_total 9
telemt_me_single_endpoint_shadow_rotate_total 780
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 38
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
telemt_desync_total 22180
telemt_desync_full_logged_total 7431
telemt_desync_suppressed_total 14749
telemt_desync_frames_bucket_total{bucket="1_2"} 5421
telemt_desync_frames_bucket_total{bucket="3_10"} 8494
telemt_desync_frames_bucket_total{bucket="gt_10"} 8265
telemt_pool_swap_total 112
telemt_pool_force_close_total 3270
telemt_pool_stale_pick_total 1618
telemt_me_writer_close_signal_drop_total 379
telemt_me_draining_writers_reap_progress_total 34864
telemt_me_writer_removed_unexpected_total 789
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2894
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 32772
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 11
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3055
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 215
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 31594
telemt_me_writer_teardown_success_total{mode="normal"} 35666
telemt_me_writer_teardown_noop_total 34875
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 68032
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 69394
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 69833
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 70291
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 70498
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 70523
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 70541
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 70541
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 70541
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 70541
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 70541
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 70541
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 70541
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 25.712783
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 70541
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 379
telemt_me_refill_failed_total 59
telemt_me_writer_restored_same_endpoint_total 756
telemt_me_writer_restored_fallback_total 5
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 42
telemt_me_writer_removed_unexpected_minus_restored_total 28
telemt_user_connections_total{user="hello"} 4596646
telemt_user_connections_current{user="hello"} 1278
telemt_user_octets_from_client{user="hello"} 132867352251 (123.74 GB)
telemt_user_octets_to_client{user="hello"} 2099091538719 (1.91 TB)
telemt_user_msgs_from_client{user="hello"} 44246
telemt_user_msgs_to_client{user="hello"} 113178
telemt_user_unique_ips_current{user="hello"} 657
telemt_user_unique_ips_recent_window{user="hello"} 129
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 104324.3 (28h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 20234390
telemt_connections_bad_total 1560924
telemt_connections_current 1983
telemt_connections_me_current 1983
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 593801
telemt_upstream_connect_attempt_total 193742
telemt_upstream_connect_success_total 175830
telemt_upstream_connect_fail_total 16216
telemt_upstream_connect_attempts_per_request{bucket="1"} 192046
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 124168
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 41532
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1221
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8909
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 16216
telemt_me_keepalive_timeout_total 398
telemt_me_reconnect_attempts_total 64762
telemt_me_reconnect_success_total 2267
telemt_me_reader_eof_total 1403
telemt_me_idle_close_by_peer_total 1402
telemt_me_route_drop_no_conn_total 39485435
telemt_me_route_drop_channel_closed_total 124
telemt_me_route_drop_queue_full_total 12
telemt_me_route_drop_queue_full_profile_total{profile="high"} 12
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 16402826
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 5
telemt_me_endpoint_quarantine_total 809
telemt_me_single_endpoint_outage_enter_total 133
telemt_me_single_endpoint_outage_exit_total 133
telemt_me_single_endpoint_outage_reconnect_attempt_total 283
telemt_me_single_endpoint_outage_reconnect_success_total 68
telemt_me_single_endpoint_quarantine_bypass_total 283
telemt_me_single_endpoint_shadow_rotate_total 817
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 61
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
telemt_me_writers_active_current 46
telemt_desync_total 31771
telemt_desync_full_logged_total 9492
telemt_desync_suppressed_total 22279
telemt_desync_frames_bucket_total{bucket="1_2"} 6891
telemt_desync_frames_bucket_total{bucket="3_10"} 14099
telemt_desync_frames_bucket_total{bucket="gt_10"} 10781
telemt_pool_swap_total 107
telemt_pool_force_close_total 3522
telemt_pool_stale_pick_total 29
telemt_me_writer_close_signal_drop_total 787
telemt_me_draining_writers_reap_progress_total 32476
telemt_me_writer_removed_unexpected_total 2106
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4417
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 29901
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 23
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2999
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 523
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 28954
telemt_me_writer_teardown_success_total{mode="normal"} 34318
telemt_me_writer_teardown_noop_total 32502
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 60098
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 62537
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 63809
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 65446
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 66384
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 66719
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 66801
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 66803
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 66806
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 66811
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 66811
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 66815
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 66820
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 213.695937
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 66820
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 787
telemt_me_refill_failed_total 3799
telemt_me_writer_restored_same_endpoint_total 1551
telemt_me_writer_restored_fallback_total 21
telemt_me_no_writer_failfast_total 666
telemt_me_async_recovery_trigger_total 14678
telemt_me_writer_removed_unexpected_minus_restored_total 534
telemt_user_connections_total{user="hello"} 16532433
telemt_user_connections_current{user="hello"} 1983
telemt_user_octets_from_client{user="hello"} 204813974218 (190.75 GB)
telemt_user_octets_to_client{user="hello"} 1166354154031 (1.06 TB)
telemt_user_msgs_from_client{user="hello"} 373576
telemt_user_msgs_to_client{user="hello"} 663916
telemt_user_unique_ips_current{user="hello"} 972
telemt_user_unique_ips_recent_window{user="hello"} 191
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 104292.0 (28h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5936491
telemt_connections_bad_total 557181
telemt_connections_current 1378
telemt_connections_me_current 1378
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 123688
telemt_upstream_connect_attempt_total 56996
telemt_upstream_connect_success_total 56328
telemt_upstream_connect_fail_total 571
telemt_upstream_connect_attempts_per_request{bucket="1"} 56899
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 33146
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22836
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 345
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 571
telemt_me_reconnect_attempts_total 69549
telemt_me_reconnect_success_total 1754
telemt_me_reader_eof_total 1525
telemt_me_idle_close_by_peer_total 1524
telemt_me_route_drop_no_conn_total 2376488
telemt_me_route_drop_channel_closed_total 10
telemt_me_route_drop_queue_full_total 39
telemt_me_route_drop_queue_full_profile_total{profile="high"} 39
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4631967
telemt_me_endpoint_quarantine_total 703
telemt_me_single_endpoint_outage_enter_total 23
telemt_me_single_endpoint_outage_exit_total 23
telemt_me_single_endpoint_outage_reconnect_attempt_total 24
telemt_me_single_endpoint_outage_reconnect_success_total 23
telemt_me_single_endpoint_quarantine_bypass_total 24
telemt_me_single_endpoint_shadow_rotate_total 786
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 33
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
telemt_me_writers_active_current 46
telemt_desync_total 23214
telemt_desync_full_logged_total 8156
telemt_desync_suppressed_total 15058
telemt_desync_frames_bucket_total{bucket="1_2"} 4407
telemt_desync_frames_bucket_total{bucket="3_10"} 8986
telemt_desync_frames_bucket_total{bucket="gt_10"} 9821
telemt_pool_swap_total 107
telemt_pool_force_close_total 3112
telemt_pool_stale_pick_total 54
telemt_me_writer_close_signal_drop_total 388
telemt_me_draining_writers_reap_progress_total 36398
telemt_me_writer_removed_unexpected_total 1568
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3788
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 34204
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2711
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 401
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 33286
telemt_me_writer_teardown_success_total{mode="normal"} 37992
telemt_me_writer_teardown_noop_total 36399
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 73139
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 73960
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 74239
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 74359
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 74388
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 74391
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 74391
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 74391
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 74391
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 74391
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 74391
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 74391
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 74391
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 8.089222
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 74391
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 388
telemt_me_refill_failed_total 4202
telemt_me_writer_restored_same_endpoint_total 1468
telemt_me_writer_restored_fallback_total 32
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7305
telemt_me_writer_removed_unexpected_minus_restored_total 68
telemt_user_connections_total{user="hello"} 4624963
telemt_user_connections_current{user="hello"} 1378
telemt_user_octets_from_client{user="hello"} 123189743208 (114.73 GB)
telemt_user_octets_to_client{user="hello"} 1891533326470 (1.72 TB)
telemt_user_msgs_from_client{user="hello"} 77823
telemt_user_msgs_to_client{user="hello"} 338392
telemt_user_unique_ips_current{user="hello"} 705
telemt_user_unique_ips_recent_window{user="hello"} 124
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 41127.8 (11h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3827615
telemt_connections_bad_total 138538
telemt_connections_current 1124
telemt_connections_me_current 1124
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 1573038
telemt_upstream_connect_attempt_total 25368
telemt_upstream_connect_success_total 25200
telemt_upstream_connect_fail_total 160
telemt_upstream_connect_attempts_per_request{bucket="1"} 25360
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16274
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8856
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 70
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 160
telemt_me_reconnect_attempts_total 45772
telemt_me_reconnect_success_total 936
telemt_me_reader_eof_total 613
telemt_me_idle_close_by_peer_total 613
telemt_me_route_drop_no_conn_total 1011139
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1867314
telemt_me_endpoint_quarantine_total 305
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 50
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 50
telemt_me_single_endpoint_shadow_rotate_total 313
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 9
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
telemt_me_writers_active_current 46
telemt_me_floor_cap_block_total 23
telemt_me_floor_swap_idle_failed_total 23
telemt_desync_total 10211
telemt_desync_full_logged_total 3525
telemt_desync_suppressed_total 6686
telemt_desync_frames_bucket_total{bucket="1_2"} 1827
telemt_desync_frames_bucket_total{bucket="3_10"} 3906
telemt_desync_frames_bucket_total{bucket="gt_10"} 4478
telemt_pool_swap_total 44
telemt_pool_force_close_total 1390
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 129
telemt_me_draining_writers_reap_progress_total 14576
telemt_me_writer_removed_unexpected_total 691
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1431
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 13858
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1184
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 206
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 13186
telemt_me_writer_teardown_success_total{mode="normal"} 15289
telemt_me_writer_teardown_noop_total 14578
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 29372
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 29646
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 29761
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 29867
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 29867
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 29867
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 29867
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 29867
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 29867
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 29867
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 29867
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 29867
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 29867
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.315548
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 29867
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 129
telemt_me_refill_failed_total 2605
telemt_me_writer_restored_same_endpoint_total 837
telemt_me_writer_restored_fallback_total 12
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4264
telemt_user_connections_total{user="hello"} 1871004
telemt_user_connections_current{user="hello"} 1124
telemt_user_octets_from_client{user="hello"} 53461901296 (49.79 GB)
telemt_user_octets_to_client{user="hello"} 798731091614 (743.88 GB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 631
telemt_user_unique_ips_recent_window{user="hello"} 121
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 22098.6 (6h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 181033
telemt_connections_bad_total 1542
telemt_connections_current 275
telemt_connections_me_current 275
telemt_handshake_timeouts_total 4973
telemt_upstream_connect_attempt_total 10546
telemt_upstream_connect_success_total 10522
telemt_upstream_connect_fail_total 22
telemt_upstream_connect_attempts_per_request{bucket="1"} 10544
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4477
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5971
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 74
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 22
telemt_me_reconnect_attempts_total 227
telemt_me_reconnect_success_total 141
telemt_me_reader_eof_total 144
telemt_me_idle_close_by_peer_total 144
telemt_me_route_drop_no_conn_total 49750
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 159267
telemt_me_endpoint_quarantine_total 218
telemt_me_single_endpoint_shadow_rotate_total 195
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 3
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
telemt_desync_total 998
telemt_desync_full_logged_total 251
telemt_desync_suppressed_total 747
telemt_desync_frames_bucket_total{bucket="1_2"} 388
telemt_desync_frames_bucket_total{bucket="3_10"} 366
telemt_desync_frames_bucket_total{bucket="gt_10"} 244
telemt_pool_swap_total 24
telemt_pool_force_close_total 537
telemt_me_writer_close_signal_drop_total 21
telemt_me_draining_writers_reap_progress_total 9490
telemt_me_writer_removed_unexpected_total 139
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 633
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 9001
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 535
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 8953
telemt_me_writer_teardown_success_total{mode="normal"} 9634
telemt_me_writer_teardown_noop_total 9490
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 18944
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 19096
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 19114
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 19124
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 19124
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 19124
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 19124
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 19124
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 19124
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 19124
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 19124
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 19124
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 19124
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.914795
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 19124
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 21
telemt_me_refill_failed_total 5
telemt_me_writer_restored_same_endpoint_total 130
telemt_me_writer_removed_unexpected_minus_restored_total 9
telemt_user_connections_total{user="hello"} 158973
telemt_user_connections_current{user="hello"} 275
telemt_user_octets_from_client{user="hello"} 2912326628 (2.71 GB)
telemt_user_octets_to_client{user="hello"} 92287940888 (85.95 GB)
telemt_user_unique_ips_current{user="hello"} 141
telemt_user_unique_ips_recent_window{user="hello"} 26
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 104296.1 (28h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7198251
telemt_connections_bad_total 733717
telemt_connections_current 1698
telemt_connections_me_current 1698
telemt_handshake_timeouts_total 205246
telemt_upstream_connect_attempt_total 40500
telemt_upstream_connect_success_total 40346
telemt_upstream_connect_fail_total 117
telemt_upstream_connect_attempts_per_request{bucket="1"} 40463
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19995
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20310
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 40
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 117
telemt_me_reconnect_attempts_total 1541
telemt_me_reconnect_success_total 824
telemt_me_reader_eof_total 806
telemt_me_idle_close_by_peer_total 806
telemt_me_route_drop_no_conn_total 2113658
telemt_me_route_drop_channel_closed_total 52
telemt_me_route_drop_queue_full_total 23
telemt_me_route_drop_queue_full_profile_total{profile="high"} 23
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5410527
telemt_me_endpoint_quarantine_total 723
telemt_me_single_endpoint_outage_enter_total 8
telemt_me_single_endpoint_outage_exit_total 8
telemt_me_single_endpoint_outage_reconnect_attempt_total 8
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 8
telemt_me_single_endpoint_shadow_rotate_total 800
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
telemt_me_writers_active_current 45
telemt_desync_total 21267
telemt_desync_full_logged_total 6982
telemt_desync_suppressed_total 14285
telemt_desync_frames_bucket_total{bucket="1_2"} 5327
telemt_desync_frames_bucket_total{bucket="3_10"} 7701
telemt_desync_frames_bucket_total{bucket="gt_10"} 8239
telemt_pool_swap_total 115
telemt_pool_force_close_total 3109
telemt_pool_stale_pick_total 3
telemt_me_writer_close_signal_drop_total 378
telemt_me_draining_writers_reap_progress_total 36483
telemt_me_writer_removed_unexpected_total 777
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2897
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 34382
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3021
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 88
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 33374
telemt_me_writer_teardown_success_total{mode="normal"} 37279
telemt_me_writer_teardown_noop_total 36485
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 72413
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 73298
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 73476
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 73676
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 73764
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 73764
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 73764
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 73764
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 73764
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 73764
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 73764
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 73764
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 73764
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 10.603241
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 73764
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 378
telemt_me_refill_failed_total 37
telemt_me_writer_restored_same_endpoint_total 734
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 35
telemt_user_connections_total{user="hello"} 5385608
telemt_user_connections_current{user="hello"} 1698
telemt_user_octets_from_client{user="hello"} 108535284648 (101.08 GB)
telemt_user_octets_to_client{user="hello"} 2516551891856 (2.29 TB)
telemt_user_unique_ips_current{user="hello"} 752
telemt_user_unique_ips_recent_window{user="hello"} 159
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 104293.1 (28h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6205446
telemt_connections_bad_total 611782
telemt_connections_current 1452
telemt_connections_me_current 1452
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 170360
telemt_upstream_connect_attempt_total 56310
telemt_upstream_connect_success_total 55889
telemt_upstream_connect_fail_total 362
telemt_upstream_connect_attempts_per_request{bucket="1"} 56251
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 32779
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21977
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 518
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 615
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 362
telemt_me_reconnect_attempts_total 5502
telemt_me_reconnect_success_total 1138
telemt_me_reader_eof_total 1020
telemt_me_idle_close_by_peer_total 1020
telemt_me_seq_mismatch_total 45
telemt_me_route_drop_no_conn_total 2167237
telemt_me_route_drop_channel_closed_total 189
telemt_me_route_drop_queue_full_total 11
telemt_me_route_drop_queue_full_profile_total{profile="high"} 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4778090
telemt_me_endpoint_quarantine_total 831
telemt_me_single_endpoint_outage_enter_total 28
telemt_me_single_endpoint_outage_exit_total 28
telemt_me_single_endpoint_outage_reconnect_attempt_total 28
telemt_me_single_endpoint_outage_reconnect_success_total 26
telemt_me_single_endpoint_quarantine_bypass_total 28
telemt_me_single_endpoint_shadow_rotate_total 795
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 33
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
telemt_me_writers_active_current 44
telemt_desync_total 19863
telemt_desync_full_logged_total 6615
telemt_desync_suppressed_total 13248
telemt_desync_frames_bucket_total{bucket="1_2"} 5044
telemt_desync_frames_bucket_total{bucket="3_10"} 7232
telemt_desync_frames_bucket_total{bucket="gt_10"} 7587
telemt_pool_swap_total 113
telemt_pool_force_close_total 3063
telemt_pool_stale_pick_total 358
telemt_me_writer_close_signal_drop_total 374
telemt_me_draining_writers_reap_progress_total 35076
telemt_me_writer_removed_unexpected_total 1032
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3406
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 32750
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2840
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 223
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 32013
telemt_me_writer_teardown_success_total{mode="normal"} 36156
telemt_me_writer_teardown_noop_total 35080
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 69609
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 70658
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 71003
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 71198
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 71236
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 71236
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 71236
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 71236
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 71236
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 71236
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 71236
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 71236
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 71236
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 10.986639
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 71236
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 374
telemt_me_refill_failed_total 252
telemt_me_writer_restored_same_endpoint_total 886
telemt_me_writer_restored_fallback_total 58
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 76
telemt_me_writer_removed_unexpected_minus_restored_total 88
telemt_user_connections_total{user="hello"} 4781221
telemt_user_connections_current{user="hello"} 1452
telemt_user_octets_from_client{user="hello"} 89943599121 (83.77 GB)
telemt_user_octets_to_client{user="hello"} 2046358203880 (1.86 TB)
telemt_user_msgs_from_client{user="hello"} 75721
telemt_user_msgs_to_client{user="hello"} 209236
telemt_user_unique_ips_current{user="hello"} 672
telemt_user_unique_ips_recent_window{user="hello"} 132
```