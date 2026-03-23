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

# Server Metrics 2026-03-23 01:05:52 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 100768.8 (27h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3510569
telemt_connections_bad_total 308812
telemt_connections_current 863
telemt_connections_me_current 863
telemt_handshake_timeouts_total 109356
telemt_upstream_connect_attempt_total 37383
telemt_upstream_connect_success_total 37382
telemt_upstream_connect_attempts_per_request{bucket="1"} 37382
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12978
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 24272
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 92
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 40
telemt_me_keepalive_failed_total 4
telemt_me_keepalive_timeout_total 451
telemt_me_reconnect_attempts_total 1394
telemt_me_reconnect_success_total 600
telemt_me_reader_eof_total 616
telemt_me_idle_close_by_peer_total 616
telemt_me_route_drop_no_conn_total 2983439
telemt_me_route_drop_channel_closed_total 1233
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2899928
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_endpoint_quarantine_total 705
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 784
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 28
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
telemt_desync_total 12435
telemt_desync_full_logged_total 3899
telemt_desync_suppressed_total 8536
telemt_desync_frames_bucket_total{bucket="1_2"} 3356
telemt_desync_frames_bucket_total{bucket="3_10"} 4524
telemt_desync_frames_bucket_total{bucket="gt_10"} 4555
telemt_pool_swap_total 111
telemt_pool_force_close_total 3430
telemt_pool_stale_pick_total 29
telemt_me_writer_close_signal_drop_total 654
telemt_me_draining_writers_reap_progress_total 34225
telemt_me_writer_removed_unexpected_total 594
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2468
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 31999
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 11
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3374
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 56
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 30795
telemt_me_writer_teardown_success_total{mode="normal"} 34467
telemt_me_writer_teardown_noop_total 34236
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 55193
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 57506
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 59631
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 63574
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 66530
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 68215
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 68698
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 68703
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 68703
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 68703
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 68703
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 68703
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 68703
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 376.267414
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 68703
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 654
telemt_me_refill_failed_total 42
telemt_me_writer_restored_same_endpoint_total 537
telemt_me_writer_restored_fallback_total 1
telemt_me_writer_removed_unexpected_minus_restored_total 56
telemt_user_connections_total{user="hello"} 2889030
telemt_user_connections_current{user="hello"} 863
telemt_user_octets_from_client{user="hello"} 41249179468 (38.42 GB)
telemt_user_octets_to_client{user="hello"} 791171437488 (736.84 GB)
telemt_user_unique_ips_current{user="hello"} 427
telemt_user_unique_ips_recent_window{user="hello"} 145
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 114134.9 (31h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3999102
telemt_connections_bad_total 367801
telemt_connections_current 329
telemt_connections_me_current 329
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 4
telemt_handshake_timeouts_total 100702
telemt_upstream_connect_attempt_total 71327
telemt_upstream_connect_success_total 70483
telemt_upstream_connect_fail_total 751
telemt_upstream_connect_attempts_per_request{bucket="1"} 71234
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 39385
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 30887
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 211
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 751
telemt_me_keepalive_timeout_total 7
telemt_me_reconnect_attempts_total 10001
telemt_me_reconnect_success_total 3606
telemt_me_reader_eof_total 3603
telemt_me_idle_close_by_peer_total 3603
telemt_me_route_drop_no_conn_total 3640826
telemt_me_route_drop_channel_closed_total 37
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3177693
telemt_me_endpoint_quarantine_total 902
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_outage_enter_total 44
telemt_me_single_endpoint_outage_exit_total 44
telemt_me_single_endpoint_outage_reconnect_attempt_total 44
telemt_me_single_endpoint_outage_reconnect_success_total 43
telemt_me_single_endpoint_quarantine_bypass_total 44
telemt_me_single_endpoint_shadow_rotate_total 889
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
telemt_me_writers_active_current 46
telemt_desync_total 12956
telemt_desync_full_logged_total 7264
telemt_desync_suppressed_total 5692
telemt_desync_frames_bucket_total{bucket="1_2"} 2940
telemt_desync_frames_bucket_total{bucket="3_10"} 5078
telemt_desync_frames_bucket_total{bucket="gt_10"} 4938
telemt_pool_swap_total 106
telemt_pool_force_close_total 3052
telemt_pool_stale_pick_total 6
telemt_me_writer_close_signal_drop_total 252
telemt_me_draining_writers_reap_progress_total 46928
telemt_me_writer_removed_unexpected_total 3533
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6188
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 44306
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2594
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 458
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 43876
telemt_me_writer_teardown_success_total{mode="normal"} 50494
telemt_me_writer_teardown_noop_total 46929
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 95461
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 96703
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 97037
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 97345
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 97408
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 97421
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 97423
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 97423
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 97423
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 97423
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 97423
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 97423
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 97423
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 14.611839
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 97423
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 252
telemt_me_refill_failed_total 246
telemt_me_writer_restored_same_endpoint_total 3224
telemt_me_writer_restored_fallback_total 29
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 280
telemt_user_connections_total{user="hello"} 3190996
telemt_user_connections_current{user="hello"} 329
telemt_user_octets_from_client{user="hello"} 43065859967 (40.11 GB)
telemt_user_octets_to_client{user="hello"} 791197788004 (736.86 GB)
telemt_user_msgs_from_client{user="hello"} 49657
telemt_user_msgs_to_client{user="hello"} 185005
telemt_user_unique_ips_current{user="hello"} 221
telemt_user_unique_ips_recent_window{user="hello"} 59
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 188994.8 (52h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 16327667
telemt_connections_bad_total 1644712
telemt_connections_current 995
telemt_connections_me_current 995
telemt_relay_adaptive_promotions_total 19
telemt_relay_adaptive_hard_promotions_total 19
telemt_handshake_timeouts_total 397333
telemt_upstream_connect_attempt_total 84613
telemt_upstream_connect_success_total 84508
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 84525
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 41455
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 41329
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1717
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 2994
telemt_me_reconnect_success_total 1571
telemt_me_reader_eof_total 1519
telemt_me_idle_close_by_peer_total 1517
telemt_me_route_drop_no_conn_total 14045050
telemt_me_route_drop_channel_closed_total 145
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 12971172
telemt_me_endpoint_quarantine_total 1244
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 11
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 11
telemt_me_single_endpoint_shadow_rotate_total 1420
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 45
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 35
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 44
telemt_desync_total 53803
telemt_desync_full_logged_total 17085
telemt_desync_suppressed_total 36718
telemt_desync_frames_bucket_total{bucket="1_2"} 11997
telemt_desync_frames_bucket_total{bucket="3_10"} 20990
telemt_desync_frames_bucket_total{bucket="gt_10"} 20816
telemt_pool_swap_total 204
telemt_pool_force_close_total 6701
telemt_pool_stale_pick_total 19
telemt_me_writer_close_signal_drop_total 1060
telemt_me_draining_writers_reap_progress_total 64061
telemt_me_writer_removed_unexpected_total 1462
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5470
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 59329
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 45
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 8
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 6231
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 470
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 57360
telemt_me_writer_teardown_success_total{mode="normal"} 64799
telemt_me_writer_teardown_noop_total 64114
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 117778
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 121419
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 123193
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 125585
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 127252
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 128303
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 128874
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 128904
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 128905
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 128909
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 128911
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 128913
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 128913
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 317.697744
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 128913
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 1060
telemt_me_refill_failed_total 78
telemt_me_writer_restored_same_endpoint_total 1359
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 22
telemt_me_writer_removed_unexpected_minus_restored_total 95
telemt_user_connections_total{user="hello"} 12971206
telemt_user_connections_current{user="hello"} 995
telemt_user_octets_from_client{user="hello"} 191105565265 (177.98 GB)
telemt_user_octets_to_client{user="hello"} 3488544561879 (3.17 TB)
telemt_user_msgs_from_client{user="hello"} 57811
telemt_user_msgs_to_client{user="hello"} 118217
telemt_user_unique_ips_current{user="hello"} 515
telemt_user_unique_ips_recent_window{user="hello"} 97
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 188996.0 (52h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11875502
telemt_connections_bad_total 1234056
telemt_connections_current 618
telemt_connections_me_current 618
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 344563
telemt_upstream_connect_attempt_total 99006
telemt_upstream_connect_success_total 97682
telemt_upstream_connect_fail_total 871
telemt_upstream_connect_attempts_per_request{bucket="1"} 98553
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 52456
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 41237
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 188
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3801
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 871
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 225
telemt_me_reconnect_attempts_total 4432
telemt_me_reconnect_success_total 1882
telemt_me_reader_eof_total 1749
telemt_me_idle_close_by_peer_total 1749
telemt_me_route_drop_no_conn_total 4555282
telemt_me_route_drop_channel_closed_total 498
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8816082
telemt_me_endpoint_quarantine_total 1255
telemt_me_single_endpoint_outage_enter_total 29
telemt_me_single_endpoint_outage_exit_total 29
telemt_me_single_endpoint_outage_reconnect_attempt_total 35
telemt_me_single_endpoint_outage_reconnect_success_total 27
telemt_me_single_endpoint_quarantine_bypass_total 35
telemt_me_single_endpoint_shadow_rotate_total 1440
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
telemt_me_writers_active_current 46
telemt_desync_total 38777
telemt_desync_full_logged_total 13060
telemt_desync_suppressed_total 25717
telemt_desync_frames_bucket_total{bucket="1_2"} 9605
telemt_desync_frames_bucket_total{bucket="3_10"} 14896
telemt_desync_frames_bucket_total{bucket="gt_10"} 14276
telemt_pool_swap_total 201
telemt_pool_force_close_total 6059
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 709
telemt_me_draining_writers_reap_progress_total 62293
telemt_me_writer_removed_unexpected_total 1779
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5563
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 58365
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 25
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5547
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 512
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 56234
telemt_me_writer_teardown_success_total{mode="normal"} 63928
telemt_me_writer_teardown_noop_total 62318
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 119499
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 122722
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 123871
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 125062
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 125821
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 126161
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 126236
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 126238
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 126244
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 126246
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 126246
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 126246
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 126246
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 104.421440
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 126246
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 709
telemt_me_refill_failed_total 137
telemt_me_writer_restored_same_endpoint_total 1610
telemt_me_writer_restored_fallback_total 20
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 216
telemt_me_writer_removed_unexpected_minus_restored_total 149
telemt_user_connections_total{user="hello"} 8753843
telemt_user_connections_current{user="hello"} 618
telemt_user_octets_from_client{user="hello"} 217774383440 (202.82 GB)
telemt_user_octets_to_client{user="hello"} 3962727416647 (3.60 TB)
telemt_user_msgs_from_client{user="hello"} 124042
telemt_user_msgs_to_client{user="hello"} 140191
telemt_user_unique_ips_current{user="hello"} 294
telemt_user_unique_ips_recent_window{user="hello"} 51
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 188959.9 (52h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11055039
telemt_connections_bad_total 975007
telemt_connections_current 463
telemt_connections_me_current 463
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 345572
telemt_upstream_connect_attempt_total 83263
telemt_upstream_connect_success_total 81704
telemt_upstream_connect_fail_total 205
telemt_upstream_connect_attempts_per_request{bucket="1"} 81909
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 37665
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 39649
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2028
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2362
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 205
telemt_me_keepalive_failed_total 4
telemt_me_keepalive_timeout_total 1420
telemt_me_reconnect_attempts_total 5743
telemt_me_reconnect_success_total 2367
telemt_me_reader_eof_total 2112
telemt_me_idle_close_by_peer_total 2111
telemt_me_route_drop_no_conn_total 5337216
telemt_me_route_drop_channel_closed_total 383
telemt_me_route_drop_queue_full_total 9
telemt_me_route_drop_queue_full_profile_total{profile="high"} 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8356152
telemt_me_endpoint_quarantine_total 1324
telemt_me_single_endpoint_outage_enter_total 37
telemt_me_single_endpoint_outage_exit_total 37
telemt_me_single_endpoint_outage_reconnect_attempt_total 38
telemt_me_single_endpoint_outage_reconnect_success_total 32
telemt_me_single_endpoint_quarantine_bypass_total 38
telemt_me_single_endpoint_shadow_rotate_total 1397
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 69
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 35
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 43
telemt_desync_total 38156
telemt_desync_full_logged_total 12636
telemt_desync_suppressed_total 25520
telemt_desync_frames_bucket_total{bucket="1_2"} 9636
telemt_desync_frames_bucket_total{bucket="3_10"} 14599
telemt_desync_frames_bucket_total{bucket="gt_10"} 13921
telemt_pool_swap_total 197
telemt_pool_force_close_total 5961
telemt_pool_stale_pick_total 1619
telemt_me_writer_close_signal_drop_total 739
telemt_me_draining_writers_reap_progress_total 62659
telemt_me_writer_removed_unexpected_total 2262
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6310
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 58543
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 25
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 46
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5390
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 571
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 56698
telemt_me_writer_teardown_success_total{mode="normal"} 64853
telemt_me_writer_teardown_noop_total 62730
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 121750
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 124465
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 125428
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 126501
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 127102
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 127316
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 127444
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 127475
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 127483
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 127496
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 127529
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 127532
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 127583
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3174.783323
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 127583
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 739
telemt_me_refill_failed_total 179
telemt_me_writer_restored_same_endpoint_total 2057
telemt_me_writer_restored_fallback_total 17
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 68
telemt_me_writer_removed_unexpected_minus_restored_total 188
telemt_user_connections_total{user="hello"} 8348115
telemt_user_connections_current{user="hello"} 463
telemt_user_octets_from_client{user="hello"} 192746027307 (179.51 GB)
telemt_user_octets_to_client{user="hello"} 3470120460049 (3.16 TB)
telemt_user_msgs_from_client{user="hello"} 46587
telemt_user_msgs_to_client{user="hello"} 113900
telemt_user_unique_ips_current{user="hello"} 219
telemt_user_unique_ips_recent_window{user="hello"} 59
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 59239.7 (16h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11240117
telemt_connections_bad_total 668664
telemt_connections_current 928
telemt_connections_me_current 928
telemt_relay_adaptive_promotions_total 8
telemt_relay_adaptive_hard_promotions_total 8
telemt_handshake_timeouts_total 271785
telemt_upstream_connect_attempt_total 57793
telemt_upstream_connect_success_total 54747
telemt_upstream_connect_fail_total 2025
telemt_upstream_connect_attempts_per_request{bucket="1"} 56772
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 28349
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18865
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1517
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6016
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2025
telemt_me_keepalive_timeout_total 975
telemt_me_reconnect_attempts_total 7715
telemt_me_reconnect_success_total 1240
telemt_me_reader_eof_total 769
telemt_me_idle_close_by_peer_total 768
telemt_me_route_drop_no_conn_total 25289665
telemt_me_route_drop_channel_closed_total 59
telemt_me_route_drop_queue_full_total 27
telemt_me_route_drop_queue_full_profile_total{profile="high"} 27
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9328325
telemt_me_endpoint_quarantine_total 445
telemt_me_single_endpoint_outage_enter_total 94
telemt_me_single_endpoint_outage_exit_total 94
telemt_me_single_endpoint_outage_reconnect_attempt_total 179
telemt_me_single_endpoint_outage_reconnect_success_total 47
telemt_me_single_endpoint_quarantine_bypass_total 179
telemt_me_single_endpoint_shadow_rotate_total 476
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 36
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
telemt_desync_total 16328
telemt_desync_full_logged_total 4452
telemt_desync_suppressed_total 11876
telemt_desync_frames_bucket_total{bucket="1_2"} 3090
telemt_desync_frames_bucket_total{bucket="3_10"} 6650
telemt_desync_frames_bucket_total{bucket="gt_10"} 6588
telemt_pool_swap_total 61
telemt_pool_force_close_total 1999
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 484
telemt_me_draining_writers_reap_progress_total 18474
telemt_me_writer_removed_unexpected_total 1126
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2514
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 17029
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 9
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 10
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1692
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 307
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 16475
telemt_me_writer_teardown_success_total{mode="normal"} 19543
telemt_me_writer_teardown_noop_total 18493
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 34123
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 35892
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 36615
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 37491
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 37857
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 37980
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 38036
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 38036
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 38036
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 38036
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 38036
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 38036
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 38036
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 53.736894
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 38036
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 484
telemt_me_refill_failed_total 337
telemt_me_writer_restored_same_endpoint_total 793
telemt_me_writer_restored_fallback_total 11
telemt_me_no_writer_failfast_total 96
telemt_me_async_recovery_trigger_total 3149
telemt_me_writer_removed_unexpected_minus_restored_total 322
telemt_user_connections_total{user="hello"} 9354205
telemt_user_connections_current{user="hello"} 928
telemt_user_octets_from_client{user="hello"} 87238893558 (81.25 GB)
telemt_user_octets_to_client{user="hello"} 606786934070 (565.11 GB)
telemt_user_msgs_from_client{user="hello"} 68321
telemt_user_msgs_to_client{user="hello"} 57932
telemt_user_unique_ips_current{user="hello"} 413
telemt_user_unique_ips_recent_window{user="hello"} 105
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 188966.5 (52h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10991050
telemt_connections_bad_total 946892
telemt_connections_current 738
telemt_connections_me_current 738
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 242081
telemt_upstream_connect_attempt_total 112183
telemt_upstream_connect_success_total 111027
telemt_upstream_connect_fail_total 983
telemt_upstream_connect_attempts_per_request{bucket="1"} 112010
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 66197
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 43231
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 238
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1361
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 983
telemt_me_keepalive_timeout_total 23
telemt_me_reconnect_attempts_total 72881
telemt_me_reconnect_success_total 3076
telemt_me_reader_eof_total 2762
telemt_me_idle_close_by_peer_total 2760
telemt_me_route_drop_no_conn_total 5262228
telemt_me_route_drop_channel_closed_total 23
telemt_me_route_drop_queue_full_total 46
telemt_me_route_drop_queue_full_profile_total{profile="high"} 46
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8674452
telemt_me_endpoint_quarantine_total 1272
telemt_me_single_endpoint_outage_enter_total 43
telemt_me_single_endpoint_outage_exit_total 43
telemt_me_single_endpoint_outage_reconnect_attempt_total 45
telemt_me_single_endpoint_outage_reconnect_success_total 43
telemt_me_single_endpoint_quarantine_bypass_total 45
telemt_me_single_endpoint_shadow_rotate_total 1426
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 54
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
telemt_desync_total 46227
telemt_desync_full_logged_total 15828
telemt_desync_suppressed_total 30399
telemt_desync_frames_bucket_total{bucket="1_2"} 9393
telemt_desync_frames_bucket_total{bucket="3_10"} 17698
telemt_desync_frames_bucket_total{bucket="gt_10"} 19136
telemt_pool_swap_total 193
telemt_pool_force_close_total 5665
telemt_pool_stale_pick_total 69
telemt_me_writer_close_signal_drop_total 663
telemt_me_draining_writers_reap_progress_total 66831
telemt_me_writer_removed_unexpected_total 2791
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6831
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 62826
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4916
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 749
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 61166
telemt_me_writer_teardown_success_total{mode="normal"} 69657
telemt_me_writer_teardown_noop_total 66832
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 134340
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 135753
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 136172
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 136445
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 136479
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 136482
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 136482
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 136485
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 136489
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 136489
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 136489
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 136489
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 136489
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 17.265091
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 136489
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 663
telemt_me_refill_failed_total 4297
telemt_me_writer_restored_same_endpoint_total 2594
telemt_me_writer_restored_fallback_total 52
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7367
telemt_me_writer_removed_unexpected_minus_restored_total 145
telemt_user_connections_total{user="hello"} 8677450
telemt_user_connections_current{user="hello"} 738
telemt_user_octets_from_client{user="hello"} 194586852545 (181.22 GB)
telemt_user_octets_to_client{user="hello"} 3316071100812 (3.02 TB)
telemt_user_msgs_from_client{user="hello"} 160634
telemt_user_msgs_to_client{user="hello"} 619200
telemt_user_unique_ips_current{user="hello"} 333
telemt_user_unique_ips_recent_window{user="hello"} 80
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 125802.7 (34h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11695914
telemt_connections_bad_total 482291
telemt_connections_current 534
telemt_connections_me_current 534
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 4760922
telemt_upstream_connect_attempt_total 60476
telemt_upstream_connect_success_total 60036
telemt_upstream_connect_fail_total 429
telemt_upstream_connect_attempts_per_request{bucket="1"} 60465
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 32155
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 27663
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 218
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 429
telemt_me_reconnect_attempts_total 48956
telemt_me_reconnect_success_total 1811
telemt_me_reader_eof_total 1483
telemt_me_idle_close_by_peer_total 1482
telemt_me_route_drop_no_conn_total 4092369
telemt_me_route_drop_channel_closed_total 13
telemt_me_route_drop_queue_full_total 10
telemt_me_route_drop_queue_full_profile_total{profile="high"} 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5619357
telemt_me_endpoint_quarantine_total 850
telemt_me_single_endpoint_outage_enter_total 19
telemt_me_single_endpoint_outage_exit_total 19
telemt_me_single_endpoint_outage_reconnect_attempt_total 59
telemt_me_single_endpoint_outage_reconnect_success_total 19
telemt_me_single_endpoint_quarantine_bypass_total 59
telemt_me_single_endpoint_shadow_rotate_total 965
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
telemt_me_floor_cap_block_total 23
telemt_me_floor_swap_idle_failed_total 23
telemt_desync_total 31593
telemt_desync_full_logged_total 10775
telemt_desync_suppressed_total 20818
telemt_desync_frames_bucket_total{bucket="1_2"} 6289
telemt_desync_frames_bucket_total{bucket="3_10"} 12462
telemt_desync_frames_bucket_total{bucket="gt_10"} 12842
telemt_pool_swap_total 133
telemt_pool_force_close_total 3892
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 375
telemt_me_draining_writers_reap_progress_total 46055
telemt_me_writer_removed_unexpected_total 1534
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3780
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 43852
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3451
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 441
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 42163
telemt_me_writer_teardown_success_total{mode="normal"} 47632
telemt_me_writer_teardown_noop_total 46062
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 92404
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 93157
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 93467
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 93694
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 93694
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 93694
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 93694
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 93694
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 93694
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 93694
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 93694
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 93694
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 93694
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 8.688816
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 93694
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 375
telemt_me_refill_failed_total 2739
telemt_me_writer_restored_same_endpoint_total 1605
telemt_me_writer_restored_fallback_total 26
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4332
telemt_user_connections_total{user="hello"} 5611551
telemt_user_connections_current{user="hello"} 534
telemt_user_octets_from_client{user="hello"} 119096260560 (110.92 GB)
telemt_user_octets_to_client{user="hello"} 2174561386018 (1.98 TB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 263
telemt_user_unique_ips_recent_window{user="hello"} 67
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 106773.3 (29h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1521378
telemt_connections_bad_total 36725
telemt_connections_current 436
telemt_connections_me_current 436
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 30686
telemt_upstream_connect_attempt_total 50316
telemt_upstream_connect_success_total 50158
telemt_upstream_connect_fail_total 130
telemt_upstream_connect_attempts_per_request{bucket="1"} 50288
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 23158
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 26211
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 789
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 130
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 2248
telemt_me_reconnect_success_total 912
telemt_me_reader_eof_total 899
telemt_me_idle_close_by_peer_total 899
telemt_me_route_drop_no_conn_total 517372
telemt_me_route_drop_channel_closed_total 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1352126
telemt_me_endpoint_quarantine_total 882
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 10
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 10
telemt_me_single_endpoint_shadow_rotate_total 883
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 16
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 33
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 44
telemt_desync_total 8961
telemt_desync_full_logged_total 2619
telemt_desync_suppressed_total 6342
telemt_desync_frames_bucket_total{bucket="1_2"} 2509
telemt_desync_frames_bucket_total{bucket="3_10"} 3424
telemt_desync_frames_bucket_total{bucket="gt_10"} 3028
telemt_pool_swap_total 115
telemt_pool_force_close_total 2945
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 166
telemt_me_draining_writers_reap_progress_total 42534
telemt_me_writer_removed_unexpected_total 867
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3261
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 40179
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2857
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 88
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 39589
telemt_me_writer_teardown_success_total{mode="normal"} 43440
telemt_me_writer_teardown_noop_total 42538
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 85006
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 85711
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 85941
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 85978
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 85978
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 85978
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 85978
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 85978
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 85978
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 85978
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 85978
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 85978
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 85978
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 5.294946
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 85978
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 166
telemt_me_refill_failed_total 74
telemt_me_writer_restored_same_endpoint_total 776
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 70
telemt_user_connections_total{user="hello"} 1347941
telemt_user_connections_current{user="hello"} 436
telemt_user_octets_from_client{user="hello"} 25974463405 (24.19 GB)
telemt_user_octets_to_client{user="hello"} 575146810939 (535.65 GB)
telemt_user_msgs_from_client{user="hello"} 18894
telemt_user_msgs_to_client{user="hello"} 38815
telemt_user_unique_ips_current{user="hello"} 192
telemt_user_unique_ips_recent_window{user="hello"} 60
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 188971.3 (52h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 13323216
telemt_connections_bad_total 1600878
telemt_connections_current 596
telemt_connections_me_current 596
telemt_handshake_timeouts_total 388840
telemt_upstream_connect_attempt_total 74253
telemt_upstream_connect_success_total 73903
telemt_upstream_connect_fail_total 214
telemt_upstream_connect_attempts_per_request{bucket="1"} 74117
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 36535
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 37264
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 100
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 214
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 2970
telemt_me_reconnect_success_total 1486
telemt_me_reader_eof_total 1470
telemt_me_idle_close_by_peer_total 1470
telemt_me_route_drop_no_conn_total 4482763
telemt_me_route_drop_channel_closed_total 123
telemt_me_route_drop_queue_full_total 42
telemt_me_route_drop_queue_full_profile_total{profile="high"} 42
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 10047182
telemt_me_endpoint_quarantine_total 1345
telemt_me_kdf_drift_total 2
telemt_me_single_endpoint_outage_enter_total 12
telemt_me_single_endpoint_outage_exit_total 12
telemt_me_single_endpoint_outage_reconnect_attempt_total 13
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 13
telemt_me_single_endpoint_shadow_rotate_total 1428
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 43
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
telemt_desync_total 42055
telemt_desync_full_logged_total 13739
telemt_desync_suppressed_total 28316
telemt_desync_frames_bucket_total{bucket="1_2"} 10169
telemt_desync_frames_bucket_total{bucket="3_10"} 15455
telemt_desync_frames_bucket_total{bucket="gt_10"} 16431
telemt_pool_swap_total 209
telemt_pool_force_close_total 5583
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 675
telemt_me_draining_writers_reap_progress_total 67101
telemt_me_writer_removed_unexpected_total 1408
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5293
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 63268
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5409
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 174
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 61518
telemt_me_writer_teardown_success_total{mode="normal"} 68561
telemt_me_writer_teardown_noop_total 67103
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 133054
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 134772
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 135155
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 135531
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 135651
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 135664
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 135664
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 135664
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 135664
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 135664
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 135664
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 135664
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 135664
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 19.773122
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 135664
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 675
telemt_me_refill_failed_total 80
telemt_me_writer_restored_same_endpoint_total 1303
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 44
telemt_me_writer_removed_unexpected_minus_restored_total 89
telemt_user_connections_total{user="hello"} 10013895
telemt_user_connections_current{user="hello"} 596
telemt_user_octets_from_client{user="hello"} 194790322908 (181.41 GB)
telemt_user_octets_to_client{user="hello"} 4439207097996 (4.04 TB)
telemt_user_unique_ips_current{user="hello"} 286
telemt_user_unique_ips_recent_window{user="hello"} 54
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 188967.7 (52h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11637901
telemt_connections_bad_total 1358805
telemt_connections_current 500
telemt_connections_me_current 500
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 311333
telemt_upstream_connect_attempt_total 101758
telemt_upstream_connect_success_total 100870
telemt_upstream_connect_fail_total 680
telemt_upstream_connect_attempts_per_request{bucket="1"} 101550
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 55034
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 42856
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 913
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2067
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 680
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 10470
telemt_me_reconnect_success_total 2579
telemt_me_reader_eof_total 2391
telemt_me_idle_close_by_peer_total 2390
telemt_me_seq_mismatch_total 97
telemt_me_route_drop_no_conn_total 5650045
telemt_me_route_drop_channel_closed_total 354
telemt_me_route_drop_queue_full_total 19
telemt_me_route_drop_queue_full_profile_total{profile="high"} 19
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8957188
telemt_me_endpoint_quarantine_total 1521
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_outage_enter_total 52
telemt_me_single_endpoint_outage_exit_total 52
telemt_me_single_endpoint_outage_reconnect_attempt_total 52
telemt_me_single_endpoint_outage_reconnect_success_total 50
telemt_me_single_endpoint_quarantine_bypass_total 52
telemt_me_single_endpoint_shadow_rotate_total 1430
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 57
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
telemt_desync_total 41792
telemt_desync_full_logged_total 13453
telemt_desync_suppressed_total 28339
telemt_desync_frames_bucket_total{bucket="1_2"} 10789
telemt_desync_frames_bucket_total{bucket="3_10"} 15373
telemt_desync_frames_bucket_total{bucket="gt_10"} 15630
telemt_pool_swap_total 199
telemt_pool_force_close_total 5361
telemt_pool_stale_pick_total 372
telemt_me_writer_close_signal_drop_total 664
telemt_me_draining_writers_reap_progress_total 67162
telemt_me_writer_removed_unexpected_total 2433
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6645
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 63034
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4890
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 471
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 61801
telemt_me_writer_teardown_success_total{mode="normal"} 69679
telemt_me_writer_teardown_noop_total 67167
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 134156
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 135938
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 136477
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 136796
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 136846
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 136846
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 136846
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 136846
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 136846
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 136846
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 136846
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 136846
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 136846
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 17.463752
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 136846
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 664
telemt_me_refill_failed_total 408
telemt_me_writer_restored_same_endpoint_total 2075
telemt_me_writer_restored_fallback_total 132
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 135
telemt_me_writer_removed_unexpected_minus_restored_total 226
telemt_user_connections_total{user="hello"} 8961787
telemt_user_connections_current{user="hello"} 500
telemt_user_octets_from_client{user="hello"} 157352683176 (146.55 GB)
telemt_user_octets_to_client{user="hello"} 3488844304322 (3.17 TB)
telemt_user_msgs_from_client{user="hello"} 103592
telemt_user_msgs_to_client{user="hello"} 254638
telemt_user_unique_ips_current{user="hello"} 243
telemt_user_unique_ips_recent_window{user="hello"} 47
```