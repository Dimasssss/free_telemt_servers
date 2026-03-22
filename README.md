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

# Server Metrics 2026-03-22 00:48:49 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 13346.9 (3h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 199448
telemt_connections_bad_total 13854
telemt_connections_current 676
telemt_connections_me_current 676
telemt_handshake_timeouts_total 11323
telemt_upstream_connect_attempt_total 5463
telemt_upstream_connect_success_total 5462
telemt_upstream_connect_attempts_per_request{bucket="1"} 5462
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2011
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3437
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_me_reconnect_attempts_total 197
telemt_me_reconnect_success_total 92
telemt_me_reader_eof_total 88
telemt_me_idle_close_by_peer_total 88
telemt_me_route_drop_no_conn_total 38501
telemt_me_route_drop_channel_closed_total 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 162641
telemt_me_endpoint_quarantine_total 94
telemt_me_single_endpoint_shadow_rotate_total 113
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 2
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
telemt_me_writers_active_current 42
telemt_desync_total 1268
telemt_desync_full_logged_total 352
telemt_desync_suppressed_total 916
telemt_desync_frames_bucket_total{bucket="1_2"} 362
telemt_desync_frames_bucket_total{bucket="3_10"} 443
telemt_desync_frames_bucket_total{bucket="gt_10"} 463
telemt_pool_swap_total 14
telemt_pool_force_close_total 374
telemt_me_writer_close_signal_drop_total 24
telemt_me_draining_writers_reap_progress_total 4891
telemt_me_writer_removed_unexpected_total 90
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 363
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 4606
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 370
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 4517
telemt_me_writer_teardown_success_total{mode="normal"} 4969
telemt_me_writer_teardown_noop_total 4892
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 9554
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 9736
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 9790
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 9835
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 9859
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 9861
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 9861
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 9861
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 9861
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 9861
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 9861
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 9861
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 9861
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 2.701894
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 9861
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 24
telemt_me_refill_failed_total 6
telemt_me_writer_restored_same_endpoint_total 84
telemt_me_writer_removed_unexpected_minus_restored_total 6
telemt_user_connections_total{user="hello"} 162387
telemt_user_connections_current{user="hello"} 676
telemt_user_octets_from_client{user="hello"} 1822557908 (1.70 GB)
telemt_user_octets_to_client{user="hello"} 55370735588 (51.57 GB)
telemt_user_unique_ips_current{user="hello"} 309
telemt_user_unique_ips_recent_window{user="hello"} 75
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 26713.3 (7h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 707818
telemt_connections_bad_total 40603
telemt_connections_current 709
telemt_connections_me_current 709
telemt_handshake_timeouts_total 26734
telemt_upstream_connect_attempt_total 11640
telemt_upstream_connect_success_total 11443
telemt_upstream_connect_fail_total 178
telemt_upstream_connect_attempts_per_request{bucket="1"} 11621
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5128
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6278
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 37
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 178
telemt_me_reconnect_attempts_total 1022
telemt_me_reconnect_success_total 343
telemt_me_reader_eof_total 297
telemt_me_idle_close_by_peer_total 297
telemt_me_route_drop_no_conn_total 331125
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 571570
telemt_me_endpoint_quarantine_total 242
telemt_me_single_endpoint_outage_enter_total 15
telemt_me_single_endpoint_outage_exit_total 15
telemt_me_single_endpoint_outage_reconnect_attempt_total 15
telemt_me_single_endpoint_outage_reconnect_success_total 15
telemt_me_single_endpoint_quarantine_bypass_total 15
telemt_me_single_endpoint_shadow_rotate_total 217
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 16
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
telemt_me_writers_active_current 48
telemt_desync_total 2495
telemt_desync_full_logged_total 1429
telemt_desync_suppressed_total 1066
telemt_desync_frames_bucket_total{bucket="1_2"} 537
telemt_desync_frames_bucket_total{bucket="3_10"} 936
telemt_desync_frames_bucket_total{bucket="gt_10"} 1022
telemt_pool_swap_total 29
telemt_pool_force_close_total 794
telemt_me_writer_close_signal_drop_total 58
telemt_me_draining_writers_reap_progress_total 10272
telemt_me_writer_removed_unexpected_total 280
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 883
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 9673
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 787
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 9478
telemt_me_writer_teardown_success_total{mode="normal"} 10556
telemt_me_writer_teardown_noop_total 10272
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 20366
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 20636
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 20722
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 20814
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 20826
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 20828
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 20828
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 20828
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 20828
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 20828
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 20828
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 20828
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 20828
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.404306
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 20828
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 58
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 238
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 8
telemt_me_writer_removed_unexpected_minus_restored_total 33
telemt_user_connections_total{user="hello"} 570725
telemt_user_connections_current{user="hello"} 709
telemt_user_octets_from_client{user="hello"} 9631023952 (8.97 GB)
telemt_user_octets_to_client{user="hello"} 201198171464 (187.38 GB)
telemt_user_unique_ips_current{user="hello"} 456
telemt_user_unique_ips_recent_window{user="hello"} 210
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 101573.3 (28h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7537215
telemt_connections_bad_total 609566
telemt_connections_current 1858
telemt_connections_me_current 1858
telemt_handshake_timeouts_total 245577
telemt_upstream_connect_attempt_total 37002
telemt_upstream_connect_success_total 36930
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 36937
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16709
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20054
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 161
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 1521
telemt_me_reconnect_success_total 759
telemt_me_reader_eof_total 770
telemt_me_idle_close_by_peer_total 770
telemt_me_route_drop_no_conn_total 4510184
telemt_me_route_drop_channel_closed_total 66
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6132765
telemt_me_endpoint_quarantine_total 642
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 755
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
telemt_me_writers_active_current 46
telemt_desync_total 26064
telemt_desync_full_logged_total 8609
telemt_desync_suppressed_total 17455
telemt_desync_frames_bucket_total{bucket="1_2"} 5605
telemt_desync_frames_bucket_total{bucket="3_10"} 10165
telemt_desync_frames_bucket_total{bucket="gt_10"} 10294
telemt_pool_swap_total 109
telemt_pool_force_close_total 3662
telemt_pool_stale_pick_total 17
telemt_me_writer_close_signal_drop_total 581
telemt_me_draining_writers_reap_progress_total 33738
telemt_me_writer_removed_unexpected_total 740
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2835
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 31202
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 40
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3423
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 239
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 30076
telemt_me_writer_teardown_success_total{mode="normal"} 34037
telemt_me_writer_teardown_noop_total 33782
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 61813
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 63598
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 64556
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 66002
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 66979
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 67518
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 67808
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 67819
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 67819
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 67819
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 67819
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 67819
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 67819
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 155.486350
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 67819
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 581
telemt_me_refill_failed_total 40
telemt_me_writer_restored_same_endpoint_total 676
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 8
telemt_me_writer_removed_unexpected_minus_restored_total 59
telemt_user_connections_total{user="hello"} 6125066
telemt_user_connections_current{user="hello"} 1858
telemt_user_octets_from_client{user="hello"} 104994034876 (97.78 GB)
telemt_user_octets_to_client{user="hello"} 2026400475084 (1.84 TB)
telemt_user_unique_ips_current{user="hello"} 926
telemt_user_unique_ips_recent_window{user="hello"} 267
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 101574.5 (28h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6202860
telemt_connections_bad_total 580888
telemt_connections_current 1407
telemt_connections_me_current 1407
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 205394
telemt_upstream_connect_attempt_total 41208
telemt_upstream_connect_success_total 40825
telemt_upstream_connect_fail_total 186
telemt_upstream_connect_attempts_per_request{bucket="1"} 41011
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20370
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19867
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 33
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 555
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 186
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 116
telemt_me_reconnect_attempts_total 1882
telemt_me_reconnect_success_total 830
telemt_me_reader_eof_total 799
telemt_me_idle_close_by_peer_total 799
telemt_me_route_drop_no_conn_total 2209367
telemt_me_route_drop_channel_closed_total 255
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4648594
telemt_me_endpoint_quarantine_total 620
telemt_me_single_endpoint_outage_enter_total 7
telemt_me_single_endpoint_outage_exit_total 7
telemt_me_single_endpoint_outage_reconnect_attempt_total 7
telemt_me_single_endpoint_outage_reconnect_success_total 7
telemt_me_single_endpoint_quarantine_bypass_total 7
telemt_me_single_endpoint_shadow_rotate_total 777
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 29
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
telemt_desync_total 22219
telemt_desync_full_logged_total 7538
telemt_desync_suppressed_total 14681
telemt_desync_frames_bucket_total{bucket="1_2"} 5352
telemt_desync_frames_bucket_total{bucket="3_10"} 8614
telemt_desync_frames_bucket_total{bucket="gt_10"} 8253
telemt_pool_swap_total 110
telemt_pool_force_close_total 3314
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 350
telemt_me_draining_writers_reap_progress_total 32468
telemt_me_writer_removed_unexpected_total 786
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2770
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 30419
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 6
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3101
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 213
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 29154
telemt_me_writer_teardown_success_total{mode="normal"} 33189
telemt_me_writer_teardown_noop_total 32474
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 62382
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 63901
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 64470
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 65047
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 65458
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 65643
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 65663
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 65663
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 65663
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 65663
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 65663
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 65663
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 65663
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 48.177918
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 65663
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 350
telemt_me_refill_failed_total 56
telemt_me_writer_restored_same_endpoint_total 723
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 20
telemt_me_writer_removed_unexpected_minus_restored_total 55
telemt_user_connections_total{user="hello"} 4582462
telemt_user_connections_current{user="hello"} 1407
telemt_user_octets_from_client{user="hello"} 138832047633 (129.30 GB)
telemt_user_octets_to_client{user="hello"} 2150731076095 (1.96 TB)
telemt_user_msgs_from_client{user="hello"} 39229
telemt_user_msgs_to_client{user="hello"} 49019
telemt_user_unique_ips_current{user="hello"} 689
telemt_user_unique_ips_recent_window{user="hello"} 122
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 101538.6 (28h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6107570
telemt_connections_bad_total 542007
telemt_connections_current 1319
telemt_connections_me_current 1319
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 195929
telemt_upstream_connect_attempt_total 47505
telemt_upstream_connect_success_total 47178
telemt_upstream_connect_fail_total 136
telemt_upstream_connect_attempts_per_request{bucket="1"} 47314
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 24488
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21247
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 390
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1053
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 136
telemt_me_keepalive_timeout_total 58
telemt_me_reconnect_attempts_total 1899
telemt_me_reconnect_success_total 859
telemt_me_reader_eof_total 799
telemt_me_idle_close_by_peer_total 799
telemt_me_route_drop_no_conn_total 2116303
telemt_me_route_drop_channel_closed_total 111
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4554044
telemt_me_endpoint_quarantine_total 696
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 9
telemt_me_single_endpoint_outage_reconnect_success_total 6
telemt_me_single_endpoint_quarantine_bypass_total 9
telemt_me_single_endpoint_shadow_rotate_total 760
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
telemt_me_writers_active_current 44
telemt_desync_total 22083
telemt_desync_full_logged_total 7379
telemt_desync_suppressed_total 14704
telemt_desync_frames_bucket_total{bucket="1_2"} 5397
telemt_desync_frames_bucket_total{bucket="3_10"} 8458
telemt_desync_frames_bucket_total{bucket="gt_10"} 8228
telemt_pool_swap_total 109
telemt_pool_force_close_total 3197
telemt_pool_stale_pick_total 1618
telemt_me_writer_close_signal_drop_total 372
telemt_me_draining_writers_reap_progress_total 33821
telemt_me_writer_removed_unexpected_total 774
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2827
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 31779
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 11
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2982
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 215
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 30624
telemt_me_writer_teardown_success_total{mode="normal"} 34606
telemt_me_writer_teardown_noop_total 33832
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 65951
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 67301
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 67731
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 68188
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 68395
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 68420
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 68438
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 68438
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 68438
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 68438
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 68438
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 68438
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 68438
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 25.563457
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 68438
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 372
telemt_me_refill_failed_total 57
telemt_me_writer_restored_same_endpoint_total 744
telemt_me_writer_restored_fallback_total 5
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 42
telemt_me_writer_removed_unexpected_minus_restored_total 25
telemt_user_connections_total{user="hello"} 4554790
telemt_user_connections_current{user="hello"} 1319
telemt_user_octets_from_client{user="hello"} 132307869339 (123.22 GB)
telemt_user_octets_to_client{user="hello"} 2082649948355 (1.89 TB)
telemt_user_msgs_from_client{user="hello"} 44246
telemt_user_msgs_to_client{user="hello"} 113178
telemt_user_unique_ips_current{user="hello"} 665
telemt_user_unique_ips_recent_window{user="hello"} 127
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 101577.9 (28h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 20116309
telemt_connections_bad_total 1520961
telemt_connections_current 1951
telemt_connections_me_current 1951
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 585542
telemt_upstream_connect_attempt_total 190397
telemt_upstream_connect_success_total 172721
telemt_upstream_connect_fail_total 16044
telemt_upstream_connect_attempts_per_request{bucket="1"} 188765
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 121907
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 40703
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1221
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8890
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 16044
telemt_me_keepalive_timeout_total 398
telemt_me_reconnect_attempts_total 64396
telemt_me_reconnect_success_total 2195
telemt_me_reader_eof_total 1378
telemt_me_idle_close_by_peer_total 1377
telemt_me_route_drop_no_conn_total 39469515
telemt_me_route_drop_channel_closed_total 122
telemt_me_route_drop_queue_full_total 12
telemt_me_route_drop_queue_full_profile_total{profile="high"} 12
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 16338061
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 5
telemt_me_endpoint_quarantine_total 779
telemt_me_single_endpoint_outage_enter_total 124
telemt_me_single_endpoint_outage_exit_total 124
telemt_me_single_endpoint_outage_reconnect_attempt_total 260
telemt_me_single_endpoint_outage_reconnect_success_total 63
telemt_me_single_endpoint_quarantine_bypass_total 260
telemt_me_single_endpoint_shadow_rotate_total 791
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 56
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
telemt_desync_total 31572
telemt_desync_full_logged_total 9416
telemt_desync_suppressed_total 22156
telemt_desync_frames_bucket_total{bucket="1_2"} 6863
telemt_desync_frames_bucket_total{bucket="3_10"} 13997
telemt_desync_frames_bucket_total{bucket="gt_10"} 10712
telemt_pool_swap_total 104
telemt_pool_force_close_total 3441
telemt_pool_stale_pick_total 29
telemt_me_writer_close_signal_drop_total 767
telemt_me_draining_writers_reap_progress_total 31591
telemt_me_writer_removed_unexpected_total 2037
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4292
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 29072
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 23
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2919
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 522
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 28150
telemt_me_writer_teardown_success_total{mode="normal"} 33364
telemt_me_writer_teardown_noop_total 31617
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 58404
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 60767
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 62018
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 63617
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 64545
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 64880
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 64962
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 64964
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 64967
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 64972
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 64972
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 64976
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 64981
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 212.407800
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 64981
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 767
telemt_me_refill_failed_total 3789
telemt_me_writer_restored_same_endpoint_total 1524
telemt_me_writer_restored_fallback_total 21
telemt_me_no_writer_failfast_total 666
telemt_me_async_recovery_trigger_total 14678
telemt_me_writer_removed_unexpected_minus_restored_total 492
telemt_user_connections_total{user="hello"} 16465686
telemt_user_connections_current{user="hello"} 1951
telemt_user_octets_from_client{user="hello"} 196245172592 (182.77 GB)
telemt_user_octets_to_client{user="hello"} 1149604268038 (1.05 TB)
telemt_user_msgs_from_client{user="hello"} 367794
telemt_user_msgs_to_client{user="hello"} 650852
telemt_user_unique_ips_current{user="hello"} 972
telemt_user_unique_ips_recent_window{user="hello"} 213
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 101545.4 (28h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5889290
telemt_connections_bad_total 554629
telemt_connections_current 1499
telemt_connections_me_current 1499
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 122441
telemt_upstream_connect_attempt_total 55698
telemt_upstream_connect_success_total 55043
telemt_upstream_connect_fail_total 562
telemt_upstream_connect_attempts_per_request{bucket="1"} 55605
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 32565
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22136
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 341
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 562
telemt_me_reconnect_attempts_total 69420
telemt_me_reconnect_success_total 1731
telemt_me_reader_eof_total 1503
telemt_me_idle_close_by_peer_total 1502
telemt_me_route_drop_no_conn_total 2367808
telemt_me_route_drop_channel_closed_total 10
telemt_me_route_drop_queue_full_total 39
telemt_me_route_drop_queue_full_profile_total{profile="high"} 39
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4592240
telemt_me_endpoint_quarantine_total 679
telemt_me_single_endpoint_outage_enter_total 23
telemt_me_single_endpoint_outage_exit_total 23
telemt_me_single_endpoint_outage_reconnect_attempt_total 24
telemt_me_single_endpoint_outage_reconnect_success_total 23
telemt_me_single_endpoint_quarantine_bypass_total 24
telemt_me_single_endpoint_shadow_rotate_total 763
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 32
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
telemt_me_writers_active_current 49
telemt_desync_total 23088
telemt_desync_full_logged_total 8098
telemt_desync_suppressed_total 14990
telemt_desync_frames_bucket_total{bucket="1_2"} 4386
telemt_desync_frames_bucket_total{bucket="3_10"} 8937
telemt_desync_frames_bucket_total{bucket="gt_10"} 9765
telemt_pool_swap_total 104
telemt_pool_force_close_total 3044
telemt_pool_stale_pick_total 54
telemt_me_writer_close_signal_drop_total 383
telemt_me_draining_writers_reap_progress_total 35213
telemt_me_writer_removed_unexpected_total 1547
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3714
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 33071
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2643
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 401
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 32169
telemt_me_writer_teardown_success_total{mode="normal"} 36785
telemt_me_writer_teardown_noop_total 35214
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 70759
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 71572
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 71847
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 71967
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 71996
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 71999
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 71999
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 71999
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 71999
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 71999
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 71999
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 71999
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 71999
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 8.024392
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 71999
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 383
telemt_me_refill_failed_total 4196
telemt_me_writer_restored_same_endpoint_total 1453
telemt_me_writer_restored_fallback_total 32
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7305
telemt_me_writer_removed_unexpected_minus_restored_total 62
telemt_user_connections_total{user="hello"} 4585258
telemt_user_connections_current{user="hello"} 1499
telemt_user_octets_from_client{user="hello"} 122786978336 (114.35 GB)
telemt_user_octets_to_client{user="hello"} 1875749872394 (1.71 TB)
telemt_user_msgs_from_client{user="hello"} 77823
telemt_user_msgs_to_client{user="hello"} 338392
telemt_user_unique_ips_current{user="hello"} 726
telemt_user_unique_ips_recent_window{user="hello"} 119
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 38381.2 (10h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3773800
telemt_connections_bad_total 136442
telemt_connections_current 1044
telemt_connections_me_current 1044
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 1560401
telemt_upstream_connect_attempt_total 23983
telemt_upstream_connect_success_total 23829
telemt_upstream_connect_fail_total 146
telemt_upstream_connect_attempts_per_request{bucket="1"} 23975
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15646
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8115
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 68
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 146
telemt_me_reconnect_attempts_total 45672
telemt_me_reconnect_success_total 906
telemt_me_reader_eof_total 582
telemt_me_idle_close_by_peer_total 582
telemt_me_route_drop_no_conn_total 1004644
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1831368
telemt_me_endpoint_quarantine_total 277
telemt_me_single_endpoint_outage_enter_total 10
telemt_me_single_endpoint_outage_exit_total 10
telemt_me_single_endpoint_outage_reconnect_attempt_total 49
telemt_me_single_endpoint_outage_reconnect_success_total 10
telemt_me_single_endpoint_quarantine_bypass_total 49
telemt_me_single_endpoint_shadow_rotate_total 292
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 7
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
telemt_me_floor_cap_block_total 23
telemt_me_floor_swap_idle_failed_total 23
telemt_desync_total 10116
telemt_desync_full_logged_total 3471
telemt_desync_suppressed_total 6645
telemt_desync_frames_bucket_total{bucket="1_2"} 1795
telemt_desync_frames_bucket_total{bucket="3_10"} 3871
telemt_desync_frames_bucket_total{bucket="gt_10"} 4450
telemt_pool_swap_total 41
telemt_pool_force_close_total 1321
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 126
telemt_me_draining_writers_reap_progress_total 13348
telemt_me_writer_removed_unexpected_total 661
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1362
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 12668
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1115
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 206
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 12027
telemt_me_writer_teardown_success_total{mode="normal"} 14030
telemt_me_writer_teardown_noop_total 13350
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 26886
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 27160
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 27274
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 27380
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 27380
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 27380
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 27380
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 27380
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 27380
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 27380
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 27380
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 27380
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 27380
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.295695
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 27380
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 126
telemt_me_refill_failed_total 2601
telemt_me_writer_restored_same_endpoint_total 813
telemt_me_writer_restored_fallback_total 11
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4264
telemt_user_connections_total{user="hello"} 1835092
telemt_user_connections_current{user="hello"} 1044
telemt_user_octets_from_client{user="hello"} 53182937500 (49.53 GB)
telemt_user_octets_to_client{user="hello"} 788284702066 (734.15 GB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 574
telemt_user_unique_ips_recent_window{user="hello"} 126
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 19352.0 (5h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 171273
telemt_connections_bad_total 1423
telemt_connections_current 311
telemt_connections_me_current 311
telemt_handshake_timeouts_total 4747
telemt_upstream_connect_attempt_total 9071
telemt_upstream_connect_success_total 9049
telemt_upstream_connect_fail_total 21
telemt_upstream_connect_attempts_per_request{bucket="1"} 9070
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3876
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5102
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 71
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 21
telemt_me_reconnect_attempts_total 187
telemt_me_reconnect_success_total 123
telemt_me_reader_eof_total 124
telemt_me_idle_close_by_peer_total 124
telemt_me_route_drop_no_conn_total 47758
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 150558
telemt_me_endpoint_quarantine_total 191
telemt_me_single_endpoint_shadow_rotate_total 172
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 3
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
telemt_me_writers_active_current 46
telemt_desync_total 994
telemt_desync_full_logged_total 248
telemt_desync_suppressed_total 746
telemt_desync_frames_bucket_total{bucket="1_2"} 388
telemt_desync_frames_bucket_total{bucket="3_10"} 363
telemt_desync_frames_bucket_total{bucket="gt_10"} 243
telemt_pool_swap_total 21
telemt_pool_force_close_total 476
telemt_me_writer_close_signal_drop_total 20
telemt_me_draining_writers_reap_progress_total 8135
telemt_me_writer_removed_unexpected_total 121
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 542
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 7717
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 474
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 7659
telemt_me_writer_teardown_success_total{mode="normal"} 8259
telemt_me_writer_teardown_noop_total 8135
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 16242
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 16366
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 16384
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 16394
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 16394
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 16394
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 16394
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 16394
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 16394
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 16394
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 16394
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 16394
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 16394
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.830479
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 16394
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 20
telemt_me_refill_failed_total 4
telemt_me_writer_restored_same_endpoint_total 115
telemt_me_writer_removed_unexpected_minus_restored_total 6
telemt_user_connections_total{user="hello"} 150272
telemt_user_connections_current{user="hello"} 311
telemt_user_octets_from_client{user="hello"} 2807284216 (2.61 GB)
telemt_user_octets_to_client{user="hello"} 86783500556 (80.82 GB)
telemt_user_unique_ips_current{user="hello"} 144
telemt_user_unique_ips_recent_window{user="hello"} 35
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 101549.8 (28h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7115690
telemt_connections_bad_total 721978
telemt_connections_current 1563
telemt_connections_me_current 1563
telemt_handshake_timeouts_total 203004
telemt_upstream_connect_attempt_total 39157
telemt_upstream_connect_success_total 39008
telemt_upstream_connect_fail_total 112
telemt_upstream_connect_attempts_per_request{bucket="1"} 39120
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19358
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19609
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 40
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 112
telemt_me_reconnect_attempts_total 1519
telemt_me_reconnect_success_total 804
telemt_me_reader_eof_total 786
telemt_me_idle_close_by_peer_total 786
telemt_me_route_drop_no_conn_total 2106056
telemt_me_route_drop_channel_closed_total 52
telemt_me_route_drop_queue_full_total 23
telemt_me_route_drop_queue_full_profile_total{profile="high"} 23
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5362194
telemt_me_endpoint_quarantine_total 699
telemt_me_single_endpoint_outage_enter_total 8
telemt_me_single_endpoint_outage_exit_total 8
telemt_me_single_endpoint_outage_reconnect_attempt_total 8
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 8
telemt_me_single_endpoint_shadow_rotate_total 779
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
telemt_me_writers_active_current 45
telemt_desync_total 20732
telemt_desync_full_logged_total 6928
telemt_desync_suppressed_total 13804
telemt_desync_frames_bucket_total{bucket="1_2"} 5041
telemt_desync_frames_bucket_total{bucket="3_10"} 7515
telemt_desync_frames_bucket_total{bucket="gt_10"} 8176
telemt_pool_swap_total 112
telemt_pool_force_close_total 3041
telemt_pool_stale_pick_total 3
telemt_me_writer_close_signal_drop_total 375
telemt_me_draining_writers_reap_progress_total 35273
telemt_me_writer_removed_unexpected_total 758
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2831
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 33218
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2953
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 88
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 32232
telemt_me_writer_teardown_success_total{mode="normal"} 36049
telemt_me_writer_teardown_noop_total 35275
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 69976
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 70858
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 71036
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 71236
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 71324
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 71324
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 71324
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 71324
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 71324
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 71324
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 71324
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 71324
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 71324
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 10.584917
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 71324
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 375
telemt_me_refill_failed_total 37
telemt_me_writer_restored_same_endpoint_total 716
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 35
telemt_user_connections_total{user="hello"} 5337322
telemt_user_connections_current{user="hello"} 1563
telemt_user_octets_from_client{user="hello"} 108184310372 (100.75 GB)
telemt_user_octets_to_client{user="hello"} 2501879038836 (2.28 TB)
telemt_user_unique_ips_current{user="hello"} 740
telemt_user_unique_ips_recent_window{user="hello"} 134
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 101546.4 (28h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6121012
telemt_connections_bad_total 602252
telemt_connections_current 1468
telemt_connections_me_current 1468
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 168834
telemt_upstream_connect_attempt_total 55009
telemt_upstream_connect_success_total 54593
telemt_upstream_connect_fail_total 357
telemt_upstream_connect_attempts_per_request{bucket="1"} 54950
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 32152
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21308
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 518
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 615
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 357
telemt_me_reconnect_attempts_total 5422
telemt_me_reconnect_success_total 1112
telemt_me_reader_eof_total 996
telemt_me_idle_close_by_peer_total 996
telemt_me_seq_mismatch_total 42
telemt_me_route_drop_no_conn_total 2159677
telemt_me_route_drop_channel_closed_total 189
telemt_me_route_drop_queue_full_total 11
telemt_me_route_drop_queue_full_profile_total{profile="high"} 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4732133
telemt_me_endpoint_quarantine_total 809
telemt_me_single_endpoint_outage_enter_total 27
telemt_me_single_endpoint_outage_exit_total 27
telemt_me_single_endpoint_outage_reconnect_attempt_total 27
telemt_me_single_endpoint_outage_reconnect_success_total 25
telemt_me_single_endpoint_quarantine_bypass_total 27
telemt_me_single_endpoint_shadow_rotate_total 774
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 32
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
telemt_desync_total 19529
telemt_desync_full_logged_total 6563
telemt_desync_suppressed_total 12966
telemt_desync_frames_bucket_total{bucket="1_2"} 4892
telemt_desync_frames_bucket_total{bucket="3_10"} 7110
telemt_desync_frames_bucket_total{bucket="gt_10"} 7527
telemt_pool_swap_total 110
telemt_pool_force_close_total 3001
telemt_pool_stale_pick_total 358
telemt_me_writer_close_signal_drop_total 371
telemt_me_draining_writers_reap_progress_total 33897
telemt_me_writer_removed_unexpected_total 1006
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3315
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 31635
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2778
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 223
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 30896
telemt_me_writer_teardown_success_total{mode="normal"} 34950
telemt_me_writer_teardown_noop_total 33901
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 67230
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 68273
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 68618
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 68813
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 68851
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 68851
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 68851
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 68851
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 68851
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 68851
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 68851
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 68851
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 68851
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 10.961996
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 68851
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 371
telemt_me_refill_failed_total 249
telemt_me_writer_restored_same_endpoint_total 866
telemt_me_writer_restored_fallback_total 55
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 76
telemt_me_writer_removed_unexpected_minus_restored_total 85
telemt_user_connections_total{user="hello"} 4735326
telemt_user_connections_current{user="hello"} 1468
telemt_user_octets_from_client{user="hello"} 89464157337 (83.32 GB)
telemt_user_octets_to_client{user="hello"} 2030213719028 (1.85 TB)
telemt_user_msgs_from_client{user="hello"} 75721
telemt_user_msgs_to_client{user="hello"} 209236
telemt_user_unique_ips_current{user="hello"} 679
telemt_user_unique_ips_recent_window{user="hello"} 137
```